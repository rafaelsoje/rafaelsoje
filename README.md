# Rafael Soje

<p align="left">
  <a href="https://rafaelsoje.com"><img src="https://img.shields.io/badge/Portfolio-rafaelsoje.com-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/rafaelsoje"><img src="https://img.shields.io/badge/LinkedIn-Rafael_Soje-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:contato@rafaelsoje.com"><img src="https://img.shields.io/badge/Email-contato@rafaelsoje.com-1e293b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open_Source-Upstream_Contributor-0ea5e9?style=for-the-badge" alt="Upstream Contributor" />
  <img src="https://img.shields.io/badge/Status-Available_for_Projects-success?style=for-the-badge" alt="Available" />
</p>

---

### Linux Systems Engineer | DevSecOps | Full-Stack & Cloud

Bachelor of Science in **Computer Science** and Postgraduate in **Information Security**.

Specialized in architecting resilient enterprise systems, high-availability Linux infrastructure automation, and perimeter defensive security:

* **Infrastructure & Linux Engineering:** Advanced server and VPS administration, automation via Shell Scripting, Systemd service orchestration, and automated backup pipelines with cryptographic SHA-256 integrity verification.
* **Defensive Security & DevSecOps:** Linux server hardening, Host-based Intrusion Detection (HIDS), automated abuse mitigation, and perimeter edge integration (Cloudflare WAF + Fail2ban + ModSecurity).
* **Application Engineering:** Resilient enterprise platforms, real-time operational telemetry dashboards, and secure RESTful APIs built with TypeScript, Python, and PHP.
* **Official Platform:** [rafaelsoje.com](https://rafaelsoje.com)

---

### Open Source Contributions

Upstream technical contributions merged and under review across global security, compliance, and Linux infrastructure ecosystems:

#### Defensive Security, Hardening & SIEM
* **[Fail2ban](https://github.com/fail2ban/fail2ban)** — Intrusion Prevention System (IPS) (+4,500 stars)  
  [Pull Request #4259 (Merged)](https://github.com/fail2ban/fail2ban/pull/4259) & [Pull Request #4262 (Merged)](https://github.com/fail2ban/fail2ban/pull/4262): New official filter and jail for automated brute-force mitigation on the Authelia authentication provider, supporting log files, structured JSON, and `systemd-journal` (resolving historical Issue #4005).  
  [Pull Request #4258](https://github.com/fail2ban/fail2ban/pull/4258): Support for systemd journal log ingestion in the `nginx-bad-request` filter (Issue #3732).

* **[SigmaHQ](https://github.com/SigmaHQ/sigma)** — Global Threat Detection Rule Standard (+11,300 stars)  
  [Pull Request #6542](https://github.com/SigmaHQ/sigma/pull/6542): Threat detection rule for `tar` utility abuse in command execution and shell escapes (`--checkpoint-action=exec` and `--to-command`), covering GTFOBins techniques and wildcard injection (MITRE ATT&CK T1059.004 and T1548.003).

* **[CISOfy Lynis](https://github.com/CISOfy/lynis)** — Security Auditing & Linux Hardening (+16,500 stars)  
  [Pull Request #1789](https://github.com/CISOfy/lynis/pull/1789): Support for Chrony configuration files in `/usr/etc` and `conf.d` subdirectories, eliminating NTP false positives on modern Linux distributions (Issue #1787).  
  [Pull Request #1805](https://github.com/CISOfy/lynis/pull/1805): Audit logic fix for task schedulers (`SCHD-7704`), ensuring accurate validation of files in `cron.d` and crontab permissions (Issue #1798).  
  [Pull Request #1806](https://github.com/CISOfy/lynis/pull/1806): OS detection for Ultramarine Linux in core release-detection routines (Issue #1804).  
  [Pull Request #1807](https://github.com/CISOfy/lynis/pull/1807): Fix in blacklist module test `FILE-6430`, resolving globbing expansion and directory traversal in `/usr/lib/modprobe.d/` (Issue #1794).

* **[Dev-Sec Hardening Collection](https://github.com/dev-sec/ansible-collection-hardening)** — Ansible CIS Benchmarks Automation (+5,500 stars)  
  [Pull Request #999](https://github.com/dev-sec/ansible-collection-hardening/pull/999): Implementation of post-quantum hybrid algorithm (`mlkem768x25519-sha256`) for OpenSSH 9.9+, modernizing KEX cryptographic negotiation (Issue #925).

* **[CrowdSec Hub](https://github.com/crowdsecurity/hub)** — Collaborative IPS & Threat Intelligence (+10,000 stars)  
  [Pull Request #1951 (Merged)](https://github.com/crowdsecurity/hub/pull/1951): Parser and detection scenario for PostgreSQL brute-force attacks via PgBouncer connection pooler with SASL authentication support (Issue #1881).  
  [Pull Request #1975](https://github.com/crowdsecurity/hub/pull/1975): Support for `h2c://` (HTTP/2 Cleartext) backend URLs in official Traefik log parser (Issue #1966).

* **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** — High-Performance System Information Tool (+25,200 stars)  
  [Pull Request #2702](https://github.com/fastfetch-cli/fastfetch/pull/2702): ASCII art logo and official distro detection for Visnux Linux (Issue #2700).

#### Offensive Security & Attack Surface Engineering
* **[ProjectDiscovery Nuclei-Templates](https://github.com/projectdiscovery/nuclei-templates)** — Vulnerability & Asset Detection Engineering (+18,500 stars)  
  [Pull Request #17604 (Merged)](https://github.com/projectdiscovery/nuclei-templates/pull/17604): Official detection template for Infisical secrets manager dashboard and endpoints via high-precision DSL matchers.  
  [Pull Request #17606 (Merged)](https://github.com/projectdiscovery/nuclei-templates/pull/17606): Official detection template for exposed Coolify PaaS panels with Shodan & FOFA search queries.

#### Canonical Systems Documentation & Open Data
* **[tldr-pages](https://github.com/tldr-pages/tldr)** — Practical Command-Line Documentation (+50,000 stars)  
  [Pull Request #24928 (Merged)](https://github.com/tldr-pages/tldr/pull/24928), [PR #24929 (Merged)](https://github.com/tldr-pages/tldr/pull/24929), [PR #24930 (Merged)](https://github.com/tldr-pages/tldr/pull/24930), [PR #24941 (Merged)](https://github.com/tldr-pages/tldr/pull/24941), [PR #24993 (Merged)](https://github.com/tldr-pages/tldr/pull/24993), [PR #24994 (Merged)](https://github.com/tldr-pages/tldr/pull/24994), [PR #24996 (Merged)](https://github.com/tldr-pages/tldr/pull/24996), [PR #24997 (Merged)](https://github.com/tldr-pages/tldr/pull/24997) & [PR #25017 (Merged)](https://github.com/tldr-pages/tldr/pull/25017): Canonical documentation and technical standards for `rclone`, `fail2ban-client`, `nuclei`, WireGuard (`wg`/`wg-quick`), Linux kernel audit subsystem (`auditctl`/`ausearch`), and `lynis`.

* **[BrasilAPI](https://github.com/BrasilAPI/BrasilAPI)** (+8,500 stars) & **[Querido Diário / OKFN](https://github.com/okfn-brasil/querido-diario)** (+2,000 stars)  
  Test suite resilience enhancements ([PR #938](https://github.com/BrasilAPI/BrasilAPI/pull/938), [PR #939](https://github.com/BrasilAPI/BrasilAPI/pull/939)) and automated government data scraper engineering ([PR #1590](https://github.com/okfn-brasil/querido-diario/pull/1590), [PR #1591](https://github.com/okfn-brasil/querido-diario/pull/1591)).

---

### Tech Stack & Tools

#### **Development & Back-End**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.x-777BB4?style=flat-square&logo=php&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00618C?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

#### **Infrastructure, DevSecOps & Security**
![Linux](https://img.shields.io/badge/Linux-Ubuntu_/_Debian-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Scripting_/_Automation-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy_/_WAF-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-DNS_/_WAF_/_Edge-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Fail2Ban](https://img.shields.io/badge/Fail2Ban-Hardening-red?style=flat-square)
![Systemd](https://img.shields.io/badge/Systemd-Services_/_Daemon-grey?style=flat-square&logo=linux&logoColor=white)
![ModSecurity](https://img.shields.io/badge/ModSecurity-OWASP_CRS-blue?style=flat-square)
![WireGuard](https://img.shields.io/badge/WireGuard-VPN-88171A?style=flat-square&logo=wireguard&logoColor=white)

---

### Featured Repositories

* **[rclone-sync-manager](https://github.com/rafaelsoje/rclone-sync-manager)**  
  Cross-platform (Linux & Windows) desktop sync application built with Python and PySide6, featuring SQLite audit history and seamless cloud storage provider integration via Rclone.

* **[gabarita](https://github.com/rafaelsoje/gabarita)**  
  Public examination prep SaaS platform featuring study planning, practice exams, gazette monitoring, and hybrid AI (OpenAI + local Ollama) built with Next.js 15, PostgreSQL, and Prisma.

* **[linux-sysadmin-toolbox](https://github.com/rafaelsoje/linux-sysadmin-toolbox)**  
  Modular Linux administration and DevSecOps toolbox: OpenSSH hardening & compliance (CIS Benchmarks), automated GFS backups with SHA-256 integrity, port/package HIDS, File Integrity Monitoring (FIM), Fail2ban + Cloudflare WAF integration, and AbuseIPDB sync. Selected for the official XERJ Corpus Hub (+18k stars) as canonical reference code for AI agents.

* **[infosec-audit-tools](https://github.com/rafaelsoje/infosec-audit-tools)**  
  Information security and reconnaissance tools built with Python: asynchronous attack surface enumeration via RDAP/DNS, HTTP security headers defensive auditing, and compliance validation.

* **[nexus](https://github.com/rafaelsoje/nexus)**  
  API-first event freelancer marketplace monorepo built with NestJS, Next.js, financial split architecture, platform escrow, and E2E testing with Playwright.

* **[gestao-operacional-eventos](https://github.com/rafaelsoje/gestao-operacional-eventos)**  
  Enterprise event operations management platform built with PHP and MySQL, featuring operational planning, power generator telemetry, inventory control, and billing workflows.

* **[rafaelsoje.com](https://github.com/rafaelsoje/rafaelsoje.com)**  
  Source code and architecture of the official personal platform built with Next.js 15, TypeScript, and Tailwind CSS, featuring continuous atomic deployments and first-party telemetry.

---

<p align="center">
  <sub>Architecting systems focused on high availability, clean code, and rigorous security engineering.</sub><br>
  <b><a href="https://rafaelsoje.com">rafaelsoje.com</a> • Rio de Janeiro, Brazil</b>
</p>
