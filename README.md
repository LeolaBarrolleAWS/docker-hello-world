# 🐳 Docker Hello World

This project demonstrates a simple Python application containerized with Docker. It’s designed to show how to build, run, and explain a Dockerized app — a common DevOps workflow.

---

## 📦 How to Build and Run

1. **Build the Docker image:**
   ```bash
   docker build -t hello-docker .
docker run hello-docker
Hello from a Docker container!

Tools Used

Docker
Python 3.9-slim base image

What I Learned

Writing and structuring a basic Dockerfile
Building Docker images
Running and managing containers with Docker CLI
Understanding the difference between images and containers

Related Commands

docker ps – List running containers
docker stop <container_id> – Stop a running container
docker rm <container_id> – Remove a stopped container
docker rmi <image_id> – Remove a Docker image
