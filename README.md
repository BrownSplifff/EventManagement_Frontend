# Event Management Frontend

Frontend application for a full-stack Event Management Platform built using React, Tailwind CSS, JavaScript, and Socket.IO.

This project was built completely from scratch and includes authentication, real-time notifications, event management features, protected routes, API integration, responsive UI, and state management.

# Vercel
event-management-frontend-yuww.vercel.app


## Features

* User authentication with JWT token-based auth
* Login and registration system
* Protected routes
* Create, edit, and manage events
* Real-time notifications using Socket.IO
* Responsive UI using Tailwind CSS
* REST API integration
* Dynamic routing
* State management using React hooks
* Image upload support
* Form validation and error handling
* Role-based functionality
* Real-time event updates

## Tech Stack

### Frontend

* React
* JavaScript
* Tailwind CSS
* React Router DOM
* Socket.IO Client
* Fetch API / REST APIs

### Backend

* Node.js
* Express.js
* PostgreSQL
* Sequelize ORM
* JWT Authentication
* Socket.IO

## Project Structure

```bash
src/
 ├── components/
 ├── pages/
 ├── routes/
 ├── context/
 ├── services/
 ├── utils/
 ├── assets/
 └── App.jsx
```

## Authentication

This project uses JWT-based authentication for secure user login and protected routes.

Features include:

* Login & signup
* Token storage
* Protected frontend routes
* Auth middleware integration
* Persistent login sessions

## Real-Time Features

Socket.IO is used for:

* Real-time notifications
* Live event updates
* User connection handling

## Deployment

Frontend deployed on Vercel.

Backend deployed on Render.

## Installation

Clone the repository:

```bash
git clone <your-repo-url>
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

## Environment Variables

Create a `.env` file:

```env
VITE_API_URL=your_backend_url
```

## Future Improvements

* Payment gateway integration
* Chat system
* Event analytics dashboard
* Admin moderation tools
* Cloud image storage
* Push notifications

## Author

Aditya Pandey (Frontend)
Abhishekh Jaisi (Backend)
