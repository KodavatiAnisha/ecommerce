E-Commerce Website
===

Filter through items from own API, add them to your cart, and see similar items.

![demo](ecommerce.gif)


# E-commerce Website README

## Overview

This is a full-featured e-commerce website built with React. It includes a front-end application for displaying products, a shopping cart, user authentication, and an administrative interface for managing products and orders. This project is designed to demonstrate the use of React in building a modern, responsive, and interactive web application.

## Features

- **User Authentication:** Sign up, log in, and log out functionality.
- **Product Catalog:** Display a list of products with pagination and filtering.
- **Product Details:** View detailed information about each product.
- **Shopping Cart:** Add and remove products, view cart summary, and proceed to checkout.
- **Order Management:** Place orders and view order history.
- **Admin Interface:** Manage products, categories, and orders.

## Technologies Used

- **Front-end:** React, Redux, React Router, Axios, Bootstrap
- **Back-end:** (Assumed to be built separately, e.g., Node.js, Express, MongoDB)
- **Authentication:** JSON Web Tokens (JWT)
- **Styling:** CSS, Bootstrap

## Getting Started

### Prerequisites

Ensure you have the following installed on your local development machine:

- Node.js (v12 or higher)
- npm (v6 or higher)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ecommerce-react.git
   cd ecommerce-react
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add your environment variables. For example:
   ```
   REACT_APP_API_URL=http://localhost:5000/api
   REACT_APP_STRIPE_KEY=your_stripe_public_key
   ```

### Running the Application

1. **Start the development server:**
   ```bash
   npm start
   ```

2. Open your browser and navigate to `http://localhost:3000` to see the application in action.

### Running Tests

To run the tests for this application, use the following command:
```bash
npm test
```

## Project Structure

- `public/`: Static files like index.html.
- `src/`: Main source directory.
  - `components/`: Reusable components.
  - `pages/`: Page components for routing.
  - `redux/`: Redux setup for state management.
    - `actions/`
    - `reducers/`
    - `store.js`
  - `services/`: API service files.
  - `App.js`: Main application component.
  - `index.js`: Entry point of the application.
  - `styles/`: CSS and style files.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

If you have any questions, feel free to reach out:

- Email: anishakodavati7@gmail.com
- GitHub: https://github.com/KodavatiAnisha/ecommerce
