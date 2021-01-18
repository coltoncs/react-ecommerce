# React.js E-Commerce App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This is a simple, frontend e-commerce application built with React. It demonstrates using React and the Context API to handle 
common e-commerce tasks, such as viewing product listings, adding products to a cart, checking out, and adding products to the 
product list (assuming credentials are given).

The backend is a spoofed server using json-server and json-server-auth. "Database" details can be viewed and edited from the backend/db.json file.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## Dependencies

* axios
* bulma
* json-server
* json-server-auth
* jwt-decode
* React v17
* react-dom
* react-router-dom
* uuid

## Startup

1. Clone code to local file

`git clone https://github.com/pizdetz/react-ecommerce`

2. Move into directory and install dependencies

`cd react-ecommerce && npm i`

3. Open new bash/cmd in same directory, run

`json-server ./backend/db.json -m ./node_modules/json-server-auth --port 3001`

Note: json-server should be installed globally if you run into issues with this: `npm i -g json-server`

4. On the original (1st) bash prompt, in the same directory, run the React dev server and load up the webpage.

`npm start`

5. Admin access:
* Email: admin@example.com
* Password: password

6. Enjoy