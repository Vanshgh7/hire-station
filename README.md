# hire station App

A sleek, full-stack job portal crafted with the MERN stack. This application empowers job seekers (students) and recruiters to connect efficiently. Enjoy an animated, mobile-friendly interface where students can explore jobs, and recruiters can manage postings with minimal effort.

---

## ✨ Features

### ✅ General
- 🔐 Secure authentication with JWT
- 👥 Distinct dashboards for students and recruiters
- 🌐 Responsive design using Tailwind CSS 
- 🚦 Dynamic routing and smooth state transitions

### 🎓 For Students
- Search and browse current job listings
- Apply instantly for jobs
- Track applications via the personal dashboard

### 🧑‍💼 For Recruiters
- Post new job positions
- Review and manage applicants
- Update or remove job postings
- Oversee all listings in a unified dashboard

---

## 🎨 UI & Animations

The portal looks and feels modern thanks to Tailwind CSS. Framer Motion adds seamless animations, ensuring visually appealing transitions and feedback.

- Fully responsive layout for all devices
- Optional support for dark and light odes
- shadcn/ui for Flexible UI
- Animated modals, buttons, and transitions
- Accessible components throughout

---

## 🛠️ Tech Stack

### 🧑‍💻 Frontend
- React.js — Modular and fast
- Tailwind CSS — Modern styling
- shadcn/ui — Flexible UI components
- Framer Motion — Animation handling
- React Router — Smooth navigation
- Axios — Data fetching

### 🖥️ Backend
- Node.js — Server-side logic
- Express.js — API layer
- MongoDB — Database for jobs and users
- Mongoose — Data modeling
- JWT — User authentication

---

## 🔒 Authentication Flow

- Users register and log in with email and password
- JWT tokens issued for secure sessions
- User roles restrict access (student/recruiter)
- Protected endpoints for sensitive actions

---

## ⚙️ Getting Started

#### 1. Clone the Project

git clone https://github.com/Vanshgh7/hire-station.git
cd job-portal

#### 2. Configure Environment Variables

Create a `.env` file in the `server/` directory:

MONGODB_URI=""
PORT=8000
SECRET_KEY=""

CLOUDINARY_API_KEY=""
CLOUDINARY_SECRET_KEY=""
CLOUDINARY_NAME=""

NODE_ENV=""

#### 3. Install Packages

Frontend
cd client
npm install

Backend
cd ../server
npm install

#### 4. Launch the App

Start backend
cd server
npm run dev

Start frontend
cd ../client
npm start

text

- Frontend is live at: [**http://localhost:5137**](http://localhost:5137)
- Backend is live at: [**http://localhost:5000**](http://localhost:5000)
---

## 🙌 Contributions

Fork the repository, file issues, or submit pull requests—everyone is welcome to contribute and suggest improvements!
