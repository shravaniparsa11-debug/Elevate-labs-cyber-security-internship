Objective
To scan a target device and identify active TCP ports and their associated services.
Tool
Nmap Wrapper
Network
scanme.nmap.org (45.33.32.156)
Command
nmap -sT scanme.nmap.org
Scan Results
1 IP address was scanned.
1 host was found up.
1000 TCP ports were scanned.
Open ports: 22 (SSH), 80 (HTTP), 9929 (nping-echo), 31337 (Elite).
Filtered ports: 25, 135, 139, 445.
992 TCP ports were closed.
Description
The Nmap scan was performed to identify the active host, open TCP ports, and services running on the target system.
Screenshot Evidence
The screenshot shows the completed Nmap Wrapper scan and the detected ports and services.
Conclusion
The scan was completed successfully. It identified an active host along with its open, filtered, and closed TCP ports, demonstrating the use of Nmap for basic network scanning.
