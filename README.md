# DumbDrop Windows

**DumbDrop** on Windows, providing a seamless, secure, and ready-to-use file upload server.

![DumbDrop](https://github.com/user-attachments/assets/1b909d26-9ead-4dc7-85bc-8bfda0d366c1)

## Features

- **Automatic DumbDrop installation** with all dependencies
- **Automatic HTTPS configuration** using a self-signed certificate or optionally your own certificate
- **Windows Firewall port opening** for the configured server port
- **Service setup** to run DumbDrop automatically at Windows startup
- **Secure configuration** with PIN saved in decrypted config file

## Installation

1. **Run the installer executable** (`DumbDrop.exe`).
2. The installer will:
   - Download and install Node.js (if not already present)
   - Clone or download the latest DumbDrop release
   - Configure HTTPS certificates (self-signed by default)
   - Open the specified port in Windows Firewall
   - Register DumbDrop as a Windows service to start on boot
3. Once complete, DumbDrop will be accessible via your **https://PUBLIC_IP:3475**

## Usage

This application is ideal for remote cloud-based Windows setups, allowing seamless file uploads from PC to PC without intermediate apps. It also works great on mini-PCs, enabling file uploads from your phone to your PC at home.

> **Important:** Only share your public IP address with people you trust to keep your uploads secure.

---
[![Download DumbDrop Windows](https://img.shields.io/badge/Download-DumbDrop%20Windows-blue?style=for-the-badge&logo=windows)](https://github.com/SongDrop/dumbdropwindows/releases/tag/windows)
