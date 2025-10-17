# Project-2---Implementing-Confidentiality-on-Cisco-Networks-Using-SSH-ACL-and-Password-Encryption

The security and confidentiality of data communication are vital to maintaining the integrity of modern network infrastructures. As organizations increasingly depend on interconnected systems, protecting sensitive information from unauthorized access has become a critical priority. However, many networks still use unsecured methods like Telnet, which transmits credentials in plaintext and leaves data vulnerable to interception and misuse.
To overcome these issues, this project implements several confidentiality mechanisms on Cisco network devices to enhance security and control access. The configuration involves key components such as Telnet (to demonstrate insecure communication), SSH (Secure Shell) (to replace Telnet with encrypted sessions), Access Control List (ACL) (to restrict access to authorized IPs), Enable Secret (to encrypt privileged passwords), and console/VTY passwords (to secure both local and remote logins).
The network topology 

System Summary

The project “Implementing Confidentiality Mechanisms on Cisco Networks Using Telnet, SSH, ACL, and Password Encryption” aims to strengthen data confidentiality and network security through the application of multiple protective mechanisms within Cisco devices. The system focuses on demonstrating the differences between unsecured and secured communication, preventing unauthorized access, and ensuring that sensitive data remains encrypted and protected across network connections.
The network topology consists of one router, one switch, and two PCs representing authorized and unauthorized users, designed to simulate real-world access control scenarios. Five main security components are implemented and analyzed:
•	Telnet: Used to demonstrate unencrypted communication, showing potential risks when transmitting plaintext credentials.
•	SSH (Secure Shell): Replaces Telnet with encrypted communication.

•	Access Control List (ACL): Limits access to specific authorized IPs.

•	Enable Secret Encryption: Protects privileged passwords by encrypting them.

•	Console and VTY Passwords: Secures both local and remote access with authentication.

Through configuration and testing, the system compares Telnet and SSH traffic to highlight the difference between unsecured and encrypted communication. The use of ACL, Enable Secret, and password protection further strengthens confidentiality and access control.

Overall, this project demonstrates how combining Telnet analysis, SSH encryption, and layered security mechanisms effectively secures Cisco networks from unauthorized access and data exposure.

System Processes

The system operates through a series of structured processes that define how confidentiality mechanisms are implemented, configured, and tested within a Cisco network environment:

1.	Network Setup
•	A basic topology is built consisting of one router, one switch, and two PCs
representing authorized and unauthorized users.
•	Each device is assigned an IP address to enable communication and support access
control configuration.
2.	Telnet and SSH Configuration
•	Telnet is first configured to demonstrate unencrypted communication between
devices.
•	SSH (Secure Shell) is then implemented to replace Telnet, ensuring all transmitted
data, including login credentials, is encrypted and protected from interception.
3.	Access Control List (ACL) Implementation
•	ACLs are applied to the router interfaces to restrict access based on source IP
addresses.
•	Only authorized devices can connect via SSH, while unauthorized devices are
automatically denied access.
4.	Password and Privilege Security
•	Console and VTY passwords are configured to secure local and remote access.
•	The enable secret command is used to encrypt privileged EXEC mode passwords,
preventing them from being displayed in plaintext in the router’s configuration file

5.	Testing and Verification
•	Each configuration is tested by attempting access from both authorized and
unauthorized devices.
•	Packet captures are performed to compare plaintext Telnet traffic with encrypted
SSH sessions.
•	Results confirm that SSH and ACL effectively protect data confidentiality an restrict unauthorized access.



6.	Analysis and Documentation
•	The outcomes of each security configuration are analyzed to assess their
effectiveness.
•	Findings are documented to highlight how each mechanism contributes to
maintaining confidentiality in Cisco networks.
