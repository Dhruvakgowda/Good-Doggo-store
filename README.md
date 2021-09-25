# The Good Doggo Store
#### Video Demo:  <https://youtu.be/bm9FpXhqj2M>
#### Description:
Its a Flask Web-based Application using HTML,CSS,JavaScript and basic Bootstrap syntax.
It allows the user to login and Add their favourite dog products to their Cart and Buy the products.
and finally end session using Log out.

The logging in happens through recording the user name and hashed password in the user database.


application.py is where the flask/python code takes place along with helpers.py to assist in seperate functions.

CSS file helds the key to the design of every html page that has been output using the help of regular class variables and bootstrap manipulation.

Index.html ("/")  page describes the first as the user logs in , it contains three bars with the three category of shopping the user can perform. have used .png files in the header block to generate ad like images over the category table to give a further idea of whats inside.

Login.html ("/login") contains html form attribute used to store their Username and password  in the database and to verify for further login.

the food.html ("/food")is used to dynamically generate the products in the database into the loading sheet.

Cart.html("/cart") is generated using the information  of the users id and the products id of the respective user and products that they added to cart and displays a table of all the things the user added to cart.

layout.html contains the layout for the jinga syntax along with connection to the css and bootstrap syntax files.

apology.html for any errors caused during the process of registering and logging in with specification as to what the mistake or error is.

the finance.db database contains three tables
the user table which stores the userid,username and hashed password in which id is the primary key which gets auto incremented.

the product table stores the product id which here is the primary key and is auto incremented as new products are added, along with a name column for the names of the products,
a decription column for a one-line description for the products , a price column for the price of the product , a category column with txt field for specifiying the category among the three and a quantity column for the number or the weight of the product.

and a connecting table for the two called cart to form communication between the tables user and its userid and the primary key of products table product id to form a connecting table to be used later for generating table for everything the user added to cart using only the link between the primary keys.
                                                                                                                                                                   .

accessories.html("/accessories")is used to dynamically generate the food products in the database into the loading sheet.

training.html("/training")  is used to dynamically generate the training products in the database into the loading sheet.

A requirement.txt file for mentioning every installment needed for the webapp to function and import.

Finally when the user clicks the CHECKOUT button , an alert using javascript function syntax is generated to inform the user of their purchase.
