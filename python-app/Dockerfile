# Dockerfile
# Use an official Python runtime as a parent image
FROM python:3.9-slim-buster

# Set the working directory inside the container
WORKDIR /app

# Copy the Python application file from the host (your repository)
# into the container's /app directory
COPY app.py .

# Command to run the Python script when the container starts
CMD ["python", "app.py"]