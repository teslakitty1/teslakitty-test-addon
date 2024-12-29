# Base image
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy files
COPY web_server/ /app/web_server/
COPY main/ /app/main/

# Install dependencies
RUN pip install flask

# Set entry point
CMD ["python", "/app/web_server/app.py"]
