# 🏨 BookMyStayApp – Hotel Booking Application

## 📌 Overview
**BookMyStayApp** is a full-stack web application designed to provide a seamless hotel booking experience for users. It allows users to search for hotels, view details, and manage bookings efficiently.

The platform simulates a real-world booking system with features like:
- Hotel search & filtering  
- User authentication  
- Booking management  
- Responsive UI  

---

## 🚀 Features

### 👤 User Features
- 🔐 User Registration & Login  
- 🔍 Search hotels by location, date, and preferences  
- 📋 View hotel details (price, amenities, availability)  
- 🛏 Book rooms easily  
- 📅 View & manage bookings  

---

### 🏢 Admin Features
- ➕ Add / Update hotel listings  
- 🗑 Delete hotels  
- 📊 Manage bookings and users  
- 📈 Dashboard for monitoring activity  

---

## 🛠️ Tech Stack

### Frontend
- HTML  
- CSS  
- JavaScript  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  

### Tools
- Git & GitHub  
- Postman  

---

## 📂 Project Structure
```
BookMyStayApp/
│── frontend/
│── backend/
│── models/
│── routes/
│── controllers/
│── config/
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/devcrazy2812/BookMyStayApp.git
cd BookMyStayApp
```

---

### 2️⃣ Install Dependencies
```bash
npm install
```

---

### 3️⃣ Setup Environment Variables
Create a `.env` file and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

### 4️⃣ Run the Application
```bash
npm start
```

---

## 🌐 API Endpoints (Sample)

### User
- POST /auth/signup → Register user  
- POST /auth/login → Login  

### Hotels
- GET /hotels → Get all hotels  
- GET /hotels/:id → Get hotel details  

### Booking
- POST /bookings → Create booking  
- GET /bookings → Get user bookings  

---

## 📊 Key Concepts Used
- REST API Design  
- Authentication & Authorization  
- CRUD Operations  
- MVC Architecture  
- Database Integration  

---

## 📌 Use Cases
- Hotel booking platforms  
- Travel & tourism apps  
- Reservation management systems  

---

## 🧠 Learning Outcomes
- Real-world full-stack project development  
- API integration & backend logic  
- Database handling with MongoDB  
- Building scalable applications  

---

## 🙌 Author
**Abhay Goyal**

---

## ⭐ Contribute
- Fork the repo  
- Improve UI/UX  
- Add new features  
- Submit pull requests  

---

## 📜 License
This project is for educational purposes.
