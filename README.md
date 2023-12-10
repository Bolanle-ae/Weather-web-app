# Weather-web-app
Weather information webapp with python and flask

Weather Information Web App with Python and Flask

This project utilizes Python and the Flask framework to create a simple web application that fetches weather data from the weatherstack.com API. The web interface consists of two HTML files, namely "indexx.html" and "weather.html," allowing users to input a location and view relevant weather statistics.

Features:
Weatherstack API Integration: The Python script connects to the weatherstack.com API to retrieve up-to-date weather information based on user input.

Flask Web Interface: The web application is built using Flask, providing a user-friendly experience. Users can navigate between the input form and the weather statistics display.

Interactive Input: Users can input a location, and the application fetches and displays real-time weather statistics, including temperature, descriptiod, and more.

Project Structure:
app.py: The main Python script containing the Flask application and integration with the weatherstack API.

templates/: This directory includes the HTML files used for rendering the web pages, namely "indexx.html" for user input and "weather.html" for displaying weather statistics.

weather.ipynb: Jupyter notebook file providing a detailed walkthrough and explanation of the project, making it easy for others to understand and contribute.

Getting Started:
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Run the Flask application using python app.py.
Open a web browser and navigate to http://localhost:5000 to access the weather information web app.
Contributions:
Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback to enhance the functionality and usability of the application.

Dependencies:
Flask
Requests
(Other dependencies as mentioned in requirements.txt)
Disclaimer:
Make sure to obtain your own API key from weatherstack.com and replace the placeholder in the script with your key for proper API access.
