# Expense Tracker Fullstack

A full-stack expense tracker application with a React frontend and Node.js backend.

---

## Project Structure

- `backend/` — Node.js/Express server, API routes, controllers, models, and database connection.
- `frontend/` — React application for the user interface.
- `.env` — Environment variables (not included in the repo for security).

---

## Features

- Track expenses by categories and amounts
- User authentication and authorization
- Responsive UI built with React
- RESTful API backend with Express and MongoDB

---

## Prerequisites

- [Node.js](https://nodejs.org/en/download/) and npm installed
- MongoDB or any other database running and accessible

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd expense-tracker_fullstack
   ```

2. Install backend dependencies:

   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

---

## Running the Application Locally

1. Start the backend server:

   ```bash
   cd backend
   npm start
   ```

2. Start the frontend development server (in a separate terminal):

   ```bash
   cd frontend
   npm start
   ```

3. Open your browser and visit: `http://localhost:3000`

---

## Environment Variables

Create a `.env` file in the `backend` folder with the following variables:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

**Note:** Keep your `.env` file private and do not commit it to the repository.

---

## Usage

- Add, edit, and delete expenses
- View expenses categorized and summarized

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## Contact

For questions or suggestions, please contact [Yogeeshkulal](mailto:yogeeshkulal1234@.com)