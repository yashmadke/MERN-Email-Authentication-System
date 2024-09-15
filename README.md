# MERN Email Authentication System

This is a secure and scalable email authentication system built with the MERN stack (MongoDB, Express.js, React.js, Node.js). The system allows users to create accounts, verify their email addresses using a 6-digit verification code, and provides a "forgot password" feature. It incorporates **Framer Motion** for enhanced UI animations and **Zustand** for state management, while **Mailtrap** is used to send emails during the verification process.

## Features
- User Registration
- Email Verification with 6-digit Code
- Forgot Password Functionality
- Smooth UI Animations using **Framer Motion**
- Efficient State Management with **Zustand**
- Email delivery via **Mailtrap**

## Tech Stack
- **MongoDB**: Database
- **Express.js**: Backend framework
- **React.js**: Frontend framework
- **Node.js**: Server environment
- **Framer Motion**: UI animations
- **Zustand**: State management
- **Mailtrap**: Email testing and delivery

## Installation and Setup

Follow these steps to set up the project locally.

### Prerequisites
- [Node.js](https://nodejs.org/en/) installed
- MongoDB Atlas or a locally running MongoDB instance
- Mailtrap account for email delivery setup
- Git installed

### 1. Clone the Repository
```bash
git clone https://github.com/yashmadke/MERN-Email-Authentication-System.git
cd MERN-Email-Authenticaton-System
```

### 2. Install Dependencies
Backend Setup (run this command in root folder)
```bash
npm install
```
Frontend Setup
```bash
cd ./frontend
npm install
```

### 3. Environment Variables Setup
Create a **.env** file in the root folder and add the following environment variables:
```bash
MONGO_URI=mongodb connection string
PORT=port number
JWT_SECRET=jwt secret key
NODE_ENV=development
MAILTRAP_TOKEN=mailtrap token
CLIENT_URL=client url
```

### 4. Running the Application
Run Backend (in root folder)
```bash
npm run dev
```
Run Frontend
```bash
cd ./frontend
npm run dev
```
