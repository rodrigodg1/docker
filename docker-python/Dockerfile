FROM python:3.8-slim

COPY . /app

# Set the working directory in the container
WORKDIR /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 5000 available to the world outside this container
EXPOSE 5000

# Define environment variable
ENV FLASK_ENV=production

# Run app.py when the container launches
CMD ["flask", "run", "--host=0.0.0.0"]
