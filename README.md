# Blog-MERN

Blog-MERN is a full-stack blogging application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to create, update, and delete blog posts, manage user accounts, and enjoy a dynamic and responsive user interface.

# Deploy Link on render.com: https://blog-mern-lpwd.onrender.com/

## Admin Login Details

Username: admin@gmail.com
Password: 123456
**Note:** Becoming an admin in this app is possible only by having access to MongoDB Atlas. You can become an admin by setting `isAdmin` to "True" in MongoDB collection. For demonstration purposes, an admin login is provided for testing CRUD operations on posts.

## Features

- **User Authentication:** Secure user authentication with JWT tokens.
- **Blog Post Management:** Create, update, and delete blog posts.
- **User Management:** Admins can manage user accounts and delete users.
- **Dashboard:** A user-friendly dashboard to view and manage posts.
- **Dark Mode:** Toggle between light and dark modes.
- **Google Authentication:** Login using Google accounts with Firebase.
- **Private Routes:** Access control for certain routes.
- **Redux State Management:** State management using Redux Toolkit.
- **Theme Persistence:** Theme choice persistence using Redux Persist.
- **Responsive Design:** Mobile-friendly layout for a seamless experience.
- **Image Upload:** Upload images while creating a new post.
- **Signout Functionality:** Log out securely from the application.

## Libraries Used


## Backend Libraries

- **bcryptjs (^2.4.3):** Used for hashing passwords, enhancing security by storing password hashes instead of plain text passwords.
- **cookie-parser (^1.4.6):** Middleware for parsing cookies in the incoming request object, crucial for managing user sessions and authentication.
- **dotenv (^16.4.5):** Loads environment variables from a .env file into process.env, facilitating the configuration of environment-specific variables.
- **express (^4.18.3):** Web application framework for Node.js, handling HTTP requests, defining routes, and managing middleware.
- **jsonwebtoken (^9.0.2):** Generates and verifies JSON Web Tokens (JWT) for user authentication, facilitating secure communication between the frontend and backend.
- **mongoose (^8.2.1):** MongoDB object modeling tool designed to work in an asynchronous environment, simplifying interactions with MongoDB.

## Frontend Libraries

- **@reduxjs/toolkit (^2.2.1):** Redux toolkit for efficient state management in the frontend.
- **firebase (^10.8.1):** Firebase for Google authentication on the frontend.
- **flowbite-react (^0.7.2):** React components for the Flowbite UI library.
- **react (^18.2.0):** JavaScript library for building user interfaces.
- **react-circular-progressbar (^2.1.0):** Circular progress bar component for React.
- **react-dom (^18.2.0):** Entry point for interacting with the DOM in React applications.
- **react-icons (^5.0.1):** Library for popular icons in React projects.
- **react-quill (^2.0.0):** Rich text editor for React applications.
- **react-redux (^9.1.0):** Official React bindings for Redux.
- **react-router-dom (^6.22.2):** Routing library for React applications.
- **redux-persist (^6.0.0):** Library for persisting and rehydrating a Redux store.
- **tailwind-scrollbar (^3.1.0):** Tailwind CSS plugin for customizing scrollbars.
- **tailwindcss (^3.4.1):** Utility-first CSS framework for styling.
- **vite (^5.1.4):** Build tool that aims to provide a faster and more efficient development experience for frontend projects.

## Tech Stack

- **Backend:**
  - Node.js
  - Express.js

- **Database:**
  - MongoDB

- **Frontend:**
  - React
  - Redux
  - Firebase

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Blog-MERN.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Blog-MERN
   ```
3. Install backend dependencies: 
   ```bash
   cd backend
   npm install
   ```
4. Install frontend dependencies:  
  ```bash
   cd ../frontend
   npm install
  ```
5. Set up environment variables:

Create a .env file in the backend and frontend directories.
**Note:** Here, I provided my .env file intentionally for reference
6. Run the development server:
```
# In the backend directory
npm run dev

# In the frontend directory
npm run dev
```
