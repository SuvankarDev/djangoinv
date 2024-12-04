Invoice Management System
A full-stack application for managing invoices, built with Django Rest Framework for the backend and React for the frontend.

Table of Contents
Features
Tech Stack
Setup Instructions
Backend Setup
Frontend Setup
Usage
License

Features
Create, view, update, and delete invoices.
User-friendly interface for managing invoice data.


Tech Stack
Backend: Django
Frontend: React.js
Package Manager: npm
Database: SQLite (default with Django)

Setup Instructions
Follow these steps to set up and run the project locally.

Prerequisites
Ensure you have the following installed on your system:
Python (3.x)
Pip (Python package manager)
Node.js (includes npm)


Backend Setup

Open a terminal for the backend.

Verify Python and Pip installation:

Copy code
python --version
pip --version
now install all requirement

copy code 
pip install -r requirements.txt


Navigate to the backend project directory:

Copy code
cd invoice-project
Start the Django development server:

Copy code
py manage.py runserver


Frontend Setup
Open a second terminal for the frontend.
Navigate to the frontend project directory:

Copy code
cd invoice-management
Install dependencies:

Copy code
npm install
Start the React development server:

Copy code
npm start

Open the backend server URL in your browser to verify the server is running.
Default URL: http://127.0.0.1:8000/

Open the frontend URL to access the React application.
Default URL: http://localhost:3000/
Interact with the application to manage invoices.


![App Screenshot](images/Screenshot2024-12-04141709.png)


