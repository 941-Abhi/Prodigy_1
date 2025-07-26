HEAD
# User Authentication System

## Features
- User registration (email & password)
- Secure login with JWT
- Protected route example

## Setup
1. Install dependencies:
   ```
npm install
   ```
2. (Optional) Create a `.env` file with:
   ```
JWT_SECRET=your_secret_key
PORT=3000
   ```
   If not set, defaults will be used.

3. Start the server:
   ```
node index.js
   ```

## API Endpoints

### Register
- **POST** `/register`
- Body: `{ "email": "user@example.com", "password": "yourpassword" }`

### Login
- **POST** `/login`
- Body: `{ "email": "user@example.com", "password": "yourpassword" }`
- Returns: `{ "token": "..." }`

### Protected Route
- **GET** `/protected`
- Header: `Authorization: Bearer <token>`

---

You can test with Postman, curl, or a simple frontend. 

# Prodigy_1
 05038b181d6ff49af2632cdc530f7c707b15f11b
