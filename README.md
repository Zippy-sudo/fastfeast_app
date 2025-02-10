# FastFeast App

The **FastFeast App** is a web application designed to help users manage restaurants, menu items, orders, and reviews. Users can add, update, delete, and view restaurant details, menu items, place orders, and leave reviews. The app is built with **React** for the frontend and **Flask** for the backend.

---

## Features

- **Restaurant Management**: Add restaurants
- **Menu Management**: Add items .
- **Order Management**: Place and delete orders.
- **Review Management**: Add, update, and delete reviews for items.

---

## Tech Stack

- **Frontend**: React (with Create-React-App)
- **Backend**: Flask
- **Database**: SQLite (or any other database configured in the backend)
- **Styling**: CSS

---

## Table of Contents

1. [Installation & Setup](#installation-setup)
2. [Frontend Setup](#frontend-setup)
3. [Backend Setup](#backend-setup)
4. [API Endpoints](#api-endpoints)
5. [Running Tests](#running-tests)
6. [Environment Variables](#environment-variables)
7. [Contributing](#contributing)
8. [License](#license)

---

## Installation & Setup

### Frontend Setup

Follow the steps below to set up the frontend application.

1. Clone the repository:

   ```bash
   git clone https://github.com/Zippy-sudo/FastFeast.git
   cd fastfeast_app/frontend
   ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the frontend app:

    ```bash
    npm start
    ```

    The frontend will be accessible at http://localhost:3000.

## Backend Setup

Follow the steps below to set up the backend application.

1. Clone this repository:

    ```bash
    git clone https://github.com/Zippy-sudo/fastfeast_app.git
    ```

2. Set up a virtual environment and enter it:

    ```bash
    pipenv install && pipenv shell
    ```

4. Set up environment variables:

     ```bash
     export FLASK_APP=app.py
     export FLASK_RUN_PORT=5555
     ```

5. Run the backend server:
    
    ```bash
    flask run
    ```

    The backend will be accessible at http://localhost:5555.

## API Endpoints

##Here are the main API endpoints exposed by the backend:
    
### Restaurants

- GET /restaurants: Fetch all restaurants.
- POST /restaurants: Add a new restaurant.
- GET /restaurants/:id: Get details of a specific restaurant.
- PATCH /restaurants/:id: Update restaurant details.
- DELETE /restaurants/:id: Delete a restaurant.

### Menu Items

- GET /items: Get all menu items.
- POST /items: Add a new menu item to a restaurant.
- GET /items: Get a specificitems details
- PATCH /items/:id: Update an item.
- DELETE /items/:id: Delete a menu item.

### Orders

- GET /orders: Get all orders.
- POST /orders: Add a new order.
- GET /orders/:id Get a specific orders details
- PATCH /orders/:id: Update an order.
- DELETE /items/:id: Delete an order.

### Reviews

- GET /reviews: Get all reviews.
- POST /reviews: Add a new review.
- GET /reviews/:id Get a specific reviews details
- PATCH /reviews/:id: Update an review.
- DELETE /reviews/:id: Delete an review.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or suggestions, feel free to contact me at:

GitHub: github.com/Zippy-sudo
