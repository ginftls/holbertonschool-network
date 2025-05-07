# Networking Basics Project

This project includes Bash scripts that configure network settings on Ubuntu 20.04 LTS.

## Requirements

- All scripts are written for Ubuntu 20.04 LTS
- All files end with a new line
- All Bash script files are executable
- All scripts pass Shellcheck version 0.7.0 without errors
- Scripts follow the required format:
  - First line: `#!/usr/bin/env bash`
  - Second line: Comment explaining the script's purpose

## Tasks

### 0. Change your home IP

The script `0-change_your_home_IP` configures an Ubuntu server to:
- Change `localhost` resolution from `127.0.0.1` to `127.0.0.2`
- Change `facebook.com` resolution to `8.8.8.8` (instead of its real IP)

**Warning:** Running this script on your main machine may cause connectivity issues. Make sure to revert the changes to `localhost` if needed.

## Usage

Make the script executable and run with sudo:

```
chmod +x 0-change_your_home_IP
sudo ./0-change_your_home_IP

