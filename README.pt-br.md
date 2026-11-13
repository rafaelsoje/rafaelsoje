# Rafael Soje

<p align="left">
  <a href="https://rafaelsoje.com"><img src="https://img.shields.io/badge/Portf%C3%B3lio-rafaelsoje.com-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio" /></a>
  <a href="https://linkedin.com/in/rafaelsoje"><img src="https://img.shields.io/badge/LinkedIn-Rafael_Soje-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:contato@rafaelsoje.com"><img src="https://img.shields.io/badge/E--mail-contato@rafaelsoje.com-1e293b?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" /></a>
  <a href="https://hub.xerj.org/contributors/rafaelsoje"><img src="https://img.shields.io/badge/XERJ_Corpus_Hub-Contribuidor-7c3aed?style=for-the-badge&logo=rust&logoColor=white" alt="Contribuidor XERJ Corpus Hub" /></a>
  <img src="https://img.shields.io/badge/Open_Source-Contribuidor_Upstream-0ea5e9?style=for-the-badge" alt="Contribuidor Upstream" />
  <img src="https://img.shields.io/badge/Status-Dispon%C3%ADvel_para_Projetos-success?style=for-the-badge" alt="Disponível" />
</p>

[ [English Version](README.md) ] • [ Português ]

---

### Engenheiro de Sistemas Linux | DevSecOps | Full-Stack & Nuvem

Bacharel em **Ciência da Computação** e Pós-Graduado em **Segurança da Informação**.

Especializado na arquitetura de sistemas corporativos resilientes, automação de infraestrutura Linux em alta disponibilidade e segurança defensiva de perímetro:

