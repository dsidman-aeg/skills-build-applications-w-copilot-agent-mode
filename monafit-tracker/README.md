# monafit Tracker

## Overview
The monafit Tracker is a comprehensive fitness application designed to help users track their activities, manage teams, and compete on a leaderboard. It includes features for user authentication, personalized workout suggestions, and activity logging, all within a single application.

## Features
- **User Authentication**: Secure login and registration for users.
- **User Profiles**: Manage personal information and track fitness progress.
- **Activity Logging**: Log various fitness activities and track performance over time.
- **Team Management**: Create and manage teams for collaborative fitness challenges.
- **Competitive Leaderboard**: View rankings based on user activities and scores.
- **Personalized Workout Suggestions**: Receive tailored workout plans based on user preferences and goals.

## Project Structure
```
monafit-tracker
├── backend
│   ├── venv/
│   ├── monafit_tracker/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── settings.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   ├── requirements.txt
│   └── manage.py
├── frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Activities.js
│   │   │   ├── Leaderboard.js
│   │   │   ├── Login.js
│   │   │   ├── Profile.js
│   │   │   ├── Register.js
│   │   │   ├── Teams.js
│   │   │   ├── Workouts.js
│   │   │   └── Dashboard.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── App.css
│   ├── package.json
│   └── README.md
└── README.md
```

## Installation

### Backend
1. Navigate to the `backend` directory.
2. Create a Python virtual environment:
   ```
   python3 -m venv venv
   ```
3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```
4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

### Frontend
1. Navigate to the `frontend` directory.
2. Install the necessary dependencies:
   ```
   npm install
   ```

## Running the Application

### Backend
1. Navigate to the `backend` directory.
2. Run the Django server:
   ```
   python manage.py runserver
   ```

### Frontend
1. Navigate to the `frontend` directory.
2. Start the React application:
   ```
   npm start
   ```

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.