# pull-zoom-meeting-data
A python program to pull data from zoom for a specific date

### Introduction
This Python program allows you to pull data from Zoom for a specific date. Zoom is a video conferencing platform widely used for online meetings, webinars, and virtual classrooms. This script will help you retrieve relevant data for analysis and reporting purposes.


### Prerequisites
Python 3.x installed on your machine.
Zoom API credentials: You will need a Zoom API key and secret to access the Zoom API endpoints. Obtain these by creating a Zoom Developer account and generating the necessary credentials.


### Usage
Ensure you have the Zoom API credentials (API key and secret) handy.
Open the config.py file and update the API_KEY and API_SECRET variables with your Zoom API credentials.
Run the Python script to pull data for a specific date

### Configuration
In the config.py file, you can customize the following options:

API_KEY: Your Zoom API key.
API_SECRET: Your Zoom API secret.
DATE: The specific date for which you want to pull data. (Please use the format "YYYY-MM-DD").


### Data Pull
The Python program utilizes the Zoom API to fetch data for the specified date. The data retrieved may include information about meetings, participants, attendance, or any other relevant details based on your API request.

### Output
The program will generate a data file (e.g., CSV or JSON) containing the information retrieved from Zoom for the specific date. The output file will be saved in the project directory with a filename reflecting the date of the data pull.