* **Engenharia de Infraestrutura & Linux:** Administração avançada de servidores e VPS, automação via Shell Scripting, orquestração de serviços com Systemd e rotinas automatizadas de backup com verificação criptográfica de integridade SHA-256.
* **Segurança Defensiva & DevSecOps:** Hardening de servidores Linux, Detecção de Intrusão baseada em Host (HIDS), mitigação automatizada de abusos e integração defensiva de borda (Cloudflare WAF + Fail2ban + ModSecurity).
* **Engenharia de Aplicações:** Plataformas corporativas resilientes, painéis de telemetria operacional em tempo real e APIs RESTful seguras construídas com TypeScript, Python e PHP.
* **Plataforma Oficial:** [rafaelsoje.com](https://rafaelsoje.com)

---

### Contribuições Open Source & Memória de Referência para IA

Contribuições técnicas aceitas (*merged*) e em revisão em ecossistemas globais de segurança, conformidade e infraestrutura Linux:

#### Agentes de IA & Memória de Referência
* **[XERJ Corpus Hub](https://hub.xerj.org/contributors/rafaelsoje)** — Memória de Referência Aberta para Agentes Autônomos de Programação (+19.000 estrelas)  
  [Perfil Oficial de Contribuidor](https://hub.xerj.org/contributors/rafaelsoje): Selecionado como implementação de referência verificada para agentes autônomos de IA. O repositório [`linux-sysadmin-toolbox`](https://github.com/rafaelsoje/linux-sysadmin-toolbox) foi auditado e indexado como exemplo canônico para automação em Shell/Python, hardening CIS de Nginx, higiene de contêineres Docker e detecção de intrusão HIDS.  
  [![XERJ Corpus Hub Contributor](https://hub.xerj.org/contributors/rafaelsoje/badge.svg)](https://hub.xerj.org/contributors/rafaelsoje)

#### Segurança Defensiva, Hardening & SIEM
* **[Fail2ban](https://github.com/fail2ban/fail2ban)** — Sistema de Prevenção de Intrusão (IPS) (+4.500 estrelas)  
  [Pull Request #4259 (Mesclada)](https://github.com/fail2ban/fail2ban/pull/4259) & [Pull Request #4262 (Mesclada)](https://github.com/fail2ban/fail2ban/pull/4262): Novo filtro e jail oficial para mitigação de força bruta no provedor de autenticação Authelia, com suporte a arquivos de log, JSON estruturado e `systemd-journal` (resolvendo a Issue histórica #4005).  
  [Pull Request #4258](https://github.com/fail2ban/fail2ban/pull/4258): Suporte à ingestão de logs do systemd journal no filtro `nginx-bad-request` (Issue #3732).

* **[SigmaHQ](https://github.com/SigmaHQ/sigma)** — Padrão Global de Regras de Detecção de Ameaças (+11.300 estrelas)  
  [Pull Request #6542](https://github.com/SigmaHQ/sigma/pull/6542): Regra de detecção de ameaças contra o abuso do utilitário `tar` para execução de comandos e escapes de shell (`--checkpoint-action=exec` e `--to-command`), cobrindo técnicas GTFOBins e injeção de wildcards (MITRE ATT&CK T1059.004 e T1548.003).

* **[CISOfy Lynis](https://github.com/CISOfy/lynis)** — Auditoria de Segurança & Hardening Linux (+16.500 estrelas)  
  [Pull Request #1789](https://github.com/CISOfy/lynis/pull/1789): Suporte a arquivos de configuração do Chrony em subdiretórios `/usr/etc` e `conf.d`, eliminando falsos positivos de NTP em distribuições Linux modernas (Issue #1787).  
  [Pull Request #1805](https://github.com/CISOfy/lynis/pull/1805): Correção na lógica de auditoria de agendadores de tarefas (`SCHD-7704`), garantindo validação correta de permissões em `cron.d` e crontabs (Issue #1798).  
  [Pull Request #1806](https://github.com/CISOfy/lynis/pull/1806): Detecção oficial da distribuição Ultramarine Linux nas rotinas de identificação do sistema operacional (Issue #1804).  
  [Pull Request #1807](https://github.com/CISOfy/lynis/pull/1807): Correção no teste de blacklist `FILE-6430`, resolvendo expansão de globbing e directory traversal em `/usr/lib/modprobe.d/` (Issue #1794).

* **[Dev-Sec Hardening Collection](https://github.com/dev-sec/ansible-collection-hardening)** — Automação de CIS Benchmarks em Ansible (+5.500 estrelas)  
  [Pull Request #999](https://github.com/dev-sec/ansible-collection-hardening/pull/999): Implementação de algoritmo pós-quântico híbrido (`mlkem768x25519-sha256`) para OpenSSH 9.9+, modernizando a negociação criptográfica KEX (Issue #925).

* **[CrowdSec Hub](https://github.com/crowdsecurity/hub)** — IPS Colaborativo & Inteligência contra Ameaças (+10.000 estrelas)  
  [Pull Request #1951 (Mesclada)](https://github.com/crowdsecurity/hub/pull/1951): Parser e cenário de detecção de ataques de força bruta contra PostgreSQL via pooler PgBouncer com autenticação SASL (Issue #1881).  
  [Pull Request #1975](https://github.com/crowdsecurity/hub/pull/1975): Suporte a URLs de backend `h2c://` (HTTP/2 Cleartext) no parser oficial de logs do Traefik (Issue #1966).

* **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** — Ferramenta de Informações de Sistema em Alta Performance (+25.200 estrelas)  
  [Pull Request #2702](https://github.com/fastfetch-cli/fastfetch/pull/2702): Logo em arte ASCII e detecção de distribuição oficial para o Visnux Linux (Issue #2700).

#### Segurança Ofensiva & Engenharia de Superfície de Ataque
* **[ProjectDiscovery Nuclei-Templates](https://github.com/projectdiscovery/nuclei-templates)** — Engenharia de Detecção de Ativos e Vulnerabilidades (+18.500 estrelas)  
  [Pull Request #17604 (Mesclada)](https://github.com/projectdiscovery/nuclei-templates/pull/17604): Template oficial de detecção do gerenciador de segredos Infisical e endpoints via DSL de alta precisão.  
  [Pull Request #17606 (Mesclada)](https://github.com/projectdiscovery/nuclei-templates/pull/17606): Template oficial de detecção de painéis expostos do Coolify PaaS com queries Shodan e FOFA.

#### Documentação Canônica de Sistemas & Dados Abertos
* **[tldr-pages](https://github.com/tldr-pages/tldr)** — Documentação Prática de Linha de Comando (+50.000 estrelas)  
  [Pull Request #24928 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24928), [PR #24929 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24929), [PR #24930 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24930), [PR #24941 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24941), [PR #24993 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24993), [PR #24994 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24994), [PR #24996 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24996), [PR #24997 (Mesclada)](https://github.com/tldr-pages/tldr/pull/24997) e [PR #25017 (Mesclada)](https://github.com/tldr-pages/tldr/pull/25017): Padrões técnicos e documentação oficial para `rclone`, `fail2ban-client`, `nuclei`, WireGuard (`wg`/`wg-quick`), subsistema de auditoria do kernel Linux (`auditctl`/`ausearch`) e `lynis`.

* **[BrasilAPI](https://github.com/BrasilAPI/BrasilAPI)** (+8.500 estrelas) & **[Querido Diário / OKFN](https://github.com/okfn-brasil/querido-diario)** (+2.000 estrelas)  
  Melhorias de resiliência na suíte de testes ([PR #938](https://github.com/BrasilAPI/BrasilAPI/pull/938), [PR #939](https://github.com/BrasilAPI/BrasilAPI/pull/939)) e raspadores governamentais de diários oficiais ([PR #1590](https://github.com/okfn-brasil/querido-diario/pull/1590), [PR #1591](https://github.com/okfn-brasil/querido-diario/pull/1591)).

---

### Tecnologias & Ferramentas

#### **Desenvolvimento & Back-End**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.x-777BB4?style=flat-square&logo=php&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00618C?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

#### **Infraestrutura, DevSecOps & Segurança**
![Linux](https://img.shields.io/badge/Linux-Ubuntu_/_Debian-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Scripting_/_Automacao-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy_/_WAF-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-DNS_/_WAF_/_Edge-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Fail2Ban](https://img.shields.io/badge/Fail2Ban-Hardening-red?style=flat-square)
![Systemd](https://img.shields.io/badge/Systemd-Services_/_Daemon-grey?style=flat-square&logo=linux&logoColor=white)
![ModSecurity](https://img.shields.io/badge/ModSecurity-OWASP_CRS-blue?style=flat-square)
![WireGuard](https://img.shields.io/badge/WireGuard-VPN-88171A?style=flat-square&logo=wireguard&logoColor=white)

---

### Repositórios em Destaque

* **[rclone-sync-manager](https://github.com/rafaelsoje/rclone-sync-manager)**  
  Aplicação desktop multiplataforma (Linux e Windows) desenvolvida em Python e PySide6 para sincronização com histórico de auditoria SQLite e integração a provedores de nuvem via Rclone.

* **[gabarita](https://github.com/rafaelsoje/gabarita)**  
  Plataforma SaaS para preparação de concursos públicos com simulados, planos de estudo e inteligência artificial híbrida (OpenAI + Ollama local) construída com Next.js 15, PostgreSQL e Prisma.

* **[linux-sysadmin-toolbox](https://github.com/rafaelsoje/linux-sysadmin-toolbox)**  
  Caixa de ferramentas modular de administração Linux e DevSecOps: hardening e conformidade OpenSSH (CIS Benchmarks), backups GFS automatizados com SHA-256, HIDS de portas e pacotes, integridade de arquivos (FIM), integração Fail2ban + Cloudflare WAF e sincronização AbuseIPDB. Selecionado oficialmente para o XERJ Corpus Hub (+18k estrelas).

* **[infosec-audit-tools](https://github.com/rafaelsoje/infosec-audit-tools)**  
  Ferramentas de segurança da informação e reconhecimento desenvolvidas em Python: enumeração assíncrona de superfície de ataque via RDAP/DNS, auditoria defensiva de cabeçalhos de segurança HTTP e validação de conformidade.

* **[nexus](https://github.com/rafaelsoje/nexus)**  
  Monorepo de marketplace API-first para freelancers de eventos construído com NestJS, Next.js, arquitetura de split financeiro, custódia de pagamentos (escrow) e testes E2E com Playwright.

* **[gestao-operacional-eventos](https://github.com/rafaelsoje/gestao-operacional-eventos)**  
  Sistema de gestão operacional corporativa para o setor de eventos em PHP e MySQL, contemplando planejamento de escalas, telemetria de geradores, controle de estoque e fluxo de faturamento.

* **[rafaelsoje.com](https://github.com/rafaelsoje/rafaelsoje.com)**  
  Código-fonte e arquitetura da plataforma pessoal oficial desenvolvida em Next.js 15, TypeScript e Tailwind CSS, com deploys atômicos contínuos e telemetria própria.

---

<p align="center">
  <sub>Arquitetando sistemas focados em alta disponibilidade, código limpo e rigorosa engenharia de segurança.</sub><br>
  <b><a href="https://rafaelsoje.com">rafaelsoje.com</a> • Rio de Janeiro, Brasil</b>
</p>
