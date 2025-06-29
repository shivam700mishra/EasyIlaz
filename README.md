#  Doctor Appointment Booking App

EasyIlaz is a full-stack doctor appointment booking application with three main modules:
- **Frontend**: Patient-facing React app
- **Admin**: Admin/Doctor dashboard React app
- **Backend**: Node.js/Express REST API

---

## Folder Structure

```
EasyIlaz/
│
├── admin/         # Admin & Doctor dashboard (React)
├── backend/       # Node.js/Express backend API
├── frontend/      # Patient-facing frontend (React)

```

---

## Features

### Patient/Frontend
- Register/Login
- Browse doctors by speciality
- Book/cancel appointments
- View appointment history
- Profile management
- Online payments (Razorpay/Stripe)

### Admin
- Secure login
- Dashboard with stats
- Add new doctors (with image upload)
- View/cancel all appointments
- Manage doctor availability
- View all doctors

### Doctor
- Secure login
- Dashboard with stats
- View/manage own appointments
- Mark appointments as complete
- Update profile & availability

---

## Tech Stack
- **Frontend/Admin**: React, React Router, Tailwind CSS, Axios, React Toastify, Vite
- **Backend**: Node.js, Express, MongoDB, Cloudinary, Multer, JWT Auth, CORS

---

## Getting Started

### 1. Clone the repository
```sh
git clone <repo-url>
cd prescripto-full-stack
```

### 2. Setup Backend
```sh
cd backend
npm install
# Create a .env file (see How_To_Run_Project.pdf for details)
npm start
```

### 3. Setup Frontend (Patient)
```sh
cd ../frontend
npm install
npm run dev
```

### 4. Setup Admin Dashboard
```sh
cd ../admin
npm install
npm run dev
```

---

## API Endpoints
- `/api/user` - Patient APIs
- `/api/admin` - Admin APIs
- `/api/doctor` - Doctor APIs

See backend `routes/` and `controllers/` for details.

---

## Environment Variables
- See `How_To_Run_Project.pdf` for required environment variables and setup instructions.

---

## Credits
- UI inspired by modern healthcare platforms.
- Built with ❤️ by the Shivam Mishra.
