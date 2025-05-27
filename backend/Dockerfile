# Base Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy files to container
COPY . .

# Install dependencies
RUN pip install -r requirements.txt

# Expose backend port
EXPOSE 5000

# Run the Flask app
CMD ["python", "app.py"]
