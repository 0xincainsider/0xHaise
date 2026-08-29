### System Engineering Student · DevSecOps · Backend · Offensive Security

Software engineering and cybersecurity enthusiast focused on building, deploying and security-testing production systems.

My profile combines **backend/full-stack development**, **DevSecOps**, **cloud infrastructure** and **authorized offensive security**. I enjoy working across the entire lifecycle of a system: from architecture and implementation to deployment, hardening, testing and controlled exploitation.

```text
Build → Deploy → Test → Break → Harden
```

---

## About Me

* Systems Engineering student
* Focused on **DevSecOps, backend engineering and offensive security**.
* Experience building production-oriented applications with **Next.js, Node.js and PostgreSQL**.
* Strong interest in **application security, red teaming, Active Directory and cloud security**.
* Experience implementing **JWT, RBAC, PostgreSQL RLS and multi-tenant architectures**.
* Security-oriented development using **SAST, DAST, automated testing and vulnerability remediation**.
* Interested in **AI Engineering, agentic systems, MCP and multi-agent orchestration**.
* Currently based in **Peru**.

---


| **Category**           | **Technologies**                                                                                                                                           |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Languages**          | `TypeScript` `JavaScript` `Python` `Go` `Rust` `Java` `C#` `Kotlin`                                                                                        |
| **Backend**            | `Node.js` `Express` `NestJS` `Hono` `FastAPI` `Flask` `Spring Boot`                                                                                        |
| **Web**                | `Next.js 16` `React` `App Router` `Server Actions` `REST APIs` `WebSockets` `Socket.IO`                                                                    |
| **Mobile**             | `React Native` `Android` `Kotlin`                                                                                                                          |
| **Desktop**            | `Java` `C#` `Electron`                                                                                                                                     |
| **Database**           | `PostgreSQL` `MySQL` `SQL Server` `MongoDB` `Redis` `SQLite` `Firebase` `Supabase` `DuckDB` `ClickHouse`                                                   |
| **Message Queues**     | `RabbitMQ`                                                                                                                                                 |
| **Deployment**         | `Docker` `Kubernetes` `GitHub Actions` `Jenkins` `Terraform` `Nginx` `Vercel` `AWS` `GCP` `Azure`                                                          |
| **Cloud Services**     | `AWS EC2` `Fargate` `S3` `Lambda` `RDS` `CloudWatch` `Cloudflare Tunnel`                                                                                   |
| **App Security**       | `OWASP Top 10` `JWT` `OAuth2` `RBAC` `RLS` `SAST` `DAST` `Security Testing` `Hardening` `Input Validation` `Secure Authentication` `Multi-Tenant Security` |
| **Offensive Security** | `Burp Suite` `Nmap` `Metasploit` `Impacket` `Wireshark` `FFUF` `Gobuster` `Wfuzz` `WPScan` `SearchSploit` `Hydra` `John` `Bash`                            |
| **AI Engineering**     | `Claude Code` `OpenAI` `Gemini` `Open-Source LLMs` `MCP` `n8n` `OpenClaw`                                                                                  |

### Application Security

* Secure authentication and authorization.
* JWT-based authentication using secure cookies.
* OAuth2 and session security.
* RBAC and server-side authorization.
* PostgreSQL RLS with deny-by-default policies.
* Multi-tenant isolation.
* OWASP Top 10 mitigation.
* SAST, DAST and security regression testing.
* Input validation and backend hardening.
* Vulnerability remediation and PoC reproducibility.

### Offensive Security

Areas:

* Web application penetration testing.
* Authentication and authorization testing.
* SQL Injection.
* XSS / DOM XSS.
* CSRF.
* SSRF.
* XXE.
* IDOR.
* Race conditions.
* HTTP request smuggling.
* Cache deception.
* Host Header Injection.
* WebSockets security.
* Active Directory attacks.
* Kerberos attacks.
* Cloud security.
* AWS / Azure / GCP IAM and storage security.
* Security reconnaissance and network mapping.
* MITRE ATT&CK-based assessment.

---

# Certifications

### Offensive Security & Red Team

| Certification                            | Issuer               | Year |
| ---------------------------------------- | -------------------- | ---: |
| **Certified Red Team Analyst (CRTA)**    | CyberWarfare Labs    | 2026 |
| **Multi-Cloud Red Team Analyst (MCRTA)** | CyberWarfare Labs    | 2026 |
| **Web Red Team Analyst**                 | CyberWarfare Labs    | 2026 |

Currently pursuing:

* **Burp Suite Certified Practitioner — PortSwigger**

### Infrastructure & Cybersecurity

| Certification                            | Issuer     | Year |
| ---------------------------------------- | ---------- | ---: |
| **ISC2 Certified in Cybersecurity (CC)** | ISC2       | 2023 |
| **Linux Administrator LPIC-1**           | LPI / PCM  | 2023 |
| **Digital Forensics**                    | PCM        | 2023 |
| **Linux Essentials**                     | PCM        | 2023 |
| **SQL Intermediate**                     | HackerRank | 2025 |
| **Advanced Program of English**          | ICPNA      | 2023 |

---

# Featured Projects

## Multi-Tenant Agricultural Management

Production-oriented full-stack platform for livestock management.

**Stack:** `Next.js 16` `PostgreSQL` `TypeScript` `JWT` `RLS` `RBAC`

Key engineering work:

