# URL Shortener

This is a simple URL shortener web application built using Django, CSS, and JavaScript. It allows users to shorten long URLs into shorter, more manageable links (localhost format).

## Features

- Converts a user-provided URL into a shortened localhost URL.
- Utilizes Django's built-in database for storing and retrieving URL mappings.
- Simple and intuitive user interface.

## Getting Started

To get started with the URL shortener, follow these steps:

1. Clone this repository to your local machine.

2. Navigate to the project directory.
```cd URL_Shortener```

3. Create a virtual environment (optional but recommended):

4. Apply the database migrations.
```python manage.py migrate```

5. Start the development server.
```python manage.py runserver```

6. Open your web browser and go to `http://localhost:8000` to access the URL shortener.

## Usage

1. Open your web browser and navigate to [http://localhost:8000/](http://localhost:8000/).

2. Enter a URL into the input field on the homepage.

3. Click the "Shorten" button.

4. The shortened URL will be displayed below the input field.

5. To access a shortened URL and be redirected to the original page, simply enter the shortened URL in your browser's address bar.