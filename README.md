# URL Shortener Web Application 🚀

Welcome to My URL Shortener Web Application! This URL Shortener is a powerful tool that allows you to convert long, complex URLs into concise and easy-to-share links. Built with React, Node.js, and MongoDB, our application provides users with a seamless and secure platform to shorten URLs and manage their shortened links efficiently. It allows users to securely login with their passwords using JWT authentication.

## FrontEnd Netlify Deployed URL ⌛

🔸*Click on the Badge to Check out My URL Shortener Application Here*👉🏻 [![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
](https://url-shortener-front-end-three.vercel.app)

## BackEnd Render Deployed URL ⌛
🔸[![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)](https://url-shortener-backend-8dli.onrender.com)

## BackEnd GitHub Repository URL ⌛
🔸*Click on the Badge to Check out My BackEnd GitHub Repository Here*👉🏻[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Harsha-2324/URL-Shortener-BackEnd.git)

## Video Demo 🎥

Watch a quick video demonstration of My URL Shortener Web Application:

## **Video: 1 Featuring** 🎥
   - `Register`: POST Data to MongoDB Database
   - `Login`: GET Data from MongoDB Database
   - `Forgot Password`: Mail Sent to Registered User's Mail ID using SMTP Protocol
   - `JWT Token Generation`: For Secure user authentication
   - `Reset Password`: PUT Data to MongoDB Database
   - `Login`: using New Password
   
<video controls src="public/image/URL Shortener App - Google Chrome 2024-03-22 21-10-56.mp4" title="Title"></video>


## **Video: 2 Featuring** 🎥
   - `Email Validation`: Ensure user input email requirements for user security
   - `Password Validation`: Ensure user input password requirements for user security
   - `JWT Token Expiry`: After a Password Reset expiration for enhanced security




## Features ✨

- **URL Shortening**: Shorten long URLs into concise, easy-to-share links.
- **URL Management**: View, edit, and delete your shortened URLs from your dashboard.
- **Statistics**: Track statistics such as clicks and views for each shortened URL.
- **JWT Authentication**: Secure user authentication with JSON Web Tokens.
- **Password Reset**: Seamless password reset functionality for users.
- **Email Notifications**: Nodemailer integration to send password reset emails.
- **JWT Token Expiry**: Automatic expiration of JWT tokens for enhanced security.
- **Signup**: User registration with email and password.
- **Authorize Email**: Validate email addresses to ensure they are legitimate.
- **Password Validation**: Ensure strong password requirements for user security.
- **React Frontend**: Modern and intuitive user interface built with React.
- **Node.js Backend**: Robust backend server developed with Node.js.
- **MongoDB Integration**: Integration with MongoDB for efficient data storage.


## Technologies Used Technologies Used in FrontEnd and BackEnd 🌐
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)
![dotenv](https://img.shields.io/badge/dotenv-007A88?style=for-the-badge&logo=dotenv&logoColor=white)
![cors](https://img.shields.io/badge/cors-1572B6?style=for-the-badge&logo=cors&logoColor=white)
![Nodemailer](https://img.shields.io/badge/Nodemailer-339933?style=for-the-badge&logo=nodemailer&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)

## Tools Used Technologies Used in FrontEnd and BackEnd 🛠️
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB%20Atlas-4DB33D?style=for-the-badge&logo=mongodb&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white)

## Installation 🧑🏻‍💻

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/url-shortener.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd url-shortener
   ```

3. **Install Dependencies for the Frontend**:

   ```bash
   cd client
   npm install
   ```

4. **Install Dependencies for the Backend**:

   ```bash
   cd ..
   cd server
   npm install
   ```

5. **Set up Environment Variables**:

   - Create a `.env` file in the `server` directory.
   - Define the following variables:

     ```plaintext
     PORT=8090
     MONGODB_URI=<your-mongodb-uri>
     JWT_SECRET=<your-jwt-secret>
     ```

## Usage 🚀

1. **Start the Backend Server**:

   ```bash
   cd server
   npm start
   ```

2. **Start the Frontend Development Server**:

   ```bash
   cd client
   npm start
   ```

3. **Visit `http://localhost:3000`** in your web browser to access the application.