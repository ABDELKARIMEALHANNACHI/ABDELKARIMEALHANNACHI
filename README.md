<div align="center">

<img src="github-header-banner.png" width="100%" alt="Abdelkarime Al Hannachi — Offensive Security Researcher"/>

### Offensive Security Researcher · Application Security · Bug Bounty

*Breaking systems to understand them — documenting root causes, not just payloads.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelkarime-al-hannachi/)
[![HackerOne](https://img.shields.io/badge/HackerOne-494949?style=flat-square&logo=hackerone&logoColor=white)](https://hackerone.com/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](#)

</div>

<br/>

## 🎯 At a Glance

| | |
|---|---|
| **Focus** | Web & API security · authentication/authorization · business logic |
| **Active program** | GitLab, via HackerOne |
| **Lab work** | PortSwigger Web Security Academy |
| **Building** | Offensive-security tooling · SecureCorp DB |
| **Approach** | Architecture-first — I map trust boundaries before I touch a payload |

<br/>

## About

I'm an offensive security researcher working across web application security, API security, authentication/authorization, and application architecture.

I treat vulnerabilities as symptoms, not the story. The real question is never just "can I exploit this" — it's which security assumption failed and which trust boundary let it happen. That means understanding a target's architecture well enough to predict where it will fail, not just running a scanner until something lights up.

```text
Attack Surface → Architecture → Trust Boundaries → Security Assumption → Exploitation → Root Cause → Remediation
```

Current focus: authorized bug bounty research on GitLab, structured lab work through PortSwigger's Web Security Academy, and building tooling that automates the repetitive parts of that process.

<br/>

## 🔴 Current Research — GitLab Bug Bounty

Authorized vulnerability research through GitLab's HackerOne program.

| Area | |
|---|---|
| Reconnaissance | Passive recon, attack-surface mapping |
| Enumeration | Web & API enumeration |
| Access control | Authentication, authorization, IDOR / BOLA |
| Application logic | Business logic vulnerabilities |
| Server-side | SSRF, security control inconsistencies |
| Output | Vulnerability validation, reproducible reporting |

```text
Recon → Map → Hypothesize → Test → Validate → Document → Report
```

<br/>

## Published Research

I write up research that goes past the payload — the architecture and assumptions behind it.

| Research | Focus |
|---|---|
| **Bug Bounty Hunting Methodology (2026)** | A structured, repeatable methodology for vulnerability research |
| **Foundational Security Design Principles** | Security principles → failure conditions → exploitation paths |
| **SSRF: Practical Research & Attack Surface Analysis** | Discovery, blind SSRF, redirect abuse, parser inconsistencies |
| **React2Shell (CVE-2025-55182)** | Technical analysis of an insecure deserialization → RCE chain |
| **Security Design Principles** | Architectural security analysis |

> Understand why the vulnerability exists, how it becomes exploitable, and how the underlying trust boundary should be fixed.

<br/>

## Featured Projects

<details open>
<summary><b>🔐 Web Application Security Research — PortSwigger Web Security Academy</b></summary>
<br/>

A practical research repository covering web application vulnerabilities through controlled labs.

`SQLi` `XSS` `SSRF` `JWT` `OAuth` `CORS` `CSRF` `XXE` `GraphQL` `Race Conditions` `Business Logic`

```text
Vulnerability → Exploitation → Root Cause → Secure Implementation → Detection
```

</details>

<details>
<summary><b>🧰 Offensive Security Toolkit</b></summary>
<br/>

A growing collection of tools that automate repetitive offensive-security workflows: intelligent fuzzing, payload generation and mutation, response analysis, and context-aware testing. Built primarily in Python.

</details>

<details>
<summary><b>🗄️ SecureCorp DB — Build → Breach → Harden</b></summary>
<br/>

A controlled enterprise security database lab connecting database engineering with offensive security.

```text
BUILD    Enterprise security model · PostgreSQL implementation · realistic data
BREACH   SQL injection · race conditions · privilege escalation
HARDEN   Parameterized queries · transactions · least privilege
RETEST   Confirm the fix holds under the same attack
```

</details>

<br/>

## Methodology

| Phase | Objective |
|---|---|
| 01 · Recon | Identify the attack surface |
| 02 · Map | Understand endpoints, parameters, APIs, and trust boundaries |
| 03 · Model | Identify security assumptions and attacker-controlled inputs |
| 04 · Test | Build hypotheses and test them manually |
| 05 · Chain | Combine weaknesses where the architecture allows it |
| 06 · Validate | Prove impact and eliminate false positives |
| 07 · Analyze | Determine the underlying root cause |
| 08 · Fix | Design the appropriate security control |
| 09 · Detect | Automate detection where possible |
| 10 · Document | Produce reproducible technical evidence |

<br/>

## Security Philosophy

```python
def security_research(target):
    understand(target)

    attack_surface   = map_attack_surface(target)
    trust_boundaries = identify_trust_boundaries(target)

    hypothesis = build_security_hypothesis(attack_surface, trust_boundaries)
    result     = test_manually(hypothesis)

    if result.is_valid:
        root_cause  = analyze_root_cause(result)
        remediation = design_secure_fix(root_cause)
        detection   = automate_detection(root_cause)
        document(result, root_cause, remediation, detection)
```

Security research isn't only *"can I exploit this?"* — it's *"which assumption failed, which boundary broke, and how do we make sure it's caught automatically next time?"*

<br/>

## Tech Stack

**Offensive Security**
`Web Application Security` `API Security` `Penetration Testing` `Bug Bounty` `Reconnaissance` `Burp Suite`

**Vulnerability Research**
`SSRF` `IDOR / BOLA` `Authentication` `Authorization` `JWT` `OAuth` `CORS` `XSS` `SQL Injection` `Business Logic`

**Application Security**
`Secure Code Review` `Security Architecture` `Threat Modeling` `Semgrep` `OWASP`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C%23](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-3B82F6?style=flat-square&logo=semgrep&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

<br/>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ABDELKARIMEALHANNACHI&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ABDELKARIMEALHANNACHI&layout=compact&theme=dark&hide_border=true" height="165"/>

</div>

<br/>

## Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelkarime-al-hannachi/)
[![HackerOne](https://img.shields.io/badge/HackerOne-494949?style=flat-square&logo=hackerone&logoColor=white)](https://hackerone.com/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](#)

**Think like an attacker. Understand like an engineer. Build like a defender.**

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ABDELKARIMEALHANNACHI&color=00FF41&style=flat-square&label=PROFILE+VIEWS)

</div>
