# Yamuna.devtern

# Secure Login System

## Description
This project is a secure login system built using Node.js and Express. It demonstrates secure password handling and user authentication using bcrypt for hashing passwords.

## Features
- **Secure Password Storage**: Passwords are securely hashed using bcrypt, ensuring safe storage.
- **User Authentication**: Provides a basic authentication system that validates users against stored hashed passwords.
- **Static File Serving**: Serves static files such as HTML and CSS from the `public` directory.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yamuna-1128/Yamuna.devtern
   cd Yamuna.devtern
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the server:
   ```
   node server.js
   ```

## Usage

Once the server is running:
- Navigate to `http://localhost:3000` in your web browser to access the main login page.
- Log in using the credentials. If no specific credentials are provided, check the server.js for predefined user details.
- After logging in, additional features can be accessed through `upload.html`.

## Frontend Components

The frontend includes:
- **index.html**: The main page that contains the login interface.
- **styles.css**: Provides styling for the HTML pages.
- **upload.html**: A page for additional user interactions post-login.

## Endpoints

- **POST `/login`**: Accepts username and password for authentication. Returns success or failure based on the credentials.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with your enhancements.
