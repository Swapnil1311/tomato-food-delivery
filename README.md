# Tomato Food Delivery

A food delivery website built with React.js, designed to allow users to browse food items, add them to their cart, and place orders. The project makes use of Vite for fast development, ESLint for linting, and a clean, modular directory structure to maintain readability and scalability.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Development](#development)
- [License](#license)

## Project Overview

Tomato Food Delivery is a simple yet fully functional food delivery web application, where users can explore menus, view different food items, add them to their cart, and complete the order. The app also includes user login pop-ups and a section for viewing past orders.

## Technologies Used

- **React**: Frontend UI framework
- **Vite**: Development build tool for faster startup and fast refresh
- **CSS**: For styling components and layouts
- **ESLint**: Code quality and linting tool

## Folder Structure

This is the directory structure of the project:

Directory structure:
└── swapnil1311-tomato-food-delivery/
├── README.md
├── index.html
├── package.json
├── vite.config.js
├── .eslintrc.cjs
├── public/
└── src/
├── App.jsx
├── index.css
├── main.jsx
├── Context/
│ └── StoreContext.jsx
├── assets/
│ └── assets.js
├── components/
│ ├── AppDownload/
│ │ ├── AppDownload.css
│ │ └── AppDownload.jsx
│ ├── ExploreMenu/
│ │ ├── ExploreMenu.css
│ │ └── ExploreMenu.jsx
│ ├── FoodDisplay/
│ │ ├── FoodDisplay.css
│ │ └── FoodDisplay.jsx
│ ├── FoodItem/
│ │ ├── FoodItem.css
│ │ └── FoodItem.jsx
│ ├── Footer/
│ │ ├── Footer.css
│ │ └── Footer.jsx
│ ├── Header/
│ │ ├── Header.css
│ │ └── Header.jsx
│ ├── LoginPopup/
│ │ ├── LoginPopup.css
│ │ └── LoginPopup.jsx
│ └── Navbar/
│ ├── Navbar.css
│ └── Navbar.jsx
└── pages/
├── Cart/
│ ├── Cart.css
│ └── Cart.jsx
├── Home/
│ └── Home.jsx
├── MyOrders/
│ ├── MyOrders.css
│ └── MyOrders.jsx
└── PlaceOrder/
├── PlaceOrder.css
└── PlaceOrder.jsx

- **App.jsx**: The main React app component.
- **Context/StoreContext.jsx**: Stores global state, such as the user's cart and login data.
- **assets/assets.js**: Stores image paths or asset links.
- **components/**: Contains reusable components such as header, footer, navbar, food display items, etc.
- **pages/**: Contains page-specific components such as Home, Cart, MyOrders, and PlaceOrder.

## Features

- **Responsive Design**: Ensures that the web app works well on mobile and desktop devices.
- **Product Display**: Food items are displayed with essential details such as images and prices.
- **Add to Cart**: Users can add and view food items in their cart.
- **User Login/Registration**: Popup modals for user login.
- **Order History**: Users can view their past orders.
- **Place Order**: A page to finalize and place the order for selected food items.

## Setup and Installation

Follow the steps below to set up the project locally on your machine:

1. Clone this repository:
   git clone https://github.com/Swapnil1311/tomato-food-delivery.git

2. Navigate into the project folder:
   cd swapnil1311-tomato-food-delivery

3. Install dependencies using npm:
   npm install

4. Start the development server:
   npm run dev

5. Visit the website:
   Open [http://localhost:3000](http://localhost:3000) in your web browser.
