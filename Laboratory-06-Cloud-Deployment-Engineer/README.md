# Laboratory 06: Cloud Deployment Engineer

## Mission Overview
This project demonstrates the transition from manual container deployment to Infrastructure as Code (IaC). By utilizing Docker Compose, a multi-tier enterprise private cloud storage application (Nextcloud and MariaDB) was deployed simultaneously using a declarative YAML configuration file.

## Objectives
* Understand the purpose and structure of a multi-tier application architecture.
* Write a `docker-compose.yml` file using a Linux command-line text editor (nano).
* Deploy and link a multi-container stack (Web Application + Database).
* Document Infrastructure as Code (IaC) principles and deployment procedures.

## Commands Executed
* `mkdir nextcloud-deployment`
* `cd nextcloud-deployment`
* `nano docker-compose.yml`
* `docker-compose up -d`
* `docker-compose ps`
* `docker-compose down`

## Skills Learned
* Infrastructure as Code (IaC) configuration.
* Multi-tier container networking and internal DNS routing.
* YAML syntax formatting and structure.
* Environment variable injection for secure credential management.
