# install_java
This Bash script is designed to update your package list, check the installed Java version, and validate if the correct version of Java (version 11 or higher) is installed on a Debian/Ubuntu system.

## Script Overview
The script performs the following actions:

Updates the system package list.
Checks the currently installed Java version.
Determines if:
No Java version is found, indicating a failed installation.
An older version of Java is installed (version less than 11).
Java version 11 or higher is installed.

## Prerequisites
A Debian or Ubuntu-based Linux distribution.
User must have sudo privileges to update packages.

## Usage
1.Clone this repository or download the script file directly.
2.Make the script executable:
'''bash
chmod +x install_java.sh
'''
