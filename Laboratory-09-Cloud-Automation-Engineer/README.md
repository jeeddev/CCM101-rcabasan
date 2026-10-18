**Inside `README.md`:**
```markdown
# Mission 9: The Cloud Automation Engineer

## Mission Overview
This laboratory involves stepping into the role of a Cloud Automation Engineer at CloudNova Technologies to eliminate human error from data backup procedures[cite: 1, 2]. The mission required creating an automated Bash script to compress and secure application data, testing it manually, and utilizing Linux Cron to schedule the routine autonomously every night at 2:00 AM[cite: 2].

## Objectives
* Understand fundamental Bash shell script syntax, variables, and commands[cite: 1].
* Use a command-line text editor (`nano`) to write executable scripts[cite: 1].
* Modify Linux file permissions using `chmod`[cite: 1].
* Understand task scheduling and the syntax of a Linux crontab[cite: 1].
* Document automation code and Cron job configurations using Markdown[cite: 1].

## Commands Executed
* `mkdir app-data`
* `echo "This is critical client data." > app-data/data.txt`
* `nano backup.sh`
* `./backup.sh`
* `chmod +x backup.sh`
* `ls -l backups/`
* `crontab -l`
* `env EDITOR=nano crontab -e`

## Skills Learned
* Shell scripting and automated archive creation using `tar`.
* Modifying system execution privileges.
* Scheduling autonomous cloud operations using cron tables.
