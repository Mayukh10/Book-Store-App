

# 📚 Book Store MERN Application

A full-stack Book Store application built using the MERN (MongoDB, Express, React, Node) stack. This application allows users to browse books, view detailed information, add books to a shopping cart, and complete purchases. The project demonstrates end-to-end functionality using a modern web development stack.

## 🔗 Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Environment Variables](#environment-variables)
- [Future Improvements](#future-improvements)

## ✨ Features
- **Book Browsing**: View a collection of books available for purchase.
- **Book Details**: See specific details like author, genre, price, and description.
- **Shopping Cart**: Add books to a cart for purchase.
- **Checkout**: Review and complete the purchase order.

## 💻 Technologies Used
- **Frontend**: React.js, HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Additional Libraries**: Axios (API requests), Mongoose (database management), dotenv (environment management)

## ⚙️ Installation

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed.

### Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/book-store-app.git
   cd book-store-app
   ```

2. **Install dependencies**:

   - **Backend Setup**:
     ```bash
     cd backend
     npm install
     ```

   - **Frontend Setup**:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set up environment variables**:
   - In the `backend` directory, create a `.env` file with the following variables:

     ```plaintext
     MONGODB_URI=<your_mongodb_connection_string>
     PORT=5000
     ```

   Replace `<your_mongodb_connection_string>` with your actual MongoDB connection string.

## 🚀 Running the Application

1. **Start MongoDB**:
   ```bash
   mongod
   ```

2. **Start the Backend**:
   In the `backend` folder:
   ```bash
   npm run start
   ```
   The backend server will run on `http://localhost:5000`.

3. **Start the Frontend**:
   In the `frontend` folder:
   ```bash
   npm start
   ```
   The frontend application will run on `http://localhost:3000`.

4. **Access the Application**: Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📂 Project Structure

```plaintext
book-store-app/
├── backend/                   # Server-side code
│   ├── config/                # Database configuration
│   ├── controllers/           # API route controllers
│   ├── models/                # Database models (schemas)
│   ├── routes/                # API routes
│   └── server.js              # Main server file
├── frontend/                  # Client-side code
│   ├── public/                # Public assets
│   ├── src/
│   │   ├── components/        # Reusable components
│   │   ├── pages/             # Main app pages
│   │   ├── App.js             # Root component
│   │   └── index.js           # Entry point
├── README.md
└── package.json
```

## 🔑 Environment Variables

Define the following environment variables in `backend/.env`:

```plaintext
MONGODB_URI=<your_mongodb_connection_string>
PORT=5000
```

Replace `<your_mongodb_connection_string>` with your actual MongoDB URI.

## 🚧 Future Improvements
- **User Authentication**: Enable users to register and log in.
- **Advanced Search & Filter**: Filter books by genre, author, and price range.
- **Order Management**: Allow users to view order history.
- **Admin Panel**: Provide an admin dashboard for book management and order overview.

---

Contributions are welcome! Feel free to open an issue or submit a pull request. Let’s build a better Book Store experience together!

