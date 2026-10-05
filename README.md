Task 3: Basic Vulnerability Scan

Objective
To perform a basic security scan on the local computer and identify commonly open network ports and services.

 Description
This project performs a basic vulnerability assessment on the localhost using Python. It checks commonly used ports and identifies whether they are open or closed.

Tools Used
- Python
- Pydroid 3
- Socket Library

 Target
127.0.0.1 (Localhost)

Features
- Scans common network ports
- Identifies open and closed ports
- Displays the associated service
- Generates a simple scan report
- Provides basic security recommendations

Ports Checked
- 21 - FTP
- 22 - SSH
- 23 - Telnet
- 25 - SMTP
- 53 - DNS
- 80 - HTTP
- 443 - HTTPS
- 3306 - MySQL
- 3389 - RDP
- 8080 - HTTP Proxy

How to Run
1. Open Pydroid 3.
2. Create a new Python file.
3. Copy and paste the provided code.
4. Run the program.
5. Check the scan results in the output.
6. Take a screenshot of the results for submission.

 Sample Output
The program displays the status of each port as:

[OPEN] 80 - HTTP
[CLOSED] 22 - SSH
[CLOSED] 21 - FTP

Result
The program successfully performs a basic localhost port scan and identifies commonly open services.

Security Recommendation
Close unnecessary services and keep the operating system and applications updated.

Conclusion
This task provides basic practical knowledge of vulnerability assessment, port scanning, and identifying potentially exposed services on a computer.

