# Trip Mate - Vacation Rental System
A full stack web application built with Node.js, Express, and other modern tools, featuring a clean architecture with MVC pattern, environment variable support, and modular routing.


# Features
- RESTful API endpoints with Express.js
- Dynamic routing and templating via `views/`
- Organized folder structure (MVC: models, views, controllers)
- Secure environment variable handling using `.env`
- Utility modules and custom middleware support
- Cloud integration (e.g., Cloudinary)


# Project Structure
├── app.js # Entry point of the application
├── controllers/ # Business logic
├── models/ # Mongoose or DB schemas
├── routes/ # Route definitions
├── views/ # Templates
├── public/ # Static files (CSS, JS, images)
├── utils/ # Utility functions
├── middleware.js # Custom middleware
├── cloudConfig.js # Cloud service setup (e.g., Cloudinary)
├── schema.js # Validation or DB schemas
├── .env # Environment variables
├── .gitignore # Git ignored files
├── package.json # Project metadata and dependencies
└── README.md # This file
