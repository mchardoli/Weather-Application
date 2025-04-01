# Weather Application

A simple weather application with user authentication that allows users to check weather information for any city around the world.

## Features

- User registration and login system
- Real-time weather information using OpenWeatherMap API
- Responsive design with Bootstrap
- Secure password hashing
- SQLite database for user management

## Setup

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file in the root directory with the following variables:
   ```
   SECRET_KEY=your-secret-key-here
   OPENWEATHER_API_KEY=your-openweather-api-key
   ```
   You can get an OpenWeather API key by signing up at [OpenWeatherMap](https://openweathermap.org/api)

5. Run the application:
   ```bash
   python app.py
   ```

## Usage

1. Register a new account or login with existing credentials
2. Enter a city name to get weather information
3. View detailed weather data including:
   - Temperature
   - Weather conditions
   - Humidity
   - Wind speed
   - Pressure

## Security Features

- Password hashing using Werkzeug
- Protected routes requiring authentication
- SQLite database for secure user data storage
- Environment variables for sensitive information

## Technologies Used

- Python Flask
- SQLite
- Flask-Login
- Bootstrap 5
- OpenWeatherMap API 