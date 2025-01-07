# Use the official Python image
FROM python:3.10-slim

# Set the working directory
WORKDIR /app

# Copy project files
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Set environment variables
ENV REDIS_HOST=redis
ENV REDIS_PORT=6379

# Expose the application port
EXPOSE 8001

# Command to run the application
CMD ["python", "manage.py", "runserver", "0.0.0.0:8001"]
