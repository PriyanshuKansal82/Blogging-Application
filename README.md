📝 Blogging Application
A full-stack blogging platform built using Node.js, Express.js, MongoDB, and EJS, featuring secure authentication, blog management, and image uploads.

🚀 Features
🔐 User Authentication
JWT-based authentication
Secure password hashing
Cookie-based session handling
Login / Signup / Logout functionality

📝 Blog Management
Create, view, and list blogs
Author-based blog ownership
Dynamic rendering using EJS templates

🖼️ Image Uploads
Upload blog cover images using Multer
Server-side validation for uploads

🛡️ Protected Routes
Only authenticated users can create blogs
Authorization handled via middleware

⚙️ Middleware Architecture
Authentication middleware
Global state handling using res.locals
Error-safe request flow

🛠️ Tech Stack
Frontend
EJS (Embedded JavaScript Templates)
HTML, CSS, Bootstrap
Backend
Node.js
Express.js
Database
MongoDB (Mongoose ODM)
Authentication & Security
JSON Web Tokens (JWT)
Cookies
Crypto module for password hashing
Other Tools
Multer (File Uploads)
Git & GitHub


⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/PriyanshuKansal82/Blogging-Application.git
cd Blogging-Application

2️⃣ Install Dependencies
npm install

3️⃣ Start MongoDB
Make sure MongoDB is running locally:
mongosh

4️⃣ Run the Application
npm start
or
nodemon index.js

🌐 Usage
Open browser and go to:
http://localhost:800

Create an account
Sign in
Add new blogs with optional cover images
View blogs on the home page

🔐 Environment Variables (Optional)
Create a .env file in the root directory:
JWT_SECRET=your_secret_key

📌 Learning Outcomes
Implemented secure authentication using JWT
Designed RESTful routes with Express
Worked with MongoDB schema relationships
Built reusable middleware

Managed file uploads in Node.js

Server-side rendering with EJS
