<div align="center">

<img src="github-header-banner.png" width="100%" alt="ABDELKARIME AL HANNACHI — Offensive Security Researcher"/>

### Offensive Security Researcher · Application Security · Bug Bounty

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/abdelkarime-al-hannachi/)
[![HackerOne](https://img.shields.io/badge/HackerOne-494949?style=flat-square\&logo=hackerone\&logoColor=white)](https://hackerone.com/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square\&logo=vercel\&logoColor=white)](#)

</div>

---

## About

I am an offensive security researcher focused on **web application security, API security, authentication, authorization, and application architecture**.

My approach is centered on understanding how systems actually behave rather than simply matching vulnerabilities to checklists.

I study vulnerabilities through the full chain:

```text
Attack Surface
      ↓
Architecture
      ↓
Trust Boundaries
      ↓
Security Assumption
      ↓
Exploitation
      ↓
Root Cause
      ↓
Detection / Remediation
```

Current work includes authorized bug bounty research, PortSwigger Web Security Academy labs, application security research, and building security tooling.

---

## Current Research

🔴 **GitLab Bug Bounty Research**

Authorized vulnerability research through GitLab's HackerOne program.

Focus areas:

* Passive reconnaissance
* Attack surface mapping
* Web & API enumeration
* Authentication & authorization
* IDOR / BOLA
* Business logic vulnerabilities
* SSRF
* Security control inconsistencies
* Vulnerability validation
* Reproducible reporting

Research workflow:

```text
Recon → Map → Hypothesize → Test → Validate → Document → Report
```

---

## Security Research

I publish technical research focused on understanding vulnerabilities beyond the payload itself.

| Research                                               | Focus                                                          |
| ------------------------------------------------------ | -------------------------------------------------------------- |
| **Bug Bounty Hunting Methodology 2026**                | Structured methodology for vulnerability research              |
| **Foundational Security Design Principles**            | Security principles → failure conditions → exploitation paths  |
| **SSRF: Practical Research & Attack Surface Analysis** | SSRF discovery, blind SSRF, redirects, parsing inconsistencies |
| **React2Shell / CVE-2025-55182**                       | Technical analysis of insecure deserialization and RCE         |
| **Security Design Principles**                         | Architectural security analysis                                |

The objective is simple:

> Understand why the vulnerability exists, how it becomes exploitable, and how the underlying security boundary should be fixed.

---

## Featured Projects

### 🔐 Web Application Security Research

**PortSwigger Web Security Academy**

A practical research repository covering web application vulnerabilities through controlled labs.

Focus:

`SQLi` · `XSS` · `SSRF` · `JWT` · `OAuth` · `CORS` · `CSRF` · `XXE` · `GraphQL` · `Race Conditions` · `Business Logic`

Research structure:

```text
Vulnerability
      ↓
Exploitation
      ↓
Root Cause
      ↓
Secure Implementation
      ↓
Detection
```

---

### 🧰 Offensive Security Toolkit

A growing collection of security research tools focused on automating repetitive offensive-security workflows.

Current direction:

* Intelligent fuzzing
* Payload generation
* Payload mutation
* Response analysis
* Security automation
* Context-aware testing

Built primarily with Python.

---

### 🗄️ SecureCorp DB

**Build → Breach → Harden**

A controlled enterprise security database laboratory designed to connect database engineering with offensive security.

```text
BUILD
  ↓
Enterprise security model
  ↓
PostgreSQL implementation
  ↓
Realistic security data
  ↓
BREACH
  ↓
SQL Injection
Race Conditions
Privilege Escalation
  ↓
HARDEN
  ↓
Parameterized Queries
Transactions
Least Privilege
  ↓
Retest
```

---

## Technical Focus

### Offensive Security

`Web Application Security` · `API Security` · `Penetration Testing` · `Bug Bounty` · `Reconnaissance` · `Burp Suite`

### Vulnerability Research

`SSRF` · `IDOR / BOLA` · `Authentication` · `Authorization` · `JWT` · `OAuth` · `CORS` · `XSS` · `SQL Injection` · `Business Logic`

### Application Security

`Secure Code Review` · `Security Architecture` · `Threat Modeling` · `Semgrep` · `OWASP`

### Development

`Python` · `Java` · `JavaScript` · `C#` · `SQL` · `PostgreSQL`

### Environment

`Linux` · `Kali Linux` · `Docker` · `Git` · `GitHub`

---

## Methodology

My security work follows a repeatable process rather than a collection of random payloads.

```text
01  RECON
    Identify the attack surface

02  MAP
    Understand endpoints, parameters, APIs and trust boundaries

03  MODEL
    Identify security assumptions and attacker-controlled inputs

04  TEST
    Build hypotheses and test them manually

05  CHAIN
    Combine weaknesses when the architecture allows it

06  VALIDATE
    Prove impact and eliminate false positives

07  ANALYZE
    Determine the underlying root cause

08  FIX
    Design the appropriate security control

09  DETECT
    Automate detection where possible

10  DOCUMENT
    Produce reproducible technical evidence
```

---

## Security Philosophy

```python
def security_research(target):

    understand(target)

    attack_surface = map_attack_surface(target)
    trust_boundaries = identify_trust_boundaries(target)

    hypothesis = build_security_hypothesis(
        attack_surface,
        trust_boundaries
    )

    result = test_manually(hypothesis)

    if result.is_valid:
        root_cause = analyze_root_cause(result)
        remediation = design_secure_fix(root_cause)
        detection = automate_detection(root_cause)

        document(
            result,
            root_cause,
            remediation,
            detection
        )
```

Security research is not only:

```text
"Can I exploit this?"
```

It is also:

```text
"Why was this possible?"
"Which security assumption failed?"
"What trust boundary was violated?"
"How should the system prevent it?"
"Can the failure be detected automatically?"
```

---

## Selected Technologies

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![C%23](https://img.shields.io/badge/C%23-239120?style=flat-square\&logo=csharp\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square\&logo=burpsuite\&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-3B82F6?style=flat-square\&logo=semgrep\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)

</div>

---

## GitHub

I use GitHub as a technical laboratory rather than simply a collection of repositories.

Repositories contain:

* Security research
* Vulnerability analysis
* Exploitation methodology
* Secure implementations
* Security automation
* Application security experiments
* Engineering projects

**Quality over repository count.**

---

<div align="center">

### Think like an attacker. Understand like an engineer. Build like a defender.

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ABDELKARIMEALHANNACHI\&color=00FF41\&style=flat-square\&label=PROFILE+VIEWS)

</div>
