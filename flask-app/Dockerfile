# Base image with python
FROM python:3.9

# Working directory for the apo
WORKDIR app/

# Copy the code from system
COPY app.py .

# Install required libraries
RUN pip install Flask

# Run the application
CMD ["python", "app.py"]
