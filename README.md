# TryHackMe: Summit Room – Detection Engineering & Purple Team Project

This repository documents my practical hands-on work from the [Summit room on TryHackMe](https://tryhackme.com/room/summit?utm_source=linkedin&utm_medium=social&utm_campaign=social_share&utm_content=room). This lab simulates real-world adversary behavior and challenges you to detect and block malicious actions using defensive tools and strategies.

## ✅ Completion

🔗 [Room Completed on TryHackMe](https://tryhackme.com/room/summit?utm_source=linkedin&utm_medium=social&utm_campaign=social_share&utm_content=room)

## Skills Gained

- Malware sandbox analysis
- Defense building using the **Pyramid of Pain** framework
- Hash-based detection and mitigation
- Firewall and DNS-based blocking
- Writing Sigma rules for:
  - Registry changes
  - Network anomalies
  - File creation events
- Detection of MITRE ATT&CK TTPs
- Practical blue-team defense escalation techniques

## Learning Progression

| Challenge | Skill Demonstrated | Tool/Strategy Used |
|----------|--------------------|--------------------|
| Sample 1 | Static hash detection | SHA-256 hash block |
| Sample 2 | IP-based network block | Egress firewall rule |
| Sample 3 | Domain filtering | DNS-based blocking |
| Sample 4 | Registry artifact detection | Sigma rule + Sysmon |
| Sample 5 | Network pattern detection | Sigma rule for periodic C2 |
| Sample 6 | File exfil pattern | File creation Sigma rule |
