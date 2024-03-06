# Social Network API

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

## Usage

After installation, you can interact with the API using tools like Insomnia or Postman to perform various CRUD operations:

- Use GET requests to retrieve user data, thoughts, and reactions.
- Use POST requests to create new users, thoughts, reactions, and friend relationships.
- Use PUT requests to update existing user data or thoughts.
- Use DELETE requests to remove users, thoughts, reactions, or friend relationships.

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

## Credits

Developed by Leighton Van Ness. 

## License

This project is licensed under the [MIT License](LICENSE). 

---

## Features

- Provides endpoints for managing users, thoughts, reactions, and friend relationships.
- Utilizes MongoDB to store and query data, ensuring scalability and performance.
- Follows RESTful principles for predictable and intuitive API interactions.

## How to Contribute

Contributions are welcome! If you'd like to contribute, please fork the repository, create a feature branch, and submit a pull request. If you encounter any issues or have suggestions for improvement, please open an issue [here](https://github.com/lvanness7690/social-network-api/issues).
