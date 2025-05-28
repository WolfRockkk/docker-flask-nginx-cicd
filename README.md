# Dockerized Flask Web Application with NGINX and Docker Compose

## Overview

This project demonstrates how to build and deploy a simple web application using Flask (Python) and Docker. It uses Docker Compose to run both the application and an NGINX reverse proxy in separate containers, simulating a typical production deployment environment.

## Features

- Python Flask web application
- Containerization with Docker for portability and consistency
- NGINX as a reverse proxy for efficient HTTP request handling
- Multi-container orchestration using Docker Compose

## Getting Started

### Prerequisites

- Docker and Docker Compose installed on your system
- (Optional) Python 3.x for running locally without Docker

### Running the Application

1. **Clone this repository:**
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. **Build and start the services using Docker Compose:**
    ```bash
    docker compose up --build
    ```

3. **Access the application:**
    - Open your web browser and go to [http://localhost](http://localhost)

### Stopping the Application

- In your terminal, press `CTRL+C` to stop.
- To remove the containers, run:
    ```bash
    docker compose down
    ```

## Project Structure
