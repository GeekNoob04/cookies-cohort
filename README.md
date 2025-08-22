# 🔐 Authentication System with React Frontend and Node.js Backend

This project implements a basic authentication system with a React frontend and a Node.js backend. It allows users to sign up, sign in, view their user ID, and log out. **Please note that the current backend implementation has a critical security vulnerability: it does not validate usernames and passwords against a database.** This is a simplified example for demonstration purposes only and should not be used in a production environment without proper security measures.

## 🚀 Key Features

- **User Signup:** Allows new users to create an account (username and password).
- **User Signin:** Allows existing users to log in with their credentials.
- **User Profile:** Displays the user's ID after successful login.
- **Logout:** Allows users to invalidate their session.
- **Cookie-based Authentication:** Uses JWTs stored in cookies for authentication.
- **React Frontend:** A user-friendly interface built with React.
- **Node.js Backend:** A simple backend server built with Express.

## 🛠️ Tech Stack

**Frontend:**

-   **React:** JavaScript library for building user interfaces.
-   **React Router DOM:** For handling client-side routing.
-   **Axios:** For making HTTP requests to the backend.
-   **Vite:** Build tool for modern web development.
-   **@vitejs/plugin-react:** Vite plugin for React support.

**Backend:**

-   **Node.js:** JavaScript runtime environment.
-   **Express:** Web application framework for Node.js.
-   **Cookie Parser:** Middleware for parsing cookies.
-   **CORS:** Middleware for enabling Cross-Origin Resource Sharing.
-   **JSON Web Token (JWT):** For creating and verifying tokens.

## 📦 Getting Started / Setup Instructions

### Prerequisites

-   Node.js and npm installed
-   Basic knowledge of React and Node.js

### Installation

**Backend:**

```bash
cd backend
npm install
```

**Frontend:**

```bash
cd frontend
npm install
```

### Running Locally

1.  **Start the Backend:**

```bash
cd backend
npm run start
```

2.  **Start the Frontend:**

```bash
cd frontend
npm run dev
```

The frontend will be accessible at `http://localhost:5173`, and the backend will be running on `http://localhost:3000`.

## 💻 Usage

1.  **Signup:** Navigate to `http://localhost:5173/signup` to create a new user account. Enter a username and password, and click "Submit".
2.  **Signin:** Navigate to `http://localhost:5173/signin` to log in. Enter your username and password, and click "Submit".
3.  **User Profile:** After successful login, you will be redirected to `http://localhost:5173/user`, where your user ID will be displayed.
4.  **Logout:** Click the "Logout" button on the user profile page to invalidate your session.

## 📂 Project Structure

```
├── backend/
│   ├── src/
│   │   └── index.ts       # Main backend application file
│   ├── package.json
│   └── tsconfig.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Signin.tsx   # Signin component
│   │   │   ├── Signup.tsx   # Signup component
│   │   │   └── User.tsx     # User component
│   │   ├── App.tsx          # Main application component
│   │   ├── config.ts        # Configuration file
│   │   ├── main.tsx         # Entry point for the React application
│   │   └── index.css        # Global CSS styles
│   ├── public/
│   │   └── vite.svg
│   ├── index.html
│   ├── vite.config.ts     # Vite configuration file
│   ├── package.json
│   └── tsconfig.json
├── .gitignore
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

If you have any questions or suggestions, please feel free to contact me at [harshitbudhraja0@gmail.com](mailto:harshitbudhraja0@gmail.com).

## 💖 Thanks Message

Thank you for checking out this project! I hope it's helpful for learning about authentication with React and Node.js.

This is written by [readme.ai](https://readme-generator-phi.vercel.app/).
