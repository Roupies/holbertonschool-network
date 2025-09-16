# Network Basics

This project contains a series of tasks focused on network configuration and manipulation using Bash scripts. Each script demonstrates different aspects of network management and configuration on Ubuntu servers.

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

## Requirements
- All scripts are tested on Ubuntu 20.04 LTS
- All Bash scripts are exactly 3 lines long
- All files end with a new line
- All files must be executable
- All files start with `#!/usr/bin/env bash`
- Second line of all Bash scripts is a comment explaining what the script does

## Author
Maxime