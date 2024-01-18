FROM python:3.8

# Set the working dir
WORKDIR /app

# Copy the Python script into the container
COPY app/server.py .

# Expose the port for app
EXPOSE 8000

# Create a non-root user, i skipped this part so nothing breaks
#RUN useradd -ms /bin/bash myuser
#USER myuser

# Command to run the application
CMD ["python", "server.py"]