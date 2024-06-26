<h1> Ethical Hacking Technical Report</h1>
<h2> Name of Company: Sorr Y. Late </h2>
<h2> Prepared by: Cyril Christian B. Imperial</h2>
<h2> Date: May 28, 2024 </h2>
<h3> Executive Summary:</h3>
This report presents the technical findings of the ethical hacking assessment conducted for Company Sorr Y. Late. The engagement aimed to assess and enhance the security posture of Company Sorr Y. Late by identifying and addressing vulnerabilities within its organization's web applications, wireless networks, and through social engineering techniques. This proactive approach is crucial for preventing potential security breaches and protecting sensitive customer and company data. This report also provides detailed descriptions of these findings, along with actionable recommendations for remediation.

<h3> Vulnerability Summary:</h3>
<ol>
<li>SQL Injection in Customer Login Portal (CVE-2021-44228)</li>
•	Critical: A critical SQL injection vulnerability was found in Sorr Y. Late's customer login webpage. Because of this vulnerability, attackers can run any SQL command and perhaps access the database without authorization, extract confidential information, and alter its contents. <br>
<li>	Remote Code Execution via Unpatched Software (CVE-2021-34527)</li>
•	Critical: Unpatched software on the application server was discovered to have a high-risk remote code execution vulnerability. Attackers can run arbitrary code with elevated privileges because to this vulnerability.<br>
  
<li>	Outdated Software (Various CVEs, CVSS: Variable)</li> 
•	High: Several applications and operating systems are outdated and no longer supported, leaving them vulnerable to known exploits.<br>
  
<li> Denial-of-Service (DoS) Vulnerability (CVE-2022-7890, CVSS: 7.2) </li>
•	High: Due to the application server's vulnerability to DoS attacks, there may be service interruptions and website outages.<br>

<li> Weak Password Policies (CVSS: 5.3) </li>
•	High: It was discovered that there were weak password restrictions, which made it possible for brute force assaults to breach administrative accounts.<br>

<li>	Insecure Wireless Network (CVSS: 4.0) </li>
•	High: The company's Wi-Fi network lacks strong encryption, allowing attackers to intercept sensitive data.<br>

<li>	Security Misconfigurations (CVE-2022-21894) </li>
•	High: Several types of security configuration errors were discovered, including incorrect security settings and information leakage via out-of-date software banners and error messages.<br>

<li>	Cross-Site Scripting (XSS) in Web Application (CVE-2021-22942)</li> 
•	Medium: The online application of Sorr Y. Late was found to have a cross-site scripting vulnerability that lets attackers insert malicious scripts that run in the background of a different user's browser session.<br>

<li>	Unattended Physical Access (CVSS: N/A)</li> 
•	High: Unlocked server rooms and unattended workstations pose a physical security risk. <br>

<li>Lack of Backup and Disaster Recovery Plan (CVSS: N/A)</li>	
•	High: The absence of a formal backup and disaster recovery plan hinders the organization's ability to recover from data loss or system outages. <br>

</ol>
<h3>Recommendations for Remediation:</h3> 
<ol>
<li>	Implement prepared statements and parameterized queries to mitigate SQL injection risks. Regularly audit and sanitize input data.</li>
<li>	Update all systems and software with the most recent security fixes. Put in place a reliable patch management procedure.</li>	
<li>	Implement multi-factor authentication (MFA) and enforce strict password restrictions, such as minimum complexity requirements and frequent password changes.</li>	
<li>		Review and update security setups on a regular basis, turn off detailed error messages, and get rid of pointless service banners.</li>
<li>		To prevent XSS attacks, use appropriate output encoding and input validation. Make use of security frameworks and libraries that offer XSS prevention.</li>
<li>	Implement security measures to mitigate DoS attacks.</li>	
<li>		Secure the Wi-Fi network with strong WPA2 encryption and change the default password.</li>
<li>	Implement physical security measures, including access control systems and locked server rooms.</li>	
<li>	Update all software applications and operating systems to the latest versions.</li>	
<li>	Develop a formal backup and disaster recovery plan to ensure business continuity in case of IT disruptions.</li>	
</ol>
<h3> Conclusion:</h3>
Several vulnerabilities in Company Sorr Y. Late network infrastructure, applications, and systems were found by this ethical hacking examination. By implementing the suggested remediation measures to address these vulnerabilities, the organization's overall security posture will be greatly improved, and the danger of cyberattacks and data breaches will be reduced.
