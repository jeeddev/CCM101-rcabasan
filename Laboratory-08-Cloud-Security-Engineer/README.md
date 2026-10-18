# Laboratory Activity 8 - The Cloud Security Engineer

## Mission Overview
In this mission, I acted as a Cloud Security Engineer to secure a vulnerable Ubuntu server using the principle of defense in depth. I established a host-based firewall to lock down the server, blocking malicious traffic while selectively permitting necessary application access.

## Objectives
* Understand the Attack Surface and the Principle of Least Privilege (PoLP).
* Perform a basic security audit of active network ports on a Linux server.
* Configure the Uncomplicated Firewall (UFW) with a Default Deny policy.
* Implement granular port management to selectively allow SSH and HTTP traffic.
* Document firewall rules and security best practices using Markdown.

## Commands Executed
* `docker run -d --name secure-web-app -p 8080:80 nginx`
* `curl http://localhost:8080`
* `sudo ufw allow ssh`
* `sudo ufw default deny incoming`
* `sudo ufw default allow outgoing`
* `sudo ufw enable`
* `sudo ufw status verbose`
* `sudo ufw allow 8080/tcp`
* `sudo ufw status numbered`

## Skills Learned
* Deploying web containers for security testing.
* Activating and configuring UFW on Linux servers.
* Shrinking a server's attack surface using granular port rules.
* Creating comprehensive technical documentation in Markdown.
