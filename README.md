# 🚀 Full Stack Blog Platform

A scalable and secure full-stack blog application enabling authenticated users to create, manage, and display personalized blog content with image uploads.

---

## 📚 Overview

This application provides a feature-rich blogging experience tailored for individual users. It supports blog creation, previewing images before upload, categorization, and secure CRUD operations — all under user authentication.

> Developed with scalability, modularity, and user experience in mind.

---

## 🎯 Key Features

- **User Authenticated Blog Management**
  - Create, Read, Update, Delete (CRUD) functionality
- **Blog Metadata**
  - Title, Category, Image Upload, and Description
- **Image Upload with Preview**
  - Local preview before submission
- **Instant Feedback**
  - Success & error notifications with `react-hot-toast`
- **Secure API Calls**
  - Handled with Axios and cookie-based auth
- **Responsive UI**
  - Tailwind CSS ensures mobile-first design

---

## 🛠️ Tech Stack

### 📦 Frontend
- **React.js** – UI library
- **React Router DOM** – Client-side routing
- **Axios** – HTTP client for API integration
- **React Hot Toast** – UX notifications
- **Tailwind CSS** – Utility-first styling

### 🧠 Backend *(Expected Setup)*
- **Node.js + Express.js**
- **MongoDB** – NoSQL database
- ** Cloudinary** – Image handling
- **JWT with Cookies** – Auth mechanism
- **CORS & Middleware Configured**

---

## 📂 Directory Structure



---

## 🌐 API Endpoints Used

| Method | Endpoint                           | Description                     |
|--------|------------------------------------|---------------------------------|
| POST   | `/api/blogs/create`                | Create a new blog               |
| GET    | `/api/blogs/my-blog`               | Get blogs for logged-in user    |
| DELETE | `/api/blogs/delete/:id`            | Delete a user’s blog by ID      |
| PUT    | `/api/blogs/update/:id` *(assumed)*| Update an existing blog         |

---

## 🧪 Local Development Setup

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>/client


2. Install Dependencies
npm install

3.Start the Frontend
npm run dev

4.Backend API Server (Required)
http://localhost:4001
