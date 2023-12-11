# Python Script Collection for Network and Security Tasks

This repository contains a collection of Python scripts designed for various network and security tasks including brute-forcing web logins, directory discovery, remote shell creation, port scanning, and reverse shell establishment. Below are the descriptions and usage instructions for each script.

## Script Descriptions

1. **Brute Force Login Script**
   - **Purpose**: To attempt to brute-force a web login form.
   - **Key Features**: 
     - Input URL, username, password file, login failure indicator, and optional cookies.
     - Automated login attempts using a list of passwords.

2. **Directory Discovery Script**
   - **Purpose**: To discover directories on a specified website.
   - **Key Features**: 
     - Input target URL and file containing a list of directories.
     - Lists discovered directories.

3. **Remote Shell Server Script**
   - **Purpose**: To create a server for remote shell access.
   - **Key Features**:
     - Bind to a specified IP and port.
     - Accept commands and send back the execution result.
     - Upload and download file capabilities.

4. **Port Scanner Script**
   - **Purpose**: To scan open ports on a target or multiple targets.
   - **Key Features**: 
     - Input target IP(s) and range of ports to scan.
     - Display open ports.

5. **Reverse Shell Script**
   - **Purpose**: To establish a reverse shell connection.
   - **Key Features**:
     - Connect to a remote server.
     - Execute received commands and return results.
     - Upload and download file capabilities.

## Installation

Before running the scripts, ensure you have Python installed on your system. Some scripts require additional modules:

```bash
pip install requests
pip install termcolor
```

## Usage

### 1. Brute Force Login Script

```bash
python brute_force_login.py
```

### 2. Directory Discovery Script

```bash
python directory_discovery.py
```

### 3.  Remote Shell Server Script

```bash
python remote_shell_server.py
```

### 4.  Port Scanner Script

```bash
python port_scanner.py
```

### 5.  Reverse Shell Script

```bash
python reverse_shell.py
```


