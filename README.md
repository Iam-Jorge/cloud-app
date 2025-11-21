# Cloud App - Dockerized Flask Example

This is a simple Flask web application created for **Exercise 1.16** of the Docker MOOC from the University of Helsinki.

The application returns a message on the root URL and has been containerized using Docker. All dependencies are listed in `requirements.txt`.

## Running Locally

1. Build the Docker image:

```bash
docker build -t cloud-app .
```

2. Run the container 
```bash
docker run -p 5000:5000 cloud-app
```

3. View on browser at http://localhost:5000
