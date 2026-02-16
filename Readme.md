# 📝 Attendance Management System (MERN Stack)

Hello! This is my full-stack attendance tracking system developed for the **Project Evaluation Round**. It features a secure, role-based interface for both Managers and Employees.

 Key Features
* **Employee Role**: Log in to check in and out. The system automatically tags your status as **On Time** or **Late** based on your entry time.
* **Manager Role**: Access a high-level dashboard to see total staff counts, daily presence stats, and department breakdowns.
* **Data Analytics**: A full history of attendance records that can be filtered and **Exported to CSV** for reporting.
* **Security**: Built with **JWT (JSON Web Tokens)** to ensure user data remains private and secure.
* **Profile Management**: A dedicated page for users to view their personal work details and department info.

 How to Run the Project
Follow these steps to set up the app on your local machine:

 1. Install Dependencies
Open your terminal in both the **frontend** and **backend** folders and run:
```bash
npm install
2. Database & Sample Data
Ensure your MongoDB link is set in the .env file within the backend folder. Then, run the seed script to populate the app with test data:
node seed.js
Gemini said
Here is the clean, simple, and humanized text you can copy and paste directly into your README.md file.

Markdown
# 📝 Attendance Management System (MERN Stack)

Hello! This is my full-stack attendance tracking system developed for the **Project Evaluation Round**. It features a secure, role-based interface for both Managers and Employees.

---

## 🌟 Key Features
* **Employee Role**: Log in to check in and out. The system automatically tags your status as **On Time** or **Late** based on your entry time.
* **Manager Role**: Access a high-level dashboard to see total staff counts, daily presence stats, and department breakdowns.
* **Data Analytics**: A full history of attendance records that can be filtered and **Exported to CSV** for reporting.
* **Security**: Built with **JWT (JSON Web Tokens)** to ensure user data remains private and secure.
* **Profile Management**: A dedicated page for users to view their personal work details and department info.

---

## 🚀 How to Run the Project
Follow these steps to set up the app on your local machine:

### 1. Install Dependencies
Open your terminal in both the **frontend** and **backend** folders and run:
```bash
npm install
Note: This recreates the 'node_modules' folder which was excluded to keep the file size small.

2. Database & Sample Data
Ensure your MongoDB link is set in the .env file within the backend folder. Then, run the seed script to populate the app with test data:

Bash
node seed.js
3. Start the Application
Backend: Run npm start in the backend folder.
Frontend: Run npm start in the frontend folder.
Demo Accounts:
Use these credentials to test the different
Role,Email,Password
Manager,manager@test.com,password123
Employee,kesir@test.com,password123
Tech Stack
Frontend: React.js with React Router

Backend: Node.js & Express

Database: MongoDB & Mongoose

Security: JWT & Bcrypt
