# Messaging Website

A full-stack real-time messaging application that enables users to communicate through secure authentication and persistent conversations. The application consists of a React frontend and an Express.js backend with PostgreSQL for data storage, Prisma ORM for database management, and Socket.IO for real-time communication.

## Overview

This project demonstrates the development of a modern messaging platform with a strong focus on backend engineering, authentication, database design, and real-time communication. The application follows a client-server architecture where the frontend communicates with REST APIs while Socket.IO enables instant message delivery between connected users.

---

## Features

- Secure user registration and login
- JWT-based authentication and authorization
- Password hashing using bcrypt
- Real-time messaging powered by Socket.IO
- Persistent conversations stored in PostgreSQL
- RESTful APIs for authentication and messaging
- Database management using Prisma ORM
- Responsive frontend built with React and Vite

---

## Tech Stack

### Backend

- Node.js
- Express.js
- TypeScript
- PostgreSQL
- Prisma ORM
- JWT Authentication
- bcrypt
- Socket.IO
- Cookie Parser
- dotenv

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- DaisyUI
- Zustand
- Socket.IO Client

---

## Project Structure

```text
Messaging-Website/
│
├── Backend/
│   ├── prisma/
│   └── src/
│       ├── Controllers/
│       ├── Routes/
│       ├── middleware/
│       ├── socket/
│       ├── db/
│       ├── utils/
│       └── index.ts
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── package.json
└── README.md
```

---

## System Architecture

```text
                React Frontend
                       │
          REST API + Socket.IO Client
                       │
               Express.js Backend
                       │
        ┌──────────────┴──────────────┐
        │                             │
 JWT Authentication             Socket.IO Server
        │                             │
        └──────────────┬──────────────┘
                       │
                 Prisma ORM
                       │
                  PostgreSQL
```

---

## Backend Responsibilities

- User authentication
- Authorization using JWT
- Password encryption
- Conversation management
- Message management
- Real-time communication
- Database interaction using Prisma
- API request handling

---

## Frontend Responsibilities

- User interface
- Authentication screens
- Chat interface
- Conversation management
- Real-time message updates
- State management using Zustand

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/Dhanshekar-P/Messaging-Website.git
```

### Install Backend Dependencies

```bash
npm install
```

### Install Frontend Dependencies

```bash
cd frontend
npm install
```

### Configure Environment Variables

Create a `.env` file in the project root.

Example:

```env
DATABASE_URL=your_database_url
JWT_SECRET=your_secret_key
```

### Run Backend

```bash
npm run dev
```

### Run Frontend

```bash
cd frontend
npm run dev
```

---

## Database

This project uses **PostgreSQL** with **Prisma ORM**.

Main entities include:

- User
- Conversation
- Message

Prisma manages schema generation and database access.

---

## API Modules

### Authentication

- User Registration
- User Login
- Authentication Middleware

### Messaging

- Create Conversations
- Send Messages
- Retrieve Messages
- Real-time Message Delivery

---

## My Contribution

This project was developed collaboratively.

My primary contribution was focused on **backend development**, including:

- Backend application development
- REST API implementation
- Authentication integration
- Backend architecture and project organization
- Database integration
- Backend debugging and feature development
- Collaboration on backend functionality and system integration

---

## Future Improvements

- Group chat functionality
- Image and file sharing
- Message reactions
- Typing indicators
- Online/offline presence
- Read receipts
- Push notifications
- Docker support
- Automated testing
- CI/CD pipeline

---

## Technologies Used

<p align="left">

Node.js • Express.js • TypeScript • React • Vite • PostgreSQL • Prisma • Socket.IO • JWT • bcrypt • Tailwind CSS • Zustand

</p>

---

## Acknowledgement

This project was developed collaboratively as a team project. The repository documents the application's architecture and functionality while highlighting my primary contribution toward backend development.
