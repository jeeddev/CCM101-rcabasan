# Mission Overview
In this mission, we transition from traditional virtualization to containerization by acting as a Cloud-Native Engineer for CloudNova Technologies. The goal is to deploy a live, containerized Nginx web server using Docker to demonstrate how containers offer faster boot times and better resource efficiency compared to traditional Virtual Machines.

# Objectives
* Differentiate between traditional Virtual Machines (VMs) and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI (Command Line Interface) commands.
* Pull, run, manage, and terminate a containerized application (Nginx).
* Create professional technical documentation of container operations using Markdown.
* Continue developing a well-organized GitHub Cloud Computing Portfolio.

# Docker Commands Executed
* `docker --version`
* `docker info`
* `docker pull nginx`
* `docker run -d -p 8080:80 --name my-nginx nginx`
* `curl http://localhost:8080`
* `docker ps`
* `docker stop my-nginx`
* `docker ps -a`
* `docker rm my-nginx`

# Skills Learned
I learned how to pull container images from Docker Hub and map host ports to container ports to expose web services to the outside network. I also learned how to manage the lifecycle of a container, from running it in detached mode to safely stopping and removing it.

# Challenges Encountered
The main challenge was understanding how port mapping works, specifically differentiating between the host port (8080) and the internal container port (80).
