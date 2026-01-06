# Use the official Ubuntu image as a base
FROM ubuntu:22.04

# Install curl
RUN apt-get update && apt-get install -y curl

# Set the working directory
WORKDIR /usr/src/app

# Copy the script into the container
COPY script.sh .

# Make the script executable
RUN chmod +x script.sh

# Define the ENTRYPOINT
ENTRYPOINT ["./script.sh"]
