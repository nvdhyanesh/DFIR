
OVERVIEW

This repository contains the methodology and tools used for a comprehensive forensic investigation on a compromised Metasploitable 3 Ubuntu server. The investigation was conducted using various forensic tools and techniques to gather and analyze evidence, aiming to understand the nature and extent of the security breach.


The project involved the following key activities:

Acquisition: Forensic disk and memory images were acquired to preserve the state of the compromised system.
Analysis: Detailed analysis was performed on the acquired data to identify malicious activities, compromised files, and network anomalies.
Documentation: Findings were documented to assist in improving security measures and informing incident response strategies


Tools and Techniques
1. Disk Forensics
Tool: FTK Imager
Action: Acquired a forensic disk image for in-depth analysis.
2. Memory Forensics
Tool: AVML (Acquire Volatile Memory for Linux)
Action: Captured a memory image to investigate running processes and potential malware.
3. Network Forensics
Tool: tcpdump
Action: Recorded network traffic during the attack, creating a pcap file for further analysis.
4. Data Analysis
Disk Analysis: Utilized Autopsy to analyze the disk image, identifying malicious files and traces of the attack.
Memory Analysis: Used Volatility to examine the memory image, uncovering active processes, network connections, and indicators of compromise.
Network Analysis: Employed Security Onion to analyze the pcap file, investigating suspicious network activity and data exfiltration attempts.


Conclusion

This project demonstrates a systematic approach to digital forensic investigation and highlights the importance of using specialized tools and techniques to uncover the full scope of security incidents
