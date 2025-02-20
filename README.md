📑 Overview
This repository contains the detailed penetration testing report for the N7 Web Machine, documenting the methodology, vulnerabilities discovered, exploitation techniques, and remediation recommendations.

🕵️ Objective
The primary goal of this assessment was to identify security weaknesses in the N7 web application and its underlying infrastructure, evaluate their potential impact, and provide actionable mitigation strategies.

🔍 Scope
Target: N7 Web Machine
Assessment Type: Black Box Penetration Testing

Tools Used:
Nmap for network scanning and service enumeration
OWASP ZAP and Burp Suite for web application testing
Dirbuster for directory enumeration
Hydra for brute-force attacks
Metasploit for exploitation
Kali Linux as the testing environment

🚦 Methodology
The testing approach followed the OWASP Testing Guide and included the following phases:
Information Gathering: Identifying open ports, services, and exposed resources.
Enumeration: Probing for potential vulnerabilities and weak configurations.
Exploitation: Attempting to gain unauthorized access or execute malicious code.
Post-Exploitation: Assessing the impact and extracting sensitive data.
Reporting: Documenting findings, evidence, and remediation strategies.

🛠️ Exploitation Highlights
Vulnerability 1: SQL Injection on the login page
Vulnerability 2: Unrestricted File Upload allowing remote code execution
Vulnerability 3: Sensitive information exposure via misconfigured directories

🛡️ Remediation Recommendations
Implement input validation and prepared statements to mitigate SQL Injection.
Sanitize file uploads and restrict executable file types.
Secure directory permissions and avoid exposing sensitive files to the public.

📈 Impact
Exploiting these vulnerabilities could lead to:
Unauthorized access to sensitive data
Server compromise
Potential lateral movement within the network


🧠 Learnings
This assessment provided hands-on experience with:
Real-world web application vulnerabilities
Effective use of penetration testing tools
Reporting and documentation of security findings

📬 Contact
For any queries or collaboration opportunities, feel free to reach out:

LinkedIn: Abinesh Sri
Medium: Abinesh's Cybersecurity Blog
Email: abineshsri72@gmail.com
