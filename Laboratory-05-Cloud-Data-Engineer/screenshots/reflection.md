# Laboratory 5 Reflection

**1. Why is object storage better suited for storing millions of photos compared to a traditional block storage hard drive?**
Traditional block storage relies on strict directory structures, which become sluggish and difficult to manage when dealing with millions of files. Object storage solves this by placing all data into a scalable, flat structure. Each photo becomes an "object" with a unique identifier, making retrieval incredibly fast and allowing the storage capacity to scale outward without limits.

**2. How did using Docker make it easier to deploy the MinIO storage server?**
Docker simplified the deployment by packaging the MinIO software and all its requirements into one portable container. Instead of downloading dependencies and configuring network settings manually on the host machine, a single Docker command handled the installation, port mapping, and credential setup simultaneously.

**3. What is a "bucket" in the context of cloud storage?**
In object storage architecture, a bucket is the primary logical container where files (objects) are stored. It replaces the concept of traditional root folders. Buckets help administrators organize data logically, apply specific security policies, and manage access rules for different applications.

**4. How do you think large enterprise companies ensure their object storage data is not lost if the physical server crashes?**
Large enterprises rely heavily on data replication and distributed systems. When a file is uploaded, the cloud provider automatically copies that object across multiple separate servers and even different geographical locations. They also use advanced techniques like erasure coding to reconstruct data seamlessly if a piece of hardware fails.

**5. How is your confidence in navigating the Linux command line growing?**
Deploying these cloud services continues to build my confidence in using Linux environments. Running complex Docker parameters and managing ports entirely through the command line is becoming standard practice for me. I am getting much more comfortable relying on the terminal over graphical interfaces, which is essential for managing real-world server infrastructure.
