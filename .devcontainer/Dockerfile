# Use the official image as a parent image
FROM python:3.9.16-slim-buster

# Set the working directory in the container to /app
WORKDIR /app

# Install Git
RUN apt-get update && apt-get install -y git

# Copy the requirements.txt file into the container
COPY requirements.txt .

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
