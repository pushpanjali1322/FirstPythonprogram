# Use an official Python runtime as a parent image
FROM python:3.11-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . .

# Install any dependencies specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 for the web server
EXPOSE 5000

# Define environment variable
ENV FLASK_APP=app3.py

# Run the Flask app when the container launches
CMD ["python", "app3.py"]
