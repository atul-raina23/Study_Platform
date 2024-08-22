StudyNotion - EdTech Platform 🚀

Link to website
https://studynotion-frontend.vercel.app/

StudyNotion is a fully functional EdTech platform that allows users to create, consume, and rate educational content. Built using the MERN stack (ReactJS, NodeJS, MongoDB, and ExpressJS), StudyNotion offers a comprehensive learning experience for students and instructors alike.

📚 Table of Contents

    Introduction
    System Architecture
        Front-end
        Back-end
        Database
        Architecture Diagram
    API Design
    Installation
    Configuration
    Usage

🎓 Introduction

StudyNotion aims to make education more accessible and engaging by providing a seamless and interactive learning experience. It also serves as a platform where instructors can showcase their expertise and connect with learners worldwide.

This README will provide detailed information about the platform’s architecture, API design, installation steps, and usage instructions.

🏗️ System Architecture

The StudyNotion platform consists of three primary components: the front-end, the back-end, and the database. It follows a client-server architecture, with the front-end acting as the client and the back-end and database as the server.

🌐 Front-end

The front-end is built using ReactJS, which helps create dynamic and responsive user interfaces. The front-end interacts with the back-end via RESTful APIs.

🔹 Front-end Features for Students:

    Homepage: Overview of the platform with links to courses and user details.
    Course List: Displays available courses with descriptions and ratings.
    Wishlist: Lists courses added to the wishlist.
    Cart Checkout: Facilitates course purchase and enrollment.
    Course Content: Provides access to course materials and videos.
    User Details: Displays user information, including account settings.
    User Edit Details: Allows students to edit their profile.

🔹 Front-end Features for Instructors:

    Dashboard: Overview of courses, ratings, and feedback.
    Insights: Detailed analytics and engagement metrics.
    Course Management: Tools to create, update, and manage courses and pricing.
    Profile Management: Allows instructors to view and edit their profile details.

💻 Back-end

The back-end is built using NodeJS and ExpressJS. It provides APIs for the front-end, handling user authentication, course creation, payment processing, and other core functions.

🔐 Back-end Features:

    User Authentication and Authorization: Supports email/password login, OTP verification, and password reset.
    Course Management: Instructors can manage courses, while students can rate and view them.
    Payment Integration: Razorpay is integrated for handling course purchases.
    Cloud-based Media Management: Cloudinary is used for storing and managing media content.
    Markdown Support: Course content is formatted using Markdown for easy rendering.

🗄️ Database

The database is built using MongoDB, a NoSQL solution that allows flexible storage of data. It manages course content, user data, and other platform-related information.

Database Schema

🖼️ Architecture Diagram

Below is a high-level diagram that represents the architecture of the StudyNotion platform:

Architecture

📡 API Design

The StudyNotion platform’s API follows the REST architectural style, built using Node.js and Express.js. Data is exchanged using JSON, and standard HTTP request methods (GET, POST, PUT, DELETE) are used.

For more detailed information, please refer to the API Documentation.

🛠️ Installation

    Clone the repository.
    Navigate to the project directory.
    Install dependencies using your preferred package manager.

⚙️ Configuration

    Set up a MongoDB database and obtain the connection URL.
    Create environment variables for your database connection, JWT secret, and other sensitive information.

🚀 Usage

    Start the back-end server.
    Start the React development server.
    Access the application in your browser at http://localhost:3000.
