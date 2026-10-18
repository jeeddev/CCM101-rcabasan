# Firewall Configuration Documentation

### 1. Command used to allow SSH:
`sudo ufw allow ssh`

### 2. Commands used to set the Default Deny policy:
`sudo ufw default deny incoming`
`sudo ufw default allow outgoing`

### 3. Command used to allow Port 8080:
`sudo ufw allow 8080/tcp`

### 4. Consequence of enabling UFW before allowing SSH:
If you run `sudo ufw enable` before executing `sudo ufw allow ssh`, the default deny policy will instantly block your active connection, locking you out of the server and preventing any further remote administration.
