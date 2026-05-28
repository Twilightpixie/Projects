# Honeypot Deployment and Threat Analysis

> Security Research Project | 2024

---

## Overview

Deployed a honeypot to attract and capture real attack traffic, then analysed attacker behaviour to produce actionable threat intelligence. The goal was not just to log attacks — it was to understand *how* attackers operate when they believe no one is watching.

---

## Objectives

- Deploy a convincing vulnerable target to attract unsolicited attack traffic
- Capture and log attacker TTPs (Tactics, Techniques and Procedures)
- Extract Indicators of Compromise (IOCs)
- Analyse patterns across sessions to identify common attack vectors
- Produce a structured threat intelligence report

---

## Tools used

| Purpose | Tool |
|---------|------|
| Honeypot framework | Cowrie / OpenCanary |
| Traffic capture | Wireshark |
| Log analysis | ELK Stack |
| OS | Kali Linux / Ubuntu |
| Reporting | Manual — structured to threat intel standards |

---

## What was captured

- Brute force attempts on SSH and Telnet
- Port scanning activity and reconnaissance patterns
- Credential stuffing attempts
- Command sequences run by attackers post-access
- Geographic distribution of source IPs (anonymised)

> Full findings in the PDF report below.

---

## Key takeaways

Real attacker behaviour in the wild is different from what lab exercises simulate. Attackers are methodical, patient, and often automated. The volume of unsolicited traffic hitting even a small, obscure endpoint is significant. Log enrichment matters — raw logs alone are not enough to extract meaningful IOCs without proper normalisation and tagging.

---

## Report

[View full PDF report](https://github.com/Twilightpixie/Projects/blob/main/honeypot.pdf)

---

**Sristi Ghosh** | Sristixwork@gmail.com | [LinkedIn](https://www.linkedin.com/in/sristighosh-work2003/)
