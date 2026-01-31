StudentLMS

A full-stack Learning Management System (LMS) web application to support student learning, course management, and academic interactions. It includes both frontend and backend components so students and instructors can interact with the platform.

🧠 What This Is

This project integrates:

A React frontend (client/)

A Node.js / Express backend API (server/)

A database (e.g., MongoDB — configurable via .env)

It aims to offer a system where users can sign up, view courses, submit assignments, track progress, and interact with academic resources.

🚀 Features (Typical LMS)

🧑‍🎓 User authentication (register / login)

📚 Course listing and enrollment

📂 Assignment upload and management

🛠️ Tech Stack

Frontend

React

JavaScript

CSS

Backend

Node.js

Express.js

Database

MongoDB (or other, configured via .env)

Authentication

JWT (JSON Web Tokens)

📁 Directory Structure
StudentLMS/
├── client/                # React frontend
├── server/                # Express backend
├── .gitignore
├── README.md

📦 Installation & Setup
Clone the repository
git clone https://github.com/kosanaharshavardhan/StudentLMS.git
cd StudentLMS

Backend setup
cd server
npm install


Create a .env file in the server folder and add:

PORT=5000
MONGO_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>

Frontend setup
cd ../client
npm install

▶️ Running the Application
Backend
cd ../server
npm start

Frontend
cd ../client
npm start


The app should now run with:

Frontend: http://localhost:3000

Backend: http://localhost:5000

📌 Environment Variables

Ensure the following are set in your .env file:

PORT=5000
MONGO_URI=...
JWT_SECRET=...

🙌 Contributing

Contributions are welcome!

Fork the repository

Create a branch (git checkout -b feature/foo)

Commit your changes

Push to your fork

Open a Pull Request

📄 License

This project is open-source.
