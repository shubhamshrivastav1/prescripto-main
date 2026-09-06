<div align="center">

# 🩺 PRESCRIPTO

### Full-Stack Doctor Appointment Booking System

A modern full-stack healthcare appointment management platform that connects patients, doctors, and administrators through a secure and user-friendly web application.

<p>
  <a href="https://prescripto-client-m3fe86doe-shubhamshrivastav1s-projects.vercel.app/">🌐 Live Website</a>
  &nbsp; • &nbsp;
  <a href="https://prescripto-admin-nine-gamma.vercel.app/">🎯 Admin Dashboard</a>
  &nbsp; • &nbsp;
  <a href="https://prescripto-backend-blond.vercel.app/">⚙️ Backend API</a>
</p>

</div>

---

## 📌 About The Project

**Prescripto** is a full-stack Doctor Appointment Booking System developed to simplify the process of finding doctors, booking appointments, and managing healthcare-related operations online.

The platform provides dedicated functionality for:

- 👤 **Patients** – Discover doctors and book appointments
- 🧑‍⚕️ **Doctors** – Manage appointments and professional information
- 🎯 **Administrators** – Manage doctors, appointments, and platform operations

The project follows a modern client-server architecture using **React.js, Node.js, Express.js, MongoDB, JWT, Cloudinary, and Vercel**.

---

## ✨ Key Features

### 👤 Patient Features

- User registration and login
- JWT-based authentication
- Browse available doctors
- Search doctors
- Filter doctors by speciality
- View detailed doctor profiles
- View doctor experience and education
- View consultation fees
- View doctor address
- Book appointments
- View booked appointments
- Cancel appointments
- Update profile information
- Upload profile picture

---

### 🧑‍⚕️ Doctor Features

- Doctor authentication
- Doctor dashboard
- View appointments
- Manage appointments
- View earnings
- Update doctor profile
- Manage professional information
- Manage appointment information

---

### 🎯 Admin Features

- Admin authentication
- Admin dashboard
- Add new doctors
- Upload doctor profile pictures
- View all doctors
- Manage doctor profiles
- View appointments
- Manage appointments
- View application statistics
- Manage platform information

---

## 🛠️ Technology Stack

### Frontend

| Technology | Purpose |
|------------|---------|
| ⚛️ React.js | Frontend UI |
| ⚡ Vite | Frontend build tool |
| 🟨 JavaScript | Application logic |
| 🎨 CSS3 | Styling |
| 🌐 HTML5 | Structure |
| 🔗 Axios | API communication |

### Backend

| Technology | Purpose |
|------------|---------|
| 🟢 Node.js | Server-side runtime |
| 🚀 Express.js | Backend framework |
| 🍃 MongoDB | Database |
| 📦 Mongoose | MongoDB ODM |
| 🔐 JWT | Authentication |
| 🔒 bcrypt | Password hashing |
| 📤 Multer | File uploads |
| ☁️ Cloudinary | Image storage |
| 🌐 CORS | Cross-origin requests |
| 🔧 dotenv | Environment configuration |
| ✅ Validator | Input validation |

### Deployment & Services

- ▲ Vercel
- 🍃 MongoDB Atlas
- ☁️ Cloudinary

---

## 🏗️ System Architecture

```text
                         ┌─────────────────────────┐
                         │       PATIENT           │
                         │     USER WEBSITE        │
                         └────────────┬────────────┘
                                      │
                                      │ REST API
                                      ▼
                         ┌─────────────────────────┐
                         │        BACKEND          │
                         │    Node.js + Express    │
                         └────────────┬────────────┘
                                      │
                         ┌────────────┴────────────┐
                         │                         │
                         ▼                         ▼
                  ┌───────────────┐        ┌───────────────┐
                  │    MongoDB    │        │   Cloudinary  │
                  │    Database   │        │ Image Storage │
                  └───────────────┘        └───────────────┘
                                      ▲
                                      │
                                      │ REST API
                                      │
                         ┌────────────┴────────────┐
                         │                         │
                         │        ADMIN            │
                         │       DASHBOARD         │
                         └─────────────────────────┘
```

---

## 📂 Project Structure

```text
prescripto-main/
│
├── backend/
│   ├── config/
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
│   ├── package.json
│   └── vite.config.js
│
├── admin/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

---

## 🔐 Authentication & Security

Prescripto uses **JSON Web Token (JWT)** based authentication for secure user sessions.

### Authentication

The application supports separate authentication flows for:

- 👤 Patients
- 🧑‍⚕️ Doctors
- 🎯 Administrators

### Password Security

User passwords are securely hashed using **bcrypt** before being stored in the database.

### Environment Variables

Sensitive configuration is managed through environment variables instead of hardcoding credentials in the source code.

> ⚠️ Never commit `.env` files, database credentials, API secrets, JWT secrets, or admin passwords to GitHub.

---

## 🗄️ Database

**MongoDB** is used as the primary database, with **Mongoose** providing schema definitions and database interaction.

The application manages data such as:

- 👤 User accounts
- 🧑‍⚕️ Doctor profiles
- 📅 Appointments
- 🏥 Doctor information
- 👤 User profile information
- 📋 Appointment status
- 💰 Appointment and earnings information

---

## ☁️ Image Management

**Cloudinary** is used for cloud-based image storage and management.

The application can manage images such as:

- Doctor profile pictures
- User profile pictures
- Application-related images

---

# 🚀 Getting Started

Follow the steps below to run Prescripto locally.

---

## 📋 Prerequisites

Before running the project, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm
- MongoDB / MongoDB Atlas account
- Cloudinary account
- Git

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/shubhamshrivastav1/prescripto-main.git
```

