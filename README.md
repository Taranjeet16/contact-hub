# Contact Management Web App (MERN Stack)

A full-stack **Contact Management Web Application** built using the **MERN stack** as part of a Web Developer interview assignment.

---

## 🚀 Features

- Add, update, delete contacts
- Contact fields:
  - Name (required)
  - Email (valid format)
  - Phone (required)
  - Category (optional)
  - Message (optional)
- Client-side form validation
- Contacts stored in MongoDB
- Real-time UI updates without page reload
- Responsive and clean UI

---

## 🛠 Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- React Query

### Backend
- Node.js
- Express.js
- MongoDB (MongoDB Atlas)

---

## 📁 Project Structure
contact-hub/
├── frontend/
└── backend/

---

## 🔗 Live Demo

- **Frontend (Vercel)**  
  https://contact-hub-frontend.vercel.app/

- **Backend API (Render)**  
  https://contact-hub-backend.onrender.com/api/contacts

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|------|--------|------------|
| GET | /api/contacts | Fetch all contacts |
| POST | /api/contacts | Create new contact |
| PUT | /api/contacts/:id | Update contact |
| DELETE | /api/contacts/:id | Delete contact |

---

## ▶️ Run Locally

### Backend
cd backend
npm install
npm run dev

Create .env file:
MONGO_URI=your_mongodb_connection_string
PORT=5000

### Frontend
cd frontend
npm install
npm run dev

🌐 Deployment
Frontend deployed on Vercel
Backend deployed on Render
Database hosted on MongoDB Atlas

🔗 Links
Frontend-: https://github.com/Taranjeet16/contact-hub-frontend.git
Backend-: https://github.com/Taranjeet16/contact-hub-backend.git

👤 Author
Taranjeet Singh
B.Tech – Computer Science & Engineering
Aspiring MERN Stack Developer
