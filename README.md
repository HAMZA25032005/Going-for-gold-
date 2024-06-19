# Going for Gold 

A contemporary, interactive quiz web application inspired by Kahoot, "Going for Gold" leverages a suite of advanced technologies to offer a seamless user experience. Built within a Node.js environment, this app employs JavaScript for both client-side and server-side code, MongoDB for database management, Socket.IO for real-time communication, and Object-Oriented Programming (OOP) principles to ensure modular, maintainable code.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Architecture](#architecture)
4. [Installation](#installation)
5. [Usage](#usage)


## Introduction 

"Going for Gold" is an engaging and interactive quiz web application, inspired by Kahoot, designed to deliver a dynamic user experience. This application is built using a Node.js environment, with Express.js for the server-side and JavaScript for both the front-end and back-end. Real-time interactions are powered by Socket.IO, ensuring instantaneous updates and communication between the server and clients. MongoDB is employed for scalable and reliable data storage. The project follows Object-Oriented Programming (OOP) principles, making the codebase well-organized and easy to maintain.

## Features 

- **Real-time Interaction:** Leverages Socket.IO for instantaneous communication between server and clients.
- **User Management:** Supports multiple users joining and participating in quizzes simultaneously.
- **Dynamic Content:** Enables the creation and management of quizzes through an admin interface.
- **Responsive Design:** Optimized for accessibility on various devices.

## Architecture 

The architecture of "Going for Gold" includes the following components:

- **Frontend:** Built with HTML, CSS, and JavaScript to provide a user-friendly interface.
- **Backend:** Utilizes Node.js and Express.js to handle server-side logic and API requests.
- **Database:** Uses MongoDB for storing user data, quiz questions, and scores.
- **Real-time Communication:** Implemented with Socket.IO to facilitate real-time updates and interactions during quizzes.

## Installation 

To install and run the application locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yassine-AO/Going-for-Gold.git
    cd going-for-gold
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:** Create a `.env` file in the root directory and add your MongoDB connection string and other necessary environment variables.

    ```text
    MONGODB_URI=your_mongodb_uri
    PORT=your_port
    ```

4. **Start the application:**

    ```bash
    npm start
    ```

## Usage 

Once the application is running, you can access it via your web browser at `http://localhost:your_port`.

- **Admin Interface:** For creating and managing quizzes.
- **User Interface:** Allows players to join quizzes and participate in real-time.

