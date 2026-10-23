# OS_hardening_techniques

## Overview
This project is a cybersecurity course activity based on a fictional website compromise. I reviewed a provided tcpdump log and wrote a security incident report.

## Incident
An attacker guessed the default administrator password using a brute force attack. They modified the website to prompt visitors to download a malicious file. Running the file redirected visitors to a fake website.

## Analysis
- Identified DNS, TCP and HTTP traffic.
- Followed connections to the original and fake websites.
- Documented the incident using the scenario and provided evidence.
- Recommended limiting failed login attempts.
- The traffic log shows communication with both websites. Information about the brute force attack comes from the scenario.

## Recommendation
Temporarily block further login attempts after several incorrect passwords to slow automated password guessing.

## Skills Practiced
- Reading tcpdump logs
- Understanding network protocols
- Writing incident reports
- Identifying security improvements

## Report
The completed security incident report is included in this repository.
