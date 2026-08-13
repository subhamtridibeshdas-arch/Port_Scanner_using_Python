# Python Port Scanner

## About

This project is a simple TCP Port Scanner developed in Python using the socket module. It scans a target host and identifies open ports within a specified range. The project demonstrates basic network reconnaissance techniques commonly used during security assessments.

## Features

- Scans TCP ports on a target host
- Identifies open ports
- Lightweight and easy to use
- Built using Python socket programming
- Displays scan results in the terminal

## Technologies Used

- Python 3
- Socket Library

## How It Works

1. Enter the target IP address.
2. The scanner attempts to connect to ports within the specified range.
3. If a connection is successful, the port is reported as OPEN.
4. If no open ports are found, an appropriate message is displayed.

## Sample Output

```text
Enter Target IP: 127.0.0.1

Scanning 127.0.0.1...

Port 80 is OPEN

Scan Completed!
```

## Learning Outcomes

- Understanding TCP/IP networking concepts
- Working with Python socket programming
- Learning basic network reconnaissance techniques
- Identifying exposed services through port scanning

## Disclaimer

This project is intended for educational purposes only. Always obtain proper authorization before scanning any system or network.
