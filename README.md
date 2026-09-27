# Phishing Email Investigation:

## Overview

A SOC analyst-style investigation of a suspicious email using Splunk, email analysis, IOC extraction, threat intelligence, and MITRE ATT&CK mapping.

The investigation focused on identifying phishing indicators, analyzing the email header and body, reviewing the attachment, extracting IOCs, and assessing the overall risk.

## Tools & Technologies

- Splunk – Event and log analysis
- VirusTotal – IOC reputation and threat-intelligence checks
- Email Header Analysis
- MITRE ATT&CK – Technique mapping

## Investigation

The investigation included:

- Splunk-based event analysis
- Email header and authentication analysis
- Email body and URL analysis
- Attachment analysis
- IOC extraction
- Threat intelligence checks
- MITRE ATT&CK mapping
- Risk assessment and recommended response

## MITRE ATT&CK Techniques

- T1566.001 – Spearphishing Attachment
- T1566.002 – Spearphishing Link

## Assessment

The available evidence indicated that the email was likely phishing rather than confirmed malicious activity.

The investigated URL, domain, and IP did not receive malicious verdicts from the available threat-intelligence checks, and no malicious verdict was available for the attachment.

## Report

📄 [View Full Investigation Report](./Phishing_Email_Investigation_Report.pdf)
