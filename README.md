# dockertesting
Tests for docker applications


# Mini Snake Game in Docker

This project is a browser-based Snake game built with Python and Flask, then containerized with Docker.

## What it does
The application starts a local web server and serves a playable Snake game in the browser.

## Dependency used
- Flask

## Project files
- `app.py` - Flask application
- `requirements.txt` - Python dependency list
- `Dockerfile` - Docker container setup
- `templates/index.html` - Snake game frontend

## Build the Docker image
How to run the docker image


use bash/powershell/equivalent
docker build -t mini-snake .
docker run -p 8000:8000 mini-snake

This runs a webserver on your system on port 8000.

Go to this url:
http://localhost:8000/

Use arrow keys to play.
