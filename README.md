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

Install dependencies with:

```bash
pip install -r requirements.txt
````

## Usage

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2. Run the app locally:

```bash
python app.py
```

3. Open your browser and go to:

```
http://127.0.0.1:5000
```

4. Enter a URL and check its status.

## Deployment

This app can be deployed on platforms like Heroku using the provided `Procfile`:

```
web: gunicorn app:app
```


You can paste this directly into a `README.md` file.  

If you want, I can also make a **super short version under 100 words** suitable for GitHub repos.
```
