# 🏗️ Vesta Labs: Enterprise-Grade Infrastructure Blueprints

[![Proxmox](https://img.shields.io/badge/Virtualization-Proxmox-orange?logo=proxmox)](https://www.proxmox.com)
[![Docker](https://img.shields.io/badge/Container-Docker-blue?logo=docker)](https://www.docker.com)
[![Security](https://img.shields.io/badge/Security-First-green?logo=google-cloud)](https://vestasec.com)

Welcome to the technical hub of **Vesta Security LATAM S.A.** This repository is more than just code; it is a collection of **Standardized Reference Architectures** (Blueprints) for building secure, scalable, and automated business environments.

---

## 🚀 Why This Matters
For businesses and developers, this repository provides:
- **Resilience:** Pre-tested configurations for high-availability clusters.
- **Speed:** Automated Bash scripts to deploy complex stacks in minutes.
- **Security:** "Least Privilege" design integrated with Vaultwarden and Mesh VPNs.

## 📂 Repository Structure
```
labs/
└── vesta-lab/
    ├── docs/            # Technical documentation (.md)
    ├── assets/          # Architecture Diagrams & Screenshots
    ├── exports/         # Real production-ready configs (MikroTik, PBS)
    ├── scripts/         # Modular Bash automation scripts
    ├── templates/       # VM skeletons, Cloud-init, and Docker Compose
    └── mkdocs.yml       # MkDocs configuration for live site
```

## 🛠️ Tech Stack & Expertise
- **Hypervisors:** Proxmox VE 8.x Clusters, VMware ESXi.
- **Networking:** MikroTik (VLANs/Routing), Tailscale & WireGuard.
- **Storage:** TrueNAS SCALE (ZFS Pools), PBS (Proxmox Backup Server).
- **Orchestration:** Docker, Portainer, and custom CI/CD via GitLab.
- **Monitoring:** Prometheus, Grafana, and Uptime Kuma dashboards.

## 🌐 Live Documentation
Explore the full lab details and implementation guides here:  
👉 [https://ifezgez.github.io/labs/](https://ifezgez.github.io/labs/)

---

## 👤 Maintainer
**Ignacio Fernandez** | CEO @ Vesta Security LATAM  
[VestaSec.com](https://vestasec.com) | [LinkedIn](https://www.linkedin.com/in/ignacio-fernandez-vesta/)

---
**Standardization is the key to reliability. Use these blueprints to scale your infrastructure with confidence.**
