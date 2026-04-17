# URL Shortener + Analytics System

A Flask backend project that shortens URLs, tracks clicks, and provides basic analytics with authentication and caching.

## Features
- User login/register (JWT auth)
- Shorten long URLs into short links
- URL redirection system
- Click tracking + analytics
- Rate limiting to prevent abuse
- URL expiration support
- In-memory caching for faster redirects
- Per-user dashboard for stats

## Tech Stack
- Python
- Flask
- Flask-SQLAlchemy
- Flask-JWT-Extended
- SQLite

## How to Run

```bash
pip install -r requirements.txt
python app.py
