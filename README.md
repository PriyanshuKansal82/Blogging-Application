# 📝 Blogging Application

A full-stack blogging platform built using **Node.js**, **Express.js**, **MongoDB**, and **EJS**, featuring secure authentication, blog management, and image uploads.

---

## 🚀 Features

### 🔐 User Authentication
- JWT-based authentication  
- Secure password hashing  
- Cookie-based session handling  
- Login / Signup / Logout functionality  

### 📝 Blog Management
- Create, view, and list blogs  
- Author-based blog ownership  
- Dynamic rendering using EJS templates  

### 🖼️ Image Uploads
- Upload blog cover images using Multer  
- Server-side validation for uploads  

### 🛡️ Protected Routes
- Only authenticated users can create blogs  
- Authorization handled via middleware  

### ⚙️ Middleware Architecture
- Authentication middleware  
- Global state handling using `res.locals`  
- Error-safe request flow  

---

## 🛠️ Tech Stack

### Frontend
- EJS (Embedded JavaScript Templates)  
- HTML, CSS, Bootstrap  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB (Mongoose ODM)  

### Authentication & Security
- JSON Web Tokens (JWT)  
- Cookies  
- Crypto module for password hashing  

### Other Tools
- Multer (File Uploads)  
- Git & GitHub  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/PriyanshuKansal82/Blogging-Application.git
cd Blogging-Application
