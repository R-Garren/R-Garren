# Hi, I'm River Garren 👋

<a href="https://www.linkedin.com/in/river-garren-1aa985409/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

Cyber Defense student at Roane State Community College (AAS, Computer Information Technology, expected May 2027) and holder of **CompTIA Security+** and **Network+**. I run a self-hosted home lab where I build, break, monitor, and document real services, and I treat it as infrastructure as code so I can rebuild it from scratch.

## 🎯 Objective

My goal is to land an **entry-level SOC or NOC Analyst** role. I bring hands-on Linux and Windows Server administration, DNS/DHCP troubleshooting, and Ansible automation, plus a background in shift work where keeping a service running (and fixing it fast when it broke) was my job.

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

## 🎓 Education

**AAS, Computer Information Technology – Cyber Defense** · Roane State Community College · *Expected May 2027*
CIT Program GPA 4.00 · President's List (Fall 2025, Spring 2026)
Coursework: Network Security, Principles of Information Assurance, Windows Server Administration, Digital Forensics (in progress)

## 📫 Let's Connect

I'm open to SOC/NOC analyst opportunities. The fastest way to reach me is on [LinkedIn](https://www.linkedin.com/in/river-garren-1aa985409/).

## 🗺️ Roadmap

Each step builds on my home lab and on the step before it: attack the lab, detect it, investigate it, and recover from it.

🔄 In progress · ⏳ Up next · ✅ Done

<!-- When you start a project, swap "Coming soon" for a link, e.g. <a href="https://github.com/R-Garren/REPO-NAME">REPO-NAME</a>, and update its status emoji. -->

| Step | Project | Skills it builds | Repo |
|:----:|---------|------------------|------|
| 1 | 🔄 **Wazuh SIEM:** collect logs from all lab hosts | SIEM, log monitoring | <a href="https://github.com/R-Garren/homelab-iac/tree/main/siem">homelab-iac / siem</a> |
| 2 | ⏳ **Attack & investigate:** run SSH brute force, Nmap scans, and file changes from Kali, then trace each alert in Wazuh | Alert triage, MITRE ATT&CK, incident write-ups | *Coming soon* |
| 3 | ⏳ **Packet analysis:** capture step 2's traffic in Wireshark and pick out scan and brute-force patterns ⭐ | Wireshark, packet analysis | *Coming soon* |
| 4 | ⏳ **Firewall + IDS:** OPNsense with Suricata in front of the lab, VLAN segmentation, alerts sent to Wazuh | Firewalls, IDS/IPS, segmentation | *Coming soon* |
| 5 | ⏳ **Splunk alongside Wazuh:** same logs into both SIEMs, one dashboard and one alert | Splunk, SPL, detection rules | *Coming soon* |
| 6 | ⏳ **Disaster recovery:** back up, break, restore, and time a service, then write the runbook | Backup & recovery, runbooks | *Coming soon* |
| 7 | ⏳ **Blue-team labs:** 5–10 CyberDefenders / Blue Team Labs Online investigations with write-ups | DFIR, investigation | *Coming soon* |
| 8 | ⏳ **Vulnerability triage:** case notes on CISA KEV entries, plus Wazuh vulnerability detection and CIS checks ⭐ | Vulnerability management, CVSS, CIS | *Coming soon* |
| 9 | ⏳ **Scripting toolkit:** SSH brute-force detector, PowerShell account audit, Bash service-health check ⭐ | Bash, PowerShell, Python | *Coming soon* |
| 10 | ⏳ **Microsoft Sentinel:** connect a VM, find sign-in events, write a detection rule (SC-200 path) | Cloud SIEM, KQL | *Coming soon* |
| 11 | ⏳ **AI alert triage:** local LLM (Ollama) that summarizes and prioritizes Wazuh alerts | Automation, AI-assisted SOC | *Coming soon* |

⭐ Builds on a project from [CarterPerez-dev/Cybersecurity-Projects](https://github.com/CarterPerez-dev/Cybersecurity-Projects).
