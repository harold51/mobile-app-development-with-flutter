Overview 
This simple web application provides an API endpoint for calculating Body Mass Index (BMI). It accepts POST requests with weight and height parameters, calculates the BMI, and returns the result as JSON.
Getting Started
Prerequisites 
Python 3.x Flask (install using pip install Flask) 
API Endpoint Endpoint: /calculate_bmi Method: POST Parameters: weight (float): Weight in kilograms height (float): Height in meters 
Response 
The response will be a JSON object containing the calculated BMI and a remark based on predefined BMI range