# UFW Basic Firewall Configuration

## 🎯 Objective
Set up a basic firewall using **UFW (Uncomplicated Firewall)** on a Linux system.

## 🛠 Tools Used
- UFW (Uncomplicated Firewall)
- Linux Command Line

## 📋 Steps Performed
1. Installed UFW using the command: `sudo apt install ufw`
2. Allowed SSH traffic to prevent locking out remote access: `sudo ufw allow ssh`
3. Denied HTTP traffic for security: `sudo ufw deny http`
4. Enabled the firewall: `sudo ufw enable`
5. Verified the rules using: `sudo ufw status verbose`

## ✅ Final Firewall Rules
- **SSH** (Port 22): `ALLOW`
- **HTTP** (Port 80): `DENY`
- **Firewall Status**: `ENABLED`

## 📷 Screenshot
A screenshot showing the result of `sudo ufw status verbose` is included in this repository.
# Basic-Firewall-Configuration-with-UFW
