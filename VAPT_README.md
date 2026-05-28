# Vulnerability Assessment and Penetration Testing
## Simulated Web Application Environment

> Capstone Project | 2024

---

## Overview

End-to-end VAPT engagement conducted on a simulated web application, following industry-standard methodology from reconnaissance through to a professional remediation report. The goal was to approach the target the way a real attacker would — and document everything the way a real security professional should.

---

## Scope

| Item | Detail |
|------|--------|
| Target | Simulated e-commerce / corporate web application |
| Test type | Black-box and grey-box |
| Methodology | OWASP Testing Guide v4 + PTES framework |

---

## Methodology

```
Reconnaissance  →  Scanning  →  Vulnerability Analysis  →  Exploitation  →  Reporting
```

---

## Tools by phase

| Phase | Tools used |
|-------|-----------|
| Reconnaissance | Nmap, Whois, Google Dorking, theHarvester |
| Scanning | Nikto, Nmap scripts, Burp Suite |
| Exploitation | Metasploit, Burp Suite, SQLMap |
| Reporting | Manual — structured to professional VAPT standard |

---

## Vulnerabilities identified

| Severity | Vulnerability | OWASP Category | CVSSv3 |
|----------|--------------|----------------|--------|
| Critical | SQL Injection | A03:2021 Injection | 9.8 |
| High | Cross-Site Scripting (XSS) | A03:2021 Injection | 7.2 |
| High | Broken Authentication | A07:2021 | 8.1 |
| Medium | Security Misconfiguration | A05:2021 | 5.3 |
| Low | Sensitive Data Exposure | A02:2021 | 3.7 |

---

## Deliverables

- Executive summary written for non-technical stakeholders
- Technical findings with CVSSv3 scores and evidence
- Proof-of-concept documentation for each vulnerability
- Prioritised remediation roadmap

---

## Report

[View full PDF report](https://github.com/Twilightpixie/Projects/blob/main/capstone%20project.pdf)

---

**Sristi Ghosh** | CEH (in progress) | Sristixwork@gmail.com | [LinkedIn](https://www.linkedin.com/in/sristighosh-work2003/)
