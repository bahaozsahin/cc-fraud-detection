# Use the official image as a parent image
FROM python:3.9.16-slim-buster

# Set the working directory in the container to /app
WORKDIR /app

# Install Git
RUN apt-get update && apt-get install -y git

# Install JupyterLab dependencies
RUN apt-get install -y nodejs npm && \
    npm install -g yarn

# Install JupyterLab
RUN pip install --no-cache-dir jupyterlab

# Copy the requirements.txt file into the container
COPY requirements.txt .

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 8888 for JupyterLab
EXPOSE 8888

# Set the default command to run JupyterLab
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--port=8888", "--no-browser"]
