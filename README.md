# Devops Assignment 

This repository demonstrates a Node.js application packaged into a Docker container. The pre-built Docker image for this application is hosted on Docker Hub and can be pulled and run locally.
Link : https://hub.docker.com/r/siddhantk7/node-docker-app

---

## How to Use

### Step 1: Pull the Docker Image
To get the Docker image, pull it from Docker Hub using the following command:
```bash
docker pull siddhantk7/node-docker-app
```

#### Step 2: After pulling the Image, Run the Docker Container Command:
```bash
docker run -p 3000:3000 siddhantk7/node-docker-app
```
#### Step 3 : Once the container is running, open your browser and navigate to:
````bash
http://localhost:3000
