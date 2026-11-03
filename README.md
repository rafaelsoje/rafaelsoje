# Rafael Soje

<p align="left">
  <a href="https://rafaelsoje.com"><img src="https://img.shields.io/badge/Portfólio-rafaelsoje.com-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio" /></a>
  <a href="https://linkedin.com/in/rafaelsoje"><img src="https://img.shields.io/badge/LinkedIn-Rafael_Soje-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:contato@rafaelsoje.com"><img src="https://img.shields.io/badge/E--mail-contato@rafaelsoje.com-1e293b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open_Source-Upstream_Contributor-0ea5e9?style=for-the-badge" alt="Upstream Contributor" />
  <img src="https://img.shields.io/badge/Status-Disponível_para_Projetos-success?style=for-the-badge" alt="Disponível" />
</p>

---

### Engenheiro de Sistemas Linux | DevSecOps | Full Stack & Cloud

Bacharel em **Ciência da Computação** e pós-graduado em **Segurança da Informação**.

Minha atuação é focada em projetar e implementar sistemas corporativos robustos, automação de infraestruturas Linux em alta disponibilidade e segurança defensiva perimetral:

* **Engenharia de Infraestrutura & Linux:** Administração avançada de servidores e VPS, automação de rotinas em Shell Script, orquestração via Systemd e contingência de backups com integridade criptográfica SHA-256.
* **Segurança Defensiva & DevSecOps:** Hardening de servidores Linux, sistemas de detecção de intrusão no host (HIDS), mitigação ativa de abusos e integração de regras de borda (Cloudflare WAF + Fail2ban + ModSecurity).
* **Desenvolvimento de Aplicações:** Construção de sistemas corporativos, painéis operacionais com métricas em tempo real, APIs seguras e plataformas resilientes utilizando TypeScript, Python e PHP.
* **Plataforma Oficial:** [rafaelsoje.com](https://rafaelsoje.com)

---

### Contribuições Open Source

Contribuições técnicas aceitas e em análise nos principais ecossistemas globais de segurança da informação, auditoria e infraestrutura Linux:

#### Segurança Defensiva, Hardening & SIEM
* **[Fail2ban](https://github.com/fail2ban/fail2ban)** — Sistema de Prevenção de Intrusão (IPS) (+4.500 estrelas)  
  [Pull Request #4259 (Merged)](https://github.com/fail2ban/fail2ban/pull/4259) & [Pull Request #4262](https://github.com/fail2ban/fail2ban/pull/4262): Novo filtro oficial e jail para mitigação automatizada de ataques de força bruta no provedor de autenticação Authelia, com suporte a logs de arquivo, JSON estruturado e `systemd-journal` (resolvendo a Issue histórica #4005).  
  [Pull Request #4258](https://github.com/fail2ban/fail2ban/pull/4258): Suporte à captura de logs no formato journal do systemd para o filtro `nginx-bad-request` (Issue #3732).

* **[SigmaHQ](https://github.com/SigmaHQ/sigma)** — Padrão Global de Regras de Detecção de Ameaças (+11.300 estrelas)  
  [Pull Request #6542](https://github.com/SigmaHQ/sigma/pull/6542): Regra de detecção para abuso do utilitário `tar` na execução de comandos e quebra de shells (`--checkpoint-action=exec` e `--to-command`), cobrindo técnicas GTFOBins e injeção de wildcards (MITRE ATT&CK T1059.004 e T1548.003).

* **[CISOfy Lynis](https://github.com/CISOfy/lynis)** — Auditoria de Conformidade e Hardening Linux (+16.500 estrelas)  
  [Pull Request #1789](https://github.com/CISOfy/lynis/pull/1789): Suporte a arquivos de configuração do Chrony em `/usr/etc` e diretórios `conf.d`, eliminando falsos positivos de NTP em distribuições Linux modernas (Issue #1787).  
  [Pull Request #1805](https://github.com/CISOfy/lynis/pull/1805): Correção na lógica de auditoria de agendadores (`SCHD-7704`), garantindo validação precisa de arquivos em `cron.d` e permissões de crontab (Issue #1798).  
  [Pull Request #1806](https://github.com/CISOfy/lynis/pull/1806): Detecção de sistema operacional para Ultramarine Linux na rotina de descoberta de SO (Issue #1804).  
  [Pull Request #1807](https://github.com/CISOfy/lynis/pull/1807): Correção no teste `FILE-6430` de módulos em blacklist, resolvendo expansão de glob no shell e busca em `/usr/lib/modprobe.d/` (Issue #1794).

* **[Dev-Sec Hardening Collection](https://github.com/dev-sec/ansible-collection-hardening)** — Automação de CIS Benchmarks em Ansible (+5.500 estrelas)  
  [Pull Request #999](https://github.com/dev-sec/ansible-collection-hardening/pull/999): Implementação de algoritmo híbrido pós-quântico (`mlkem768x25519-sha256`) para OpenSSH 9.9+, modernizando a negociação criptográfica KEX (Issue #925).

* **[CrowdSec Hub](https://github.com/crowdsecurity/hub)** — IPS Colaborativo e Inteligência de Ameaças (+10.000 estrelas)  
  [Pull Request #1951 (Merged)](https://github.com/crowdsecurity/hub/pull/1951): Parser e cenário de detecção de ataques de força bruta no PostgreSQL através do pooler PgBouncer com suporte a autenticação SASL (Issue #1881).  
  [Pull Request #1975](https://github.com/crowdsecurity/hub/pull/1975): Suporte a URLs de backend com esquema `h2c://` (HTTP/2 Cleartext) no parser oficial de logs do Traefik (Issue #1966).

* **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** — Ferramenta de Informações de Sistema em Alta Performance (+25.200 estrelas)  
  [Pull Request #2702](https://github.com/fastfetch-cli/fastfetch/pull/2702): Adição do logotipo ASCII e identificação oficial da distribuição Visnux Linux (Issue #2700).

#### Segurança Ofensiva & Análise de Superfície de Ataque
* **[ProjectDiscovery Nuclei-Templates](https://github.com/projectdiscovery/nuclei-templates)** — Engenharia de Detecção de Vulnerabilidades e Ativos (+18.500 estrelas)  
  [Pull Request #17604 (Merged)](https://github.com/projectdiscovery/nuclei-templates/pull/17604): Template oficial de detecção do painel e endpoints do gerenciador de credenciais Infisical via DSL matchers de alta precisão (integrado à base de regras oficial).  
  [Pull Request #17606](https://github.com/projectdiscovery/nuclei-templates/pull/17606): Template oficial para identificação de painéis PaaS Coolify expostos, integrado com consultas para Shodan e FOFA.

#### Documentação Canônica de Sistemas & Dados Abertos
* **[tldr-pages](https://github.com/tldr-pages/tldr)** — Documentação Prática de Linha de Comando (+50.000 estrelas)  
  [Pull Request #24928 (Merged)](https://github.com/tldr-pages/tldr/pull/24928): Tradução e localização técnica das rotinas de auditoria do `lynis`.  
  [Pull Request #24929 (Merged)](https://github.com/tldr-pages/tldr/pull/24929): Tradução e padronização dos comandos do `fail2ban-client` (revisado e aprovado com destaque de clareza pelo mantenedor).  
  [Pull Request #24930 (Merged)](https://github.com/tldr-pages/tldr/pull/24930): Tradução e padronização dos parâmetros de auditoria do `nuclei`.  
  [Pull Request #24941 (Merged)](https://github.com/tldr-pages/tldr/pull/24941): Inclusão do comando global de auditoria `fail2ban-client status` e refinamento conceitual na documentação canônica em inglês (incorporado à base oficial).  
  [Pull Request #24993](https://github.com/tldr-pages/tldr/pull/24993) & [Pull Request #24994](https://github.com/tldr-pages/tldr/pull/24994): Documentação canônica em português dos utilitários de VPN `wg` e `wg-quick` (WireGuard).  
  [Pull Request #24996](https://github.com/tldr-pages/tldr/pull/24996) & [Pull Request #24997](https://github.com/tldr-pages/tldr/pull/24997): Documentação canônica do sincronizador de nuvem `rclone` e do subsistema de auditoria do kernel Linux `auditctl`.

* **[BrasilAPI](https://github.com/BrasilAPI/BrasilAPI)** (+8.500 estrelas) & **[Querido Diário / OKFN](https://github.com/okfn-brasil/querido-diario)** (+2.000 estrelas)  
  Melhorias de resiliência em baterias de testes ([PR #938](https://github.com/BrasilAPI/BrasilAPI/pull/938), [PR #939](https://github.com/BrasilAPI/BrasilAPI/pull/939)) e engenharia de spiders de coleta de dados governamentais ([PR #1590](https://github.com/okfn-brasil/querido-diario/pull/1590), [PR #1591](https://github.com/okfn-brasil/querido-diario/pull/1591)).

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
![Bash](https://img.shields.io/badge/Bash-Scripting_/_Automação-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy_/_WAF-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-DNS_/_WAF_/_Edge-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Fail2Ban](https://img.shields.io/badge/Fail2Ban-Hardening-red?style=flat-square)
![Systemd](https://img.shields.io/badge/Systemd-Services_/_Daemon-grey?style=flat-square&logo=linux&logoColor=white)
![ModSecurity](https://img.shields.io/badge/ModSecurity-OWASP_CRS-blue?style=flat-square)
![WireGuard](https://img.shields.io/badge/WireGuard-VPN-88171A?style=flat-square&logo=wireguard&logoColor=white)

---

### Repositórios em Destaque

* **[gabarita](https://github.com/rafaelsoje/gabarita)**  
  Plataforma SaaS para preparação de concursos públicos com planejamento de estudos, simulados, monitor de editais e IA híbrida (OpenAI + Ollama local) em Next.js 15, PostgreSQL e Prisma.

* **[nexus](https://github.com/rafaelsoje/nexus)**  
  Monorepo API-first para marketplace de freelancers de eventos com NestJS, Next.js, arquitetura de split financeiro, retenção de plataforma e testes E2E com Playwright.

* **[linux-sysadmin-toolbox](https://github.com/rafaelsoje/linux-sysadmin-toolbox)**  
  Caixa de ferramentas modular de administração Linux e DevSecOps: automação de backups GFS com integridade SHA-256, HIDS de portas, pacotes e integridade de arquivos (FIM), integração Fail2ban + Cloudflare WAF e sincronização com AbuseIPDB.

* **[infosec-audit-tools](https://github.com/rafaelsoje/infosec-audit-tools)**  
  Ferramentas de segurança da informação em Python: reconhecimento assíncrono de superfície de ataque via RDAP/DNS, auditoria defensiva de cabeçalhos HTTP e validação de conformidade.

* **[rclone-sync-manager](https://github.com/rafaelsoje/rclone-sync-manager)**  
  Aplicativo desktop de sincronização multiplataforma (Linux & Windows) em Python e PySide6 com SQLite e integração com provedores de Cloud Storage via Rclone.

* **[gestao-operacional-eventos](https://github.com/rafaelsoje/gestao-operacional-eventos)**  
  Plataforma corporativa de gestão operacional de eventos em PHP e MySQL, cobrindo planejamento, telemetria de geradores, controle de insumos e faturamento.

* **[rafaelsoje.com](https://github.com/rafaelsoje/rafaelsoje.com)**  
  Código-fonte e arquitetura da plataforma corporativa oficial em Next.js 15, TypeScript e Tailwind CSS com deploy atômico contínuo e telemetria first-party.

---

<p align="center">
  <sub>Construindo sistemas com foco em alta disponibilidade, código limpo e segurança rigorosa.</sub><br>
  <b><a href="https://rafaelsoje.com">rafaelsoje.com</a> • Rio de Janeiro, Brasil</b>
</p>
