# ShopVista - A Fully Functional E-Commerce Website

## Overview
ShopVista is a feature-rich e-commerce platform designed to provide a seamless online shopping experience. It includes product listings, a shopping cart, order management, and secure payment integration.

## Features
- **User Authentication**: Sign up, login, and secure authentication with JWT.
- **Product Management**: Add, edit, and delete products (Admin access).
- **Shopping Cart**: Users can add/remove items and update quantities.
- **Order Processing**: Checkout, order placement, and order history tracking.
- **Payment Integration**: Secure payments using Stripe.
- **Responsive UI**: Optimized for mobile and desktop devices.

## Technologies Used
- **Frontend**: React, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Token)
- **Payment Gateway**: Stripe
- **State Management**: Redux Toolkit

## Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/ShopVista.git
   cd ShopVista
   ```

2. **Setup the Backend**
   ```sh
   cd api
   npm install
   ```
   - Create a `.env` file inside `api` and add necessary environment variables:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     STRIPE_SECRET_KEY=your_stripe_secret
     ```
   - Start the backend server:
     ```sh
     nodemon index.js
     ```

3. **Setup the Frontend**
   ```sh
   cd ../client
   npm install
   ```
   - Start the frontend development server:
     ```sh
     npm start
     ```

## Usage
1. Register/Login as a user.
2. Browse products and add items to your cart.
3. Proceed to checkout and make a payment.


## Contributing
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For inquiries, reach out to himanshsood311@gmail.com

