# The Complete Guide To Building A REST API With Node, Express, TypeScript & MongoDB

This repository on building a REST API using Node.js, Express, TypeScript, and MongoDB.

## Features

- Environment setup with TypeScript and Nodemon
- MongoDB and Mongoose connection, including database creation
- Creation of controllers for handling API routes
- Creation of middlewares for request processing
- Cookie-based authentication for secure API access
- Postman testing for API endpoints
- CRUD operations (Create, Read, Update)

## Prerequisites

- Node.js version 18.x

## Cloning the Repository

To get started, clone this repository using the following command:
https://github.com/bagashanantoputra/rest-api-express.git

## Installing Packages

Install the necessary packages by running the following command:
npm install

## Starting the Application

To start the application, run the following command:
npm start

## Setting up MongoDB URL

In the `src/index.ts` file, set the value of `MONGO_URL` variable to your MongoDB database URI:

```typescript
const MONGO_URL = 'mongodb://localhost:27017/mydatabase'; // Replace with your DB URI 

