# E-Commerce Application Frontend

## Overview
This is the frontend of the E-Commerce Application, built using **React.js**. It provides a user-friendly interface for customers to browse products, manage their shopping carts, and place orders. The application communicates with a backend API (developed using Java Spring Boot) to handle data and business logic.  

## Features
- **Home Page**: Displays featured and categorized products.
- **Product Search and Filters**: Allows users to search for products and apply filters like price range and category.
- **User Authentication**: Login and signup functionality with JWT-based authentication.
- **Shopping Cart**: Add, update, and remove products from the cart.
- **Checkout Process**: Seamless order placement with address management and payment integration.
- **Order Management**: View past orders and their statuses.
- **Role-Based Features**: Different views for admin and customers (e.g., admin dashboard for product management).

## Tech Stack
- **Frontend Framework**: React.js
- **State Management**: React Context API / Redux (if applicable)
- **Styling**: CSS / Tailwind CSS / Bootstrap (depending on what you used)
- **API Integration**: Axios for REST API calls
- **Build Tool**: Vite / Create React App / Webpack (specify the tool used)

## Project Structure
```plaintext
src/
├── components/         # Reusable UI components
├── pages/              # Page components (e.g., Home, ProductDetails, Cart, Login)
├── services/           # API service functions
├── context/            # Context for state management (if used)
├── assets/             # Images, icons, and static assets
├── styles/             # CSS or SCSS files
├── App.js              # Main application component
├── index.js            # Entry point
└── utils/              # Utility functions
```

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd e-commerce-frontend
   ```

2. **Install Dependencies**:
   Ensure you have Node.js and npm installed, then run:
   ```bash
   npm install
   ```

3. **Set Environment Variables**:
   Create a `.env` file in the root directory and configure the following:
   ```plaintext
   REACT_APP_API_URL=http://localhost:8080/api
   ```

4. **Run the Application**:
   Start the development server:
   ```bash
   npm start
   ```

5. **Build for Production**:
   Generate a production build:
   ```bash
   npm run build
   ```
