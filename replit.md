# MongoDB & Mongoose Challenges

## Overview
This is a FreeCodeCamp boilerplate project for learning MongoDB and Mongoose. The application is a Node.js/Express backend with a simple HTML frontend, designed as a learning platform for database operations.

## Project Structure
- `server.js` - Main Express server with API endpoints (DO NOT EDIT - required for FreeCodeCamp tests)
- `myApp.js` - Student implementation file for MongoDB/Mongoose exercises
- `views/index.html` - Simple frontend page
- `package.json` - Node.js dependencies

## Recent Changes (November 10, 2025)
- Configured for Replit environment
- Added basic MongoDB connection code in myApp.js
- Created Person schema and model
- Set up workflow to run on port 5000
- Installed npm dependencies

## Configuration
### Required Environment Variables
- `MONGO_URI` - MongoDB connection string (from MongoDB Atlas or similar)
- `PORT` - Server port (set to 5000 for Replit frontend preview)

### Dependencies
- express - Web framework
- mongoose - MongoDB ODM
- body-parser - Request parsing middleware
- dotenv - Environment variable management

## How to Use
This is a learning project where students complete MongoDB/Mongoose challenges by implementing functions in `myApp.js`. The server provides test endpoints under `/_api` that verify the implementation.

## API Endpoints
- `GET /` - Homepage
- `GET /_api/is-mongoose-ok` - Check MongoDB connection status
- Various `/_api/*` endpoints for testing Mongoose operations

## Links
- [FreeCodeCamp MongoDB/Mongoose Course](https://www.freecodecamp.org/learn/apis-and-microservices/mongodb-and-mongoose/)
- [Original Repository](https://github.com/freeCodeCamp/boilerplate-mongomongoose)
