# Security Audit Report

**The Principle of Least Privilege (PoLP):** 
The Principle of Least Privilege dictates that users, applications, and systems should only be granted the minimum level of access permissions necessary to perform their specific tasks. In cloud environments, this is critical because it limits the potential damage of a compromised account by preventing unauthorized lateral movement and accidental administrative errors.

**Attack Surface:** 
An attack surface refers to the total number of exposed entry points, open ports, and vulnerable services on a virtual machine that an unauthorized user could potentially exploit. By shutting down unnecessary services and closing unused ports, cloud engineers actively shrink the attack surface and make the system much harder to infiltrate.

**Default Deny Policy:** 
A Default Deny policy operates on the assumption that all incoming network traffic is malicious, automatically blocking all connections unless explicitly permitted by an administrator rule. It is significantly safer than attempting to block specific hackers because it proactively protects the server from unknown threats and automated scanning tools by default.
