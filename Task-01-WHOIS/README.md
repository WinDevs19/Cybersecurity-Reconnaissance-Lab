# Task 01 – WHOIS Domain Reconnaissance

## Objective
The objective of this task was to query publicly available domain registration information for the target domain using WHOIS.

## Target
networkwalks.com

## Environment
- Kali Linux

## Tool Used
- WHOIS

## Commands
`whois networkwalks.com`

`whois networkwalks.com > task1_whois.txt`

## Findings
The WHOIS lookup identified:

- **Registrar:** GoDaddy.com, LLC
- **Creation Date:** November 6, 2019
- **Registry Expiry Date:** November 6, 2027
- **Name Server:** NS6135.HOSTGATOR.COM
- **Name Server:** NS6136.HOSTGATOR.COM

## Security Relevance
WHOIS provides publicly available domain-registration information that can be useful during the reconnaissance phase of an authorized security assessment. It can reveal information about registrars, name servers, registration dates, and infrastructure.

## Evidence
The terminal screenshot and complete WHOIS output are included as evidence for this task.

## Disclaimer
This exercise was performed as part of an authorized cybersecurity training lab for educational purposes.
