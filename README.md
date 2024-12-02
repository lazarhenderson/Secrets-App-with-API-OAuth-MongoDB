# Secrets App

## Overview

A web application that enables users to anonymously submit secrets. The app leverages Node.js, Express, MongoDB, and Passport.js for secure authentication, including Google OAuth integration.

## Features

- **User Authentication:**

  - Register/login with email and password.
  - Login with Google OAuth 2.0.

- **Anonymous Secrets Sharing:**

  - Users can submit secrets anonymously.
  - View all shared secrets from other users.

- **Session Management:**
  - Persistent login using Express sessions and Passport.js.

---

## Prerequisites

Ensure you have the following installed:

1. **Node.js** (v14 or later)
2. **MongoDB** (local instance or Atlas)
3. **Google Cloud Project** with OAuth 2.0 credentials.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/secrets-app.git
   cd secrets-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:  
   Create a `.env` file in the root directory and add:

   ```
   CLIENT_ID=your_google_client_id
   CLIENT_SECRET=your_google_client_secret
   ```

4. Start MongoDB:

   ```bash
   mongod
   ```

5. Start the server:
   ```bash
   npm start
   ```

---

## Usage

1. Open your browser and navigate to:  
   [http://localhost:3000](http://localhost:3000)

2. Register, log in, and start sharing secrets.

---

## Project Structure

```
secrets-app/
├── public/               # Static files (CSS)
├── views/                # EJS templates
├── .env                  # Environment variables
├── app.js                # Main application logic
├── package.json          # Dependencies and scripts
└── README.md             # Documentation
```

---

## Technologies Used

- **Backend:** Node.js, Express.js
- **Authentication:** Passport.js, Passport-Local, Google OAuth 2.0
- **Database:** MongoDB, Mongoose
- **Templating Engine:** EJS

---

## Contributing

1. Fork the project.
2. Create your feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License.

---
