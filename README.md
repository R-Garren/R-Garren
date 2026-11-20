<div align="center">

# Hi, I'm River Garren 👋

**Cyber Defense student · Home lab builder · Looking for IT roles and internships**

<a href="https://www.linkedin.com/in/river-garren/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<a href="https://www.credly.com/badges/2d1d0517-d85b-459f-987d-8de3c5e85553/public_url"><img alt="CompTIA Security+" src="https://img.shields.io/badge/CompTIA_Security%2B-C8202F?style=for-the-badge&logoColor=white" /></a>
<a href="https://www.credly.com/badges/26264293-a4fa-48c6-8ae1-2e50ab663950/public_url"><img alt="CompTIA Network+" src="https://img.shields.io/badge/CompTIA_Network%2B-007ACC?style=for-the-badge&logoColor=white" /></a>

</div>

---

## 👤 Summary

I'm a Cyber Defense student at Roane State Community College with **CompTIA Security+** and **Network+**. I learn by building: my home lab runs real network services that I deploy, secure, troubleshoot, and document. I'm now rebuilding the whole lab as code, in public, so it can be torn down and rebuilt with one command.

## 🎯 Objective

An **entry-level IT role or an internship**, where I can help keep systems running and secure. I bring hands-on Linux and Windows Server administration, DNS/DHCP troubleshooting, and Ansible automation, plus a key-holder background where my job was keeping service up and getting it back fast when something broke.

## 🎓 Education

**AAS, Computer Information Technology – Cyber Defense** · Roane State Community College · *Expected May 2027*
CIT Program GPA 4.00 · President's List (Fall 2025, Spring 2026)
Coursework: Network Security, Principles of Information Assurance, Windows Server Administration, Digital Forensics (in progress)

## 🔨 Currently Working On

### [homelab-as-code](https://github.com/R-Garren/homelab-as-code): Home Lab v2, Rebuilt as Code

v1 of my lab worked, but too much was built by hand. v2 rebuilds it from scratch with Ansible, tested on a VM before it touches the production server, one milestone per week.

