<<<<<<< HEAD
# Job Portal 🧑‍💼💻

A full-stack Job Portal web application built with the MERN stack (MongoDB, Express, React, Node.js) that allows job seekers to apply for jobs and companies to post job openings.

## 🔗 Live Links

* **Frontend**: [Live on Render](https://jobportal-frontend-vjgp.onrender.com)
* **Backend**: [Live API](https://jobportal-2-9aor.onrender.com)

## ✨ Features

* User Authentication (Signup/Login)
* Job Listings and Search
* Apply for Jobs
* Company Dashboard to Post/Edit/Delete Jobs
* Responsive Design using Tailwind CSS

## 🧪 Tech Stack

* **Frontend**: React, Tailwind CSS, Vite
* **Backend**: Node.js, Express
* **Database**: MongoDB (with Mongoose)

## 📦 Installation

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## 🌐 Environment Variables

Create a `.env` file in the `backend` folder and add:

```env
PORT=8000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## 📁 API Endpoints

Base URL: `https://jobportal-2-9aor.onrender.com`

* `POST /api/v1/user/register` — Register user
* `POST /api/v1/user/login` — Login user
* `GET /api/v1/job/all-jobs` — List all jobs
* `POST /api/v1/job/create-job` — Create a job (Company only)
* `POST /api/v1/application/apply/:jobId` — Apply to job

## 🧑‍💻 Author

Created by [pushpam kumar](https://github.com/pushpamkumar)

## 📄 License

[MIT](LICENSE)

