# OAuth Login Demo

A simple Node.js app demonstrating login using **Google** and **Facebook** with Passport.js.

## Features

- Google OAuth 2.0 login
- Facebook OAuth 2.0 login
- Express.js server with Passport.js integration
- Environment variables managed securely with `.env`

## 🛠 Getting Started

### 1. Clone the repository

    git clone git@github.com:calsdn/oauth-login.git
    cd oauth-login

### 2. Install dependencies

    npm install

### 3. Set up environment variables

Create a `.env` file by copying the example:

    cp .env.example .env

Then open the `.env` file and fill in your credentials:

    GOOGLE_CLIENT_ID=your-google-client-id
    GOOGLE_CLIENT_SECRET=your-google-client-secret
    FACEBOOK_APP_ID=your-facebook-app-id
    FACEBOOK_APP_SECRET=your-facebook-app-secret

### 4. Run the app

    node server.js

Then open http://localhost:3000 in your browser.
