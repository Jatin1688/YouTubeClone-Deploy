# YouTube Clone – MERN Stack Project

This is a full-stack YouTube Clone built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). The application replicates key features of YouTube, allowing users to upload, view, like, and comment on videos.

---

## 🔧 Tech Stack

- **Frontend**: React.js, Redux (if used), Axios, HTML, CSS (or Tailwind/Bootstrap)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose for schema management)
- **Storage**: File system or cloud (e.g., Cloudinary, AWS S3 – depending on your implementation)
- **Authentication**: JWT (JSON Web Tokens), bcrypt
- **Tools**: Git, GitHub, npm/yarn

---

## 🚀 Features

### 🔹 User Features
- User Registration and Login (JWT Auth)
- Video upload with title, description, thumbnail
- Video playback with custom player
- Like and dislike functionality
- View counter
- Comment system
- Search videos by title
- Responsive design for mobile and desktop

### 🔹 Admin/Owner Features
- View all uploaded videos
- Delete videos
- Moderate comments

---

## 📂 Project Structure

```
root/
├── client/                 # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
├── server/                 # Node.js backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js (or index.js)
├── .gitignore
├── README.md
└── package.json
```

---

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/youtube_clone_nullclass.git
cd youtube_clone_nullclass
```

### 2. Install dependencies

#### For the backend:

```bash
cd server
npm install
```

#### For the frontend:

```bash
cd ../client
npm install
```

### 3. Environment Variables

Create a `.env` file inside your `server` directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

If you’re using a cloud video storage service (e.g., Cloudinary), include those credentials as well.

---

### 4. Start the application

#### Start the backend server:

```bash
cd server
npm start
```

#### Start the frontend:

```bash
cd client
npm start
```

By default:
- Frontend runs on: `http://localhost:3000`
- Backend runs on: `http://localhost:5000`

---