Navigate into the project:

```bash
cd prescripto-main
```

---

# ⚙️ Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `backend` directory:

```env
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
```

### Start Backend Server

For production-style start:

```bash
npm start
```

For development using Nodemon:

```bash
npm run server
```

The backend will run on the configured server port.

---

# 👤 Client / User Website Setup

Open a new terminal and navigate to the project:

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

Start the development server:

```bash
npm run dev
```

The Vite development server will provide a local URL in the terminal.

---

# 🎯 Admin Dashboard Setup

Open another terminal and navigate to:

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

Start the admin dashboard:

```bash
npm run dev
```

The admin dashboard will be available at the local URL shown by Vite.

---

# 🌍 Live Deployment

The application is deployed using **Vercel**.

### 👤 Patient / User Website

🌐 [Open Prescripto Website](https://prescripto-client-m3fe86doe-shubhamshrivastav1s-projects.vercel.app/)

### 🎯 Admin Dashboard

🎯 [Open Admin Dashboard](https://prescripto-admin-nine-gamma.vercel.app/)

### ⚙️ Backend API

⚙️ [Open Backend API](https://prescripto-backend-blond.vercel.app/)

---

## 🔗 Production Configuration

The client and admin applications communicate with the deployed backend using:

```env
VITE_BACKEND_URL=https://prescripto-backend-blond.vercel.app
```

This environment variable should be configured in the respective Vercel projects.

> ⚠️ `VITE_` variables are exposed to the frontend. Never store private credentials or secret keys inside a `VITE_` environment variable.

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
Search / Filter Doctors
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

# 🧪 Testing Checklist

## 👤 Patient / User Testing

- [ ] User registration works
- [ ] User login works
- [ ] Authentication works correctly
- [ ] Doctors are displayed
- [ ] Doctor search works
- [ ] Speciality filtering works
- [ ] Doctor profile opens correctly
- [ ] Doctor information is displayed correctly
- [ ] Appointment booking works
- [ ] Appointment list works
- [ ] Appointment cancellation works
- [ ] User profile can be updated
- [ ] Profile image upload works

---

## 🧑‍⚕️ Doctor Testing

- [ ] Doctor login works
- [ ] Doctor dashboard loads correctly
- [ ] Appointments are displayed
- [ ] Doctor can manage appointments
- [ ] Earnings are displayed
- [ ] Doctor profile can be updated
- [ ] Professional information can be managed

---

## 🎯 Admin Testing

- [ ] Admin login works
- [ ] Admin dashboard loads correctly
- [ ] Admin can add doctors
- [ ] Doctor image upload works
- [ ] Doctors can be viewed
- [ ] Doctor profiles can be managed
- [ ] Appointments can be viewed
- [ ] Appointments can be managed
- [ ] Dashboard statistics are displayed

---

# 📸 Screenshots

Add project screenshots here to showcase the application.

### 👤 Patient / User Website

```markdown
![Patient Website](YOUR_SCREENSHOT_URL)
```

### 🧑‍⚕️ Doctor Dashboard

```markdown
![Doctor Dashboard](YOUR_SCREENSHOT_URL)
```

### 🎯 Admin Dashboard

```markdown
![Admin Dashboard](YOUR_SCREENSHOT_URL)
```

> 💡 For a more professional GitHub profile, replace the placeholders above with actual screenshots of your deployed application.

---

# 📈 Future Improvements

The following features can be added in future versions:

- 💳 Online Payment Integration
- 📧 Email Notifications
- 🔔 Appointment Reminders
- 📅 Advanced Doctor Availability Calendar
- 🩺 Patient Medical History
- 📄 Prescription Management
- 🎥 Video Consultation
- 📊 Advanced Admin Analytics
- 🔎 Advanced Appointment Filtering
- 📱 Improved Mobile Responsiveness
- 🔐 Additional Security Enhancements
- 🌍 Multi-language Support

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

### Fork the Repository

Create your own fork of the project.

### Create a Feature Branch

```bash
git checkout -b feature/your-feature
```

### Commit Your Changes

```bash
git add .
git commit -m "Add your feature"
```

### Push the Branch

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
- MongoDB
- Mongoose
- REST APIs
- JWT Authentication
- bcrypt Password Hashing
- File Uploads
- Cloudinary
- Role-Based Application Architecture
- Environment Variables
- API Integration
- Full-Stack Web Development
- Vercel Deployment

---

# 🔮 Future Vision

Prescripto can be extended into a complete digital healthcare platform by introducing:

- Secure online payments
- Digital prescriptions
- Medical records
- Doctor availability management
- Automated notifications
- Video consultations
- Patient history
- Advanced analytics
- Healthcare reminders

---

# 👨‍💻 Author

## Shubham Shrivastav

GitHub:  
👉 [github.com/shubhamshrivastav1](https://github.com/shubhamshrivastav1)

---

# 📄 License

This project is created for **learning, development, and portfolio purposes**.

---

<div align="center">

## ⭐ PRESCRIPTO

### Making Doctor Appointments Simple & Accessible

**Patient Website • Doctor Panel • Admin Dashboard**

If you find this project useful, consider giving it a ⭐ on GitHub.

</div>
