# Hi, I'm River Garren 👋

<a href="https://www.linkedin.com/in/river-garren-1aa985409/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/R-Garren/homelab-iac"><img src="https://img.shields.io/badge/-Homelab_Repo-181717?&style=for-the-badge&logo=github&logoColor=white" /></a>

Cyber Defense student at Roane State Community College (AAS, Computer Information Technology, expected May 2027) and holder of **CompTIA Security+** and **Network+**. I run a self-hosted home lab where I build, break, monitor, and document real services, and I treat it as infrastructure as code so I can rebuild it from scratch.

## 🎯 Objective

I'm looking for an **entry-level SOC or NOC Analyst** role. I bring hands-on Linux and Windows Server administration, DNS/DHCP troubleshooting, and Ansible automation, plus a background in shift work where keeping a service running (and fixing it fast when it broke) was my job. I'm comfortable with onsite and rotating-shift schedules.

## 🛠️ Skills

| Skill | Where I've used it |
|-------|--------------------|
| DNS & DHCP administration (Pi-hole + Unbound recursive resolver) | <a href="https://github.com/R-Garren/homelab-iac/tree/main/core">homelab-iac / core</a> |
| Reverse proxy & TLS/HTTPS (Nginx Proxy Manager) | <a href="https://github.com/R-Garren/homelab-iac/tree/main/core">homelab-iac / core</a> |
| Secure remote access (WireGuard VPN) | <a href="https://github.com/R-Garren/homelab-iac/tree/main/security">homelab-iac / security</a> |
| Configuration management & hardening with Ansible | <a href="https://github.com/R-Garren/homelab-iac/tree/main/ansible">homelab-iac / ansible</a> |
| Multi-container Docker environments (Compose, Portainer) | <a href="https://github.com/R-Garren/homelab-iac">homelab-iac</a> |
| Secrets management (`.env` files kept out of version control) | <a href="https://github.com/R-Garren/homelab-iac">homelab-iac</a> |
| Isolated vulnerable practice environment (DVWA + MariaDB) | <a href="https://github.com/R-Garren/homelab-iac/tree/main/lab">homelab-iac / lab</a> |
| SIEM log monitoring & alert review (Wazuh) | <a href="https://github.com/R-Garren/homelab-iac/tree/main/siem">homelab-iac / siem</a> *(in progress)* |
| Windows Server administration | Coursework: Windows Server Administration |
| Incident response fundamentals & NIST CSF | Coursework: Network Security, Principles of Information Assurance |

## 🧰 Tools

### Security Operations
<div>
    <img src="https://img.shields.io/badge/-Wazuh-3595F9?&style=for-the-badge&logo=wazuh&logoColor=white" />
    <img src="https://img.shields.io/badge/-WireGuard-88171A?&style=for-the-badge&logo=wireguard&logoColor=white" />
    <img src="https://img.shields.io/badge/-DVWA-4D4D4D?&style=for-the-badge&logoColor=white" />
</div>

### Networking
<div>
    <img src="https://img.shields.io/badge/-Pi--hole-96060C?&style=for-the-badge&logo=pihole&logoColor=white" />
    <img src="https://img.shields.io/badge/-Unbound-2A5B8C?&style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/-Nginx_Proxy_Manager-F15833?&style=for-the-badge&logo=nginxproxymanager&logoColor=white" />
</div>

### Systems & Automation
<div>
    <img src="https://img.shields.io/badge/-Linux-FCC624?&style=for-the-badge&logo=linux&logoColor=black" />
    <img src="https://img.shields.io/badge/-Ubuntu_Server-E95420?&style=for-the-badge&logo=ubuntu&logoColor=white" />
    <img src="https://img.shields.io/badge/-Windows_Server-0078D4?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-Ansible-EE0000?&style=for-the-badge&logo=ansible&logoColor=white" />
    <img src="https://img.shields.io/badge/-Python-3776AB?&style=for-the-badge&logo=python&logoColor=white" />
</div>

### Containers
<div>
    <img src="https://img.shields.io/badge/-Docker-2496ED?&style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/-Portainer-13BEF9?&style=for-the-badge&logo=portainer&logoColor=white" />
</div>

## 📜 Certifications

<div>
    <img src="https://img.shields.io/badge/-CompTIA_Security%2B-C8202F?&style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/-CompTIA_Network%2B-007ACC?&style=for-the-badge&logoColor=white" />
</div>

## 🚀 Projects

### [homelab-iac](https://github.com/R-Garren/homelab-iac) — Reproducible Home Lab Infrastructure
A self-hosted lab on an always-on Ubuntu server, defined with Docker Compose and Ansible so it can be rebuilt from scratch.

- **Core network services:** network-wide DNS and DHCP through Pi-hole, with Unbound as a private recursive resolver
- **Reduced attack surface:** self-hosted services sit behind Nginx Proxy Manager with HTTPS; remote access goes through WireGuard
- **Automation:** Ansible playbooks for provisioning, updates, and hardening (in progress)
- **Practice range:** an isolated DVWA + MariaDB environment for safely testing attacks
- **Documentation:** every config change and fix is written down so services can be recovered consistently

**Roadmap**
1. ✅ Infrastructure as code: Compose services, secrets out of version control
2. 🔄 SIEM: Wazuh ingesting logs from the core services
3. ⏳ AI-assisted alert triage: a local LLM (Ollama) that summarizes and prioritizes Wazuh alerts
4. ⏳ VLAN segmentation for the lab network

## 🎓 Education

**AAS, Computer Information Technology – Cyber Defense** · Roane State Community College · *Expected May 2027*
CIT Program GPA 4.00 · President's List (Fall 2025, Spring 2026)
Coursework: Network Security, Principles of Information Assurance, Windows Server Administration, Digital Forensics (in progress)

## 📫 Let's Connect

I'm open to SOC/NOC analyst opportunities. The fastest way to reach me is on [LinkedIn](https://www.linkedin.com/in/river-garren-1aa985409/).
