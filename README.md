## Suspicious Traffic Detection and Blocking Using Wireshark and Python

# Overview

This project automates the detection of suspicious network traffic, sends email alerts, and optionally blocks malicious IP addresses. It utilizes Wireshark/TShark, Python, and Linux tools for network traffic capture, analysis, and automated response.
# Key Features

    Capture network traffic using Wireshark/TShark
    Analyze traffic patterns and detect suspicious behavior
    Send real-time email alerts for suspicious activity
    Block malicious IPs (optional) using iptables or ufw
    Automate traffic monitoring and alerts using cron jobs

# Installation

    Install Wireshark/TShark to capture network traffic.
    Install Python and required libraries for analysis and email alerts.
    (Optional) Install UFW for IP blocking if required.

# Usage

    Use Wireshark/TShark to capture traffic.
    Analyze traffic with Python using PyShark to detect suspicious behavior.
    Configure email alerts for administrators.
    (Optional) Use iptables or ufw to block malicious IP addresses.
    Set up a cron job to automate regular monitoring.

# License

MIT License
