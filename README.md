# Flask Web Application

This repository contains the source code for a Flask-based web application. It is designed to provide a comprehensive demonstration of Flask capabilities in conjunction with MongoDB, PayPal integration, and email functionalities.

## Features

- User authentication and session management.
- MongoDB Atlas integration for data persistence.
- PayPal payment processing for e-commerce functionality.
- Email sending capability for notifications and multi-factor authentication.
- Dynamic content rendering using Flask templates.
- Wishlist and shopping cart features for a better user experience.
- Administrative features for managing products.

## Getting Started

### Prerequisites

- Python 3
- Flask
- MongoDB account
- PayPal developer account
- Email account for sending notifications

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepositoryname.git
   ```
2. Navigate to the project directory:
   ```bash
   cd yourrepositoryname
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
   (Note: Ensure you create and activate a virtual environment before this step if you prefer using virtual environments.)

### Configuration

1. Set up your MongoDB Atlas cluster and obtain the connection string.
2. Register your application with PayPal and get your client ID and secret.
3. Configure your email service and obtain the necessary credentials.
4. Create a `.env` file or set environment variables for sensitive data:
   ```
   MONGODB_URI=<your_mongodb_connection_string>
   PAYPAL_CLIENT_ID=<your_paypal_client_id>
   PAYPAL_CLIENT_SECRET=<your_paypal_client_secret>
   MAIL_USERNAME=<your_email>
   MAIL_PASSWORD=<your_email_password>
   SECRET_KEY=<your_flask_secret_key>
   ```

### Running the Application

1. Start the Flask application:
   ```bash
   python app.py
   ```
2. Access the application through your web browser at `http://127.0.0.1:5000/`.

## Usage

- Register as a new user or log in with existing credentials.
- Explore the product catalog, add items to your wishlist and shopping cart.
- Proceed to checkout and complete the payment process using the PayPal integration.
- View and update your user profile.
- Administrators can add, update, or remove products.


## Acknowledgments

- [Flask](https://flask.palletsprojects.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [PayPal Developer](https://developer.paypal.com/)
- [Flask-Mail](https://pythonhosted.org/Flask-Mail/)

