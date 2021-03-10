# Basic-Shop-WebApp
This is a simple web app designed, keeping in mind of a shopkeeper who can manage its shop inventory and orders via this app.

# Technologies used:
 - HTML, CSS for Frontend applications
 - Python Django Framework for Backend applications
 - Database used is sqlite

Focus was to implement the basic functionalities and backend working, so as to get familier with the Django Framework

# Functionalities included in this web app are :
 - Owner can register new customers into the database.
 - Owner can see all the customers registered
 - Owner can edit the details of the customers
 - Owner can register the products available on his/her shop
 - Owner can view the products 
 - Owner can edit the details of the products
 - Owner can take order
   > For orders, either owner can put in the number of customer and then proceed (Web App searches for the number and if found in the database retrieves the details of the              customer and then proceed for the order) or the owner can directly proceed to the order by clicking directly from the page where all customers are listed 
   > Cart system is implemented, so the owner can add multiple products.
   > Several checks are performed while placing the order like the quantity available, the quantity ordered.
   > At the cart page list of all products is available so the owner can directly select one and add it to cart
   > After adding all the products owner can place the order for the customer
 - Owner can change the status of the order like the payment status, and delivery status
 - Owner can view all the orders Placed
 - Owner can View all active orders ( The orders for which either payment is not done or the delivery is left)
 - Owner can cancel(Delete) the order.


Code is not optimised, i.e code is redundant.
