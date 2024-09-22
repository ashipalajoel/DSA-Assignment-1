DISTRIBUTED SYSTEMS AND APPLICATIONS ASSIGNMENT 01 2024
Course Code: DSA612S
STUDENT NAMES : THOMAS ROBERT 220108129,JONAS TOBIAS 21601730, HAMUKOTO V 220104697,PANDULENI PAULUS 218062885, MWAETAKO STEFANUS, SHONGOLO JAKULA FG, 

This assignment covers two tasks:
1.	Programme Management System using RESTful APIs.
2.	Online Shopping System using gRPC.
Both tasks require server and client-side implementation using the Ballerina language.

QUESTION 1 
Programme Management System (RESTful API)
Create a RESTful API to manage programme workflows at the Programme Development Unit. Each programme contains multiple courses and has attributes such as:
•	Programme Code (unique identifier)
•	NQF Level, Faculty, Department, Title, Registration Date
•	List of Courses (each with a name, code, and NQF level)
API Functionalities:
1.	Add a new programme.
2.	List all programmes.
3.	Update a programme by code.
4.	Get programme details by code.
5.	Delete a programme by code.
6.	List programmes due for review.
7.	List programmes by faculty.


QUESTION 2
Online Shopping System (gRPC)
Develop a gRPC-based system for customers and admins. Key operations include:
1.	add_product: Admin adds a product (name, description, price, SKU, etc.).
2.	create_users: Stream multiple users to the server.
3.	update_product: Admin updates product details.
4.	remove_product: Admin removes a product and returns the updated list.
5.	list_available_products: Customers list available products.
6.	search_product: Customers search for a product by SKU.
7.	add_to_cart: Customers add products to their cart.
8.	place_order: Customers place an order.
