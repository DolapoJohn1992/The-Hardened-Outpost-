# CloudNano Vulnerability Triage & Remediation

## Project Overview

This project serves as a demonstration of strategic vulnerability management, risk assessment, and technical triage. It involves analyzing automated scan data from a web server and prioritizing vulnerabilities based on real-world business risk (Likelihood × Impact) rather than relying solely on raw CVSS scores.

## Technical Stack

* **Operating System:** Ubuntu Linux
* **Tools:** Nikto (Vulnerability Scanner), Bash, Git/GitHub
* **Environment:** VirtualBox, VS Code

## Project Phases

1. **Target Provisioning:** Deployed a local, intentionally vulnerable web server for analysis.
2. **Automated Scanning:** Executed a vulnerability assessment using the Nikto web scanner to generate baseline security metrics.
3. **Strategic Triage:** Analyzed 20 raw scan findings, filtering out noise and false positives to identify genuine threats. 
4. **Risk Prioritization:** Applied the Risk Formula to select the top 5 critical vulnerabilities, prioritizing public-facing assets and data exposure over theoretical air-gapped vulnerabilities.

## Portfolio Artifacts

The repository includes the finalized `remediation_plan.md`, which outlines the top prioritized fixes along with business-centric justifications for their selection.
