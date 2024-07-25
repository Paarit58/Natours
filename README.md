# VoyageHub

VoyageHub is a backend API designed for a tour booking system, built with Node.js and Express.js. It provides comprehensive features for user authentication, tour management, and booking management.

## Features

- **User Authentication**: Secure sign-up, login, logout, and profile management with role-based access.
- **Tour Management**: Admins and lead guides can create, update, and delete tours; all users can view and review tours.
- **Booking Management**: Regular users can book tours, while admins and lead guides can manage all bookings.
- **Review Management**: Users can write, edit, and delete reviews for tours; admins can manage all reviews.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Security**: bcryptjs, helmet
- **Environment Management**: dotenv
- **Email Notifications**: Nodemailer

## Getting Started

### Prerequisites

- Node.js (v10 or later)
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/VoyageHub.git

2. Navigate to the project directory:
    ```bash
    cd VoyageHub

3. Install dependencies:
    ```bash
    npm install

4. Create a .env file in the root directory with the following content:
    ```php
    NODE_ENV=development
    PORT=3000
    DATABASE=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/<database>?retryWrites=true
    DATABASE_LOCAL=mongodb://localhost:27017/<database>
    DATABASE_PASSWORD=<your-database-password>

    JWT_SECRET=<your-jwt-secret>
    JWT_EXPIRES_IN=<expiry-time>
    JWT_COOKIE_EXPIRES_IN=<cookie-expiry-time>

    EMAIL_USERNAME=<your-email-username>
    EMAIL_PASSWORD=<your-email-password>
    EMAIL_HOST=<your-email-host>
    EMAIL_PORT=<your-email-port>

5. Satart the server:
    ```bash
    npm run dev


## Usage

- **Base URL**: http://localhost:3000/api/v1
- **Endpoints**: 
    - **/users**: Manage user profiles and authentication.
    - **/tours**: View, create, update, and delete tours.
    - **/reviews**: Write, edit, and view reviews.



