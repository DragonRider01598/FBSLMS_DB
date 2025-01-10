# FBSLMS_DB

FBSLMS_DB is a database management system designed to manage data for a Football Sports League Management System (FBSLMS). Developed as a student project, it integrates Python with MySQL to provide functionalities for both administrators and fans.

## Features

- **User Authentication**: Secure login system for both users and administrators.
- **Admin Menu**: Options to insert, update, and delete data in a user-friendly manner.
- **Fan Menu**: Access to a variety of football league statistics and data.
- **Data Management**: Dynamic and intuitive system for storing and retrieving football league information.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/DragonRider01598/FBSLMS_DB.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd FBSLMS_DB
   ```

3. **Install the required dependencies**:

   Ensure you have Python and MySQL installed. Then, install the MySQL connector for Python:

   ```bash
   pip install mysql-connector-python
   ```

4. **Set up the database**:

   - Create a MySQL database named `fbslms`.
   - Execute the `table_structure.sql` script to create the necessary tables.
   - Execute the `table_data.sql` script to populate the tables with initial data.
   - Execute the `pass_log.sql` script to set up user authentication data.

## Usage

1. **Run the login script**:

   ```bash
   python login.py
   ```

2. **Follow the on-screen prompts** to navigate through the admin and fan menus.

## Project Structure

- `login.py`: Handles user authentication.
- `adminMenu.py`: Contains options for administrators to manage data.
- `teamMenu.py`: Provides team-related functionalities.
- `insertMenu.py`, `updateMenu.py`, `deleteMenu.py`: Scripts for inserting, updating, and deleting data, respectively.
- `showQ.py`: Displays queries and results.
- `queries.py`: Contains database query functions.
- `table_structure.sql`: SQL script to create database tables.
- `table_data.sql`: SQL script to populate tables with initial data.
- `pass_log.sql`: SQL script for user authentication data.

## Contributors

This project was developed by a group of students as part of their coursework.
