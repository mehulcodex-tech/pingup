# 🚀 PingUp

PingUp is a modern **full-stack social media platform** where users can connect, share posts, interact with others, and manage their profiles securely. Built using the **MERN Stack**, the application focuses on performance, scalability, and a seamless user experience.

---

## ✨ Features

* 🔐 Secure User Authentication (JWT)
* 👤 User Registration & Login
* 📝 Create, Edit & Delete Posts
* ❤️ Like & Unlike Posts
* 💬 Comment on Posts
* 🖼️ User Profiles
* 📰 Personalized Feed
* 📱 Fully Responsive UI
* ⚡ RESTful API Architecture

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Bootstrap / CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JSON Web Token (JWT)
* bcrypt.js

### Version Control

* Git & GitHub

---

## 📂 Project Structure

```text
PingUp/
│
├── client/                 # React Frontend
│   ├── public/
│   ├── src/
│   └── package.json
│
├── backend/                # Express Backend
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── index.js
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mehulcodex-tech/pingup.git
cd pingup
```

---

### 2. Install Dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd ../backend
npm install
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd backend
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

Frontend:

```text
http://localhost:3000
```

Backend:

```text
http://localhost:5000
```

---

## 📌 API Features

### Authentication

* Register User
* Login User
* Get Logged-in User

### Posts

* Create Post
* Fetch Posts
* Update Post
* Delete Post
* Like / Unlike Post
* Add Comments

### Users

* View Profile
* Update Profile
* Follow / Unfollow Users

---

## 🔒 Security

* Password hashing with **bcrypt.js**
* JWT-based Authentication
* Protected Routes
* User-specific Authorization
* Secure REST APIs

---

## 🎯 Future Enhancements

* 💬 Real-time Chat
* 🔔 Notifications
* 📸 Image Uploads
* 🎥 Stories & Reels
* 🌙 Dark Mode
* 🔍 Search Users & Posts
* 📌 Saved Posts
* 🌐 Cloud Deployment
* 🤝 Friend Suggestions

---

## 📸 Screenshots

Add screenshots of:

* Login Page
* Signup Page
* Home Feed
* Profile Page
* Create Post
* Comments Section

---

## 👨‍💻 Author

**Mehul Gupta**

* GitHub: https://github.com/mehulcodex-tech

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub!
