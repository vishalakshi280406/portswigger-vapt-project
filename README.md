# PortSwigger Web Security Academy – VAPT Minor Project

## Overview
Vulnerability assessment conducted against PortSwigger Web Security Academy labs, covering 8 vulnerability categories across web applications and APIs. Includes reproduction steps, evidence, impact analysis, and remediation for each finding.

## Scope
- Target: PortSwigger Web Security Academy labs (authorized training environment)
- Testing type: Manual black-box testing
- Tools: Burp Suite Community Edition

## Vulnerabilities Covered
| # | Category | OWASP Mapping |
|---|----------|----------------|
| 1 | SQL Injection | A03:2021 – Injection |
| 2 | Cross-Site Scripting (XSS) | A03:2021 – Injection |
| 3 | Cross-Site Request Forgery (CSRF) | A01:2021 – Broken Access Control |
| 4 | CORS Misconfiguration | A05:2021 – Security Misconfiguration |
| 5 | IDOR (Broken Object Level Authorization) | API1:2023 |
| 6 | BOPLA (Broken Object Property Level Authorization) | API3:2023 |
| 7 | Unrestricted Resource Consumption | API4:2023 |
| 8 | SSRF | A10:2021 |

## Methodology
1. Reviewed lab objective and identified attack surface
2. Captured baseline requests using Burp Suite
3. Crafted and injected payload via Repeater
4. Verified exploitation and documented evidence
5. Assessed impact and mapped to OWASP category
6. Recorded remediation recommendation

## Disclaimer
All testing was performed exclusively against PortSwigger's own intentionally vulnerable lab environment, intended for this purpose. No unauthorized systems were tested.# portswigger-vapt-project
