# Networking Basics #0

## Description
This project focuses on fundamental networking concepts, including the OSI model, types of networks, MAC/IP addresses, and TCP/UDP protocols.

## Learning Objectives
By the end of this project, you should be able to explain:

### OSI Model
- What it is
- How many layers it has
- How it is organized

### Network Types
- What is a LAN
- What is a WAN
- What is the Internet

### IP/MAC Addresses
- What is an IP address
- What is a MAC address
- The difference between IP and MAC addresses

### TCP/UDP
- The two main data transfer protocols
- Main difference between TCP and UDP
- What is a port
- Memorize SSH, HTTP and HTTPS port numbers

### Network Troubleshooting
- What is ICMP
- How to use ping for basic network testing

## Tasks

### 0. OSI Model
* File: `0-OSI_model`
* Questions about the OSI model definition and organization

### 1. Types of Network
* File: `1-types_of_network`
* Questions about LAN, WAN, and Internet networks

### 2. MAC and IP Address
* File: `2-MAC_and_IP_address`
* Questions about MAC and IP address definitions

### 3. UDP and TCP
* File: `3-UDP_and_TCP`
* Questions about TCP/UDP characteristics

### 4. TCP and UDP Ports
* File: `4-TCP_and_UDP_ports`
* Bash script that displays listening ports
* Shows PID and name of the program to which each socket belongs

### 5. Is the Host on the Network
* File: `5-is_the_host_on_the_network`
* Bash script that pings an IP address 5 times
* Accepts IP address as an argument

## Requirements
### General
- Allowed editors: `vi`, `vim`, `emacs`
- All files interpreted on Ubuntu 22.04 LTS
- All files should end with a new line
- All Bash script files must be executable
- Bash scripts must pass Shellcheck (version 0.7.0) without errors
- First line of Bash scripts: `#!/usr/bin/env bash`
- Second line of Bash scripts: Comment explaining script's purpose

### Answer Files Format
For multiple choice question tasks:
- Only put the number of the correct answer in the file
- No need for a new line if it's the last character
Example:
```bash
# What is the most important position in a software company?
# 1. Project manager
# 2. Backend developer
# 3. System administrator
sylvain@ubuntu$ cat foo_answer_file
3
sylvain@ubuntu$
```
