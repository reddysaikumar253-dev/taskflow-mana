**TaskFlow-Management**

TaskFlow-Management is a modern and intuitive task & workflow management system designed to help individuals and teams organize work efficiently.
Built with a powerful tech stack — MongoDB, Express.js, React (Vite), Node.js, Tailwind CSS, and JWT Auth — the application offers a seamless, secure, and responsive user experience.

The platform allows users to:

Create, edit, delete, and organize tasks

Track task progress across multiple workflow stages

Use drag-and-drop functionality for effortless task movement

Manage priorities and deadlines

Securely register, log in, and access personalized dashboards

Experience a fast frontend powered by Vite and a scalable backend powered by Node/Express

TaskFlow-Mana’s goal is to simplify day-to-day task management with a clean UI, strong backend structure, and scalable architecture — making it suitable for students, developers, teams, and productivity enthusiasts.



**Live Links**

**Frontend**

Vercel Production: https://taskflow-mana.vercel.app

Backup Deploy 1: https://taskflow-mana-git-main-sais-projects-6a47578a.vercel.app

Backup Deploy 2: https://taskflow-mana-c03293o7h-sais-projects-6a47578a.vercel.app

**Backend**

Render API: https://taskflow-mana.onrender.com



**Local Development Setup**

**Clone the Repository**

git clone https://github.com/reddysaikumar253-dev/taskflow-mana.git

cd taskflow-mana

**Backend Setup**

**Install backend dependencies**

cd server

npm install

**Start backend**

npm run dev

**Frontend Setup**

**Install frontend dependencies**

cd client

npm install

**Run frontend**

npm run dev



**Features Implemented**

**Authentication**

User Registration

User Login

JWT-based authentication

Protected routes

Logout


**Task Management**

Create, update, delete tasks

Drag & drop workflow using Hello-Pangea DnD

Status categories: Todo → In Progress → Done

Task priority management

Persistent storage via MongoDB


**User Dashboard**

Displays task overview

Personal info and settings

Fully responsive UI


**Admin / System Features**

Centralized error handling

CORS with whitelisted origins

Middleware-based auth


**UI/UX**

Built with Tailwind CSS

Clean & modern layout

Smooth drag-and-drop interactions



**Additional Notes**

This project uses Vite for fast frontend development.

Backend is deployed on Render (free tier) — first call may take 30–60 seconds to wake up.

Add .env files in both frontend and backend before running locally.

Future enhancements planned:

Team collaboration

Task comments

File uploads

Real-time updates (WebSockets)

Notifications system
