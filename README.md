# CODTECH-IT-INTERNSHIP-TASK-2
Name:NITHYA SRI S
Company:CODTECH IT SOLUTIONS 
INTERN ID:CT4PP2825 Domain:PYTHON PROGRAMMING 
Duration:JUNE to JULY 2024 
Mentor:Neela Santhosh Kumar
OVERVIEW OF PROJECT:
This code implements a comprehensive inventory management system with a graphical user interface (GUI) using Python and the Tkinter library. Here's an overview of the different components and functionalities:
Database Setup:
The setup_database() function creates the necessary tables (users and products) in an SQLite database named inventory.db.
User Management:
The register_user() function allows users to register with a unique username and password.
The authenticate_user() function validates the user's login credentials.
Product Management:
The add_product(), edit_product(), and delete_product() functions handle the CRUD (Create, Read, Update, Delete) operations for products.
The view_products() function retrieves and returns all the products stored in the database.
The low_stock_alert() function identifies products with a quantity below a specified threshold (default is 10).
Graphical User Interface (GUI):
The InventoryApp class represents the main GUI application.
The create_login_screen() method creates the login screen, where users can enter their username and password to log in or register.
The create_inventory_screen() method creates the inventory management screen, where users can add, view, and manage products.
The GUI utilizes Tkinter widgets such as Frame, Label, Entry, and Button to build the user interface.
The GUI handles user interactions, such as logging in, registering, adding products, and viewing product information, by calling the corresponding functions.
Sample Operations:
The code includes sample operations to demonstrate the functionality of the inventory management system, such as registering users, authenticating users, adding products, viewing products, and triggering low stock alerts.
The main flow of the application is as follows:
The database is set up, creating the necessary tables if they don't already exist.
Sample user registration and authentication operations are performed.
Sample product operations are carried out, including adding, viewing, and checking for low stock.
The GUI application is initialized, and the main event loop is started, allowing the user to interact with the inventory management system.
This code provides a solid foundation for a comprehensive inventory management system, including user authentication, product management, and a user-friendly GUI. You can further expand on this code by adding more features, improving the user interface, and integrating additional functionalities as per your requirements.
