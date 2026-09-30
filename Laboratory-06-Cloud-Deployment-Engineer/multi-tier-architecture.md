## Two-Tier Architecture Definition

A two-tier architecture is a software deployment model where the application's presentation/logic layer and its data layer are logically or physically separated into two distinct environments. 

* **The Web/Application Tier:** This tier acts as the front-end interface for the user. Its primary role is to serve the user interface, process HTTP requests, execute application logic, and act as the bridge between the user and the backend data. In our deployment, Nextcloud operates in this tier.
* **The Database Tier:** This tier serves as the backend storage engine. Its role is strictly to store, manage, and retrieve persistent data efficiently and securely. In our deployment, MariaDB operates in this tier, storing user accounts, file metadata, and system configurations.

## Why Separate Them?

Separating the web server and database into two containers significantly improves scalability and security. If the web server experiences heavy traffic, it can be scaled up independently without needing to duplicate the database. Additionally, keeping them separate means a security vulnerability in the web server does not give attackers direct, file-level access to the database layer, isolating critical data from the public internet.
