# monafit-tracker

## Project Overview
The monafit-tracker project is a fitness tracking application that consists of a Django backend and a React frontend. The application allows users to track their activities, manage teams, view leaderboards, and log workouts.

## Directory Structure
The project is organized into two main directories: `backend` and `frontend`.

### Backend
- **venv/**: Contains the Python virtual environment for isolating dependencies.
- **manage.py**: Command-line utility for managing the Django application.
- **requirements.txt**: Lists the required Python packages for the Django backend.
- **monafit_tracker/**: Contains the Django project files, including:
  - **__init__.py**: Indicates that this directory is a Python package.
  - **asgi.py**: ASGI configuration for asynchronous server communication.
  - **models.py**: Defines the data models for the application.
  - **serializers.py**: Contains serializers for converting complex data types to JSON.
  - **settings.py**: Configuration settings for the Django project.
  - **urls.py**: URL routing for the Django application.
  - **views.py**: View functions or classes that handle requests and return responses.
  - **wsgi.py**: WSGI configuration for the Django project.
  - **management/commands/**: Custom management commands for the Django application.

### Frontend
- **public/**: Contains static files for the React application.
- **src/**: Contains the source code for the React application, including:
  - **components/**: React components for the application.
    - **Activities.js**: Displays activity-related data.
    - **Leaderboard.js**: Displays the leaderboard data.
    - **Teams.js**: Displays team-related data.
    - **Users.js**: Displays user-related data.
    - **Workouts.js**: Displays workout-related data.
  - **App.css**: CSS styles for the main application.
  - **App.js**: Main component of the React application.
  - **index.css**: Global CSS styles for the React application.
  - **index.js**: Entry point of the React application.

## Getting Started
To set up the project, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd monafit-tracker
   ```

2. **Set up the backend**:
   - Navigate to the `backend` directory.
   - Create a virtual environment:
     ```
     python3 -m venv venv
     ```
   - Activate the virtual environment:
     ```
     source venv/bin/activate
     ```
   - Install the required packages:
     ```
     pip install -r requirements.txt
     ```
   - Run migrations and start the server:
     ```
     python manage.py migrate
     python manage.py runserver
     ```

3. **Set up the frontend**:
   - Navigate to the `frontend` directory.
   - Install the dependencies:
     ```
     npm install
     ```
   - Start the React application:
     ```
     npm start
     ```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.