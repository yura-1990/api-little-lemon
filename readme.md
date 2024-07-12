# Little Lemon API

The Little Lemon API is an API for the Little Lemon restaurant. Little Lemon's management wants to have an online-based order management system and mobile application. The LittleLemonAPI is the back-end API that allows customers to browse food items, view the item of the day and place orders. Managers are able to update the item of the day and monitor orders and assign deliveries.  The delivery crew are able to check the orders assigned to them and update an order once it is delivered.

## Features

User groups
It contains two user groups (Manager & Delivery crew) and some random users assigned to these groups from the Django admin panel.

 Manager

Delivery crew

Users not assigned to a group will be considered customers.

This API makes it possible end-users to perform certain tasks. It has the following functionalities.

1.	The admin can assign users to the manager group

2.	You can access the manager group with an admin token

3.	The admin can add menu items 

4.	The admin can add categories

5.	Managers can log in 

6.	Managers can update the item of the day

7.	Managers can assign users to the delivery crew

8.	Managers can assign orders to the delivery crew

9.	The delivery crew can access orders assigned to them

10.	The delivery crew can update an order as delivered

11.	Customers can register

12.	Customers can log in using their username and password and get access tokens

13.	Customers can browse all categories 

14.	Customers can browse all the menu items at once

15.	Customers can browse menu items by category

16.	Customers can paginate menu items

17.	Customers can sort menu items by price

18.	Customers can add menu items to the cart

19.	Customers can access previously added items in the cart

20.	Customers can place orders

21.	Customers can browse their own orders
