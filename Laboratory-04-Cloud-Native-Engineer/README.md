# Mission Overview
This laboratory activity focuses on transitioning from traditional virtualization to containerization by deploying a live, containerized web server.

# Objectives
* Differentiate between traditional Virtual Machines (VMs) and Containers.
* Access a Docker-enabled cloud environment.
* Execute fundamental Docker CLI commands.
* Pull, run, manage, and terminate a containerized Nginx application.
* Create technical documentation using Markdown.

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
(Write 1-2 sentences here about learning how to deploy and manage containers.)

# Challenges Encountered
(Write 1-2 sentences here about any difficulties you faced, such as screenshotting or command typos.)
