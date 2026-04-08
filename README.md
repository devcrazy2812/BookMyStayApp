# 🏨 BookMyStayApp – Hotel Booking Application

## 📌 Overview
**BookMyStayApp** is a full-stack web application designed to provide a seamless hotel booking experience for users. It allows users to search for hotels, view details, and manage bookings efficiently.

The platform simulates a real-world booking system with features like:
- Hotel search & filtering  
- User authentication  
- Booking management  
- Responsive UI  

---

## 📂 Initial Setup

### 🔹 Step 1: Create Local Folder
- Create a folder in Documents  
- Folder name = **Your Full Roll Number**

---

### 🔹 Step 2: Create GitHub Repository
- Repository Name: **BookMyStayApp**
- Enable:
  - ✅ README file (**Mandatory**)

---

### 🔹 Step 3: Clone Repository
```bash
git clone <repository_link>
cd BookMyStayApp
```

---

## 💻 Project Setup (IntelliJ)

### 🔹 Step 4: Open Project
- Open IntelliJ  
- Select **Open Project**
- Choose your cloned folder  

---

### 🔹 Step 5: Create Module
- Create new module: **App**
- Uncheck: Add sample code  

---

### 🔹 Step 6: Create Java Class
- Inside `src/`
- Create class:
```java
BookMyStayApp
```

---

## 🌿 Git Branching Workflow

### 🔹 Step 7: Create Dev Branch
```bash
git checkout -b dev
git push origin dev
```

---

### 🔹 Step 8: Create Feature Branch
```bash
git checkout -b feature/UC1-WelcomePage
```

---

### 🔹 Step 9: Implement Use Case
- Write logic inside:
```java
BookMyStayApp.java
```

---

### 🔹 Step 10: Commit Changes
```bash
git add .
git commit -m "[Your Name] Added UC1-WelcomePage"
git push origin feature/UC1-WelcomePage
```

---

## 🔀 Pull Request Process

### 🔹 Step 11: Create Pull Request
- Go to GitHub  
- Click **Compare & Pull Request**

### 🔹 Important:
- Change base branch:
```
main ❌ → dev ✅
```

### 🔹 Step 12: Merge PR
- Create Pull Request  
- Merge Pull Request  
- Confirm Merge  

---

## ⚠️ Important Rules

❌ Do NOT merge `dev` into `main`  
❌ Do NOT create PR from dev → main  

✔ Always merge:
```
feature branch → dev
```

---

## 🔄 Continue Development

### 🔹 Step 13: Switch to Dev
```bash
git checkout dev
```

### 🔹 Step 14: Pull Latest Code
```bash
git pull origin dev
```

---

## 🔁 Repeat for Next Use Cases

For each new use case:
1. Create new branch:
```bash
git checkout -b feature/UCx-Name
```
2. Implement code  
3. Commit & Push  
4. Create PR → Merge into dev  

---

## 🧠 Key Concepts

- Git Branching Strategy  
- Feature-based development  
- Pull Request workflow  
- Version control best practices  

---

## 📌 Summary Workflow

```
main (stable)
   ↑
dev (integration branch)
   ↑
feature/UCx (development)
```

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
