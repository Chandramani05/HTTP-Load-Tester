# HTTP Load Testing and Benchmarking Tool

This project is a general-purpose HTTP load-testing and benchmarking tool. It consists of a backend built with FastAPI and a frontend built with React.js. The backend handles the load testing logic, while the frontend provides a user interface to input parameters and visualize results.

## Features

- Input an HTTP address to test
- Support for setting requests per second (QPS)
- Real-time reporting of latencies and error rates
- Visualization of results using charts
- Dockerized for easy deployment

## Prerequisites

- Docker
- Docker Compose (optional, but recommended for ease of use)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Chandramani05/load-testing-tool.git
cd load-testing-tool

```
Navigate to the backend and build the docker image

```bash
cd backend
docker build -t backend .
```

Run the docker container

```bash
docker run -p 8000:8000 backend
```
### Build and Run FrontEnd

Navigate to the fronend directory and build the docker image


```bash
cd frontend
docker build -t frontend .
```

Run the docker container for frontend

```bash
docker run -p 3000:80 frontend
```


## Access the Application
http://localhost:3000







