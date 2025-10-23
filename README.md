# Available Places App

A React application that allows users to view, select, and manage places.  
The app uses a Node.js + Express backend to fetch and update places data stored in JSON files.


## Features
- View available places
- Select and save user places
- Optimistic UI updates for a fast and responsive experience
- Error handling with custom error messages
- Responsive UI

---

### Installation

Prerequisites

Please ensure you have Node.js and npm installed on your system before proceeding.

1. Frontend Setup

The frontend is typically located in the root of the project.

Navigate to the project root directory:

cd your-project


Install the necessary dependencies:

npm install


2. Backend Setup

The backend service is located in the backend/ directory.

Navigate to the backend folder:

cd backend


Install the backend dependencies:

npm install


3. Running the Application

To run the full application, you will need two separate terminal windows open to execute the backend and frontend simultaneously.

Terminal 1: Start the Backend

In the terminal that is currently in the backend folder, execute:

node app.js


STATUS: The backend API is now running and listening at http://localhost:3000.

Terminal 2: Start the Frontend

In a second terminal, ensure you are in the project root (cd your-project), and then execute the development command:

npm run dev


STATUS: The frontend application will start up and typically open a browser window for you to view the app




