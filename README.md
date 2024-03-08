# Social Network API
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents\
* [Description](#description)
* [Installation](#installation)
* [Technologies Used](#technologies-used)
* [Application Demo](#application-demo)
* [Usage](#usage)
* [Features](#features)
* [API Endpoints](#api-endpoints)
* [Credits](#credits)
* [License](#license)

## Description

The Social Network API is a RESTful web service designed for managing user data and interactions in a social networking application. Built using Express.js, Mongoose, and MongoDB, this API provides endpoints for creating, reading, updating, and deleting users, thoughts, reactions, and friend relationships. It offers a flexible and scalable solution for handling large amounts of unstructured data typically found in social media platforms.

## Installation

To install and run the Social Network API, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install all required dependencies.
4. Ensure you have MongoDB installed and running on your local machine.
5. Create a `.env` file in the root directory and provide your MongoDB connection URI.
6. Run `npm start` to start the server.

## Technologies Used

This application is powered by Node.js (v16.19.1), Express.js (v.14.18.2), JavaScript, MongoDB, and Mongoose (ODM). It utilizes the node package manager (npm) dependencies express (v4.18.2), and mongoose (v7.2.2). Nodemon (v2.0.22) was utilized as a devDependency allowing the server to refresh when edits were made to application. Jest (v.29.5.0) is installed as a devDependency for future unit testing. MongoDB Compass acted as the interactive shell used to visually see the database. Also, the Insomnia application, was utilized to test the functionality of routes within the program.

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

## Application Demo

[Professional README Generator Demo Video](https://www.icloud.com/iclouddrive/05c14tUMs6o7mvLuRk3KdbHiQ#Social_Network_API_Demo)

## Usage

After installation, you can interact with the API using tools like Insomnia or Postman to perform various CRUD operations:

- Use GET requests to retrieve user data, thoughts, and reactions.
- Use POST requests to create new users, thoughts, reactions, and friend relationships.
- Use PUT requests to update existing user data or thoughts.
- Use DELETE requests to remove users, thoughts, reactions, or friend relationships.

## Features

Features of this application include the ability to create users/thoughts, find all users/thoughts, find a single user/single thought, update user/thought information, and delete a user/thought. The ability to add reactions to particular thoughts, and friends to users is also a notable feature -> when a thought, reaction, or friend is added to the database, it will update within the user object accordingly.


## API Endpoints

- `GET /api/users`: Retrieve all users or a single user by ID.
- `POST /api/users`: Create a new user.
- `PUT /api/users/:userId`: Update an existing user.
- `DELETE /api/users/:userId`: Delete a user by ID.
- `POST /api/users/:userId/friends/:friendId`: Add a friend to a user's friend list.
- `DELETE /api/users/:userId/friends/:friendId`: Remove a friend from a user's friend list.
- `GET /api/thoughts`: Retrieve all thoughts or a single thought by ID.
- `POST /api/thoughts`: Create a new thought.
- `PUT /api/thoughts/:thoughtId`: Update an existing thought.
- `DELETE /api/thoughts/:thoughtId`: Delete a thought by ID.
- `POST /api/thoughts/:thoughtId/reactions`: Add a reaction to a thought.
- `DELETE /api/thoughts/:thoughtId/reactions/:reactionId`: Remove a reaction from a thought.

## Features

- Provides endpoints for managing users, thoughts, reactions, and friend relationships.
- Utilizes MongoDB to store and query data, ensuring scalability and performance.
- Follows RESTful principles for predictable and intuitive API interactions.

## Credits

Developed by Leighton Van Ness with starter code from Columbia EDx Bootcamp

## License

Please refer to the license in the repo.
