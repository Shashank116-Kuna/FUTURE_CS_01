# Vulnerability Assessment Report - avniet.ac.in
## Target Website
- URL: https://avniet.ac.in
- CMS: WordPress 6.9.3 on PHP 8.4.8 / LiteSpeed / MySQL
- Scope: Public-facing pages only — Passive Read-Only Scan
## Tools Used
- Pentest-Tools.com Light Scanner (38 tests, 47 sec scan)
- Browser DevTools | securityheaders.com | SSL Labs
- WhatCMS / Wappalyzer | Manual Page Source Analysis
## Ethics Statement
Passive read-only scan only. No exploitation or active attacks performed.
All findings based on publicly observable information and version detection.
## Findings Summary
| ID | Finding | Status | Severity |
|------|---------------------------------|-----------|----------|
| F-01 | PHP 8.4.8 — 5 CVEs (CVSS 8.2) | CONFIRMED | HIGH |
| F-02 | Missing CSP Header | CONFIRMED | LOW |
| F-03 | Missing HSTS Header | CONFIRMED | LOW |
| F-04 | Missing X-Content-Type-Options | CONFIRMED | LOW |
| F-05 | Missing Referrer-Policy | CONFIRMED | LOW |
| F-06 | Technology Stack Disclosed | CONFIRMED | LOW |
| F-07 | robots.txt Accessible | CONFIRMED | LOW |
| F-08 | security.txt Missing | CONFIRMED | INFO |
| F-09 | WordPress Admin Panel Exposed | MANUAL | HIGH |
| F-10 | Cookie Security Flags Missing | MANUAL | HIGH |
| F-11 | Missing X-Frame-Options | MANUAL | MEDIUM |
| F-12 | Third-party Resource Risk / SRI | MANUAL | LOW |                                                                                                 F-13 | 400 Injection Points Detected | SCANNER | INFO |
## Repository Contents
- AVNIET_Vulnerability_Assessment_Report_v2.docx
- Screenshot 2026-03-11 220504.png
- Screenshot 2026-03-11 220529.png
- Screenshot 2026-03-11 221548.png
- Screenshot 2026-03-11 221829.png
Website_Scanner-https___avniet.ac.in-
## Prepared By: Shashank Kuna| Future Interns Cybersecurity Task 1 (2026)
