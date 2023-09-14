# Fast React Pizzs

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Installation](#installation)
5. [Usage](#usage)
6. [APIs](#apis)
7. [Credit](#credit)
8. [Contributing](#contributing)

## Introduction
The "Fast React Pizza" learning project is a web application built using React and Vite. It provides a seamless experience for ordering pizzas online. The application is designed to be fast, responsive, and user-friendly.

## Features
### Fake User Authentication
- Allows users to enter their name before proceeding to the menu.
  - File: [`CreateUser.jsx`](src/features/user/CreateUser.jsx)

### Menu Display
- Displays a list of available pizzas.
  - File: [`Menu.jsx`](src/features/menu/Menu.jsx)

### Cart Management
- Allows users to add pizzas to their cart and manage the cart items.
  - Files: [`Cart.jsx`](src/features/cart/Cart.jsx), [`CartItem.jsx`](src/features/cart/CartItem.jsx)

### Order Management
- Allows users to create new orders and view the status of existing orders.
  - File: [`Order.jsx`](src/features/order/Order.jsx)

### UI Components
- Reusable UI components like buttons and headers.
  - Files: [`Button.jsx`](src/ui/Button.jsx), [`AppLayout.jsx`](src/ui/AppLayout.jsx)

### Utilities
- Helper functions for formatting currency and calculating time.
  - File: [`helpers.js`](src/utils/helpers.js)

## Technologies
- React
- Vite
- Redux Toolkit
- Tailwind CSS
- Fetch API

## Installation
1. Clone the repository: `git clone https://github.com/soeweiyan-phyo/16-fast-react-pizza.git`
2. Navigate to the project directory: `cd 16-fast-react-pizza`
3. Install dependencies: `npm install`
4. Start the development server: `npm run dev`

## Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Enter your name to proceed to the menu.
3. Select pizzas to add to your cart.
4. View your cart and proceed to place an order.

## APIs
- Geocoding API: Used to fetch address information based on latitude and longitude.
  - File: [`apiGeocoding.js`](src/services/apiGeocoding.js)
- Restaurant API: Used to fetch menu items and manage orders.
  - File: [`apiRestaurant.js`](src/services/apiRestaurant.js)

## Credit
Master modern React from beginner to advanced! Context API, React Query, Redux Toolkit, Tailwind, advanced patterns (by Jonas Schmedtmann) (Udemy)

## Contributing
Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
