# Docker Container Operations

This project demonstrates the deployment of a Dockerized web application on an AWS EC2 instance using Docker and Docker Compose.

## Project Structure

The following files are included in this project:

- **Dockerfile**: Defines the environment and builds the Docker image.
- **docker-compose.yml**: Configures and manages the Docker containers.
- **index.html**: A basic HTML file for the web application.
- **script.sh**: A shell script for setting up Docker on the EC2 instance.
- **ec2-server.png**: Screenshot of the EC2 instance in operation.
- **output-via-browser.png**: Screenshot of the web application output in a browser.

## Setup Instructions

### Launch EC2 Instance

1. Launch an EC2 instance using **Amazon Linux 2023**.

### Install Docker

2. Execute the provided `script.sh` to install Docker and Docker Compose:

   ```bash
   chmod +x script.sh
   ./script.sh

### Deploy the Application

3. Clone the repository, navigate to the project folder, and run the following command to build and deploy the application:

   ```bash
   sudo docker-compose up --build -d
   
### Access the Application

4. Open your web browser and navigate to the EC2 instance's public IP address to access the web application.

### Conclusion
This project successfully sets up a simple web application on AWS using Docker containers, showcasing the capabilities of Docker Compose for basic web hosting. The outlined steps provide a streamlined process for deploying containerized applications on cloud infrastructure.   
