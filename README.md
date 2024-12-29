# Cybersecurity-Project

Penetration Testing Report
Overview
This project evaluates the security of the target network (sunstone.in) using Nmap scans to identify vulnerabilities and provide recommendations.

Scans Performed
Ping Scan: Identified live hosts.
TCP SYN Scan: Discovered open ports.
Service Version Scan: Enumerated running services.
OS Detection: Identified operating systems.
NSE Scripts: Gathered additional information.
Results
Open Ports: 80 (HTTP), 443 (HTTPS).
OS: Linux 2.4.37.
Vulnerabilities: No XSS or CSRF issues found. Some scripts failed (e.g., CVE-2014-3704).
Recommendations
Address failed scripts and secure HTTP resources.
