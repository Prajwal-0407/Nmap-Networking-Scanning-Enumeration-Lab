# ~ Nmap-Networking-Scanning-Enumeration-Lab

# Introduction

Nmap is an open source network scanning and security auditing tool used to discover hosts, identify open ports, detect running services, and gather information about targets systems. this project demonstrates practical network reconnaissance and enumeration using Nmap in an isolated Metasploitable 2 laboratory environment.


# overview

In this project, Nmap used to perform host directory, full tcp port scanning, service and version detection, os detection, Nse script scanning and firewall/packet-filtering analysis against metasploitable 2virtual machines. the scan results were documented using command outputs and screenshots.

# Tools used:-

Kali linux - Scanning Platform
Nmap 7.99 - Network scanning and enumeration
Metaspliotable 2 - Intentionally vulnerable target VM
VMware - Virtualization environment
Zenmap (Nmap GUI)

# nmap-network-scanning-lab

Host Discovery
Port scanning
Service & version detection 
OS Detection
NSE Script scanning
Firewall Detection
Scan Report

# Step 1 - Host Discovery
: Use this command for check your target host is up & no
Nmap -sn 192.168.5.129

<img width="1919" height="567" alt="Screenshot 2026-08-17 233530" src="https://github.com/user-attachments/assets/2312100a-ee8d-46d3-a5bd-7990a334aad8" />

# Step 2 - Basic port scan
nmap -p- 192.168.5.129

<img width="975" height="712" alt="image" src="https://github.com/user-attachments/assets/5123a08d-c224-448e-bd4c-2cf0a540d7a5" />

# Step 4 - Service & Version Detection
nmap -sV 192.168.5.129

<img width="812" height="325" alt="image" src="https://github.com/user-attachments/assets/dab86763-dc79-4800-9f08-60209e46660c" />

# Step 5 — OS Detection
sudo nmap -O 192.68.5.129

<img width="895" height="710" alt="image" src="ht

# Step 6 - NSE Default Scripts
nmap -sC 192.168.5.129

<img width="731" height="335" alt="image" src="https://github.com/user-attachments/assets/9159dccf-e6c5-4cf4-a527-a554671c08ba" />

# Step 7 - Firewall/Filtering Analysis
sudo nmap -sA 19.168.5.129

<img width="731" height="335" alt="image" src="https://github.com/user-attachments/assets/9159dccf-e6c5-4cf4-a527-a554671c08ba" />

# Step:-8 
sudo nmap -sC -sV -O 192.168.5.129 -oN scan-report.txt

<img width="1712" height="871" alt="image" src="https://github.com/user-attachments/assets/fc6b089a-c36b-471e-88a7-cebf96120cc9" />
<img width="1712" height="867" alt="image" src="https://github.com/user-attachments/assets/ee03a99a-5844-4834-a162-12a8a7a7e706" />
<img width="1717" height="542" alt="image" src="https://github.com/user-attachments/assets/5d21e027-982c-4e05-9fb8-4ee3f979435e" />

-sC → default NSE scripts
-sV → service/version detection
-O → OS detection
-oN → normal output ko scan-report.txt
And Port and visions services lik --
Port	Service	      Version / Information
21    	FTP	            vsftpd 2.3.4
22	    SSH	            OpenSSH 4.7p1
23	    Telnet	            Linux telnetd

# step:-9
sudo nmap -p- 192.168.5.129 -oN port-scan.txt

<img width="1712" height="867" alt="image" src="https://github.com/user-attachments/assets/9b0ee162-e574-4562-8794-73fa350174c9" />

# step:-10
•	Check the how many system connected your network this command
nmap -sn 192.168.5.0/24

<img width="1336" height="367" alt="image" src="https://github.com/user-attachments/assets/a1411844-cf70-4133-93b6-3dc6861309f5" />

# Step:-11 ZENAMP

Use ZENMAP SCAN to target ip Address collect all data (host name, ip, port, OS)
Target ip address (192.168.5.129)

# Open Ports & hosts

<img width="1716" height="876" alt="image" src="https://github.com/user-attachments/assets/73a59b14-204a-4e9e-a404-f9882354ee06" />

# Topology

<img width="1711" height="877" alt="image" src="https://github.com/user-attachments/assets/8ccad293-0247-496e-b610-40fb914dd37d" /

# Host Details

<img width="1715" height="877" alt="image" src="https://github.com/user-attachments/assets/f97aac1b-2ae5-466b-9a43-395251b80d35" />
<img width="1722" height="225" alt="image" src="https://github.com/user-attachments/assets/0d7bed54-4053-4118-bf80-87d895b537c6" />

# Nmap Outputs

<img width="1722" height="910" alt="image" src="https://github.com/user-attachments/assets/70c4647b-84e9-4c65-b9af-5bde0b4dfddf" />
<img width="1715" height="845" alt="image" src="https://github.com/user-attachments/assets/477904d1-e8f7-4f61-b293-0cf9bca810f9" />
<img width="1712" height="836" alt="image" src="https://github.com/user-attachments/assets/fcb4f75c-917e-4fa5-8cfe-dab564f9cfbe" />
<img width="1712" height="817" alt="image" src="https://github.com/user-attachments/assets/2c3fb258-d3a7-41a1-ab2d-416826b68f3c" />
<img width="1716" height="826" alt="image" src="https://github.com/user-attachments/assets/39fa132f-28f1-4a73-a9b3-31e400b2e8e9" />
<img width="1731" height="821" alt="image" src="https://github.com/user-attachments/assets/89786e1d-e6ef-4741-af6e-bd02925ec69f" />
<img width="1717" height="837" alt="image" src="https://github.com/user-attachments/assets/2fbe7698-fb5e-4c8a-89f8-dd6664006e24" />

# Conclusion

This project provided practical experience in network reconnaisance and service enumeration using Nmap. The assesment demonstrated how host discovery, port scanning, service identification  OS detection, NSE scripts, and packet-filtering analysis can be combined to understandthe attack surface of a system. The exercise was conducted in an isolated and authorized  Metasploitable 2 laboratory environment.


<img width="895" height="710" alt="image" src="https://github.com/user-attachments/assets/6c95b2ac-0d5c-4a79-bac1-83e303953989" />

