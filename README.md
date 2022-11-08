# Honeypot Assignment

**Time spent:** **58** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** For this project, I deployed the VM's through Google Cloud Platform(GCP). The Honeypot framework that I used was Modern Honey Network. The instance was created with Ubuntu 18.04.

<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** Dionaea intention is to trap malware exploiting vulnerabilities exposed by services offered to a network, the ultimate goal is gaining a copy of the malware.

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

*Be sure to upload [session.json](https://github.com/AtVict0r/CodePath_Cybersecurity_Week9_Project/blob/master/session.json) directly to this GitHub repo/branch in order to get full credit.*

List of the most frequently attacked ports:

| Attacked Ports        | Common Use     |
| --------------------- | -------------- |
| 22                    | SSH            |
| 25                    | SMTP           |
| 445                   | Windows Server |
| 3306                  | MySQL          |
| 5060                  | VoIP           |

Some ountries responsible for the attempts:

| Attacker IPs    | Country   |
| --------------  | --------- |
| 91.134.213.144  | Bulgaria  |
| 195.154.105.200 | France    |
| 46.101.178.128  | Germany   |
| 150.95.146.205  | Japan     |
| 198.24.171.250  | USA       |

## Notes

Describe any challenges encountered while doing the assignment.
