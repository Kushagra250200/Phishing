Project Overview:

This project simulates a simple web page designed to collect credit card details. It is a rudimentary demonstration of how a phishing site might be constructed, not a fully functional or secure payment system.

Key Components and Topics:
Topic: Flask Web Application:
The `main.py` file contains a Python script that sets up a Flask web application. Flask is a web framework used to build web applications in Python.
The application renders an HTML template that displays a form for entering credit card information. It also handles the form submission and saves the collected data to an Excel file.
Topic: HTML Template:
The `main.py` file includes an embedded HTML template. This template creates the webpage seen by the user, including:
A visual representation of an iPhone 15 Pro being offered for 1 Rupee.
Input fields for credit card details (number, expiry date, CVV, name on card).
A "Submit Details" button.
The HTML is designed to look like a checkout page, potentially tricking users into entering their credit card information.
Topic: Data Capture and Storage:
When the user submits the form, the Flask app captures the entered data.
The data is then organized into a Pandas DataFrame and saved as an Excel file named `submission_data.xlsx`. This file serves as a simulated storage of captured information, similar to how a real phishing operation might store stolen data.
File Comparison Table:
File
Description
main.py
Python script using Flask to create a web application, render an HTML form, and capture/save submitted credit card details to an Excel file.
submission_data.xlsx
Excel spreadsheet where the captured credit card data is stored. It contains columns for Credit Card Number, Expiry Date, CVV Code, and Name on Card.

Important Notes:
This project is for educational and demonstrative purposes only. It is crucial to understand that creating and using such a website for malicious purposes is illegal and unethical.
The provided code is a simplified version of what a real phishing site might entail. Real-world phishing attacks often involve more sophisticated techniques.

