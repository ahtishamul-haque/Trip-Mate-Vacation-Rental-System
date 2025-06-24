# Trip Mate - Vacation Rental System

A full-stack web application built with Node.js, Express, and other modern tools, featuring a clean MVC architecture, modular routing, environment variable support, and third-party cloud integrations.

## Features

- RESTful API endpoints using Express.js
- Dynamic routing and templating via EJS in `views/`
- MVC architecture (models, views, controllers)
- Secure environment variable management using `.env`
- Utility modules and custom middleware support
- Cloud integration (e.g., Cloudinary for image uploads)

## Project Structure

```
├── app.js             #Entry point of the application
├── controllers/       #Business logic
├── models/            #Mongoose schemas / data models
├── routes/            #Route definitions
├── views/             #EJS templates
├── public/            #Static files (CSS, JS, images)
├── utils/             #Utility/helper functions
├── middleware.js      #Custom middleware
├── cloudConfig.js     #Cloud service setup (e.g., Cloudinary)
├── schema.js          #Validation or DB schemas
├── .env               #Environment variables
├── .gitignore         #Git ignored files
├── package.json       #Project metadata and dependencies
├── README.md          #This file
```

## Getting Started

### 1. Install Dependencies

```bash
npm install
```

### 2. Start the Server

```bash
node app.js
```

## Deployment

It uses:

- Environment variables stored in Render's dashboard
- Cloudinary configuration via `.env` and `cloudConfig.js`
- Static files hosted from the `public/` directory

## Tech Stack

- Backend: Node.js, Express.js
- Database: MongoDB (via Mongoose)
- Templating: EJS
- Utilities: dotenv, nodemon, cloudinary, multer, etc.
- Deployment: Render

## Live Demo

🔗 [View Live Site](https://major-project-trip-mate.onrender.com/listings)

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/)

