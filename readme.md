# Task 2 – Phishing Email Analysis  
Cyber Security Internship

## Overview
This repository contains my analysis of a sample phishing email as part of Task 2 of the Cyber Security Internship. The goal was to identify red flags, malicious indicators, and techniques used by attackers.

## Tools Used
- Email Header Analyzer (MXToolbox)
- Google Header Analyzer
- Email client (Gmail/Outlook) for preview
- Manual inspection techniques

## Key Findings
- Spoofed sender domain pretending to be Microsoft
- Suspicious mismatched URLs
- Fear-based language to manipulate the victim
- ZIP file attachment containing supposed “verification form”
- SPF, DKIM, and DMARC failures in header analysis
- Multiple grammatical and formatting errors

## Phishing Indicators Identified
- Typosquatting in domain name
- Multi-subdomain obfuscated URLs
- Fake Microsoft branding
- Threat-based urgency
- Malicious attachment
- Invalid email authentication headers

## Files in This Repository
- `Task2_Report.txt` – Full phishing analysis report
- `README.md` – Explanation of task and findings

## What I Learned
- How to inspect email headers
- How phishing emails spoof sender identity
- How to analyze URLs for redirection and impersonation
- How social engineering manipulates users psychologically
- How attackers distribute malware through attachments

## Notes
This analysis is for educational and ethical cybersecurity training only.
Never attempt to phish or target real users.
