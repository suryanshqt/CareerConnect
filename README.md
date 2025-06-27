CareerConnect — MERN Job Portal Web App

CareerConnect is a full-stack job portal application built using the MERN stack (MongoDB, Express, React, Node.js). It enables recruiters to post and manage job opportunities while allowing job seekers to discover and apply to relevant positions. Developed as a comprehensive learning exercise in full-stack development.


Key Features :-
Recruiter Capabilities
Create, edit, and delete job postings
Manage applicant pipeline (view applications, update status)
Company profile management
Dashboard analytics for job performance

Job Seeker Capabilities
Browse and filter job listings
Submit applications with resume/CV
Track application status history
Personal profile management

Security & UX
JWT-based authentication with role-based access control
Responsive design for all device sizes
Form validation and error handling
Protected routes for authenticated users

Tech Stack
Layer    Technology    Purpose
Database    MongoDB Atlas    Cloud NoSQL data storage
Backend    Node.js, Express.js, Mongoose    API development & data modeling
Auth    JSON Web Tokens (JWT), bcryptjs    Secure authentication
Frontend    React.js, React Router, Context API    SPA with state management
Styling    Bootstrap 5, CSS3    Responsive UI components
Build    Webpack, Babel    Code transpilation & bundling
Deployment    Render (Backend), Vercel (Frontend)    Cloud hosting solutions
Application Screenshots
Authentication & Onboarding
Login Page    Signup Page
https://./screenshots/Login.png    https://./screenshots/SignUp.png
User Experience
Home Page    Job Listings
https://./screenshots/Home.png    https://./screenshots/Job.png
Recruiter Workspace
Dashboard    Company Management
https://./screenshots/Company.png    https://./screenshots/Company2.png
Job Management
Create New Job    Job Details
https://./screenshots/Job2.png    https://./screenshots/Job3.png
Job Seeker Experience
Applicant Dashboard    Browse Jobs
https://./screenshots/applicant.png    https://./screenshots/Browse.png
Getting Started
Prerequisites
Node.js (v16+)

MongoDB Atlas account

Git

Installation
Clone repository:

bash
git clone https://github.com/your-username/CareerConnect.git
cd CareerConnect
Install backend dependencies:

bash
cd server
npm install
Install frontend dependencies:

bash
cd ../client
npm install
Configuration
Create .env file in server directory:

env
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secure_jwt_secret
PORT=5000
Start development servers:

bash
# Terminal 1 (backend)
cd server
npm run dev

# Terminal 2 (frontend)
cd client
npm start
Access application at http://localhost:3000

Project Structure
bash
CareerConnect/
├── client/            # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── context/     # Auth context providers
│   │   ├── pages/       # Application screens
│   │   ├── utils/       # Helper functions
│   │   └── App.js       # Main application router
│
├── server/            # Express backend
│   ├── config/        # Database configuration
│   ├── controllers/   # Business logic handlers
│   ├── middleware/    # Authentication middleware
│   ├── models/        # MongoDB schemas
│   ├── routes/        # API endpoints
│   └── server.js      # Server entry point
Future Enhancements
Monetization
Premium job listings with payment integration (Stripe/PayPal)

Enhanced Discovery
Advanced search with filters (salary, experience, remote)
Saved jobs and search alerts

Communication
Email notifications for application updates
Real-time chat between recruiters/applicants

Analytics
Admin dashboard with job market insights
Applicant tracking metrics for recruiters

Accessibility
WCAG 2.1 compliant interfaces
Multi-language support
