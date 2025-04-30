# Hospital_Management_System

🏥 MERN Stack Hospital Management System
📌 Project Description
The MERN Stack Hospital Management System is a comprehensive web application designed to streamline hospital operations. Built using the MERN stack—MongoDB, Express.js, React.js, and Node.js—this system offers robust features for both patients and administrators. Key functionalities include:

Authentication & Authorization: Secure login mechanisms with support for multiple JSON Web Tokens (JWTs).

Dual Frontends: Separate interfaces tailored for users (patients) and administrators.

Scalable Architecture: Modular design ensuring ease of maintenance and scalability.

Comprehensive Management: Tools for managing appointments, patient records, prescriptions, lab reports, and billing.

This project aims to digitize hospital workflows, reducing manual errors and enhancing patient care through efficient data management.

🛠️ Tech Stack
Frontend: React.js, CSS3, Bootstrap

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JSON Web Tokens (JWT)

Version Control: Git & GitHub

📁 Folder Structure
graphql
Copy
Edit
MERN-Stack-Hospital-Management-System-Web-Application/
├── backend/        # Express.js backend with MongoDB integration
├── dashboard/      # Admin dashboard frontend
├── frontend/       # Patient/user-facing frontend
├── .gitignore
└── README.md
⚙️ Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (v14 or higher)

npm (v6 or higher)

MongoDB (local or cloud instance)

Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Zeeshu911/MERN-Stack-Hospital-Management-System-Web-Application.git
cd MERN-Stack-Hospital-Management-System-Web-Application
Set Up the Backend

bash
Copy
Edit
cd backend
npm install
Create a .env file in the backend directory and add your MongoDB connection string:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
Start the backend server:

bash
Copy
Edit
npm start
Set Up the Frontend

Open a new terminal window:

bash
Copy
Edit
cd frontend
npm install
npm start
Set Up the Admin Dashboard

Open another terminal window:

bash
Copy
Edit
cd dashboard
npm install
npm start
The application will be accessible at http://localhost:3000 for the frontend and http://localhost:3001 for the admin dashboard.
<img width="1146" alt="Screenshot 2025-04-30 at 10 49 13 PM" src="https://github.com/user-attachments/assets/8555ed01-d909-461b-b08c-1bd30f24422b" />

🧪 Usage
User Registration & Login

Users can register and log in through the frontend interface.

Secure authentication is managed using JWTs.

Admin Access

Administrators can log in through the admin dashboard.

Admins have access to manage appointments, patient records, prescriptions, lab reports, and billing.

Appointment Management

Users can book appointments with doctors.

Admins can view, approve, or reject appointments.

Patient Records

Admins can add, update, or delete patient information.

Users can view their medical history and prescriptions.

Lab Reports & Billing

Admins can upload lab reports and manage billing details.

Users can view their lab results and billing information.

📸 Screenshots
Note: Replace the placeholders below with actual screenshots.

User Interface

Admin Dashboard

📝 License
This project is licensed under the MIT License.

🙏 Acknowledgements
React.js

Node.js

Express.js

MongoDB

Bootstrap

