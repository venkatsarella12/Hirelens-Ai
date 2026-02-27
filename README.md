🚀 HireLens AI

AI-powered Resume-to-Job Compatibility Analyzer built with a hybrid scoring system (Rule-Based + LLM Semantic Analysis).

📌 Overview

HireLens AI is a full-stack web application that evaluates how well a candidate’s resume matches a job description.

Instead of relying only on AI, the system combines:

Rule-based keyword extraction

Skill overlap calculation

LLM-powered contextual evaluation

Weighted hybrid scoring logic

The platform generates a structured compatibility report including:

Match percentage

Missing skills

Strength highlights

Actionable improvement suggestions

🎯 Problem Statement

Job seekers apply blindly without knowing:

If their resume aligns with the role

What technical gaps exist

How competitive their profile is

HireLens AI provides instant, structured, and data-driven feedback.

🧠 Core Features

Secure User Authentication (JWT-based)

Resume Upload (PDF + Text Input Option)

Automatic Skill Extraction Engine

AI-Powered Semantic Resume Analysis

Hybrid Match Score Calculation

Interactive Dashboard with History

Modern UI with Dynamic Effects & Animations

Fully Responsive Design

🏗 System Architecture

Frontend (Next.js + Tailwind CSS)
⬇
Backend API (Node.js + Express)
⬇
MongoDB Atlas
⬇
OpenAI API (LLM Analysis)

🧮 Hybrid Scoring Logic

The final match score is calculated using:

Rule-Based Skill Matching

AI Semantic Evaluation

Formula:

Final Score = (0.6 × Skill Match Score) + (0.4 × AI Score)

This ensures logical consistency and avoids blind AI dependency.

🛠 Tech Stack
Frontend

Next.js (App Router)

Tailwind CSS

Framer Motion

Axios

Backend

Node.js

Express.js

MongoDB Atlas

JWT Authentication

Multer (File Upload)

PDF-Parse

AI Integration

OpenAI API (Structured JSON Prompting)

📂 Project Structure
Backend
backend/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── utils/
└── server.js
Frontend
frontend/
│
├── app/
├── components/
├── lib/
└── styles/
🔑 Environment Variables

Create a .env file inside backend:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_openai_key

Never commit .env to version control.

🚀 Installation
Clone Repository
git clone https://github.com/yourusername/hirelens-ai.git
Backend Setup
cd backend
npm install
npm run dev
Frontend Setup
cd frontend
npm install
npm run dev
📊 Sample AI Response
{
  "ai_match_score": 88,
  "missing_skills": ["CI/CD pipelines", "Advanced AWS deployment"],
  "strengths": [
    "Strong Node.js experience",
    "REST API development",
    "Good MongoDB schema design"
  ],
  "improvement_suggestions": [
    "Add measurable impact metrics",
    "Mention specific AWS services used",
    "Include CI/CD experience if available"
  ]
}
🌐 Deployment

Frontend: Vercel

Backend: Render

Database: MongoDB Atlas

🔮 Future Improvements

Resume rewriting AI

Role-based optimization modes

Downloadable PDF analysis report

Recruiter comparison dashboard

Skill-gap learning roadmap generator

📈 Why This Project Stands Out

Hybrid AI + Rule-Based architecture

Structured JSON prompt engineering

Scalable backend design

Production-style deployment

Solves a real job-seeking problem

👤 Author

Sarella Venkat
Full-Stack Developer | AI Enthusiast
