There were some questions that needed content to write. This app has that content.

# Flask Application with Docker
This repository contains a simple Flask web application that is containerized using Docker. Follow the steps below to build and run the Docker container.
## Prerequisites
Make sure you have the following installed on your machine:
1. **Python** (for local development, optional)
2. **Docker** (for building and running the container)
3. **Git** (for cloning the repository)
## Steps to Build and Run the Container

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/ainamanidickson/ci-cd-assignment.git
cd ci-cd-assignment
## Build the Docker Image using the command
- docker build -t assign-app 
After building the image, you can run the container with the following command
docker run -p 5000:5000 assign-app
The application will be accessible at http://localhost:5000.


