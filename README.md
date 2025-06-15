# 📝 NOTEs.me

A full-stack Note Taking Application that allows users to create, read, update, and delete personal notes securely. Built with **React.js**, **Node.js**, **Express.js**, and **MongoDB**, this project implements full authentication and RESTful APIs to manage user-specific data efficiently.

## 🚀 Features

- 🔐 User Authentication (Login/Signup with JWT)
- 🗂️ Create, Read, Update, Delete (CRUD) Notes
- 🔍 Search and filter notes in real-time
- 🎨 Responsive and clean UI with React
- 🌐 RESTful API with secure endpoints
- ☁️ Deployed on Render (Backend) and Netlify (Frontend)

## 🛠️ Tech Stack

**Frontend**  
- React.js  
- Axios  
- React Router DOM  
- Tailwind CSS

**Backend**  
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JSON Web Token (JWT)  
- bcrypt.js

## 🌐 Deployment

- **Project Link**: [Netlify](https://notes-me-web.netlify.app/)  



## 📸 Screenshots

![Screenshot 2024-07-24 011426](https://github.com/user-attachments/assets/6b3f46fc-fea6-49e8-ac5a-10f8403f7b13)
![Screenshot 2024-07-24 011444](https://github.com/user-attachments/assets/c2462b2b-b027-4492-8cab-9e5ecf052942)




## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Shivang139/NOTEs.me.git
cd NOTEs.me
```
### 2. Setup Backend
```
cd backend
npm install
# Add your .env file with MongoDB URI and JWT_SECRET
npm start
```

### 3. Setup Frontend

```
cd frontend
npm install
npm start
```

### 4. Environment Variables

```
In backend/.env:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

```

## 📂 Folder Structure
```
NOTEs.me/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
└── README.md
```

## 🧠 Future Enhancements

#### 1. Add note categories/tags

#### 2. Dark mode toggle

#### 3. Rich text editor for notes

#### 4. Notes sharing or collaboration

## 🙋‍♂️ Author

### Shivang Agrawal
