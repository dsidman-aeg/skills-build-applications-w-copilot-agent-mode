# Frontend Documentation for the Monafit Tracker Project

## Overview

The Monafit Tracker frontend is built using React and serves as the user interface for the Monafit Tracker application. It interacts with the Django backend to provide a seamless experience for users to track their fitness activities, view leaderboards, manage teams, and more.

## Project Structure

The frontend project is organized as follows:

```
frontend/
├── public/                # Contains static files like index.html
├── src/                   # Contains the source code for the React application
│   ├── components/        # Contains React components for different features
│   │   ├── Activities.js  # Component for displaying activities
│   │   ├── Leaderboard.js  # Component for displaying leaderboard
│   │   ├── Teams.js       # Component for displaying teams
│   │   ├── Users.js       # Component for displaying users
│   │   └── Workouts.js    # Component for displaying workouts
│   ├── App.css            # CSS styles for the main application
│   ├── App.js             # Main component that sets up routing
│   ├── index.css          # Global CSS styles
│   └── index.js           # Entry point of the React application
├── package.json           # Configuration file for npm
└── README.md              # Documentation for the frontend
```

## Getting Started

To get started with the Monafit Tracker frontend, follow these steps:

1. **Install Dependencies**: Navigate to the `frontend` directory and run the following command to install the necessary packages:

   ```
   npm install
   ```

2. **Run the Application**: Start the development server with the following command:

   ```
   npm start
   ```

   This will launch the application in your default web browser at `http://localhost:3000`.

## Components

The frontend consists of several key components:

- **Activities**: Displays a list of activities tracked by users.
- **Leaderboard**: Shows the leaderboard with user scores.
- **Teams**: Manages and displays teams participating in activities.
- **Users**: Displays user profiles and information.
- **Workouts**: Lists available workouts and their details.

## API Integration

The frontend communicates with the Django backend via RESTful API endpoints. Ensure that the backend server is running to fetch data correctly.

## Contributing

Contributions to the Monafit Tracker frontend are welcome! Please follow the standard practices for contributing to open-source projects, including forking the repository, making changes, and submitting a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.