# Use an official Python runtime as a parent image
FROM python:2.7-slim
Maintainer jealdana@gmail.com
# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app

# Install any needed packages specified in requirements.txt
RUN pip install --trusted-host pypi.python.org -r requirements.txt

# Define environment variable
ENV NAME Python2.7_appPython2Redis

# Run app.py when the container launches
RUN  ["python", "appPython2Redis.py"]
