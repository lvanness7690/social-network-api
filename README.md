# Social Network API

![Status](https://img.shields.io/badge/Status-Local%20API%20project-000000?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-Express-000000?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-MongoDB-000000?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-REST%20API-000000?style=for-the-badge)

REST API for users, thoughts, reactions, and friend relationships.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Links](#links)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Credits](#credits)
- [License](#license)

## Overview

A MongoDB/Mongoose API that models core social-network interactions and exposes routes for CRUD operations and relationship updates.

## Features

- 👤 User CRUD routes
- 💭 Thought CRUD routes
- ❤️ Reaction routes
- 🤝 Friend relationship routes
- 🗃️ MongoDB/Mongoose data model

## Tech Stack

- JavaScript
- Node.js
- Express
- MongoDB
- Mongoose
- Nodemon

## Links

- Repository: [https://github.com/lvanness7690/social-network-api](https://github.com/lvanness7690/social-network-api)
- Live application: Not currently deployed. This repository is intended to run locally or serve as a code sample.

## Getting Started

1. `npm install`
2. `Ensure MongoDB is running locally or configure a MongoDB URI`
3. `npm run seed`
4. `npm start`

Common scripts:

- `npm run start`
- `npm run dev`
- `npm run seed`
- `npm run test`

## Usage

Run locally and test user, thought, reaction, and friend routes with Insomnia or Postman.

## Project Structure

- `README.md`
- `config`
- `controllers`
- `index.js`
- `models`
- `package-lock.json`
- `package.json`
- `routes`
- `utils`

## Credits

Developed and maintained by Leighton Van Ness.

## License

This project is licensed under the MIT license. See the license file in the repository for details.
