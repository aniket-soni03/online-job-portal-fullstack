# 🧾 Online Job Portal — Full Stack Project

This repository provides an overview of my **full-stack job management system**, built with **React (frontend)** and **Spring Boot (backend)**.
It allows users to register, authenticate, and manage job postings with real-time updates and secure authentication.

---

## 📂 Repositories

* 🎨 **Frontend (React + Vite):**
  [👉 View Frontend Repo](https://github.com/aniket-soni03/online-job-portal-frontend)

* ⚙️ **Backend (Spring Boot + MySQL):**
  [👉 View Backend Repo](https://github.com/aniket-soni03/online-job-portal-backend)

---

## 🚀 Tech Stack

**Frontend:** React.js, React Hook Form, React Router DOM, Tailwind CSS
**Backend:** Spring Boot, Spring Security (JWT), REST API, Spring Data JPA
**Database:** MySQL
**API Integration:** Fast2SMS API for SMS Notifications
**Tools:** Git, GitHub, VS Code, IntelliJ IDEA

---

## 🧠 Features

* User Registration & Authentication (JWT-based)
* Role-based Authorization (Admin/User)
* Manage Job Listings (Add, Edit, Delete)
* Responsive UI built with React
* Real-time form validation (React Hook Form)
* SMS Notification on successful job application

---

## ⚙️ Setup Instructions

### 🔹 Backend Setup

1. Clone the backend repository:

   ```bash
   git clone https://github.com/AniketSoni/job-portal-backend.git
   ```
2. Open the project in IntelliJ IDEA or Eclipse.
3. Update your `application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/jobportal
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   jwt.secret=yourSecretKey
   fast2sms.apiKey=yourFast2SMSKey
   ```
4. Run the Spring Boot application.

### 🔹 Frontend Setup

1. Clone the frontend repository:

   ```bash
   git clone https://github.com/AniketSoni/job-portal-frontend.git
   ```
2. Navigate to the project folder:

   ```bash
   cd job-portal-frontend
   ```
3. Install dependencies:

   ```bash
   npm install
   ```
4. Run the app:

   ```bash
   npm run dev
   ```

---

## 🌐 Live Demo (optional)

If deployed later, you can add:

```
Frontend Live: https://your-frontend-url.netlify.app  
Backend Live: https://your-backend-url.onrender.com
```

---

## 💡 Author

👨‍💻 **Aniket Soni**
📧 [aniketsoni.work@gmail.com](mailto:aniketsoni.work@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/aniketsoni) | [GitHub](https://github.com/AniketSoni)

---

✅ **Note:** This project was developed for learning and demonstration purposes to showcase full-stack development skills with React and Spring Boot.
