# JobZee - MERN Stack Job Seeking Web Application

JobZee is a full-stack web application built with the MERN stack (MongoDB, Express.js, React, Node.js) that connects job seekers and employers. Job seekers can browse and apply for jobs, while employers can post and manage job listings and view applications.

## Features

### For Job Seekers

- Register and login as a job seeker
- Browse all available jobs
- View detailed job descriptions
- Apply for jobs with resume upload (image format)
- View and manage your applications

### For Employers

- Register and login as an employer
- Post new job listings
- View and edit your posted jobs
- Delete jobs
- View applications from job seekers

### General

- Responsive and modern UI
- Authentication with JWT and cookies
- File upload support for resumes (image formats)
- Toast notifications for user feedback

## Tech Stack

- **Frontend:** React, Vite, React Router, Axios, React Hot Toast, React Icons
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT, Cloudinary (for resume uploads)
- **Other:** dotenv, cookie-parser, express-fileupload, CORS

## Folder Structure

MERN-Stack-Job-Seeking-Web-Application/ backend/ controllers/ database/ middlewares/ models/ routes/ utils/ app.js server.js package.json config/ frontend/ public/ src/ index.html App.jsx App.css package.json vite.config.js

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB instance (local or cloud)
- Cloudinary account for resume uploads

### Backend Setup

1. Navigate to the `backend` folder:

   ```sh
   cd backend


   2. Installl Dependencies
   npm install

   3. Create a config/config.env file with the following variables:
   PORT=4000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET_KEY=your_jwt_secret
   JWT_EXPIRES=7d
   COOKIE_EXPIRE=7
   CLOUDINARY_CLIENT_NAME=your_cloudinary_cloud_name
   CLOUDINARY_CLIENT_API=your_cloudinary_api_key
   CLOUDINARY_CLIENT_SECRET=your_cloudinary_api_secret
   FRONTEND_URL=http://localhost:5173

   ```

2. Start the backend Server
   npm run dev

Frontend Setup

1. Navigate to the frontend folder
   cd ../frontend

2. Install dependencies
   npm install

3.Start the frontend development server:
npm run dev

4.Open http://localhost:5173 in your browser.

Usage
Register as a Job Seeker or Employer.
Job Seekers can browse jobs and apply.
Employers can post jobs and manage applications.

License
This project is for educational purposes.

Developed by Vicky Kumar
Contact vk2388275@gmail for any project related information
