Description
The screenshot shows the result of an Nmap TCP SYN scan using the command:
nmap -sT scanme.nmap.org
Nmap successfully detected that the host scanme.nmap.org (45.33.32.156) is up. The scan identified several TCP ports and their states:
22/tcp – Open – SSH
25/tcp – Filtered – SMTP
80/tcp – Open – HTTP
135/tcp – Filtered – MSRPC
139/tcp – Filtered – NetBIOS-SSN
445/tcp – Filtered – Microsoft-DS
9929/tcp – Open – nping-echo
31337/tcp – Open – Elite
Most other ports (992) were reported as closed.
Conclusion
The Nmap scan was completed successfully in 7.59 seconds. The target host is active and has several open TCP ports providing services such as SSH and HTTP. Some ports are filtered, indicating that a firewall or filtering mechanism may be blocking access. This demonstrates how Nmap can be used to identify active hosts, open ports, and associated network services.
