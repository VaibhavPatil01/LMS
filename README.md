# LMS (Learning Management System)

Welcome to the Learning Management System (LMS) project! This is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js) that allows educators to publish courses and students to enroll and watch them. The platform integrates **Clerk** for user authentication and **Stripe** for secure payments.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Demo](#demo)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [Screenshots](#screenshots)

## Project Overview

LMS is designed for educators to create, manage, and sell online courses. It provides a user-friendly platform where students can browse, enroll, and pay for courses.

### Key Features:
- **User Authentication**: Secure login and registration using **Clerk** authentication, with pre-built UI components like sign-in, sign-up, and profile management.
- **Course Management**: Educators can upload and manage their courses, including course titles, descriptions, and media content.
- **Payment Integration**: **Stripe** payment gateway allows students to purchase courses and educators to earn from their content.
- **Responsive Design**: Mobile-friendly layout ensuring a smooth user experience on all devices.

## Features

- **User Registration & Login**: Built using **Clerk** for secure sign-in, sign-up, and profile management.
- **Course Enrollment**: Students can browse courses, view details, and enroll by making payments via **Stripe**.
- **Payment Integration**: Secure payment system through **Stripe**, allowing course purchases and educator earnings.
- **Course Content Delivery**: Students can access enrolled courses, watch videos, take quizzes, and track progress.

## Tech Stack

- **Frontend**: 
  - **React.js** (for building the user interface)
  - **React Router** (for navigation)
  - **Axios** (for API calls)
  - **Clerk** (for authentication and user management)
- **Backend**:
  - **Node.js** (for server-side logic)
  - **Express.js** (for building the REST API)
  - **MongoDB** (for database storage)
  - **Mongoose** (for object modeling with MongoDB)
  - **Stripe** (for payment processing)

## Usage

- **As a Student**:
  1. Sign up or log in using your **Clerk** credentials.
  2. Browse the course catalog.
  3. Enroll in courses by making a payment via **Stripe**.
  4. Access your enrolled courses and start learning.

- **As an Educator**:
  1. Sign up or log in using your **Clerk** credentials.
  2. Create and manage your courses.
  3. View earnings from your courses.

## Demo

You can view the live demo of the project here:  
[Live Demo](https://lms-frontend-eight-orpin.vercel.app/)

## Future Improvements

This project is continuously evolving! Here are some features that could be added in the future:

- **Certificates**: Generate a downloadable PDF certificate on course completion.
- **Notifications System**: Implement an email and in-app notification system to alert students about new course offerings, promotions, and deadlines.
- **Mobile App**: Convert the platform into a mobile app using **React Native** for a more portable learning experience.
- **Live Classes Integration**: Integration with live video platforms (like Zoom) for live classes with real-time interaction.

## Screenshots

Here are some screenshots of the project in action:

### 1. **Homepage**:  
![Homepage](https://i.imgur.com/FtnaZwm.png)  

### 2. **Course List**:  
![Course List](https://i.imgur.com/3c2l3vl.png)  

### 3. **Course Details**:  
![Course Details](https://i.imgur.com/sKHWL14.png)  

### 4. **Payment Gateway**:  
![Payment Gateway](https://i.imgur.com/8UuNqrC.png)  

### 5. **My Enrollments**:  
![My Enrollments](https://i.imgur.com/ReDiriG.png)  

### 6. **Watch Course**:  
![Watch Course](https://i.imgur.com/gHe4FVI.png)  

### 7. **Educator Dashboard**:  
![Educator Dashboard](https://i.imgur.com/Uhmd9jD.png)  

## Contributing
Contributions are welcome!

Thank you for checking out the LMS project! If you have any questions or would like the setup instructions to run the project locally, feel free to reach out to me directly.

