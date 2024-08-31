#  Fitness Tracker Web App

This project is a Fitness Tracker web Application. Designed and developed a full-stack fitness tracker web app that empowers users to monitor their fitness journey, track workouts, and analyze their progress through dynamic visualization.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Technologies](#technologies)

## Features

- 📝 User Registration: Users can create accounts with their name, email and password etc.
- 🔑 User Login: Registered users can log in using their email and password.
- 🏋️‍♂️ Add Workout: It allow user to add the workout with sets and reps.
- 📊 DashBoard: Dashboard shows workout journey in the form dynamic visualization.
- 📆 History: It allows user to see the workout history of any perticular date.
- 🔒 JWT Authentication: JSON Web Tokens are used for secure user authentication and authorization.
- 🔐 Password Security: User passwords are hashed using bcrypt to protect sensitive data.
- 

## Prerequisites

Before you begin, ensure you have met the following requirements:

- 🚀 Node.js and npm (Node Package Manager) installed.
- 📦 MongoDB database for storing user data.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Hrushikeshn123/Fitness.git
   ```

2. Change into the project directory:

   ```bash
   cd Fitness
   ```

3. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

4. Install client dependencies:

   ```bash
   cd client
   npm install
   ```

## Configuration

1. Create a `.env` file in the `root` directory with the following environment variables:

   ```env
   URI=your_mongodb_uri
   JWT =  jwt_key
   PORT= your port
   ```

## Usage

1. Start the server:

   ```bash
   cd server
   npm start
   ```

2. Start the client:

   ```bash
   cd client
   npm start
   ```

3. Access the application in your web browser at `http://localhost:3000`.

## Technologies

- 📦 **MongoDB**: A NoSQL database for storing user data.
- ⚙️ **Express.js**: A web application framework for Node.js.
- ⚛️ **React**: A JavaScript library for building user interfaces.
- 🚀 **Node.js**: A JavaScript runtime for server-side development.
- 🔑 **JWT**: JSON Web Tokens for user authentication.
- 🔒 **bcrypt**: A library for hashing user passwords.

Happy coding! 👩‍💻👨‍💻
