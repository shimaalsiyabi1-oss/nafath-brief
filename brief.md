Version: NAFATH-V4
Track: Data

## Overview
A national service provider must protect people's data from cyberattacks. It uses software, mobile applications, and networks to provide services. AI can help detect unusual activity and cybersecurity helps protect systems. Data helps organizations understand their systems and identify software components that may have security risks. Mobile apps must be tested for security, and network routes must be checked to prevent attackers from redirecting internet traffic. Together, these fields help make the software supply chain safer and more reliable. Software teams must keep passwords and secrets outside the code. A list of software components helps teams identify known security risks and fix them before attackers exploit them. 
## Software
The Twelve-factor App explains how to manage application settings safely. Passwords and secret keys should not be written in the source code. Instead, environment variables can be used to store these settings separately. This helps protect sensitive information when code is shared or published. Developers should keep these secrets secure to protect their applications and services.


Resource: The Twelve-Factor App - config - https://12factor.net/config
## AI
To help organizations select appropriate security measures and protect AI model from manipulation, it is essential to understand the nature of the attacks they face. Several types of attacks can affect AI systems, including evasion attacks, which alter input data to deceive the AI model during operation, and poisoning attacks, which target training data to influence the model's learning process. Both types of attacks can compromise the reliability of AI systems.


Resource: IBM - Adversarial Machine Learning - https://www.ibm.com/think/topics/adversarial-machine-learning
## Mobile
Designed to improve mobile security, OWASP MASVS establishes standard requirements for protecting sensitive data, securing data in transit, and preventing unauthorized access. Using MASVS as a guide for testing and development helps teams identify security flaws early and protect users' information. Security testing is important because it helps developers find weaknesses before attackers can exploit them and improve the overall security of mobile applications. 

Resource: OWASP MASVS - https://mas.owasp.org
## Networking
Internet routing relies on BGP to distribute path information, making it susceptible to route hijacking through unauthorized route announcement. This can redirect internet traffic to an unintended destination. RPKI helps network operators verify whether a network is authorized to announce routes for specific IP address ranges. However, RPKI is only one layer of defense, so additional security measures are needed to protect internet traffic from routing attacks. 

Resource: cloudflare -what is BGP? - https://www.cloudflare.com/learning/security/glossary/what-/is-bgp
## Cybersecurity
Characterized as a high-severity flaw, Log4Shell (CVE-2021-44228) exposes Java applications using the Apache Log4j library to remote code execution (RCE) attacks. This can put organizational systems and sensitive information at risk. Remediation requires updating Log4j to a fixed version and scanning affected systems for vulnerable software. Regular checks help organizations confirm that vulnerable versions have been removed and reduce the risk of future attacks.

Resource: NIST - CVE-2021-44228 - https://nvd.nist.gov/vuln/detail/cve-2021-44228
## Data
Functioning as a detailed inventory, a Software Bill of Materials (SBOM) records the components and dependencies included in a software build. It provides organizations with clear visibility into their codebases to detect known vulnerabilities. Important metadata-such as supplier details, version numbers, unique identifiers, and dependency relationships-helps security teams track supply chain risks and respond to vulnerabilities more efficiently. 

Resource: CISA - Software Bill of Materials (SBOM) - https://www.cisa.gov/sbom
## Misconception in My Track

## Open Question
