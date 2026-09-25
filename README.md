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

1. Install Node.js 18 or newer and MongoDB, then start MongoDB locally or prepare an Atlas connection.
2. Open a terminal in `Server/` and install dependencies:

   ```bash
   cd Server
   npm install
   ```

3. Create `Server/.env`. Port `3001` matches the URL currently configured in `Client/src/Api/index.js`:

   ```dotenv
   NODE_ENV=development
   PORT=3001
   DATABASE=mongodb://127.0.0.1:27017/gestion_stock
   ```

4. Start the API:

   ```bash
   npm start
   ```

5. Open another terminal and prepare the React application:

   ```bash
   cd Client
   npm install
   npm start
   ```

6. Open `http://localhost:3000`. If the backend address changes, update `Client/src/Api/index.js` before starting the client.
