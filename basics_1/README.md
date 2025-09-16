# Network Basics

This project contains a series of tasks focused on network configuration and manipulation using Bash scripts. Each script demonstrates different aspects of network management and configuration on Ubuntu servers.

## General Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted on Ubuntu 22.04
- All files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- All Bash script files must be executable
- Bash scripts must pass Shellcheck (version 0.7.0 via apt-get) without any errors
- The first line of all Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what the script does

## Tasks

### 0. Change your home IP
**File:** `0-change_your_home_IP`

A Bash script that configures an Ubuntu server with the following requirements:
- `localhost` resolves to `127.0.0.2`
- `facebook.com` resolves to `8.8.8.8`

Usage:
```bash
sudo ./0-change_your_home_IP
```

**Note:** Be cautious when running this script on a production machine as changing localhost from 127.0.0.1 can break various applications.

### 1. Show attached IPs
**File:** `1-show_attached_IPs`

A Bash script that displays all active IPv4 IPs on the machine it's executed on.

Usage:
```bash
./1-show_attached_IPs
```

Example output:
```
10.0.2.15
127.0.0.1
```

### 2. Port listening on localhost
**File:** `2-port_listening_on_localhost`

A Bash script that listens on port 98 on localhost using netcat.

Usage:
Terminal 1:
```bash
sudo ./2-port_listening_on_localhost
```

Terminal 2:
```bash
telnet localhost 98
```

This script can be used for:
- Debugging socket connection issues
- Testing network connectivity
- Verifying firewall rules
- Basic network communication testing



## Author
Maxime