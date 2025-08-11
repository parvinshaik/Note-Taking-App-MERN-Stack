# 📒 Note-Taking App
A full-stack **Note-Taking Web Application** built with the **MERN stack** (MongoDB, Express, React, Node.js) and styled using **Tailwind CSS**.  
The app allows users to **register**, **log in**, **create**, **edit**, **pin**, and **delete** notes with an intuitive UI.



## 🚀 Features
- **User Authentication**
  - Register with name, email, and password
  - Secure login & logout functionality
- **Note Management**
  - Create new notes with title, content, and tags
  - Edit existing notes
  - Pin/unpin notes for quick access
  - Delete notes
- **UI & UX**
  - Modern responsive design with Tailwind CSS
  - Smooth transitions & hover effects
  - Pin icon toggle
  - "Read More / Read Less" for long notes
- **Backend**
  - RESTful API with Express.js
  - MongoDB for data storage
  - JWT-based authentication
  - CORS-enabled API for frontend access



## 🛠️ Tech Stack
### Frontend
- React.js
- Tailwind CSS
- Axios
- React Icons
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Token (JWT)
- bcrypt.js


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/mern-note-app.git

cd mern-note-app

2️⃣ Setup Backend
cd backend
npm install


Create a .env file in backend/ with:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

Run backend:
node index.js

3️⃣ Setup Frontend
cd frontend
npm install

Create a .env file in frontend/ with:
REACT_APP_API_URL=http://localhost:5000/api

Run frontend:
npm run dev
