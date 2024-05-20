# eCommerce Frontend   
                                                                      
This repository contains the frontend code for the eCommerce platform, built using React and TypeScript. The frontend provides a dynamic and responsive user interface for browsing products, managing the shopping cart, and processing orders. It also includes an admin dashboard for managing products, users, and orders. The project utilizes modern state management with Redux Toolkit and RTK Query, employs lazy loading for improved performance, and leverages custom hooks for reusable logic.

## Features                                                                          

User Features
User Authentication: Secure user registration and login functionalities.  

Product Browsing: Browse a catalog of products with advanced filtering and search options.

Product Details: Detailed product pages with descriptions, images, and reviews.

Shopping Cart: Add, update, and remove items in the shopping cart.
Order Processing: Create orders and view detailed order history.

User Profile: Manage personal information and view past orders.

Responsive Design: Optimized for both desktop and mobile devices.

Admin Features
Admin Dashboard: Overview of key metrics such as sales, orders, and user activity.

Product Management: Add, update, delete products, and manage inventory.
User Management: View user profiles, manage user roles, and perform administrative actions.

Order Management: View, update, and manage customer orders.

Performance and Optimization
Efficient Data Fetching: Leveraging Redux Toolkit Query for optimized data fetching and caching.

Lazy Loading: Implemented lazy loading to enhance performance by loading components only when needed.

Custom Hooks: Used custom hooks for encapsulating reusable logic.

## Technologies Used

React: A JavaScript library for building user interfaces.

TypeScript: A statically typed superset of JavaScript that improves code quality and maintainability.

Redux Toolkit: A powerful state management library.

Redux Toolkit Query: For efficient data fetching and caching.

React Router: For client-side routing and navigation.

### Install Dependencies

**For Dev** - `npm i && npm run dev`
**For Product** - `npm i && npm run preview`

### Env Variables

Make Sure to Create a .env file in root directory and add appropriate variables in order to use the app.

**Essential Variables**

VITE_FIREBASE_KEY= `from firebase`

VITE_AUTH_DOMAIN= `from firebase`

VITE_PROJECT_ID=`from firebase`

VITE_STORAGE_BUCKET=`from firebase`

VITE_MESSAGING_SENDER_ID=`from firebase`

VITE_APP_ID=`from firebase`

VITE_SERVER=`Your Backend Server URl`

VITE_STRIPE_KEY=`Stripe Publishable Key`


