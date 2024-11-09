# Netflix Clone Full-Stack Project

A full-stack Netflix-inspired streaming platform built with the MERN stack (MongoDB, Express.js, React, Node.js) that provides users with an immersive experience to browse, search, and stream movies and TV shows.

![Image](https://github.com/pushan-alagiya/Netflix-FullStack-Clone/blob/main/frontend/public/Screenshot%20From%202024-11-09%2017-56-17.png?raw=true)

## Features

- **User Authentication**: Secure user sign-up, login, and logout using JSON Web Tokens (JWT) and bcrypt for hashing passwords.
- **Movie and TV Show Browsing**: A categorized and paginated catalog of movies and TV shows.
- **Search Functionality**: Search bar for quick access to content by title or genre.
- **Responsive Design**: Optimized for all device types using CSS3 and responsive design libraries.
- **Dynamic Recommendations**: Displays trending content and suggests similar titles based on viewing history.

## Tech Stack

### Frontend

- **React.js**: Main UI library for creating dynamic, component-based user interfaces.
- **React Router DOM**: Manages in-app routing for a seamless single-page application (SPA) experience.
- **Axios**: For HTTP requests to interact with the backend API.
- **Tailwind** to enhance UI with ready-made components and responsive design features.

### Backend

- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Web application framework for building RESTful APIs.
- **MongoDB**: NoSQL database for efficient data storage and retrieval.
- **JWT (JSON Web Token)**: Secure token-based authentication for managing user sessions.
- **bcrypt**: Password hashing to enhance user security.

## Project Setup

### Prerequisites

- Node.js (v14+)
- MongoDB (local instance or MongoDB Atlas)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/pushan-alagiya/Netflix-FullStack-Clone
   cd Netflix-FullStack-Clone
   ```

2. **Install dependencies for both frontend and backend**

   ```bash
   # Install backend dependencies
   npm install

   # Install frontend dependencies
   cd ./frontend
   npm install
   ```

3. **Environment Variables**

   Create a `.env` file in the `server` directory with the following variables:

   ```plaintext
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. **Running the Project**

   Start the backend and frontend servers concurrently.

   ```bash
   # Start backend server
   cd server
   npm run dev

   # Start frontend
   cd ./frontend
   npm start
   ```
