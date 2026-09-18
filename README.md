# Flask Web Calculator

A simple web-based calculator application built using Python Flask. The application provides a browser-based interface for performing basic mathematical operations such as addition, subtraction, multiplication, and division.

This project demonstrates fundamental concepts of Flask web development, including routing, HTTP POST requests, HTML forms, Jinja2 templates, and serving static CSS files.

## Features

- Simple web-based calculator interface
- Addition
- Subtraction
- Multiplication
- Division
- Flask URL routing
- HTML form handling using POST requests
- Jinja2 template rendering
- Separate result page
- Custom CSS styling

## Technologies Used
- Python
- Flask
- HTML
- CSS
- Jinja2

## Application Workflow

The application follows this flow:

User opens application
        │
        ▼
    index.html
        │
        ▼
Select operation + Enter numbers
        │
        ▼
   POST /operation
        │
        ▼
     Flask app
        │
        ▼
Perform calculation
        │
        ▼
   results.html
        │
        ▼
Display result

## Future Improvements

Possible improvements for this project include:

- Add exponentiation
- Add modulus operation
- Support decimal numbers
- Add input validation
- Handle division by zero
- Display calculation history
- Improve responsive UI
- Add error messages for invalid input
- Add unit tests
- Convert the calculator into a REST API
- Deploy the application using Docker and a cloud platform
