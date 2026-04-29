# CLOUDNANO REMEDIATION PLAN
**Operator:** ## TOP 5 CRITICAL FIXES
*(From the 20 raw findings, select the 5 that pose the greatest ACTUAL risk. Explain your reasoning.)*

1. **Remote Code Execution in Apache Struts**
   **Justification:** This is on the public internet, making it much easier for hackers to reach than the air-gapped CVSS 10.0 server.

2. **Unauthenticated AWS S3 Bucket**
   **Justification:** This public bucket contains customer PII; fixing it prevents a major data breach and legal trouble.

3. **SQL Injection in Login Page**
   **Justification:** The login page is a top target, and this hole lets attackers steal the entire customer database.

4. **Cross-Site Scripting (XSS) on Support Forum**
   **Justification:** This is a high-risk public area where hackers can easily steal user login sessions.

5. **Outdated PHP Version 5.4**
   **Justification:** This old software on a public blog is an easy entry point that hackers use to get inside our network.
