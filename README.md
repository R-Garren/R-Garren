# Hi, I'm River Garren 👋

<a href="https://www.linkedin.com/in/river-garren/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

I'm a Cyber Defense student at Roane State Community College (AAS in Computer Information Technology, May 2027) with **CompTIA Security+** and **Network+**. I learn by building. My home lab runs real network services that I deploy, secure, troubleshoot, and document. I'm now rebuilding the whole lab as code, in public, so it can be torn down and rebuilt from scratch with one command.

🔨 **Currently building:** [homelab-ansible](https://github.com/R-Garren/homelab-ansible): Week 0 of 12, mapping and re-addressing my home network

## 🎯 Objective

I'm looking for an **entry-level SOC, NOC, or IT role, or an internship**, where I can help keep systems running and secure. From my lab I bring hands-on Linux and Windows Server administration, DNS/DHCP troubleshooting, and Ansible automation. Before IT, I ran shifts as a key holder. My job was keeping service running and getting it back up fast when something broke. A SOC or NOC needs that same mindset.

## 🛠️ Skills

| Skill | Where I've used it |
|-------|--------------------|
| DNS & DHCP administration (Pi-hole + Unbound recursive resolver) | Pi-hole handles DNS and DHCP for my home network and forwards to Unbound, so no third-party resolver sees my lookups |
| Reverse proxy & TLS/HTTPS (Nginx Proxy Manager) | Nginx Proxy Manager handles HTTPS for internal services like Portainer, with admin UIs reachable from the LAN only |
| Configuration management & hardening with Ansible | Base-host playbook that installs packages, turns on automatic security updates, and sets up IP forwarding, tested on a VM before running on the production server |
| Multi-container Docker environments (Compose, Portainer) | Compose stacks for core services, VPN, and SIEM on separate Docker networks |
| Secure remote access (WireGuard VPN) | Containerized WireGuard server for remote access to the lab, with keys kept out of version control *(rebuilding in v2, Week 12)* |
| Secrets management | Service passwords kept out of version control in gitignored `.env` files *(moving to Ansible Vault in v2)* |
| SIEM log monitoring (Wazuh) | Started a Wazuh deployment collecting Pi-hole DNS logs, with custom rules for DNS tunneling (MITRE T1071.004) and DGA-style bursts (T1568.002) *(paused during the v2 rebuild)* |
| Windows Server administration | Coursework: Windows Server Administration |
| Incident response fundamentals & NIST CSF | Coursework: Network Security, Principles of Information Assurance |

Everything above except coursework comes from v1 of my home lab. I'm rebuilding it in public as [homelab-ansible](https://github.com/R-Garren/homelab-ansible), and each row will link to its proof as the matching week ships.

## 📜 Certifications

<div>
    <a href="https://www.credly.com/badges/2d1d0517-d85b-459f-987d-8de3c5e85553/public_url"><img src="https://img.shields.io/badge/-CompTIA_Security%2B-C8202F?&style=for-the-badge&logoColor=white" /></a>
    <a href="https://www.credly.com/badges/26264293-a4fa-48c6-8ae1-2e50ab663950/public_url"><img src="https://img.shields.io/badge/-CompTIA_Network%2B-007ACC?&style=for-the-badge&logoColor=white" /></a>
</div>

## 🚀 Projects

### [homelab-ansible](https://github.com/R-Garren/homelab-ansible) 🔄: Home Lab v2, Rebuilt as Code

My first lab (v1) worked, but too much of it was assembled by hand. v2 rebuilds it from scratch with Ansible, tested on a VirtualBox VM before it touches the production server, one milestone commit per week.

What's different in v2:

- **One-command build:** Ansible takes a bare Ubuntu Server 26.04 LTS install to running DNS, proxy, and management services
- **Ansible owns the host, Portainer owns the apps:** stacks deploy from Git, so Portainer has full control (fixing v1's "created outside of Portainer" limitation)
- **Security first:** SSH hardening, a default-deny firewall, secrets in Ansible Vault, Unbound reachable only from the host, admin panels kept off the LAN
- **Proof, not claims:** every week has a build log, decision records, and test results, including what broke and how I fixed it

| Week | Milestone | Status |
|:----:|-----------|:------:|
| 0 | Map the home network, remove a double NAT, re-address to a planned subnet and DHCP scope | 🔄 |
| 1–4 | Control node, Ansible fundamentals, hardened base role, Ansible Vault + Docker | ⏳ |
| 5–8 | Portainer, Pi-hole + Unbound with DNSSEC, Nginx Proxy Manager with a private CA, one-command build via the Portainer API | ⏳ |
| 9–10 | Backups, CI linting, a timed disaster-recovery drill, production cutover → **v2.0.0** | ⏳ |
| 11 | VLAN segmentation and Suricata IDS in an OPNsense lab, with tested firewall rules → **v2.1.0** | ⏳ |
| 12 | WireGuard remote access with Vault-managed keys → **v2.2.0** | ⏳ |

v1 (`homelab-iac`) is archived. v2's README explains what I changed and why.

## 🎓 Education

**AAS, Computer Information Technology – Cyber Defense** · Roane State Community College · *Expected May 2027*
CIT Program GPA 4.00 · President's List (Fall 2025, Spring 2026)
Coursework: Network Security, Principles of Information Assurance, Windows Server Administration, Digital Forensics (in progress)

## 📫 Let's Connect

I'm open to work and internship opportunities. The fastest way to reach me is on [LinkedIn](https://www.linkedin.com/in/river-garren/).

## 🗺️ Roadmap

Each step builds on my home lab and on the step before it: attack the lab, detect it, investigate it, and recover from it.

🔄 In progress · ⏳ Up next · ⏸️ Paused · ✅ Done

<!-- When you start a project, swap "Coming soon" for a link, e.g. <a href="https://github.com/R-Garren/REPO-NAME">REPO-NAME</a>, and update its status emoji. -->

| Step | Project | Skills it builds | Repo |
|:----:|---------|------------------|------|
| 0 | 🔄 **Home lab v2 rebuild:** the whole lab as code, built and tested week by week | Ansible, Linux, Docker, networking | [homelab-ansible](https://github.com/R-Garren/homelab-ansible) |
| 1 | ⏸️ **Wazuh SIEM:** collect logs from all lab hosts *(resumes after v2.0)* | SIEM, log monitoring | *Coming soon* |
| 2 | ⏳ **Attack & investigate:** run SSH brute force, Nmap scans, and file changes from Kali, then trace each alert in Wazuh | Alert triage, MITRE ATT&CK, incident write-ups | *Coming soon* |
| 3 | ⏳ **Packet analysis:** capture step 2's traffic in Wireshark and pick out scan and brute-force patterns ⭐ | Wireshark, packet analysis | *Coming soon* |
| 4 | ⏳ **Firewall + IDS:** OPNsense with Suricata in front of the lab, VLAN segmentation, alerts sent to Wazuh | Firewalls, IDS/IPS, segmentation | Part of [homelab-ansible](https://github.com/R-Garren/homelab-ansible) (Week 11) |
| 5 | ⏳ **Splunk alongside Wazuh:** same logs into both SIEMs, one dashboard and one alert | Splunk, SPL, detection rules | *Coming soon* |
| 6 | ⏳ **Disaster recovery:** back up, break, restore, and time a service, then write the runbook | Backup & recovery, runbooks | Part of [homelab-ansible](https://github.com/R-Garren/homelab-ansible) (Week 9) |
| 7 | ⏳ **Blue-team labs:** 5–10 CyberDefenders / Blue Team Labs Online investigations with write-ups | DFIR, investigation | *Coming soon* |
| 8 | ⏳ **Vulnerability triage:** case notes on CISA KEV entries, plus Wazuh vulnerability detection and CIS checks ⭐ | Vulnerability management, CVSS, CIS | *Coming soon* |
| 9 | ⏳ **Scripting toolkit:** SSH brute-force detector, PowerShell account audit, Bash service-health check ⭐ | Bash, PowerShell, Python | *Coming soon* |
| 10 | ⏳ **Microsoft Sentinel:** connect a VM, find sign-in events, write a detection rule (SC-200 path) | Cloud SIEM, KQL | *Coming soon* |
| 11 | ⏳ **AI alert triage:** local LLM (Ollama) that summarizes and prioritizes Wazuh alerts | Automation, AI-assisted SOC | *Coming soon* |

⭐ Builds on a project from [CarterPerez-dev/Cybersecurity-Projects](https://github.com/CarterPerez-dev/Cybersecurity-Projects).
