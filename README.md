# Docker Flask Blog

A simple Flask application running inside a Docker container.

## Features

- Minimal Flask app setup
- Dockerized for easy deployment
- Ready for local development and containerized environments

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine

### Build and Run with Docker

1. **Clone the repository:**
   ```sh
   git clone https://github.com/akshaygarg3110/docker-flask-blog.git
   cd docker-flask-blog
   ```

2. **Build the Docker image:**
   ```sh
   docker build -t flask-docker-blog .
   ```

3. **Run the Docker container:**
   ```sh
   docker run -p 5000:5000 flask-docker-blog
   ```

4. **Visit the app:**
   Open [http://localhost:5000](http://localhost:5000) in your browser.

## Project Structure

```
.
├── app.py
├── requirements.txt
├── Dockerfile
└── .dockerignore
```

## Development (without Docker)

1. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the app:
   ```sh
   python app.py
   ```

## License

MIT
