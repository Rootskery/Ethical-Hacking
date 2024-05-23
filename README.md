# Ethical Hacking Technical Report
# Name of Company: Sorr Y. Late 
# Prepared by: Cyril Christian B. Imperial
# Date: May 28, 2024
# Executive Summary:
This report presents the technical findings of the ethical hacking assessment conducted for Company Sorr Y. Late. The engagement aimed to assess and enhance the security posture of Company Sorr Y. Late by identifying and addressing vulnerabilities within its organization's web applications, wireless networks, and through social engineering techniques. This proactive approach is crucial for preventing potential security breaches and protecting sensitive customer and company data. This report also provides detailed descriptions of these findings, along with actionable recommendations for remediation.

# Vulnerability Summary:
1.	SQL Injection in Customer Login Portal (CVE-2021-44228
•	Critical: A critical SQL injection vulnerability was found in Sorr Y. Late's customer login webpage. Because of this vulnerability, attackers can run any SQL command and perhaps access the database without authorization, extract confidential information, and alter its contents.
2.	Remote Code Execution via Unpatched Software (CVE-2021-34527)
•	Critical: Unpatched software on the application server was discovered to have a high-risk remote code execution vulnerability. Attackers can run arbitrary code with elevated privileges because to this vulnerability.
3.	Outdated Software (Various CVEs, CVSS: Variable): 
•	High: Several applications and operating systems are outdated and no longer supported, leaving them vulnerable to known exploits.
4.	Denial-of-Service (DoS) Vulnerability (CVE-2022-7890, CVSS: 7.2)
•	High: Due to the application server's vulnerability to DoS attacks, there may be service interruptions and website outages.
5.	Weak Password Policies (CVSS: 5.3)
•	High: It was discovered that there were weak password restrictions, which made it possible for brute force assaults to breach administrative accounts.
6.	Insecure Wireless Network (CVSS: 4.0)
•	High: The company's Wi-Fi network lacks strong encryption, allowing attackers to intercept sensitive data.
7.	Security Misconfigurations (CVE-2022-21894): 
•	High: Several types of security configuration errors were discovered, including incorrect security settings and information leakage via out-of-date software banners and error messages.
8.	Cross-Site Scripting (XSS) in Web Application (CVE-2021-22942)
•	Medium: The online application of Sorr Y. Late was found to have a cross-site scripting vulnerability that lets attackers insert malicious scripts that run in the background of a different user's browser session.
9.	Unattended Physical Access (CVSS: N/A): 
•	High: Unlocked server rooms and unattended workstations pose a physical security risk.
10.	Lack of Backup and Disaster Recovery Plan (CVSS: N/A): 
•	High: The absence of a formal backup and disaster recovery plan hinders the organization's ability to recover from data loss or system outages.
# Recommendations for Remediation:
1.	Implement prepared statements and parameterized queries to mitigate SQL injection risks. Regularly audit and sanitize input data.
2.	Update all systems and software with the most recent security fixes. Put in place a reliable patch management procedure.
3.	Implement multi-factor authentication (MFA) and enforce strict password restrictions, such as minimum complexity requirements and frequent password changes.
4.	Review and update security setups on a regular basis, turn off detailed error messages, and get rid of pointless service banners.
5.	To prevent XSS attacks, use appropriate output encoding and input validation. Make use of security frameworks and libraries that offer XSS prevention.
6.	Implement security measures to mitigate DoS attacks.
7.	Secure the Wi-Fi network with strong WPA2 encryption and change the default password.
8.	Implement physical security measures, including access control systems and locked server rooms.
9.	Update all software applications and operating systems to the latest versions.
10.	Develop a formal backup and disaster recovery plan to ensure business continuity in case of IT disruptions.
# Conclusion:
# Several vulnerabilities in Company Sorr Y. Late network infrastructure, applications, and systems were found by this ethical hacking examination. By implementing the suggested remediation measures to address these vulnerabilities, the organization's overall security posture will be greatly improved, and the danger of cyberattacks and data breaches will be reduced.
