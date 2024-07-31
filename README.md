# ReactJS Authentication

A simple ReactJS application that implements user authentication using context API, local storage, and axios for API calls. This project includes a login and registration page, as well as protected routes for authenticated users.

## Features

- User registration with form validation
- User login with email and password
- Protected routes accessible only to authenticated users
- Context API for state management
- Local storage to persist user authentication state
- Responsive design using Bootstrap

## Technologies Used

- ReactJS
- React Router DOM
- Bootstrap
- Axios
- JSON Server (for mock API)

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (version 18 or higher)
- npm (Node package manager)

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vinojv96/react-authentication.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd react-authentication
   ```

3. **Install the dependencies:**

   ```bash
   npm install
   ```

4. **(Optional) If you're using JSON Server for the mock API, install it globally:**

   ```bash
   npm install -g json-server
   ```

5. **Create a `db.json` file in the root directory of the project with the following content:**

   ```json
   {
     "users": []
   }
   ```

6. **Start the JSON server:**

   ```bash
   json-server --watch db.json --port 8000
   ```

7. **Start the React application:**

   ```bash
   npm start
   ```

### Usage

- Visit `http://localhost:3000` to view the application.
- Navigate to the registration page to create a new account.
- After registering, you can log in with your credentials.
- Access protected routes by logging in.

### Project Structure

```
/react-authentication
|-- /src
|   |-- /components         # Reusable components (Navbar, AuthProvider, etc.)
|   |-- /pages              # Main application pages (Home, Login, Registration, etc.)
|   |-- App.js              # Main application component
|   |-- index.js            # Entry point of the application
|-- db.json                 # Mock database for user data
|-- package.json             # Project dependencies and scripts
|-- README.md               # Project documentation
```

### License

This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgments

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [React Router Documentation](https://reactrouter.com/web/guides/quick-start)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [Axios Documentation](https://axios-http.com/docs/intro)
- [JSON Server Documentation](https://github.com/typicode/json-server)
