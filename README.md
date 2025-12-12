# NMAP-and-Scapy-assignment-
Assignment Roadmap: Nmap + Scapy Lab Reproduction &amp; Documentation

1.	Overview
	This repository contains my reproduction of the Nmap and Scapy labs conducted during our cybersecurity practical sessions. 
	The goal of this project is to reinforce foundational skills in network scanning, packet crafting, and traffic analysis. 
	Each lab includes the commands/scripts used, results, screenshots, and brief explanations.

2.	Tools Used
Example:
	Nmap: Used for host discovery, port scanning, service enumeration, OS fingerprinting, and NSE scripting.
	Scapy: Used for packet crafting, sending, sniffing, and protocol inspection.

3.	Nmap Lab Summary
This consist of Nmap command which were performed.
Example:
The following Nmap scans were performed:
	Host Discovery (-sn)  
Identifies active hosts on the network using ICMP echo requests.
	TCP Connect Scan (-sT)  
 Performs a full connection to discover open ports.
	SYN Scan (-sS)  
Sends half-open TCP handshakes for stealthier port enumeration.
	Version Detection (-sV)  
Identifies service versions running on open ports.
	OS Fingerprinting (-O)  
 Attempts to determine the target operating system.
	Scapy Lab Summary
Same concept as the Nmap summary, but for Scapy.
Include:
	Packet crafting
	Sending packets
	Sniffing
	Basic protocol analysis
Example:
Scapy Lab Summary
The Scapy portion of the lab covered:
	Crafting custom packets (IP, ICMP, TCP)
	Sending packets using send () and sr () functions
	Sniffing network traffic with sniff ()
	Inspecting packet layers and fields using summary () and show ()
	Understanding how packets are built and transmitted
4.	Key Takeaways
This is the reflective part where you summarize what you learned.
Example:
Key Takeaways
	Nmap provides fast and reliable ways to enumerate networks and services.
	SYN scans and version detection are powerful for understanding network exposure.
	Scapy offers granular control over packets, making it ideal for learning protocols.
	Packet analysis helps build intuition for how data travels through networks.
	Proper documentation and ethical practice are essential in cybersecurity work.

