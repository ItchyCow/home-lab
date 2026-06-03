# 🛡️ Cybersecurity Learning Lab — Kiara Vicencio

> A documented 6-month hands-on journey in the hopes of transitioning from Technical Support & Risk Analysis into a **Security Analyst / Vulnerability Analyst** role. This repository contains lab notes, scan reports, scripts, diagrams, and write-ups built from real practice environments.

---

## 👩‍💻 About Me

I'm a cybersecurity professional based in the Philippines with experience in **attack surface monitoring, risk validation, and technical support** at UpGuard (Sydney, AU) and vulnerability assessment consulting at SGV & Co. (EY Philippines).

This lab documents my structured upskilling roadmap — bridging operational security experience with deeper technical depth in systems administration, vulnerability management, cloud hardening, and compliance frameworks.

**Current role:** Technical Support Analyst (Remote) — UpGuard  
**Target roles:** Security Analyst · SOC L1   
**Certifications:** Certified in Cybersecurity (ISC²)

📧 kiarabvicencio@gmail.com  
🔗 [linkedin.com/in/kiaravicencio](https://linkedin.com/in/kiaravicencio)

---

## 🗂️ Repository Structure

```
cybersec-lab/
│
├── month-1-os-networking/
│   ├── network-diagram.png
│   ├── home-lab-setup.md
│   ├── active-directory-setup.md
│   └── packet-capture-analysis.md
│
├── month-2-vuln-scanning/
│   ├── dvwa-scan-report.pdf
│   ├── cvss-scoring-exercise.md
│   └── nessus-vs-openvas-comparison.md
│
├── month-3-web-app-security/
│   ├── juice-shop-findings.md
│   ├── auth-misconfiguration-lab.md
│   └── tls-audit-report.md
│
├── month-4-cloud-hardening/
│   ├── aws-misconfiguration-lab.md
│   ├── cis-benchmark-report.md
│   └── ansible-hardening-playbook/
│
├── month-5-compliance-reporting/
│   ├── va-engagement-report.pdf
│   ├── risk-register.xlsx
│   └── nist-csf-self-assessment.md
│
├── month-6-portfolio-jobs/
│   ├── ctf-writeups/
│   └── interview-prep-notes.md
│
└── README.md
```

---

## 📅 6-Month Roadmap Overview

| Month | Focus Area | Key Tools | Status |
|-------|-----------|-----------|--------|
| 1 | OS Internals & Networking | Wireshark, VirtualBox, PowerShell, journalctl | 🔄 In progress |
| 2 | Vulnerability Scanning & CVSS | Nessus, OpenVAS, Nmap NSE, Shodan | ⏳ Upcoming |
| 3 | Web App Security & Identity | Burp Suite, OWASP ZAP, testssl.sh | ⏳ Upcoming |
| 4 | Cloud Infrastructure & Hardening | AWS, Terraform, Ansible, Lynis | ⏳ Upcoming |
| 5 | Compliance & Reporting | NIST CSF, OpenSCAP, Dradis, DefectDojo | ⏳ Upcoming |
| 6 | Portfolio Polish & Job Readiness | TryHackMe, HTB, GitHub Pages | ⏳ Upcoming |

---

## 🧪 Lab Environment

**Virtualised home lab** running three VMs on VirtualBox:

| VM | OS | IP Address | Role |
|----|----|------------|------|
| VM1 | Ubuntu Server 22.04 | 192.168.1.10 | Linux sysadmin practice, AD client |
| VM2 | Windows 11 Pro | 192.168.1.11 | Active Directory domain controller |
| VM3 | Kali Linux | 192.168.1.12 | Scanning, exploitation, recon |

**Network:** NAT network (192.168.1.0/24) with internet access via VirtualBox NAT gateway.  
**Host machine:** macOS 26.3

---

## 🔍 Skills Being Developed

**Technical**
- Linux & Windows Server administration (AD DS, GPOs, systemd, auditd)
- Vulnerability scanning and triage (Nessus, OpenVAS, Nmap NSE)
- Web application security testing (Burp Suite, OWASP Top 10, JWT attacks)
- Cloud security and hardening (AWS IAM, CIS Benchmarks, Ansible)
- CVSS scoring, risk registers, and remediation tracking
- Compliance frameworks: NIST CSF, ISO 27001, PCI-DSS

**Soft Skills**
- Executive summary writing and technical reporting
- Vulnerability prioritisation and remediation SLA tracking
- Cross-functional communication (translating findings into business risk)

---

## 📌 Prior Experience Highlights

**UpGuard — Technical Support Analyst** *(Jan 2024 – Present, Remote)*
- Daily investigation of risk/vulnerability alerts using Nmap, OpenSSL, cURL
- Troubleshot SSO failures, DNS misconfigurations, and platform auth issues
- ~95%+ CSAT with <1 min first response and <24h resolution targets

**Dashlabs.ai — Infrustructure and Security Intern** *(Sep-Nov 2022, Remote)*
- Collaborated with the Infrastructure and Security Team to set up SSH Keys and SSH Certificates.

**Perti Solutions — Quality Assurance Intern** *(Jun-Aug 2022, Remote)*
- Maintained strong overall quality control of software by performing tests on varying platforms, adhering to reliability, performance, and customer expectation.
- Found and reported major bugs, and offered suggestions to senior management to enhance the overall quality of the software.
- Developed Low and High Fidelity Wireframes for a web application using Figma.
- Managed and tracked other interns' projects and reported their progress to senior management.
- Provided Technical Support including but not limited to setting up meetings, reviewing and creating documents for Perti and its clients, chairing meetings, and setting up demonstrations.

**SGV & Co. (EY) — Cybersecurity Consulting Intern** *(Jan–May 2022, Remote)*
- OSINT and attack surface analysis across 50+ banks and 4 government agencies
- Tools: Nmap, DNSDumpster
- Synthesised findings into client-facing vulnerability assessment reports

**Domain & Security Lab** *(Personal Project)*
- Configured custom domain with Cloudflare DNS (A, MX, CNAME records)
- Implemented DNSSEC, HTTPS enforcement, HSTS, TLS 1.3
- Integrated into an Attack Surface Management platform and iterated on remediations

---

## 📜 Certifications & Courses

| Certification | Issuer | Status |
|--------------|--------|--------|
| Introduction to Networking | CISCO | ✅ Earned |
| Introduction to Cybersecurity | CISCO | ✅ Earned |
| Certified in Cybersecurity (CC) | ISC² | ✅ Earned |
| CompTIA Security+ | CompTIA | 🔄 In progress |

---

## 📝 How I Document My Work

Each lab folder contains:
- **Setup notes** — what I configured and why
- **Commands used** — with explanations, not just copy-paste
- **What went wrong** — troubleshooting steps and lessons learned
- **Findings / output** — scan results, reports, or screenshots
- **Key takeaways** — what I'd do differently next time

The goal is a portfolio that reflects real analytical thinking, not just tool execution.

---

*Last updated: May 2026*
