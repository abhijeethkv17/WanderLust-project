# 🌍 Wanderlust — Project (MERN Stack)

Wanderlust is a full-stack web application inspired by **Airbnb**, built using the **MERN stack**. It allows users to create listings, explore places to stay, view details of each listing, leave reviews, and manage their own bookings and profiles.

This project was built as part of my Full Stack Web Development learning journey and covers everything from backend APIs to frontend UI, database modeling, authentication, authorization, and cloud image storage.

---

## 🚀 Features

### 🏡 **Listings**
- Create, edit, and delete property listings  
- Add images using **Cloudinary image uploads**  
- View all listings or a single listing  
- Integrated Map (Mapbox) to show listing location  

### ⭐ **Reviews**
- Add, edit, and delete reviews  
- Rating system with validation  
- Shows user details for each review  

### 👤 **User Authentication (Auth)**
- Register, login, logout using **Passport.js**  
- Authorization for protected routes  
- Only the listing owner can edit/delete their listing  
- Only review owner can modify/delete a review  

### 🗺️ **Maps Integration**
- Uses **Mapbox Geocoding** to convert location → coordinates  
- Interactive map showing listing location  

### 🗄️ **Database**
- MongoDB with Mongoose models  
- Listings, Reviews, and Users schema  
- Proper validations & error handling  

### 🎨 **Frontend**
- Built with **EJS / CSS / Bootstrap**  
- Fully responsive UI  
- Clean and minimal Airbnb-like layout  

### 🔐 **Security**
- Server-side validation  
- Sanitized user inputs  
- Error handling & flash messages  

---

## 🛠️ Tech Stack

### **Frontend**
- HTML, CSS, JavaScript  
- EJS Templating engine  
- Bootstrap 

### **Backend**
- Node.js  
- Express.js  
- Mongoose (MongoDB)  
- RESTful APIs  

### **Authentication & Security**
- Passport.js    
- Express Session & Cookies  

### **Cloud & Maps**
- Cloudinary (Image Uploads)  
- Mapbox API (Geocoding + Maps)  

---

## 🧩 Project Structure

```bash
Wanderlust/
│
│── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ └── utils/
│
│── init/
│
│── public/
│ ├── css/
│ ├── js/
│ └── images/
│
│── views/
│ ├── layouts/
│ ├── listings/
│ ├── reviews/
│ └── users/
│
│── app.js
│── middleware.js
│── package.json
│── schema.js
│── README.md

```
--- 

## 🧮 Database Models Overview

### **User Model**
- username
- email
- password hash
- listings[] (optional reference)

### **Listing Model**
- title
- description
- price
- location
- images (Cloudinary)
- geometry (coordinates for Mapbox)
- owner (User reference)
- reviews[] (Review reference)

### **Review Model**
- rating
- comment
- author (User reference)

### **schema.js**
Joi validation schemas for:
- Listing
- Review
- User

---

## 🧰 Important Files

### **app.js**
- Main Express application  
- Express config, sessions, middleware  
- Route mounting  
- Error handling  

### **middleware.js**
- Authentication checks  
- Authorization logic  
- Input validation blocks  

### **public/**
- Static CSS/JS/images  
- Mapbox scripts  
- Client-side JavaScript  

### **views/**
- EJS templates  
- Layouts and page components  

--- 

## 📦 Future Improvements

- Add booking/reservation system  
- Add search filters: price, rating, distance  
- Add wishlist/favorites  
- Build separate React frontend (Full MERN SPA)  
- Add messaging between hosts & guests  

---

## 🧑‍💻 Author

**Abhijeeth K V**  
Full Stack Developer | CSE Student  

- LinkedIn: https://www.linkedin.com/in/abhijeethkv  
- GitHub: https://github.com/abhijeethkv17

---

## ⭐ Support

If this project helped or inspired you, please give it a ⭐ star on GitHub!



