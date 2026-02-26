# MERN CRUD Application

A simple **MERN Stack CRUD application** that allows users to **create, edit, and update user records**.
This project was built to practice full-stack development using MongoDB, Express, React, and Node.js.

---

## 🚀 Features

* Add new users
* Edit existing user details
* Update user information
* REST API integration
* Full-stack MERN architecture

---

## 🛠️ Tech Stack

**Frontend**

* React.js
* Axios
* CSS / Basic Styling

**Backend**

* Node.js
* Express.js
* MongoDB
* Mongoose

---

## 📁 Project Structure

```
crud/
 ├── client/        # React frontend
 ├── server/        # Node + Express backend
 ├── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/haneenmuhammedkc/crud.git
cd crud
```

---

### 2️⃣ Setup Backend

```
cd server
npm install
npm run dev
```

Create a `.env` file inside the server folder:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

### 3️⃣ Setup Frontend

```
cd client
npm install
npm start
```

---

## 🌐 API Endpoints

| Method | Endpoint       | Description   |
| ------ | -------------- | ------------- |
| POST   | /api/users     | Add new user  |
| GET    | /api/users     | Get all users |
| PUT    | /api/users/:id | Update user   |

---

## 🎯 Purpose of This Project

This project was created as a learning exercise to understand:

* MERN stack architecture
* CRUD operations
* RESTful API development
* Full-stack data flow

---

## 👨‍💻 Author

**Haneen Muhammed**
MERN Stack / Full-Stack Developer

GitHub: https://github.com/haneenmuhammedkc

---

## ⭐ Future Improvements

* Delete user functionality
* Form validation
* UI enhancements
* Authentication system