# intern-database 
Intern Management System
A full-stack web application to manage and view intern details in a company. It allows users to add, update, delete, and view intern records using a user-friendly interface. The frontend is built using HTML5 and CSS, backend logic is handled by Python using the Flask framework, and intern data is stored in a MySQL database.

🖼️ Project Structure

intern-database-app/
│
├── static/ # CSS files, static assets
│ └── style.css
│
├── templates/ # HTML files (Jinja templates)
│ ├── index.html # Homepage - view all interns
│ ├── add.html # Form to add a new intern
│ ├── edit.html # Form to edit existing intern
│
├── app.py # Flask server logic
├── config.py # DB config (host, user, password)
├── requirements.txt # Python dependencies
├── README.md # This file
└── schema.sql # SQL schema to set up the intern table

🚀 Features:
📝 Add new interns
🔄 Edit intern details
❌ Delete intern records
👀 View all intern data in a table
🔍 Search interns by name or department
📱 Clean and responsive UI using HTML & CSS
