# Nmap Network Scanner

A simple Python-based network scanning tool that utilizes the Nmap library to discover hosts and services on a computer network.

## Description
This project is designed to perform various types of network scans using the `python-nmap` library. It allows users to input an IP address and choose between different scanning modes.

## Features
- **TCP Scan:** Standard scanning for open TCP ports.
- **UDP Scan:** Scanning for open UDP services.
- **Comprehensive Scan:** Detailed scanning including OS detection and service versioning.

## Prerequisites
1. **Python 3.x**
2. **Nmap Binary:** Must be installed on your system ([Download here](https://nmap.org/download.html)).
3. **python-nmap library:**
   ```bash
   pip install python-nmap
