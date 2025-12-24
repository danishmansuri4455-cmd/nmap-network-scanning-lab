# Network Scanning & Enumeration using Nmap

## 📌 Project Overview
This project demonstrates basic network scanning and enumeration techniques using Nmap in a controlled lab environment. The objective is to identify open ports, running services, and operating system details to understand system exposure.

## 🛠️ Tools Used
- Nmap
- Kali Linux
- VirtualBox / VMware

## 🎯 Objectives
- Identify live hosts
- Discover open ports
- Detect running services and versions
- Perform basic OS fingerprinting

## 🔍 Scans Performed

### 1️⃣ Basic Port Scan
Command:
nmap 127.0.0.1
Purpose:
- Identify open ports on the target system

### 2️⃣ Service & Version Detection
Command: 
nmap -sV 127.0.0.1
Purpose:
- Detect services and their versions running on open ports

### 3️⃣ OS Detection
Command:
sudo nmap -O 127.0.0.1

Purpose:
- Identify the operating system of the target host

## 📊 Observations
- Identified open ports and associated services
- Detected service versions that could be reviewed for vulnerabilities
- Gained understanding of system exposure through enumeration

## ⚠️ Disclaimer
All scans were performed on a personal lab environment for educational purposes only. Unauthorized scanning of systems is illegal.

## 📚 Learning Outcome
- Practical understanding of Nmap scanning techniques
- Improved knowledge of network enumeration
- Hands-on experience in documenting security findings
