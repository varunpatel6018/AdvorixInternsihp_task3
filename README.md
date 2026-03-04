# AdvorixInternsihp_task3
Pyhton Programming Project ( Task 3)  Command-line Data Storage System


📌 Simple REST API using Flask




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
AdvorixInternship_tasks/
│── AdvorixInternship_task3.py
│── users.json
│── my_venv/
│── README.md

🚀 Steps to Use the Flask REST API

🔹 1️⃣ Go to your project folder
cd /path/to/your/project

🔹 2️⃣ Activate virtual environment (if created)

You already have my_venv, so run:

source my_venv/bin/activate

You will see:

(my_venv)

🔹 3️⃣ Install Flask (only first time)

pip install flask

🔹 4️⃣ Make sure required files exist

Check using:

ls

You should see:

AdvorixInternship_task3.py
users.json

If users.json is missing, create it:

echo [] > users.json
🔹 5️⃣ Run the API
python AdvorixInternship_task3.py

OR

python3 AdvorixInternship_task3.py

You will get:

Running on http://127.0.0.1:5000

✅ Server started

🌐 6️⃣ Use the API (very important)

Open browser or Postman.

👉 1. Get all users

Type in browser:

http://127.0.0.1:5000/users

👉 2. Add a new user (POST request)

Use Postman → Body → JSON

POST http://127.0.0.1:5000/users

{
  "name": "Varun",
  "age": 20
}

👉 3. Get single user

http://127.0.0.1:5000/users/1

👉 4. Update user

PUT request:

http://127.0.0.1:5000/users/1

{
  "name": "Rahul",
  "age": 22
}

👉 5. Delete user

DELETE request:

http://127.0.0.1:5000/users/1

🛑 7️⃣ Stop the server

Press:

CTRL + C

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

👨‍💻 Author

Varun Patel
