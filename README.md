# Project Overview
This project is a web-based savings, loan, and investment platform designed to help users manage their finances. Built using Flask, MySQL (SQLAlchemy), Bootstrap, and other JavaScript libraries, the platform offers a user-friendly interface for saving money, applying for loans, and making investments. It has two different user roles(admin and normal user). Users can deposit savings, request loans, and track their investment performance, all through a secure and intuitive web application. The platform also includes features for managing transactions, calculating interest, and providing financial reports.

## 1. Project Structure
1. models/ - 
Contains the SQLAlchemy models defining the database schema for the platform. Each model represents a table in the database
2. static/ - 
Holds static files such as CSS, JavaScript, and images. This directory is served directly to the client and helps in styling and enhancing the user interface of the platform.
3. templates/ - 
Includes HTML templates used by Flask to render web pages. These templates are rendered with dynamic data from the server and provide the structure and layout for the web pages of the application.
4. utility/ - 
Contains utility scripts and helper functions that support various operations within the platform. This can include data validation, formatting, and other reusable code snippets that assist in the smooth functioning of the application.
5. app.py - 
The main entry point of the application. This file initializes the Flask app, sets up routes, and handles the request/response cycle. It integrates the different components of the platform and starts the web server.
6. db_storage.py - 
Manages database connections and operations. This script sets up SQLAlchemy to interface with the MySQL database, handling tasks such as creating tables, querying, and committing changes to the database.
7. jobs.py - 
Schedules and runs background tasks and jobs. This can include tasks such as processing transactions, sending notifications, and performing periodic maintenance activities necessary for the platform's operation.
## 2. Installation
### Clone the repo
```
git clone https://github.com/Oduo24/Savings-Loan-and-Investment-App
cd Savings-Loan-and-Investment-App
```
### Create a Virtual Environment
```
python3 -m venv venv
source venv/bin/activate
```
### Install Dependencies
```
pip install -r requirements.txt
```
### Run application
```
python3 app.py
```
The application will be available at http://127.0.0.1:5000.
