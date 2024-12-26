# Weather_report
Weather Dashboard Application This project is a weather dashboard application that fetches real-time weather data from OpenWeather API and stores search history in a MySQL database.Additionally, the application stores the search history in a MySQL database and allows users to view previous searches in a history window.

Key Features:
Fetch current weather data using OpenWeather API.
Display weather details like temperature, humidity, and weather condition.
Store search history (city name, temperature, humidity, weather condition, and timestamp) in a MySQL database.
View search history with the option to display recent searches in the GUI.
Simple and intuitive user interface built with Tkinter.

Requirements:

Python 3.x
Tkinter (for GUI)
Requests (for API requests)
MySQL Connector (for database interaction)

Setup:

Install dependencies:

bash

Copy code

pip install requests mysql-connector-python

Set up a MySQL database and configure the connection settings in the code.

Create a .env or modify the DB_CONFIG variable in the code to use your MySQL database credentials.

Run the script to start the weather dashboard GUI.
