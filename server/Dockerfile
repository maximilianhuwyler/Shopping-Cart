# Use the official Python image as the base image
FROM python:3.8

# Set environment variables for Flask (you can adjust as needed)
ENV FLASK_APP=main.py
ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_RUN_PORT=5000

# Set the working directory in the container
WORKDIR /app

# Copy the project files into the container
COPY . .

# Install project dependencies using Pipenv
RUN pip install pipenv
RUN pipenv install --deploy --ignore-pipfile

# Expose the port where the Flask app will run
# EXPOSE 5000

# Start the Flask app
CMD ["pipenv", "run", "flask", "run"]
