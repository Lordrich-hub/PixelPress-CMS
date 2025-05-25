🌐 PixelPress CMS

A modern, full-stack content management demo system built with **WordPress**, **PHP**, **React**, and **MySQL**, designed to showcase clean architecture, RESTful API integration, and cloud-ready deployment.

---

 📌 Project Overview

**PixelPress CMS** is a demo project built to simulate a real-world marketing agency platform. It features:

- A custom WordPress frontend for users and public content.
- A React-based admin dashboard for managing posts and users.
- A PHP backend with a MySQL database connected via REST APIs.
- Full user authentication with Admin and Viewer roles.
- Git version control and CI/CD-friendly deployment setup.
- Optimized for SEO and GDPR compliance.

---

🚀 Tech Stack

| Layer        | Technology                            |
|--------------|----------------------------------------|
| Frontend     | React.js, JavaScript, Tailwind CSS     |
| CMS Frontend | WordPress (Custom Theme + Pages)       |
| Backend API  | PHP (REST API)                         |
| Database     | MySQL                                  |
| Versioning   | Git + GitHub                           |
| Deployment   | Localhost → Azure (or AWS-ready)       |

---

 🔑 Key Features

- ✅ **Custom WordPress frontend** (landing page, blog view)
- ✅ **React admin panel** for post/user management
- ✅ **Role-based login system** (Admin vs Viewer)
- ✅ **RESTful API** connection between PHP & React
- ✅ **Cloud-deployable** using Azure or AWS
- ✅ **Clean, modular folder structure**

---

 📁 Folder Structure

PixelPress-CMS/
├── backend/ # PHP + MySQL (REST API)
│ ├── config/
│ ├── routes/
│ └── controllers/
├── frontend-react/ # React Admin Dashboard
│ ├── src/
│ └── public/
├── wordpress-theme/ # Custom WordPress Theme
├── database/ # SQL dump or migrations
├── .env.example
├── README.md
└── package.json / composer.json


---

 🛠️ Getting Started

1. Clone the repo
git clone https://github.com/Lordrich-hub/PixelPress-CMS.git

2. Set up the backend
Create a local MySQL database

Import database/schema.sql

Configure backend in backend/config/db.php

3. Run WordPress locally
Use XAMPP/LAMP and copy wordpress-theme/ into your WordPress themes folder

4. Start the React admin panel
cd frontend-react
npm install
npm start

🌍 Deployment Guide
Use GitHub Actions or GitLab CI for CI/CD
Host backend PHP on Azure App Service or AWS EC2
Deploy React frontend with Vercel, Netlify, or on the same server
Use Azure MySQL or RDS (AWS) for database hosting

🙌 Author
Built by Lords Jackrich — Full Stack Developer | React | WordPress | PHP | Node.js

📌 Note
This is a demo project to showcase real-world full stack experience for job applications. Not intended for production use.



