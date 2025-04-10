# Frontend README for Monafit Tracker

## Overview

The Monafit Tracker frontend is a React application that provides a user-friendly interface for tracking fitness activities, managing teams, and viewing leaderboards. It allows users to log their activities, create and manage teams, and receive personalized workout suggestions.

## Features

- **User Authentication**: Users can register, log in, and manage their profiles.
- **Activity Logging**: Users can log their fitness activities and track their progress.
- **Team Management**: Users can create teams, invite members, and manage team activities.
- **Competitive Leaderboard**: Users can view a leaderboard that ranks participants based on their activities and scores.
- **Personalized Workouts**: Users receive workout suggestions tailored to their fitness goals.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (Node package manager)

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd monafit-tracker/frontend
   ```

2. Install the dependencies:

   ```
   npm install
   ```

### Running the Application

To start the development server, run:

```
npm start
```

The application will be available at `http://localhost:3000`.

### Building for Production

To create a production build of the application, run:

```
npm run build
```

This will generate a `build` directory with the optimized production files.

## Folder Structure

- **public/**: Contains static files such as the HTML file and images.
- **src/**: Contains the source code for the React application.
  - **components/**: Contains individual React components for various features.
  - **App.js**: Main application component that sets up routing.
  - **index.js**: Entry point for the React application.
  - **App.css**: CSS styles for the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.