* Designed the application architecture using **Next.js 16 App Router**.
* Separated presentation, domain and data-access responsibilities.
* Implemented **207 RPC functions** for backend operations.
* Designed PostgreSQL with **28 versioned migrations**.
* Implemented **atomic multi-tenant transactions**.
* Secured tenant isolation using **PostgreSQL Row-Level Security**.
* Implemented **deny-by-default RLS policies**.
* Added granular **RBAC authorization** validated server-side.
* Implemented secure JWT authentication using HTTP cookies.
* Built **341 unit tests** using Vitest.
* Built **29 E2E tests** using Playwright.
* Integrated automated testing into **CI/CD**.
* Performed query profiling and **TTFB performance analysis**.
 
---

## Perú Informado — News Aggregator + AI

Full-stack news aggregation platform with automated content processing and AI-assisted analysis.

**Stack:** `Next.js` `Node.js` `PostgreSQL` `Supabase` `Clerk` `LLM` `Playwright`

Key engineering work:

* Built server-side RSS ingestion and parsing.
* Implemented authentication using **Clerk**.
* Designed persistence using **Supabase/PostgreSQL**.
* Integrated an **LLM-based news analysis pipeline**.
* Implemented subscription tiers.
* Automated performance benchmarking with **Playwright**.

**Live application:**
https://peru-informado.vercel.app

---

# Security Engagements

All security activities described below were performed in **authorized environments**.

### Web Application Security — Engagement 1

* Identified an exposed repository containing application source code, business logic and plaintext secrets.
* Discovered a **critical authentication backdoor** caused by an embedded master credential.
* Reproduced the vulnerability through a controlled PoC.
* Designed the remediation and validation strategy.
* Integrated security testing into the development workflow using **SAST and reproducibility testing**.

### Web Application Security — Engagement 2

* Identified and exploited a **blind SQL injection** in an authorized environment.
* Demonstrated database-level data exposure.
* Identified a directory listing exposing approximately **16,000 customer-related documents**.
* Documented the attack surface and impact.
* Proposed remediation involving input validation, authorization controls and backend hardening.

---

# Security Labs & Tools

| Project                                                                                            | Description                                                                                    |
| -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **[Dorking Tool](https://0xincainsider.github.io/dorktool/)**                                      | Tool for generating advanced Google Dork queries for security research and reconnaissance.     |
| **[CSRF PoC Generator](https://0xincainsider.github.io/CSRF-POC-GENERATOR/)**                      | Generates CSRF Proofs of Concept for authorized security testing and vulnerability validation. |
| **[Hackbar — Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/0xhaise-hackbar/)** | Firefox extension for manipulating HTTP requests during web security testing.                  |
| **[Firefox Security Toolkit](https://github.com/0xincainsider/firefox-security-toolkit-in-bash)**  | Security-focused Bash tooling for Firefox privacy and web application testing workflows.       |
| **[2FA Bypass Labs](https://github.com/0xincainsider/2fa-bypass-labs)**                            | Intentionally vulnerable laboratory for studying authentication and 2FA security.              |
| **[DOM Dojo](https://0xincainsider.github.io/DOM-Dojo/)**                                          | Hands-on vulnerable laboratory focused on DOM-based XSS.                                       |
| **[Burp Suite Extensions](https://0xincainsider.github.io/BurpsuiteExtensions/)**                  | Searchable and categorized directory of Burp Suite extensions for penetration testing.         |

---

# AI Engineering

Exploring the intersection between software engineering, automation and cybersecurity through AI.

Areas of interest:

* Agentic software development.
* Multi-agent orchestration.
* Tool calling.
* **Model Context Protocol (MCP)**.
* AI-assisted security workflows.
* LLM application development.
* Automated development workflows.

Technologies and tools:

`Claude Code` `OpenAI` `Gemini` `Open-Source LLMs` `MCP` `n8n` `OpenClaw`

---

# DevSecOps Philosophy

I approach security as an engineering concern rather than a final-stage audit.

```text
Requirements
     ↓
Architecture
     ↓
Secure Development
     ↓
Automated Testing
     ↓
SAST / DAST
     ↓
CI/CD
     ↓
Deployment
     ↓
Monitoring
     ↓
Security Testing
     ↓
Remediation
```

The goal is to make security **repeatable, measurable and integrated into the software lifecycle**.

---

# Engineering Principles

* **Security by design**
* **Least privilege**
* **Deny by default**
* **Defense in depth**
* **Automate repetitive work**
* **Test security continuously**
* **Measure before optimizing**
* **Reproduce vulnerabilities before fixing them**
* **Treat infrastructure as code**
* **Prefer explicit authorization over implicit trust**

---

# Education 

**Systems Engineering** · 2022 — Present

Relevant areas:

`Software Engineering` `Databases` `OOP` `UML`

`Computer Networks` `Operating Systems`

`Web Development` `Mobile Development`

`Information Security` `Software Quality`

**Languages**

* Spanish — Native
* English — Advanced

---

# GitHub & Development

<a href="https://github.com/0xincainsider">
  <img src="https://img.shields.io/badge/GitHub-0xincainsider-black?style=for-the-badge&logo=github" alt="GitHub">
</a>

<a href="https://gitroll.io/profile/u9QN0iJW8SzWU8TpIxqfeq630Il52">
  <img src="https://gitroll.io/api/badges/profiles/v1/u9QN0iJW8SzWU8TpIxqfeq630Il52?theme=light" alt="GitRoll Profile Badge">
</a>
 
---

## GitHub Metrics

[<img align="left" width="390" alt="📗 Classic" src="./metrics.classic.svg">](#)
[<img align="right" width="390" alt="🌸 Anilist " src="./metrics.plugin.anilist.svg">](#)
 
[<img align="left" width="390" alt="📅 Isometric calendar" src="./metrics.plugin.isocalendar.svg">](#)
 
[<img width="100%" height="1" alt="separator" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/placeholder.svg">](#)

