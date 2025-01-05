# Food Ordering Web App (MERN Stack)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction
This is a full-stack food ordering web application built using the MERN stack (MongoDB, Express, React, Node.js). The application that allows users to order food online and restaurant owners to register and manage their restaurants.

## Features
- User authentication and authorization
- Browse food items
- Add items to the cart and place orders
- Razorpay Payment Integration: Secure and reliable payment processing using Razorpay.
- Order tracking

## Technologies Used
- **Frontend:** React.js, Redux Toolkit, React Router
- **Backend:** Node.js, Express.js
- **Payment Gateway:** Razorpay
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Styling:** Tailwand CSS

## Installation
### Prerequisites
- Node.js
- MongoDB

### Clone the Repository
```sh
git clone https://github.com/Vivek3328/QuickBite.git
cd QuickBite
```

## Backend Setup
Navigate to the backend directory:

```sh
cd backend

```
Install dependencies:

```sh
npm install
```

Create a .env file in the backend directory and add the following:

```sh
JWT_SECRET_KEY = "random#secret"
RAZORPAY_KEY_ID = Your RAZORPAY_KEY_ID 
RAZORPAY_KEY_SECRET = Your RAZORPAY_KEY_SECRET
FRONTEND_URL = http://localhost:3000
```

Start the backend server:

```sh
nodemon index.js
```
## Frontend Setup
Navigate to the frontend directory:

```sh

cd frontend
```

Install dependencies:
```sh

npm install
```
Create a .env file in the backend directory and add the following:

```sh
REACT_APP_API_BASE_URL = http://localhost:8080
```

Start the frontend server:
```sh

npm start
```

## Usage
Access the customer-facing app at http://localhost:3000.
Register as a new user or log in with existing credentials.
Browse the menu, add items to the cart, and place an order.
Pay using UPI id: success@razorpay

## API Documentation
The API endpoints for the backend can be documented using tools like Postman or Swagger. Include endpoints for user authentication, menu items, orders, and more.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and include relevant tests.

## Contact
For any questions or suggestions, feel free to contact me.

Happy coding!

Feel free to customize this template according to your specific project details and requirements.

