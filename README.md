# task1
# Local Network Port Scan Analysis

Author: HALAVATH RAJASHEKAR  
Tools Used: Nmap.  

Project Overview
This project involved scanning my local network to identify open ports and assess potential security exposures. The goal was to:
- Discover active devices and services.
- Document open ports and their associated risks.
- Practice ethical scanning techniques.

---

## Tools & Commands
# Nmap Scan
```bash
nmap -sS 192.168.1.0/24 -oN scan_results.txt
