# Apache Web Server Log Analysis

## Overview
This project demonstrates how to install, configure, and analyze Apache Web Server logs on Kali Linux. It covers monitoring web requests, reviewing server errors, and understanding Apache access and error logs.

## Features
- Install Apache2 on Kali Linux
- Start and verify Apache service
- Access localhost using a web browser(http://localhost)
- Analyze Access Logs
- Analyze Error Logs
- Monitor logs in real time using `tail -f`
- Understand HTTP status codes (200, 404, 500)

## Requirements
- Kali Linux
- Apache2
- Terminal
- Firefox Browser

## Installation
```bash
sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2
sudo systemctl status apache2
```

## View Access Log
```bash
sudo tail -f /var/log/apache2/access.log
```

## View Error Log
```bash
sudo tail -f /var/log/apache2/error.log
```

## Commands Used
- sudo apt update
- sudo apt install apache2
- sudo systemctl start apache2
- sudo systemctl status apache2
- sudo tail -f /var/log/apache2/access.log
- sudo tail -f /var/log/apache2/error.log
- sudo apache2ctl configtest

## Learning Outcomes
- Install and configure Apache Web Server
- Monitor web server activity
- Analyze Apache access and error logs
- Interpret common HTTP status codes

## Author
Harpreet Kaur
