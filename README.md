# Sociopedia: A MERN-based Social Media Platform

Sociopedia is a fully-fledged social media platform built using the MERN stack (MongoDB, Express, React, and Node.js). Designed as a lightweight and minimalist version of popular platforms, Sociopedia offers features such as user authentication, profile customization, post interactions, and more.

## Features

- User Profiles: Create and customize profiles with profile pictures, bio, and location.
- Authentication: Secure user registration and login with JWT-based authentication.
- Post Interactions: Users can create posts with captions, like posts, and add comments.
- Follow System: Follow/unfollow functionality to connect with other users.
- Light/Dark Mode: Toggle between light and dark themes for a better user experience.

##  Technologies Used

- Frontend: React.js for building dynamic and responsive user interfaces.
- Backend: Node.js and Express.js for server-side logic and APIs.
- Database: MongoDB for storing user data, posts, and comments.
- Authentication: JSON Web Tokens (JWT) for secure user authentication.
- Styling: CSS and Material-UI for a polished and modern look.

## Setup and Installation

### Prerequisites
Node.js (v16+)
MongoDB (local or cloud-based, e.g., MongoDB Atlas)

### Installation Steps
Clone the repository:
  1. git clone https://github.com/abdulsal3m/MERN-Social-Media-App
  2. cd sociopedia
  
Install dependencies:
  1. npm install
  2. cd client
  3. npm install
  4. cd ..
  
Configure environment variables:
  1. Create a .env file in the root directory.
  2. Add the following:
    - PORT=5000
    - MONGO_URI=<!URI PENDING, DATABASE DOWN>
    - JWT_SECRET=<your_jwt_secret>
    
Start the development server:
  1. npm run dev

## Future Enhancements

- Media Uploads: Add support for image and video uploads in posts.
- Notifications: Real-time notifications for likes, comments, and follows.
- Search: Implement a search feature for users and posts.
- Analytics Dashboard: Provide users with insights on engagement.
