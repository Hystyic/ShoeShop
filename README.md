# ShoeShop - Sneaker Shopping E-Commerce Platform

ShoeShop is a fully-fledged e-commerce platform for sneaker shopping built using the MERN (MongoDB, Express, React, Node.js) stack. It features an inbuilt inventory management system, user authentication, cart functionality, a product carousel, and checkout with payment gateway integration through Stripe and PayPal.

## Features

- **MERN Stack**: Built using the popular MERN stack (MongoDB, Express, React, Node.js).
- **User Authentication**: User login and signup functionality with session management.
- **Inventory Management**: Automated inventory tracking to monitor stock levels and manage products.
- **Cart System**: Users can add items to the cart, adjust quantities, and remove items.
- **Product Carousel**: Visually appealing carousel showcasing the latest sneaker arrivals.
- **Checkout**: Seamless checkout experience with integrated payment gateways.
- **Payment Integration**: Secure payment processing through **Stripe** and **PayPal**.
- **Admin Dashboard**: Admins can manage products, inventory, and customer orders.


## Technology Stack

- **Frontend**: React.js, Redux, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Gateways**: Stripe and PayPal
- **Authentication**: JWT (JSON Web Tokens)

## Installation and Setup

Follow these steps to install and run the project locally.

### Prerequisites

- Node.js
- MongoDB (local or cloud-based, e.g., MongoDB Atlas)
- Stripe and PayPal accounts for payment integration

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Hystyic/ShoeShop.git
   cd ShoeShop

2. **Install dependencies for both the client and main directory.**

3. **Environment Variables:**

  Create a .env file in the backend folder and add the following environment variables:
 
   ```bash
    NODE_ENV=development
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    PAYPAL_CLIENT_ID=your_paypal_client_id
    STRIPE_SECRET_KEY=your_stripe_secret_key
