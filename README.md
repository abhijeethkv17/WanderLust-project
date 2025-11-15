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

```
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




