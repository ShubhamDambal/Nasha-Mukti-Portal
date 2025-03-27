# NashaMukti - De-Addiction Support Platform

NashaMukti is a full-stack web application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js) to provide support and resources for individuals struggling with addiction. Users can browse and create events related to de-addiction programs, upload images, and interact with the platform.

## 🌟 Features

✅ **User Authentication** (Sign up, Login)  
✅ **Event Management** (Create, View, Delete Events)  
✅ **Cloudinary Image Uploads** (For storing event images)  
✅ **MongoDB Database** (Stores users, events)  
✅ **RESTful API** (Backend built with Express.js)  
✅ **Responsive UI** (Ensures a mobile-friendly experience)  

---

## 📌 Tech Stack

- **Frontend:** React.js, Axios, React Router  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (with Mongoose ORM)  
- **Cloud Storage:** Cloudinary (for storing uploaded images)  
- **Authentication:** JWT (JSON Web Tokens)   

---

## 🚀 Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/NashaMukti.git
cd NashaMukti

---

### **2️⃣ Install Dependencies**
### **Backend**
```bash
cd server
npm install

---

### **Frontend**
```bash
cd client
npm install

---

### **3️⃣ Configure Environment Variables**
Create a .env file in the server folder and add:
```bash
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JWT_SECRET=your_jwt_secret

---

### **4️⃣ Run the Application**
### **Start Backend Server**
```bash
cd server
npm start

---

### **Start Frontend React App**
```bash
cd client
npm start

---

## **The application will now be running on http://localhost:3000/.**

