# User Management CRUD App

This is a simple CRUD (Create, Read, Update, Delete) application for managing user data. It consists of a server-side component built with Express and a client-side component built with React.

## Features

- View a list of users
- Create a new user
- Update existing user data
- Delete a user

## Technologies Used

- **Server-Side (Express):**
  - Node.js
  - Express.js
  - MongoDB with Mongoose
  - CORS middleware
  - Axios for handling HTTP requests

- **Client-Side (React):**
  - React.js
  - React Router for routing
  - Axios for handling HTTP requests
  - Bootstrap for styling

## Setup

### Server-Side (Express)

1. Install Node.js and MongoDB if you haven't already.

2. Clone this repository: git clone <repository-url>

3. Navigate to the server directory: cd server

4. Install server-side dependencies: npm install express axios nodemon
 
5. Start the Express server: npm start serve

   
The server will run on `http://localhost:3001`.

### Client-Side (React)

1. Navigate to the client directory: cd client
 
2. Install client-side dependencies: npm install
  
3. Start the React development server: npm start

   
The client will run on `http://localhost:3000`.

## Usage

1. Visit `http://localhost:3000` in your web browser to access the application.

2. The home page (`/`) displays a list of users. You can click the "Add +" button to create a new user or click the "Update" and "Delete" buttons to modify or remove existing users.

3. To create a new user, click the "Add +" button and fill in the required details (Name, Email, Age), then click the "Submit" button.

4. To update an existing user, click the "Update" button next to the user you want to edit. Modify the user's details and click the "Update" button on the update form.

5. To delete a user, click the "Delete" button next to the user you want to remove. Confirm the deletion when prompted.

## Contributing

Contributions are welcome! If you find a bug or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.








