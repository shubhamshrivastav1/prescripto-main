<div align="center">

# 🩺 PRESCRIPTO

### Full-Stack Doctor Appointment Booking & Management System

A modern healthcare platform that enables patients to discover doctors, book appointments, manage their profiles, and provides doctors and administrators with dedicated management dashboards.

<br />

[![Live Website](https://img.shields.io/badge/🌐_Live_Website-Prescripto-blue?style=for-the-badge)](https://prescripto-client-m3fe86doe-shubhamshrivastav1s-projects.vercel.app/)
[![Admin Dashboard](https://img.shields.io/badge/🎯_Admin-Dashboard-purple?style=for-the-badge)](https://prescripto-admin-nine-gamma.vercel.app/)
[![Backend API](https://img.shields.io/badge/⚙️_Backend-API-black?style=for-the-badge)](https://prescripto-backend-blond.vercel.app/)

<br />

![React](https://img.shields.io/badge/React.js-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [Live Demo](#-live-demo)
- [Demo Admin Access](#-demo-admin-access)
- [Features](#-features)
- [Technology Stack](#️-technology-stack)
- [System Architecture](#️-system-architecture)
- [Project Structure](#-project-structure)
- [Authentication & Security](#-authentication--security)
- [Database](#️-database)
- [Cloudinary](#️-cloudinary)
- [Application Workflow](#-application-workflow)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Production Deployment](#-production-deployment)
- [Testing](#-testing)
- [Screenshots](#-screenshots)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [Learning Outcomes](#-learning-outcomes)
- [Author](#-author)
- [License](#-license)

---

# 📌 About The Project

**Prescripto** is a full-stack **Doctor Appointment Booking & Management System** designed to make healthcare appointment management simple, organized, and accessible.

The platform provides dedicated interfaces for three different types of users:

| User Type | Responsibilities |
|-----------|------------------|
| 👤 **Patient** | Find doctors, view profiles, book appointments, and manage appointments |
| 🧑‍⚕️ **Doctor** | Manage appointments, update professional information, and view earnings |
| 🎯 **Admin** | Manage doctors, appointments, and overall platform operations |

Prescripto demonstrates a complete full-stack development workflow including:

- Modern React frontend
- RESTful backend API
- MongoDB database
- JWT authentication
- Password hashing
- Cloud image storage
- Role-based application flows
- Production deployment using Vercel

---

# 🌐 Live Demo

## 👤 Patient / User Website

🔗 **Live Website**

https://prescripto-client-m3fe86doe-shubhamshrivastav1s-projects.vercel.app/

Use the patient application to:

- Register a new account
- Login
- Browse doctors
- Search doctors
- Filter doctors by speciality
- View doctor details
- Book appointments
- View appointments
- Cancel appointments
- Manage profile

---

## 🎯 Admin Dashboard

🔗 **Admin Dashboard**

https://prescripto-admin-nine-gamma.vercel.app/

Admin functionality includes:

- Admin authentication
- Dashboard statistics
- Add doctors
- Upload doctor images
- Manage doctors
- View appointments
- Manage appointments

---

## ⚙️ Backend API

🔗 **Backend API**

https://prescripto-backend-blond.vercel.app/

The backend provides the API layer used by both the patient application and admin dashboard.

---

# 🔑 Demo Admin Access

> ⚠️ **Important:** Real production credentials must never be committed to a public GitHub repository.

For testing purposes, use a dedicated demo administrator account configured in the deployment environment.

### 🎯 Admin Login

**Admin URL:**

https://prescripto-admin-nine-gamma.vercel.app/

**Demo Email:**

```text
YOUR_DEMO_ADMIN_EMAIL
```

**Demo Password:**

```text
YOUR_DEMO_ADMIN_PASSWORD
```

> 💡 For a public portfolio project, create a separate demo admin account rather than publishing your personal or production credentials.

---

# ✨ Features

## 👤 Patient Features

### 🔐 Authentication

- User Registration
- User Login
- JWT-based Authentication
- Protected User Operations
- Secure Password Hashing

### 🔎 Doctor Discovery

- Browse Doctors
- Search Doctors
- Filter by Speciality
- View Doctor Profile
- View Doctor Experience
- View Doctor Education
- View Consultation Fees
- View Doctor Address
- View Doctor Availability

### 📅 Appointment Management

- Select Doctor
- Select Date
- Select Time
- Book Appointment
- View Booked Appointments
- Cancel Appointments
- Manage Existing Appointments

### 👤 Profile Management

- View Profile
- Update Profile Information
- Upload Profile Picture

---

# 🧑‍⚕️ Doctor Features

- Doctor Login
- Doctor Dashboard
- View Appointments
- Manage Appointments
- Update Appointment Status
- View Earnings
- Update Doctor Profile
- Manage Professional Information
- Manage Availability Information

---

# 🎯 Admin Features

- Admin Login
- Admin Dashboard
- Dashboard Statistics
- Add New Doctors
- Upload Doctor Profile Picture
- View All Doctors
- Manage Doctor Profiles
- View Appointments
- Manage Appointments
- Manage Platform Information

---

# 🛠️ Technology Stack

## 🎨 Frontend

| Technology | Usage |
|------------|-------|
| ⚛️ React.js | User Interface |
| ⚡ Vite | Development & Build Tool |
| 🟨 JavaScript | Application Logic |
| 🌐 HTML5 | Page Structure |
| 🎨 CSS3 | Styling |
| 🔗 Axios | API Communication |

---

## ⚙️ Backend

| Technology | Usage |
|------------|-------|
| 🟢 Node.js | Server Runtime |
| 🚀 Express.js | Backend Framework |
| 🍃 MongoDB | Database |
| 📦 Mongoose | MongoDB ODM |
| 🔐 JSON Web Token | Authentication |
| 🔒 bcrypt | Password Hashing |
| 📤 Multer | File Upload Handling |
| ☁️ Cloudinary | Image Storage |
| 🌐 CORS | Cross-Origin Requests |
| 🔧 dotenv | Environment Configuration |
| ✅ Validator | Input Validation |

---

## ☁️ Deployment & Services

| Service | Purpose |
|---------|---------|
| ▲ Vercel | Application Deployment |
| 🍃 MongoDB Atlas | Cloud Database |
| ☁️ Cloudinary | Image Storage |

---

# 🏗️ System Architecture

```text
                         ┌─────────────────────────┐
                         │      PATIENT / USER     │
                         │       REACT APP         │
                         └────────────┬────────────┘
                                      │
                                      │ REST API
                                      ▼
                         ┌─────────────────────────┐
                         │        BACKEND          │
                         │    NODE + EXPRESS       │
                         │       REST API          │
                         └────────────┬────────────┘
                                      │
                         ┌────────────┴────────────┐
                         │                         │
                         ▼                         ▼
                ┌──────────────────┐     ┌──────────────────┐
                │     MongoDB      │     │    Cloudinary    │
                │     Database     │     │  Image Storage   │
                └──────────────────┘     └──────────────────┘
                                      ▲
                                      │
                                      │ REST API
                                      │
                         ┌────────────┴────────────┐
                         │       ADMIN APP         │
                         │      REACT + VITE       │
                         └─────────────────────────┘
```

---

# 📂 Project Structure

```text
prescripto-main/
│
├── backend/
│   ├── config/
│   │   ├── cloudinary.js
│   │   └── mongodb.js
│   │
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── package.json
│   └── server.js
│
├── clientside/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── App.jsx
│   ├── package.json
│   └── vite.config.js
│
├── admin/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

---

# 🔐 Authentication & Security

Prescripto uses **JSON Web Tokens (JWT)** for authentication and protected API operations.

### Authentication Flow

```text
             User Login / Registration
                       │
                       ▼
                Backend API
                       │
                       ▼
              Credential Validation
                       │
                       ▼
                 JWT Generated
                       │
                       ▼
               Client Stores Token
                       │
                       ▼
              Protected API Requests
```

### Password Security

Passwords are hashed using **bcrypt** before being stored in the database.

### Protected Operations

Authentication protects operations such as:

- User profile management
- Appointment booking
- Appointment cancellation
- Doctor operations
- Admin operations

---

# 🗄️ Database

Prescripto uses **MongoDB** as the primary database with **Mongoose** for database interaction.

### Main Data

```text
Users
 │
 ├── Authentication
 ├── Profile Information
 └── Appointments
       
Doctors
 │
 ├── Professional Information
 ├── Speciality
 ├── Experience
 ├── Education
 ├── Fees
 └── Availability

Appointments
 │
 ├── User
 ├── Doctor
 ├── Date
 ├── Time
 └── Status
```

---

# ☁️ Cloudinary

**Cloudinary** is integrated for cloud-based image storage and management.

Images can include:

- User profile pictures
- Doctor profile pictures
- Application-related images

---

# 🔄 Application Workflow

## 👤 Patient Workflow

```text
Open Website
     ↓
Register / Login
     ↓
Browse Doctors
     ↓
Search / Filter
     ↓
Select Doctor
     ↓
View Doctor Profile
     ↓
Select Date & Time
     ↓
Book Appointment
     ↓
View Appointment
     ↓
Manage / Cancel Appointment
```

---

## 🧑‍⚕️ Doctor Workflow

```text
Doctor Login
     ↓
Doctor Dashboard
     ↓
View Appointments
     ↓
Manage Appointments
     ↓
View Earnings
     ↓
Update Profile
```

---

## 🎯 Admin Workflow

```text
Admin Login
     ↓
Admin Dashboard
     ↓
View Statistics
     ↓
Add Doctor
     ↓
Upload Doctor Image
     ↓
Manage Doctors
     ↓
View Appointments
     ↓
Manage Appointments
```

---

# 🚀 Getting Started

Follow these steps to run Prescripto locally.

---

## 📋 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm
- Git
- MongoDB Atlas account
- Cloudinary account

---

# 1️⃣ Clone the Repository

```bash
git clone https://github.com/shubhamshrivastav1/prescripto-main.git
```

Navigate to the project:

```bash
cd prescripto-main
```

---

# 2️⃣ Backend Setup

Navigate to the backend:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `backend` folder.

```env
MONGODB_URI=your_mongodb_connection_string

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

JWT_SECRET=your_jwt_secret

ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
```

Start the backend:

```bash
npm start
```

For development:

```bash
npm run server
```

---

# 3️⃣ Client Setup

Open a new terminal.

Navigate to the client:

```bash
cd prescripto-main/clientside
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
VITE_BACKEND_URL=http://localhost:4000
```

Start the client:

```bash
npm run dev
```

---

# 4️⃣ Admin Setup

Open another terminal.

Navigate to the admin application:

```bash
cd prescripto-main/admin
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
VITE_BACKEND_URL=http://localhost:4000
```

Start the admin application:

```bash
npm run dev
```

---

# 🔑 Environment Variables

## Backend

```env
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
```

## Client

```env
VITE_BACKEND_URL=http://localhost:4000
```

## Admin

```env
VITE_BACKEND_URL=http://localhost:4000
```

> ⚠️ Never commit `.env` files to GitHub.

---

# 🌍 Production Deployment

Prescripto is deployed using **Vercel**.

### ⚙️ Backend API

https://prescripto-backend-blond.vercel.app/

### 👤 Patient Website

https://prescripto-client-m3fe86doe-shubhamshrivastav1s-projects.vercel.app/

### 🎯 Admin Dashboard

https://prescripto-admin-nine-gamma.vercel.app/

---

# 🔗 Production Backend Configuration

The frontend and admin applications communicate with the deployed backend using:

```env
VITE_BACKEND_URL=https://prescripto-backend-blond.vercel.app
```

This variable must be configured in the respective Vercel project environment settings.

> ⚠️ `VITE_` variables are exposed to the browser. Only public configuration should be stored in them.

---

# 🛡️ Security Guidelines

Never publish sensitive credentials.

### ❌ Do NOT commit

```text
.env
.env.local

MongoDB Password
MongoDB Connection String

Cloudinary API Secret

JWT Secret

Admin Password

Private API Keys

Access Tokens
```

### ✅ Use Environment Variables

```text
Local Development
       ↓
      .env
       ↓
Environment Variables
       ↓
Application

Production
       ↓
Vercel Environment Variables
       ↓
Application
```

---

# 🧪 Testing

## 👤 Patient Testing

- [ ] User registration works
- [ ] User login works
- [ ] Authentication works
- [ ] Doctors are displayed
- [ ] Doctor search works
- [ ] Speciality filtering works
- [ ] Doctor profile opens
- [ ] Doctor details are displayed
- [ ] Appointment booking works
- [ ] Appointment list works
- [ ] Appointment cancellation works
- [ ] Profile update works
- [ ] Profile image upload works

---

## 🧑‍⚕️ Doctor Testing

- [ ] Doctor login works
- [ ] Doctor dashboard loads
- [ ] Appointments are displayed
- [ ] Appointment management works
- [ ] Earnings are displayed
- [ ] Doctor profile update works
- [ ] Professional information can be updated

---

## 🎯 Admin Testing

- [ ] Admin login works
- [ ] Admin dashboard loads
- [ ] Dashboard statistics are displayed
- [ ] Admin can add doctors
- [ ] Doctor image upload works
- [ ] Doctors can be viewed
- [ ] Doctors can be managed
- [ ] Appointments can be viewed
- [ ] Appointments can be managed

---

# 📸 Screenshots

Add screenshots of your deployed application here.

### 👤 Patient Website

```markdown
![Prescripto Patient Website](./screenshots/patient-home.png)
```

### 🧑‍⚕️ Doctor Dashboard

```markdown
![Prescripto Doctor Dashboard](./screenshots/doctor-dashboard.png)
```

### 🎯 Admin Dashboard

```markdown
![Prescripto Admin Dashboard](./screenshots/admin-dashboard.png)
```

---

# 📊 Project Highlights

| Category | Implementation |
|----------|----------------|
| Frontend | React.js + Vite |
| Backend | Node.js + Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Authentication | JWT |
| Password Security | bcrypt |
| File Upload | Multer |
| Image Storage | Cloudinary |
| API Communication | Axios |
| Deployment | Vercel |
| Architecture | Full-Stack Client / Server |

---

# 💳 Payment Status

The current project includes payment-related UI elements, but a complete online payment gateway integration is **not currently implemented**.

Possible future integrations:

- 💳 Razorpay
- 💳 Stripe

---

# 🚧 Future Improvements

Planned improvements for future versions include:

- 💳 Online Payment Integration
- 📧 Email Notifications
- 🔔 Appointment Reminders
- 📅 Advanced Doctor Availability Calendar
- 🩺 Patient Medical History
- 📄 Digital Prescription Management
- 🎥 Video Consultation
- 📊 Advanced Admin Analytics
- 🔎 Advanced Appointment Filtering
- 📱 Improved Mobile Responsiveness
- 🌍 Multi-language Support
- 🔐 Additional Security Improvements

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

### 1. Fork the Repository

Fork this repository to your GitHub account.

### 2. Clone the Repository

```bash
git clone https://github.com/shubhamshrivastav1/prescripto-main.git
```

### 3. Create a Feature Branch

```bash
git checkout -b feature/your-feature
```

### 4. Make Your Changes

Implement and test your changes locally.

### 5. Commit Your Changes

```bash
git add .
git commit -m "Add your feature"
```

### 6. Push Your Branch

```bash
git push origin feature/your-feature
```

Then open a Pull Request.

---

# 📚 Learning Outcomes

This project demonstrates practical experience with:

- React.js
- Vite
- JavaScript
- Node.js
- Express.js
- REST API Development
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt Password Hashing
- Multer File Uploads
- Cloudinary
- Axios
- Role-Based Application Architecture
- Environment Variables
- API Integration
- Full-Stack Development
- Production Deployment
- Vercel

---

# 🔮 Future Vision

Prescripto can be expanded into a complete digital healthcare ecosystem.

```text
                         PRESCRIPTO
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
       PATIENT             DOCTOR              ADMIN
          │                   │                   │
     ┌────┼────┐         ┌────┼────┐        ┌────┼────┐
     │    │    │         │    │    │        │    │    │
     ▼    ▼    ▼         ▼    ▼    ▼        ▼    ▼    ▼
  Booking Profile     Schedule Patients  Doctors Appointments
  History  Payments   Earnings Prescriptions Analytics Management
```

Potential future capabilities:

- Digital prescriptions
- Medical records
- Online payments
- Video consultations
- Doctor scheduling
- Automated notifications
- Patient medical history
- Advanced analytics
- Healthcare reminders

---

# 👨‍💻 Author

## Shubham Shrivastav

**Full-Stack Developer**

### GitHub

🔗 https://github.com/shubhamshrivastav1

### Project Repository

🔗 https://github.com/shubhamshrivastav1/prescripto-main

---

# ⭐ Support The Project

If you like this project, consider supporting it by:

- ⭐ Giving the repository a Star
- 🍴 Forking the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🤝 Contributing to the project

---

# 📄 License

This project is created for **learning, development, and portfolio purposes**.

---

<div align="center">

## 🩺 PRESCRIPTO

### Doctor Appointment Booking & Management System

**Patient Website • Doctor Panel • Admin Dashboard**

Built with ❤️ using **React • Node.js • Express • MongoDB**

<br />

⭐ **If you like this project, don't forget to star the repository!** ⭐

</div>
