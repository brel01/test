**E-Commerce Database Management System**


---

1.Description: 
---
E-Commerce Database Management System (EC-DBMS) is a system that is designed to store, process, retrieve and analyze information concerned with the administrative and management of sales activity done by a customer online sitting at home. This project aims at maintaining all the information pertaining to the customers, products, and their categories, orders, and reviews. It enables vendor to set up online shops, customers to browse through the shops, The system manages the items in the shop and also helps customers purchase them online without having to visit the shop physically. The online shopping system will use the internet as the sole method for selling goods, products, and services to its consumers. The website will show all products in a categorized manner. Customers can browse any product for its price, other details and can order the product by using their registered account. The customer has to pay the order amount at the time of delivery.

2.Basic Structure:
---
![alt text](https://github.com/brel01/test/blob/main/erd2.png)

In order to order an item it must reside in your database and exist as a unique item with appropriate name, price, and other attributes like size, color, and weight.
You'll need to identify who is making the order with unique_id of the customer, whcih will be inserted into ORDER ROW. 
Each item will have it's own unique Product ID value.
Vendors might have products with different sizes or colors. Will they be different prices based on size? (For example clothing like XXL sizes could it be a different price than other sizes?) Which brought up the need to create different rows in  for similar products with different attributes (like size). The products Table have a distinct impact on the design of Orders and Order_details tables.

