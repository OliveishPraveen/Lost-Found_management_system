# Lost-Found_management_system
# Campus Lost & Found Backend
A robust command-line interface (CLI) and backend solution for managing lost and found items on a college campus. This project is built to demonstrate a solid understanding of database design, CRUD operations, and clean, modular backend code.

## 🚀 Features
Report Lost Items: Submit detailed information about a lost item, including its description, category, and location.

Report Found Items: Post details about items you've found on campus.

Browse Listings: Search and filter through all lost and found item listings.

Update Status: Easily update an item's status once it has been recovered.

## 💻 Tech Stack
Python: Core programming language.

MySQL: Relational database for data persistence.
## 📁 Project Structure
The project is organized into three main modules to ensure separation of concerns.

main.py

This is the entry point of the application.

It handles the command-line interface and user interaction.

Calls functions from lost_found_manager.py to perform tasks.

db_connector.py

The database layer.

Manages the connection to the MySQL database.

Contains a reusable function get_db_connection() to establish and return a database connection.

lost_found_manager.py

The business logic layer.

Contains all the functions for CRUD operations.

Executes SQL queries to add, retrieve, and update data.
mysql-connector-python: The official Python library for connecting to MySQL.

Git & GitHub: Used for version control and project hosting.

## ⚙️ Setup & Installation
This project requires Python and MySQL to be installed on your system.
