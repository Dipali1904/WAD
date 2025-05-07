# Use Python base image
FROM python:3.10-slim

# Set working directory inside the container
WORKDIR /app

# Copy files into the container
COPY . .

# Install Python dependencies
RUN pip install -r requirements.txt

# Run the application
CMD ["python", "app.py"]
