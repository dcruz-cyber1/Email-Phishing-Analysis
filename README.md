# Email-Phishing-Analysis

Read me 

Summary
This project analyzes a phishing email impersonating Microsoft Outlook Support. The email was obtained from a public .eml repository and examined using forensic tools to assess its metadata, delivery path, social engineering tactics, and potential indicators of compromise (IOCs). The goal was to identify how the email bypassed authentication and what threat indicators a Tier 1 SOC analyst would use for triage and escalation.

Tools used

github for finding .eml
Thunderbird To safely open and inspect raw email headers and metadata
virus total to detect viruses from attachments 
MXToolbox  To analyze SPF, DKIM, and DMARC results from raw headers
Google Header Analyzer To trace email routing, delivery path, and delays

Final notes
This project demonstrates foundational skills for a Tier 1 SOC analyst, including:
Email threat triage
IOC extraction
Header and authentication analysis
Social engineering awareness
Communication of threat intelligence
