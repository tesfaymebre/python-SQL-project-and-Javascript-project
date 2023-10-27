# Python-SQL Project and JavaScript Project

In this repository, I have included two separate projects:

1. Little Lemon Restaurant Database Management System
2. Blog Website

## 1. Little Lemon Restaurant Database Management System

### Table of Contents
- [Prerequisites](#prerequisites)
- [Project Description](#project-description)
- [Notebooks](#notebooks)
- [Database Schema](#database-schema)
- [Stored Procedures](#stored-procedures)

### Prerequisites
- Python 3.x
- Jupyter Notebook
- MySQL Server
- Python packages: `mysql-connector-python`

Install the required Python packages with the following command:

  ```bash
  pip install mysql-connector-python
  ```

Project Description
This project is a database management system for a restaurant named "Little Lemon." It includes Python code and Jupyter notebooks for managing a MySQL database. The project consists of the following components:

Jupyter notebooks for database setup, queries, and stored procedures.
A MySQL database schema with tables for menu items, menus, bookings, orders, employees, and more.
Stored procedures for generating reports and managing data.
Notebooks
The project contains the following Jupyter notebooks:

Prerequisites_2.ipynb: Sets up the MySQL database, creates tables, and populates them with initial data.
queryStoredProcedures.ipynb: Demonstrates the use of stored procedures to retrieve information from the database.
LittleLemonAnalysis.ipynb: Additional database queries and demonstrations.
You can execute these notebooks to interact with the database and perform various queries.

Database Schema
The MySQL database schema for "Little Lemon" includes the following tables:

MenuItems
Menus
Bookings
Orders
Employees
The schema supports managing menu items, menus, customer bookings, orders, and employee information.

Stored Procedures
The project demonstrates the creation and use of stored procedures for tasks such as generating reports, data retrieval, and status updates. The stored procedures include:

PeakHours: Retrieves peak booking hours.
GuestStatus: Retrieves guest status based on employee roles.
BasicSalesReport: Generates a basic sales report.
These stored procedures enhance the functionality of the database and facilitate data analysis.

## 2. Blog Website
This is a simple blog website built using Node.js, Express.js, EJS, MongoDB, HTML/CSS, Bootstrap...

### Table of Contents
- Prerequisites
- Installation
- Usage
- Project Structure
- Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js and npm installed.
MongoDB installed and running on mongodb://127.0.0.1:27017.
Installation
Clone the repository:

  ```bash
  git clone https://github.com/tesfaymebre/blog-website.git
  ```
Change to the project directory:

  ```bash
  cd blog-website
  ```
Install the dependencies:

  ```bash
  npm install
```

Start the application:

  ```bash
  node app.js
```

Usage
Open your web browser and navigate to http://localhost:3000 to access the home page of the blog website.
You can explore different sections like Home, About Us, and Contact Us.
To create a new blog post, click on the "Compose" link (http://localhost:3000/compose) and fill in the title and content of your post. Click "Publish" to create a new post.
You can click on individual posts to view their full content.
Project Structure
The project has the following structure:

app.js: The main application file.
package.json: Contains project information and dependencies.
views: Directory containing EJS templates.
partials: Directory containing header and footer templates.
home.ejs: Template for the home page.
about.ejs: Template for the About Us page.
contact.ejs: Template for the Contact Us page.
post.ejs: Template for individual blog post pages.
compose.ejs: Template for creating new blog posts.
css




