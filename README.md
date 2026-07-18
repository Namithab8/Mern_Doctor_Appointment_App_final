# MERN Doctor Appointment App

A full-stack MERN application for managing doctor appointments, messages, and administrative dashboards.

## Overview

This repository contains separate modules for the API backend, patient-facing frontend, and admin dashboard. Each module is structured as an independent Node/React application to simplify development and deployment.

## Repository Structure

- `backend/`
  - `app.js` - Express application setup
  - `server.js` - HTTP server entry point
  - `package.json` - backend dependencies and scripts
  - `config/config.env` - environment configuration
  - `controller/` - request handlers for appointments, messages, and users
  - `database/dbConnection.js` - MongoDB connection logic
  - `middlewares/` - authentication, error handling, and async wrapper middleware
  - `models/` - Mongoose schemas for appointments, messages, stats, and users
  - `router/` - API routes for appointments, messages, and users
  - `utils/jwtToken.js` - JWT token generation helper

- `frontend/`
  - React app for patients and public users
  - `package.json` - frontend dependencies and scripts
  - `vite.config.js` - Vite configuration
  - `eslint.config.js` - linting configuration
  - `src/` - frontend source code
    - `App.jsx` - root app component
    - `main.jsx` - client entry point
    - `config.js` - environment or API config values
    - `components/` - reusable UI components
    - `Pages/` - page-level route components
  - `public/` - static assets and public files

- `dashboard/`
  - Admin dashboard React application
  - `package.json` - dashboard dependencies and scripts
  - `vite.config.js` - Vite configuration
  - `eslint.config.js` - linting configuration
  - `src/` - dashboard source code
    - `App.jsx` - root dashboard component
    - `main.jsx` - client entry point
    - `components/` - dashboard-specific UI components

- `mern_hospital_management_system/`
  - Additional Node.js service or legacy module with its own Express entry points and module structure

## Notes

- `backend/` provides the REST API and handles authentication, database access, and business logic.
- `frontend/` is the patient-facing React application.
- `dashboard/` is the React application used by administrators or doctors.
- `mern_hospital_management_system/` may contain another Node application or an alternate server implementation.

For usage instructions, review the `README.md` files found in `frontend/` and `dashboard/`.
