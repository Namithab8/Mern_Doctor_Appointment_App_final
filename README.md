# MERN Doctor Appointment App

This repository contains a full-stack MERN application for doctor appointment management, including separate frontend, dashboard, and backend services.

## Repository Structure

- `backend/`
  - `app.js`
  - `server.js`
  - `package.json`
  - `config/`
    - `config.env`
  - `controller/`
    - `appointmentController.js`
    - `messageController.js`
    - `userController.js`
  - `database/`
    - `dbConnection.js`
  - `middlewares/`
    - `auth.js`
    - `catchAsyncErrors.js`
    - `error.js`
  - `models/`
    - `appointmentSchema.js`
    - `messageSchema.js`
    - `statsSchema.js`
    - `userSchema.js`
  - `router/`
    - `appointmentRouter.js`
    - `messageRouter.js`
    - `userRouter.js`
  - `utils/`
    - `jwtToken.js`

- `frontend/`
  - `package.json`
  - `vite.config.js`
  - `eslint.config.js`
  - `index.html`
  - `README.md`
  - `src/`
    - `App.css`
    - `App.jsx`
    - `config.js`
    - `index.css`
    - `main.jsx`
    - `components/`
      - `AppointmentForm.jsx`
      - `Biography.jsx`
      - `Departments.jsx`
      - `Footer.jsx`
      - `Hero.jsx`
      - `MessageForm.jsx`
      - `Navbar.jsx`
      - `assets/`
    - `Pages/`
      - `AboutUs.jsx`
      - `Appointment.jsx`
      - `Home.jsx`
      - `Login.jsx`
      - `Register.jsx`
  - `public/`
    - `departments/`

- `dashboard/`
  - `package.json`
  - `vite.config.js`
  - `eslint.config.js`
  - `index.html`
  - `README.md`
  - `src/`
    - `App.css`
    - `App.jsx`
    - `config.js`
    - `main.jsx`
    - `components/`
      - `AddNewAdmin.jsx`
      - `AddNewDoctor.jsx`
      - `Dashboard.jsx`
      - `Doctors.jsx`
      - `Login.jsx`
      - `Messages.jsx`
      - `Sidebar.jsx`

- `mern_hospital_management_system/`
  - `app.js`
  - `server.js`
  - `package.json`
  - `package-lock.json`
  - `config/`
  - `controller/`
  - `database/`
  - `middlewares/`
  - `models/`
  - `router/`
  - `utils/`

## Notes

- `backend/` contains the Express API server and MongoDB connection.
- `frontend/` is the patient-facing React + Vite application.
- `dashboard/` is the admin/doctor dashboard React + Vite application.
- `mern_hospital_management_system/` appears to contain an additional Node service or legacy module.

For more details, check the `README.md` files inside `frontend/` and `dashboard/`.
