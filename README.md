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
| 0–7 | Network re-addressed, hardened base role, Ansible Vault, Docker, Portainer, Pi-hole + Unbound with DNSSEC deployed from Git, HTTPS through Nginx Proxy Manager with my own private CA ([latest log](https://github.com/R-Garren/homelab-as-code/blob/main/docs/build-log/week-07.md)) | ✅ |
| 8 | Portainer automated through its API | 🔄 |
| 9–10 | Backups, CI linting, disaster-recovery drill → **v2.0.0** | ⏳ |
| 11 | VLANs + Suricata IDS in OPNsense → **v2.1.0** | ⏳ |
| 12 | WireGuard remote access → **v2.2.0** | ⏳ |

<sub>v1
