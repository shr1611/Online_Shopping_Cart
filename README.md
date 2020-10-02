# Online_Shopping_Cart
A Full-Stack web application developed using Ruby on Rails with SQLite3 database. Created RESTful APIs and routing for shopper and administrator login accounts..

------- README.txt ---------
COEN278 Assignment 3 - Online Store using Ruby with Rails 
----------------------------------------------------------
Submitted by:
Shruti Jagadeesh Bhat
W1587845
Santa Clara University 
----------------------------------------------------------
Layout:
Left side of the page has all the products displayed for the shopper as well as the admin.
Right side of the page shows a column for carts and other links: HOME, ADMIN pages, both of which require admin authentication.

----------------------------------------------------------
Two User credentials are loaded in the application currently:
Username: bronco
Password: bronco

Username: shruti
Password: shruti

----------------------------------------------------------

To run the application: 


1. Open terminal at the main assignment folder "OnlineStoreRailsApp" and run the following command:
> rails server

2. A Puma server starts running at the port mentioned. (Most likely it will be localhost:3000 )
 
3. Go to the browser, run localhost:3000

There are two views:

View1: Shopper view
------------------------------------
The default page is "shopper's catalog page"

4. The products can be added to cart using "Add to Cart" button.

5. Click on check out will take you to a new page, "New order form". Fill in the details and click "Place Order". It will create the order
 redirect to the shopper page with a success message. 

View2: Admin View
------------------------------------
Both HOME and ADMIN views require login authentication. Use the credentials mentioned above to login.
These links can take you to the respective views:
"ORDER" link
The above order can be viewed in "ORDERS" in the right side column.Click "ORDERS" to view the list of all the orders.

"PRODUCTS" link
This page shows the Admin view for the same products. It has options "Show, Edit and Destroy".

"USERS" link
This shows all the admin users added to the site, who can access the admin view.

Logout leads back to the Shopper view.
