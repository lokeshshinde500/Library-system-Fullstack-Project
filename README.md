E-Library Management System

Overview

This E-Library Management System is a full-stack application that allows users to browse, borrow, and return eBooks. It consists of a React frontend and a Node.js/Express backend, using MongoDB for data storage. The application provides a responsive and user-friendly interface.

Live URLs

Frontend: https://effervescent-naiad-78ea76.netlify.app/

Backend: https://library-system-backend-4rre.onrender.com

live Url : https://effervescent-naiad-78ea76.netlify.app/

Features

User Authentication: Secure login and registration using JWT.

Book Management: Add, edit, delete, and view eBooks.

Borrow/Return Functionality: Users can borrow and return eBooks easily.

Responsive Design: Optimized for both desktop and mobile devices.

Technologies Used

Frontend: React, Tailwind CSS and Material UI

Backend: Node.js, Express, MongoDB

State Management: React Hooks (useState, useEffect)

API Communication: Axios

Installation

2. Install dependencies:

npm install

3. Create a .env file in the backend directory with the following variables:

MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=your_desired_port

4. Start the backend server:

npm start

API Endpoints

User Authentication

POST /api/auth/register: Register a new user.

POST /api/auth/login: Log in an existing user.

Book Management

POST /api/books: Add a new book.

GET /api/books: Get all books.

GET /api/books/:id: Get a book by ID.

PATCH /api/books/:id: Update book details.

DELETE /api/books/:id: Delete a book.

GET /api/books/myBooks/all: Get all book created by user.

GET /api/books/borrow/:id: borrow a book by ID.

GET /api/books/return/:id: return a book by ID.

GET /api/books//borrowed/all: return all borrowed books by ID.

Feature

User registration and login.

Adding, editing, deleting, and viewing books.

Borrowing and returning books.

Responsiveness of the UI.

Deployment

The frontend is deployed on render

The backend is deployed on Render.

Enhancements

Integrated push notifications and real-time updates for a better user experience.

Acknowledgements

Inspired by existing e-library management systems and their features.

THANK YOU!
