# Port Scanner
The project aims to provide a simple tool to detect open ports, check for known vulnerabilities using the IANA database, and offer suggestions for securing these ports.

# Problem Statement
Open ports are a common attack vector for malicious actors. Improperly configured ports can expose systems to unauthorized access and exploits.
# Importance 
Scanning open ports helps network administrators identify potential entry points and secure their systems proactively.
# Objective 
The project aims to provide a simple tool to detect open ports, check for known vulnerabilities using the IANA database, and offer suggestions for securing these ports.

# What the software does
Scans a range of well-known IANA ports on a target system.
Identifies open ports and matches them with known vulnerabilities using an embedded database.

# Architecture
Frontend: Tkinter provides the GUI.
Backend: Uses the socket library for scanning and threading for performance.
Vulnerability database: A hardcoded dictionary for mapping ports to known issues.

# Logic Workflow
The user inputs the target IP, port range, and protocol.
The backend starts scanning ports (one thread per port). Open ports are displayed along with matched vulnerabilities.
Results can be saved to a file.


---
## ❤️ Author

Created by **Jeytha Sahana** 
