# Incident-handlers-journal-example-template
This template serves as a structured format for documenting incident handling activities. It was utilized during practical exercises as part of coursework within the Coursera Google Cybersecurity Professional certificate track.

## Incident Details

- **Date and Time**: [Insert Date and Time]
- **Incident ID**: [Insert Unique Identifier]
- **Description**: [Brief description of the incident]

## Investigation Steps

| Step | Action Taken | Outcome |
|------|--------------|---------|
| 1    | [Describe the action taken during this step] | [Result or findings] |
| 2    | [Describe the action taken during this step] | [Result or findings] |
| ...  | ...          | ...     |

## Evidence and Artifacts

- Attach relevant files, logs, screenshots, or other evidence here.

## Recommendations

- Provide recommendations for mitigation, prevention, or further investigation.

## Follow-Up Actions

- List any follow-up tasks or actions required.


# List of Entries
Below are the incident journal entries developed as part of the course, utilizing the incident handler template for simulated analysis work.

### Entry #1

- **Date and Time**: 08/01/2023, Tuesday morning, 9:00 AM.
- **Incident ID**: 01
- **Description**: A ransomware attack targeted a small U.S. healthcare organization, encrypting employee workstations and disrupting operations. The incident is under investigation within the Detection and Analysis and Containment, Eradication, & Recovery phases of the NIST Incident Response Lifecycle.

#### The 5 W's

| Step | The 5 W's | Outcome |
|------|--------------|---------|
| 1    | **Who**: An organized group of unethical hackers targeting healthcare organizations. | Responsible for deploying ransomware and demanding payment for decryption. |
| 2    | **What**: Ransomware encrypted files on employee workstations, halting clinic operations. | Required a ransom payment for data recovery. |
| 3    | **When**: Occurred early Tuesday morning, reported at 9:00 AM. | Prompted technical assistance response from the organization. |
| 4    | **Where**: At a small U.S. healthcare clinic. | Specializes in primary care services. |
| 5    | **Why**: Triggered by a phishing email containing malicious attachments. | Executed upon download, encrypting files and demanding ransom. |

---

- **Additional notes**: Recommendations include proactive measures to prevent future incidents and considerations regarding ransom payments and recovery strategies.

### Entry #2

- **Date and Time**: 08/04/2023 1:20 PM
- **Incident ID**: 02
- **Description**: Investigation into a suspicious file ("bfsvc.exe") downloaded on an employee's computer, suspected to be malware. The incident is under investigation within the Detection and Analysis phase of the NIST Incident Response Lifecycle.

#### The 5 W's

| Step | The 5 W's | Outcome |
|------|--------------|---------|
| 1    | **Who**: A threat actor linked to Chinese cyber espionage (BlackTech group). | Used spear phishing tactics targeting financial services companies. |
| 2    | **What**: Spear phishing email delivered a malicious attachment ("bfsvc.exe"). | Installed unauthorized executable files on the employee's computer. |
| 3    | **When**: Incident detected at 1:20 PM; IDS alerted security team. | Prompted immediate investigation by SOC. |
| 4    | **Where**: At a financial services company based in the United States. | Targeted through spear phishing tactics. |
| 5    | **Why**: Exploited the organization's profile to infiltrate systems. | Installed malware aimed at exfiltrating sensitive data. |

---

- **Additional notes**: Detailed timeline and malware analysis using tools like VirusTotal and MalwareBazaar confirm malicious nature.

### Entry #3

- **Date and Time**: December 28, 2022, at 7:20 p.m., PT
- **Incident ID**: 03
- **Description**: Unauthorized access to customer PII and financial information via a vulnerability in an e-commerce application. Incident spans Containment, Eradication, and Recovery, and Post-Incident phases of the NIST Incident Response Lifecycle.

#### The 5 W's

| Step | The 5 W's | Outcome |
|------|--------------|---------|
| 1    | **Who**: Exploited by an individual via forced browsing. | Demanded ransom to prevent data leakage. |
| 2    | **What**: Accessed customer PII and financial data. | Extorted company with data leak threats. |
| 3    | **When**: Occurred on December 28, 2022, at 7:20 p.m. PT. | Detected and reported immediately. |
| 4    | **Where**: In a mid-sized retail company. | Vulnerability exploited in e-commerce web app. |
| 5    | **Why**: Exploited a zero-day vulnerability. | Used forced browsing to access customer data. |

---

- **Additional notes**: Response included disclosure, customer protection services, and security enhancements.

### Entry #4

- **Date and Time**: December 28, 2022, at 7:20 p.m., PT
- **Incident ID**: 04
- **Description**: Investigation into potential security issues with an organization's mail server, focusing on failed SSH logins for the root account. Incident falls within the Detection and Analysis phase of the NIST Incident Response Lifecycle.

#### The 5 W's

| Step | The 5 W's | Outcome |
|------|--------------|---------|
| 1    | **Who**: Possible brute force attacks on system user accounts. | Targeted mail server's root account. |
| 2    | **What**: Detected a surge in failed SSH login attempts. | Investigated for security breaches. |
| 3    | **When**: Occurred over eight consecutive days, from 2/27/23 to 3/6/23, at 1:39:51 AM. | Noted suspicious activity outside normal hours. |
| 4    | **Where**: At Buttercup Games' e-commerce store. | Targeted mail server for potential security breach. |
| 5    | **Why**: Attempted unauthorized access via SSH. | Investigated potential compromise or intrusion. |

---

- **Additional notes**: Used Splunk Cloud SIEM tool for analysis, highlighting abnormal login attempts and potential user compromises.

## Reflections/Notes

- **Challenges**: Setting up Splunk Cloud for incident #4 and ensuring concise yet informative logs for all entries.
- **Understanding Growth**: Increased practical understanding through hands-on challenges in the course, simulating real-world incident response scenarios.
- **Favorite Tool**: Enjoyed using VirusTotal and MalwareBazaar for malware analysis, akin to digital detective work in cybersecurity.

