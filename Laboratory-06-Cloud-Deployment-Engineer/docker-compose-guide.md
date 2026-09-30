## Docker Compose YAML Breakdown

* **What does the `services:` block do?**
  The `services:` block acts as the core definition area of the YAML file. It tells Docker Compose exactly which separate containers (e.g., the database and the app) need to be created, what images to use for them, and how they should be configured (ports, environment variables, volumes) to run as a unified application stack.

* **How did the Nextcloud app container know how to find the database container?**
  Nextcloud located the database through Docker's internal DNS resolution. By setting the environment variable `- MYSQL_HOST=database`, we instructed Nextcloud to look for a host named "database". Because both containers were deployed using the same Docker Compose file, Docker automatically placed them on the same internal network and resolved the hostname "database" to the MariaDB container's internal IP address.

* **What is the difference between `docker run` and `docker-compose up -d`?**
  `docker run` is used to deploy and configure a single container manually, requiring the engineer to type out all network, port, and environment flags in one long terminal command. Conversely, `docker-compose up -d` relies on Infrastructure as Code (IaC). It reads a predefined YAML file to automatically configure, link, and deploy multiple containers simultaneously in the background (`-d` for detached mode) with a single, short command.
