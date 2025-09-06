Perfect 👍 I see your project structure (backend/ + frontend/) in your screenshot.
Let’s update your README.md so it includes clear run commands for both backend and frontend.

Here’s the updated README for your repo FinTrack—Personal-Expense-Income-Manager:

⸻


<h1 align="center">💰 FinTrack - Personal Expense & Income Manager 💰</h1>

<p align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Spring%20Boot-darkgreen?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/React.js-blue?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/MySQL-red?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/CSS-purple?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/JWT-orange?style=for-the-badge">
</p>

---

## 📌 Description

**FinTrack** is a full-stack personal finance management system designed to help users track **expenses** and **income** seamlessly.  
It provides secure authentication, user dashboards, admin controls, and insightful financial reports.

### ✨ Features
- 🔑 **Authentication** – JWT-based login, signup, password reset, and email verification.  
- 👥 **Role-based Access** – Separate modules for **Users** and **Admins**.  
- 📊 **User Dashboard** – Add, edit, and delete transactions with categories (`income` / `expense`).  
- 📅 **Finance Tools** – Recurring transactions, monthly summaries, and budget management.  
- 📈 **Reports** – Graphs, charts, and downloadable Excel reports.  
- 🖼 **Profile Management** – Cloudinary integration for user profiles.  
- ⚡ **Admin Panel** – Manage categories, users, and transactions with search, filter, and pagination.  

---

## 🚀 How to Run

### 🛠 Backend (Spring Boot)
1. Navigate to the backend folder:
   ```sh
   cd backend

	2.	Configure database & email credentials in:
src/main/resources/application.properties

# Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/fintrack
spring.datasource.username=deepak
spring.datasource.password=deepak04@

# JPA Settings
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

# Email Configuration (Gmail)
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=your_email@gmail.com
spring.mail.password=YOUR_APP_PASSWORD
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true


	3.	Run the backend:

mvn spring-boot:run

or, if using Gradle:

./gradlew bootRun


	4.	Backend runs at 👉 http://localhost:8080

⸻

🎨 Frontend (React.js)
	1.	Navigate to the frontend folder:

cd frontend


	2.	Install dependencies:

npm install


	3.	Start the React app:

npm start


	4.	Frontend runs at 👉 http://localhost:3000


📜 License

This project is licensed under the MIT License.

---

✅ Now your README includes **backend & frontend run commands**.  

Maintainer: deepaksinghcsebtech2025 (Deepak Singh)
Maintainer: deepaksinghcsebtech2025 (Deepak Singh)
Maintainer: deepaksinghcsebtech2025 (Deepak Singh)
Maintainer: deepaksinghcsebtech2025 (Deepak Singh)