- **One-command build:** bare Ubuntu Server install → running DNS, proxy, and management services
- **Security first:** hardened SSH, default-deny firewall, secrets in Ansible Vault, admin panels kept off the LAN
- **Proof, not claims:** weekly [build logs](https://github.com/R-Garren/homelab-as-code/tree/main/docs/build-log) and [decision records](https://github.com/R-Garren/homelab-as-code/tree/main/docs/adr), including what broke and how I fixed it

| Week | Milestone | Status |
|:----:|-----------|:------:|
| 0–6 | Network re-addressed, hardened base role, Ansible Vault, Docker, Portainer, Pi-hole + Unbound with DNSSEC deployed from Git ([latest log](https://github.com/R-Garren/homelab-as-code/blob/main/docs/build-log/week-06.md)) | ✅ |
| 7 | Nginx Proxy Manager with a private CA | 🔄 |
| 8 | Portainer automated through its API | ⏳ |
| 9–10 | Backups, CI linting, disaster-recovery drill → **v2.0.0** | ⏳ |
| 11 | VLANs + Suricata IDS in OPNsense → **v2.1.0** | ⏳ |
| 12 | WireGuard remote access → **v2.2.0** | ⏳ |

<sub>v1 ([homelab-iac-v1](https://github.com/R-Garren/homelab-iac-v1)) is archived.</sub>

## 🗺️ Roadmap

Each step builds on the lab and the step before it: attack it, detect it, investigate it, recover it.
<sub>🔄 In progress · ⏳ Up next · ⏸️ Paused · ✅ Done</sub>

<!-- When you start a project, swap "Coming soon" for a link, e.g. [REPO-NAME](https://github.com/R-Garren/REPO-NAME), and update its status emoji. -->

| # | Project | Status | Repo |
|:-:|---------|:------:|------|
| 1 | **Wazuh SIEM:** logs from every lab host *(resumes after v2.0)* | ⏸️ | *Coming soon* |
| 2 | **Attack & investigate:** Kali brute force and scans, traced in Wazuh with MITRE ATT&CK write-ups | ⏳ | *Coming soon* |
| 3 | **Packet analysis:** spot scan and brute-force patterns in Wireshark ⭐ | ⏳ | *Coming soon* |
| 4 | **Firewall + IDS:** OPNsense, Suricata, VLAN segmentation | ⏳ | [homelab-as-code](https://github.com/R-Garren/homelab-as-code) (Wk 11) |
| 5 | **Splunk alongside Wazuh:** same logs, one dashboard, one alert | ⏳ | *Coming soon* |
| 6 | **Disaster recovery:** back up, break, restore, time it, write the runbook | ⏳ | [homelab-as-code](https://github.com/R-Garren/homelab-as-code) (Wk 9) |
| 7 | **Blue-team labs:** 5–10 CyberDefenders / BTLO investigations | ⏳ | *Coming soon* |
| 8 | **Vulnerability triage:** CISA KEV case notes, Wazuh vuln detection, CIS checks ⭐ | ⏳ | *Coming soon* |
| 9 | **Scripting toolkit:** Bash, PowerShell, and Python detection and audit scripts ⭐ | ⏳ | *Coming soon* |
| 10 | **Microsoft Sentinel:** VM sign-in events and a KQL detection rule | ⏳ | *Coming soon* |
| 11 | **AI alert triage:** local LLM that summarizes and prioritizes Wazuh alerts | ⏳ | *Coming soon* |

<sub>⭐ Builds on a project from [CarterPerez-dev/Cybersecurity-Projects](https://github.com/CarterPerez-dev/Cybersecurity-Projects).</sub>

## 🛠️ Skills

| Area | Skills | Proof |
|------|--------|-------|
| **Networking** | Subnetting, NAT, DHCP, VLAN design, troubleshooting | [Topology](https://github.com/R-Garren/homelab-as-code/blob/main/docs/network/current-topology.md) · [Runbook](https://github.com/R-Garren/homelab-as-code/blob/main/docs/network/migration-runbook.md) · [VLAN plan](https://github.com/R-Garren/homelab-as-code/blob/main/docs/network/segmentation-plan.md) |
| **Services** | DNS (Pi-hole + Unbound, DNSSEC validation), reverse proxy & TLS (Nginx Proxy Manager), WireGuard VPN | [DNS build log](https://github.com/R-Garren/homelab-as-code/blob/main/docs/build-log/week-06.md) · [Unbound image ADR](https://github.com/R-Garren/homelab-as-code/blob/main/docs/adr/0004-unbound-image.md) · proxy and VPN rebuilding in v2 |
| **Automation** | Ansible roles, hardening, Ansible Vault secrets | [Security baseline](https://github.com/R-Garren/homelab-as-code/blob/main/docs/security-baseline.md) · [Vault ADR](https://github.com/R-Garren/homelab-as-code/blob/main/docs/adr/0002-secrets-with-ansible-vault.md) |
| **Containers** | Docker Engine, Compose, Portainer, GitOps deploys from Git | [Docker bypasses UFW](https://github.com/R-Garren/homelab-as-code/blob/main/docs/security-baseline.md#docker-bypasses-ufw) · [Portainer ADR](https://github.com/R-Garren/homelab-as-code/blob/main/docs/adr/0003-ansible-owns-host-portainer-owns-apps.md) |
| **Security monitoring** | Wazuh SIEM, custom DNS-tunneling and DGA rules (MITRE T1071.004, T1568.002) | Home lab v1 *(paused during rebuild)* |
| **Systems** | Linux (Ubuntu Server), Windows Server administration | Lab + coursework |
| **Frameworks** | Incident response fundamentals, NIST CSF | Coursework |
