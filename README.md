# FUTURE_CS_02 – Phishing Email Detection & Awareness

## Project Overview

This project focuses on identifying phishing indicators in email messages, analyzing basic email-header information, classifying email risk, and creating phishing-awareness guidelines.

The project was completed as part of the **Future Interns Cybersecurity Internship – Task 2**.

## Objectives

- Identify common phishing indicators.
- Analyze sender addresses and suspicious links safely.
- Review basic email-header information.
- Understand SPF, DKIM, and DMARC results.
- Classify emails based on risk.
- Create practical phishing-awareness guidelines.

## Email Samples Analyzed

| Sample | Classification | Risk |
|---|---|---|
| Amazon-style account alert | Phishing | High |
| Trading/investment account alert | Phishing | High |
| Account statement notification | Safe | Low |

## Key Phishing Indicators

- Suspicious sender domains
- Urgent deadlines
- Threatening language
- Generic greetings
- Suspicious links
- Requests for sensitive information
- Financial targeting
- Social engineering
- Suspicious Reply-To addresses
- SPF/DKIM/DMARC failures

## Header Analysis

A synthetic training header was analyzed to demonstrate:

- SPF
- DKIM
- DMARC
- Sender domain
- Reply-To address

The sample produced:

```text
SPF   → FAIL
DKIM  → NONE
DMARC → FAIL
```

These results were considered together with other phishing indicators.

## Tools & Techniques

**Tools:**
- Web Browser
- Text Editor
- Email Header Analysis Concepts
- GitHub

**Techniques:**
- Sender analysis
- Domain inspection
- Link analysis
- Social-engineering identification
- Email-header analysis
- Risk classification
- Security awareness

## Repository Structure

```text
FUTURE_CS_02/
│
├── Samples/
│   ├── Phishing-Email-01.txt
│   ├── Phishing-Email-02.txt
│   ├── Legitimate-Email-01.txt
│   ├── Analysis-01.txt
│   ├── Analysis-02.txt
│   ├── Analysis-03.txt
│   ├── Header-Sample-01.txt
│   ├── Header-Analysis-01.txt
│   └── Awareness-Guidelines.txt
│
├── Evidence/
│   ├── Phishing-Email-01.png
│   ├── Analysis-01.png
│   ├── Header-Sample-01.png
│   └── Phishing-Awareness.png
│
├── Report/
│   └── Phishing-Detection-Awareness-Report.pdf
│
└── README.md
```

## Security Awareness

### DO

- Check the complete sender address.
- Inspect links before clicking.
- Verify suspicious requests through official channels.
- Report suspicious emails.
- Use multi-factor authentication.

### DON'T

- Don't click suspicious links.
- Don't open unexpected attachments.
- Don't share passwords or OTPs.
- Don't reply to suspicious emails.
- Don't bypass security warnings.

### Key Takeaway

**STOP → CHECK → VERIFY → REPORT**

All phishing emails and email headers in this project are **synthetic educational samples** created for cybersecurity training.

No real phishing campaign was conducted, no credentials were collected, and no real user account was targeted.
