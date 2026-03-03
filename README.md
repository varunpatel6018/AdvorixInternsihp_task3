# AdvorixInternsihp_task3
Pyhton Programming Project ( Task 3)  Command-line Data Storage System


📌 Simple REST API using Flask
👨‍💻 Author

Varun Patel

📖 Project Description

This project is a simple REST API built using Flask.
It performs basic CRUD (Create, Read, Update, Delete) operations on user data stored in a JSON file.

The API allows applications to communicate with the backend using HTTP requests and exchange data in JSON format.

🎯 Objectives

To understand REST API development

To implement CRUD operations

To handle JSON data using Python

To learn Flask framework basics

To build a lightweight backend system

🛠️ Technologies Used

Python 3

Flask

JSON

Virtual Environment (venv)

📂 Project Structure
PRACTICE-JS/
│── AdvorixInternship_task3.py
│── users.json
│── my_venv/
│── README.md
⚙️ Installation & Setup
1️⃣ Clone or Download the Project
2️⃣ Navigate to Project Folder
cd path/to/your/folder
3️⃣ Create Virtual Environment (Optional but Recommended)
python3 -m venv my_venv
source my_venv/bin/activate
4️⃣ Install Dependencies
pip install flask
▶️ Running the Application
python AdvorixInternship_task3.py

Server will start at:

http://127.0.0.1:5000
🌐 API Endpoints
Method	Endpoint	Description
GET	/users	Get all users
GET	/users/<id>	Get single user
POST	/users	Add new user
PUT	/users/<id>	Update user
DELETE	/users/<id>	Delete user
📌 Example JSON Format
{
  "name": "Rahul",
  "age": 20
}
🧪 Testing

The API can be tested using:

Browser (for GET requests)

Postman

Curl commands

🚀 Features

Lightweight backend

JSON-based data storage

Simple and easy to understand

Beginner-friendly REST API

Supports full CRUD functionality

📚 Learning Outcome

Through this project, I learned how to:

Create REST APIs using Flask

Handle HTTP methods (GET, POST, PUT, DELETE)

Work with JSON files

Manage backend logic in Python

🏁 Conclusion

This project demonstrates the implementation of a simple REST API using Flask and showcases backend development fundamentals required for modern web applications
