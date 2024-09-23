Exp Running Nginx Application using Docker and Managing Docker Volume
============================================================

This demonstrates how to run an Nginx application using Docker and manage the Docker volume.

**Prerequisites:**

* Docker installed on the system
* Basic knowledge of Docker and Nginx

**Steps:**

1. Pull the Nginx image from Docker Hub
2. Create a Docker volume
3. Run the Nginx container with the volume
4. Verify the Nginx application
5. Manage the Docker volume

**Commands:**

* `docker pull nginx:latest`
* `docker volume create nginx-volume`
* `docker run -d --name nginx-container -p 8080:80 -v nginx-volume:/usr/share/nginx/html nginx:latest`
* `curl http://localhost:8080`
* `docker volume ls`
* `docker volume inspect nginx-volume`
* `docker volume rm nginx-volume`

**Note:**

Assumes that you have basic knowledge of Docker and Nginx. If you are new to Docker and Nginx, please refer to the official documentation for more information.


Clone the repository:
   ```bash
https://github.com/AditiPandey568/Nginx-application-.git
