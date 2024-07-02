# Quizzie

Quizzie is a dynamic, interactive quiz platform designed to offer a seamless experience for creating and participating in quizzes. Built with modern technologies, Quizzie aims to provide an intuitive interface for quiz creators and an engaging environment for quiz takers.

## Features

- **Custom Quiz Creation**: Users can create quizzes with custom questions and answers.
- **Interactive Quiz Participation**: Engage with quizzes in real-time, with instant feedback.
- **User Authentication**: Secure signup and login functionality.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

- Node.js
- npm or yarn

### Installing

Clone the repository:

```sh
git clone https://github.com/DheerajSharma404/Quizzie-Quiz-App.git

cd Quizzie
```

## Setting up the Backend

Navigate to the backend directory:

```sh
cd Quizzie-Backend
```

Install the dependcies:

```sh
npm install
```

### Set up the .env file

Create a `.env` file in your project root and add the following environment variables with your own values:

```plaintext
PORT=your_port_number
MONGODB_URI=your_mongodb_uri
SALT_ROUND=your_salt_rounds_for_bcrypt
JWT_SECRET=your_jwt_secret
```

Start the application:

```sh
npm run dev
```

> **Note:** Above command runs the following script `"node --watch ./src/index.js"` which is an exprimental feature, you can also use `nodemon` instead.

## Setting up the Frontend

Navigate to the Frontend directory:

```sh
cd Quizzie-Frontend
```

Install the dependcies:

```sh
npm install
```

Start the application:

```sh
npm run dev
```

> **Note:** Ensure all dependencies are installed and the backend server is running before starting the frontend application.

## Built With

- **React**
- **Node.js**
- **Express**
- **MongoDB**
