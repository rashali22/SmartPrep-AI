# 🚀 SmartPrep AI – AI-Powered Interview Preparation Platform

SmartPrep AI is a full-stack AI-powered interview preparation platform that helps job seekers prepare for technical and behavioral interviews by generating personalized interview reports based on their resume, self-description, and job description.

The platform uses Google's Gemini AI to generate interview questions, identify skill gaps, provide a day-wise preparation roadmap, and even create an ATS-friendly resume PDF.

---

## ✨ Features

### 🔐 Authentication
- User Registration
- User Login
- JWT Authentication
- Secure Password Hashing using bcrypt
- Logout Functionality

### 🤖 AI Interview Report
- Upload Resume (PDF)
- Enter Job Description
- Enter Self Description
- AI-generated Interview Report
- Match Score
- Technical Interview Questions
- Behavioral Interview Questions
- Question Intentions
- Detailed Sample Answers
- Skill Gap Analysis
- 7-Day Personalized Preparation Plan

### 📄 Resume Generator
- AI-generated ATS-friendly Resume
- Resume PDF Generation using Puppeteer

### 📊 Dashboard
- View Previous Interview Reports
- Report History
- Resume Download

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Vite
- React Router
- SCSS
- Axios

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js
- Multer
- PDF Parse
- Puppeteer

## AI
- Google Gemini 3.1 Flash Lite API

## Database
- MongoDB Atlas

---

# 📂 Project Structure

```
SmartPrep-AI
│
├── client
│   ├── components
│   ├── hooks
│   ├── pages
│   ├── services
│   ├── styles
│   └── utils
│
├── server
│   ├── controllers
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── services
│   └── config
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/smartprep-ai.git
```

```bash
cd smartprep-ai
```

---

## Install Frontend

```bash
cd client
npm install
```

---

## Install Backend

```bash
cd server
npm install
```

---

# 🔑 Environment Variables

## Backend (.env)

```env
PORT=3000

MONGODB_URI=YOUR_MONGODB_CONNECTION_STRING

JWT_SECRET=YOUR_SECRET_KEY

GOOGLE_GENAI_API_KEY=YOUR_GEMINI_API_KEY

CLIENT_URL=http://localhost:5173
```

---

## Frontend (.env)

```env
VITE_API_BASE_URL=http://localhost:3000
```

---

# ▶️ Run Locally

### Backend

```bash
npm run dev
```

### Frontend

```bash
npm run dev
```


# 📌 Future Improvements

- Mock Interview Voice Assistant
- AI Feedback on Spoken Answers
- Interview Performance Analytics
- Resume ATS Score
- Company-specific Interview Preparation
- Dark Mode
- Multi-language Support

---

# 💡 Learning Outcomes

This project helped me gain practical experience with:

- MERN Stack Development
- REST API Development
- JWT Authentication
- MongoDB Atlas
- File Upload using Multer
- AI Integration using Google Gemini
- PDF Parsing
- Puppeteer PDF Generation
- Authentication & Authorization
- Deployment using Vercel and Render
- Full Stack Project Architecture



