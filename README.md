# Stock and Order Management

A small full-stack application for managing products, stock levels, and customer orders. The React client provides forms and list views, while the Express API stores products and orders in MongoDB.

## Features

- Add and review stock items
- Create and list customer orders
- Basic login and home screens
- REST endpoints for products and orders

## Tech Stack

- React and Create React App
- Node.js and Express
- MongoDB and Mongoose

## Project Structure

```text
Client/   React application
Server/   Express API, models, routes, and controllers
```

## Run Locally

Install dependencies in both applications:

```bash
cd Server
npm install
npm start
```

```bash
cd Client
npm install
npm start
```

Configure the MongoDB connection and other local values in the server environment before starting the API.
