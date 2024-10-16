# Social Media App - Frontend

This is the frontend for the Social Media App, built with React, that allows users to upload images, manage their profiles, and interact with an admin dashboard.

## Features

- User Authentication
- Upload images with Cloudinary
- Admin Dashboard
- Responsive design
- Display user submissions

## Tech Stack

- **React** - JavaScript library for building user interfaces
- **Axios** - For making API requests to the backend
- **Tailwind CSS** - For styling the application

## Installation

### Prerequisites

- **Node.js** and **npm** installed

### Steps

Clone the repository:

   ```bash
   git clone https://github.com/yourusername/social-media-frontend.git
   cd social-media-frontend
   npm install
   npm run dev
   ```
Visit http://localhost:5173 to view the application in the browser.




# Social Media App - Backend

This is the backend for the Social Media App, built with Node.js and Express, which provides APIs for user authentication, image uploads, and admin management.

## Features

- User Authentication with sessions
- Admin Dashboard API
- Image upload functionality via Cloudinary
- MongoDB for data storage

## Tech Stack

- **Node.js** - JavaScript runtime for building the backend
- **Express** - Web framework for Node.js
- **MongoDB** - NoSQL database for storing user and image data
- **Mongoose** - ODM for MongoDB
- **Cloudinary** - For image uploads

## Installation

### Prerequisites

- **Node.js** and **npm** installed
- **MongoDB** instance or MongoDB Atlas
- **Cloudinary** account for image uploads

### Steps

1. Clone the repository:
 ```
   git clone https://github.com/yourusername/social-media-backend.git
```
Navigate to the project directory:
```
  bash
  cd social-media-backend
```
Install dependencies:
```
npm install
```
Create an .env file in the root directory and add the following environment variables:
```
MONGODB_URI=your_mongodb_uri
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```
Start the server:
```
npm start
```
The backend will be running on http://localhost:5000.
## Admin Dashboard
![image](https://github.com/user-attachments/assets/2100d53b-2598-4006-85b2-3c6c78419c9f)

## Admin Login
![image](https://github.com/user-attachments/assets/8e054ced-e23d-45a3-8548-9f4d3dfd5be9)

## User Dashboard

![image](https://github.com/user-attachments/assets/bc13a3e2-a12d-47e4-b331-d1fe678ec5d5)
