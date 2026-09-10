**1. How does the boot time and setup process of a Docker container compare to installing an operating system on a Virtual Machine?**
The boot time of a Docker container is nearly instantaneous, often taking only seconds, whereas a Virtual Machine takes several minutes. This is because a VM requires booting a complete, heavy Guest Operating System from scratch. A container simply starts a process within the already running Shared Host OS, bypassing the entire OS boot sequence and hardware initialization phase.

**2. Why is port mapping (-p 8080:80) necessary when running a web server inside a container?**
Port mapping bridges the isolated container network with the host machine network. The web server inside the container listens on its internal port 80. Without port mapping, that internal port is completely invisible to the outside world. By mapping host port 8080 to container port 80, any traffic hitting `localhost:8080` on the host machine is directly forwarded to the container's web server.

**3. What happens to the data inside a container when you use the docker rm command?**
When you execute `docker rm`, the container is completely destroyed, and any data written inside its isolated filesystem during its runtime is permanently lost. Containers are ephemeral by design.

**4. How do you think containerization changes the way software developers and IT operations teams work together (DevOps)?**
Containerization standardizes the environment. It eliminates the "it works on my machine" problem because developers package the application and all its dependencies into a single image. IT operations can then run that exact same image in production with guaranteed consistency. 

**5. How is your GitHub portfolio evolving?**
My GitHub portfolio is becoming a comprehensive, professional record of my cloud engineering skills, expanding from infrastructure blueprints to modern cloud-native container deployments.
