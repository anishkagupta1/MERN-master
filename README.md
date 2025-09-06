# MERN Master

A full-stack Learning Management System (LMS) built with the MERN stack (MongoDB, Express.js, React, Node.js). This platform allows instructors to create and manage courses, and students to browse, purchase, and track their learning progress.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
  - [Running the App](#running-the-app)
- [Key Functionality](#key-functionality)
  - [Authentication](#authentication)
  - [Instructor Features](#instructor-features)
  - [Student Features](#student-features)
  - [Media Upload](#media-upload)
  - [Payments](#payments)
- [Folder Overview](#folder-overview)
- [License](#license)

---

## Features

### Instructor

- Create, edit, and manage courses
- Upload course images and video lectures (single & bulk upload)
- Set course curriculum, free previews, and course settings
- View all created courses

### Student

- Browse and filter available courses by category, level, etc.
- View course details, curriculum, and free previews
- Purchase courses securely via PayPal
- Track progress and completion of purchased courses
- Rewatch completed courses

---

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, Radix UI, Lucide Icons
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Token)
- **Media Storage:** Cloudinary (via server-side upload)
- **Payments:** PayPal REST SDK

