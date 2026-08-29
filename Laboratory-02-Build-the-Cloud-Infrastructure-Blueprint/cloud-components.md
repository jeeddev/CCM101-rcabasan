**Compute Resources**
* **Purpose:** This acts as the "brain" that processes data, runs applications, and provides memory.
* **Importance in Cloud Computing:** It provides on-demand processing power to run virtual machines without the need to purchase physical hardware.
* **Relation to KillerCoda:** We observed the compute resources of the KillerCoda server when we executed the `lscpu` command (for CPU cores) and `free -h` (for RAM).

**Storage Resources**
* **Purpose:** This is where files, databases, and the operating system are stored and saved.
* **Importance in Cloud Computing:** It ensures there is scalable, secure, and persistent storage for data in the cloud that can be accessed at any time.
* **Relation to KillerCoda:** We checked the storage resources of the KillerCoda environment when we ran `df -h` to view the disk capacity and mounted file systems.

**Networking Resources**
* **Purpose:** This connects various cloud resources, servers, and users so they can communicate and exchange data.
* **Importance in Cloud Computing:** Without networking, cloud servers cannot be accessed from the internet, and cloud architectures cannot communicate with each other.
* **Relation to KillerCoda:** The network resources of KillerCoda were verified using the `hostname` and `ip a` commands to determine its IP address.

**Operating System**
* **Purpose:** This is the primary software system that manages the server hardware and allows other cloud applications to run.
* **Importance in Cloud Computing:** It serves as the bridge and foundational layer between the cloud infrastructure and the cloud engineer, enabling resource management.
* **Relation to KillerCoda:** The OS of KillerCoda is the specific Linux distribution we accessed, which was confirmed when we ran `cat /etc/os-release` and `uname -r`.
