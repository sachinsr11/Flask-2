# Site Connectivity Checker

A simple Flask web application that lets you check if a website is UP or DOWN.

## Features

- Enter any URL to check its connectivity.
- Displays whether the site is UP (accessible) or DOWN (not reachable).
- Simple and lightweight web interface.

## Requirements

- Python 3.8+
- Flask
- Requests
- Gunicorn (for deployment)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/sachinsr11/Flask-2.git
cd Flask-2
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the app locally:

```bash
python app.py
```

2. Open your browser and go to:

```
http://127.0.0.1:5000
```

3. Enter a URL and check its status.

## Deployment

This app is configured for deployment on platforms like Heroku using the provided `procfile`:

```
web: gunicorn app:app
```
