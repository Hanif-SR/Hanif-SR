# 🚀 Hanif Sebastian Ramanda — Security Portfolio

> Hands‑on labs, reproducible guides, and structured writeups demonstrating practical work with **Ubuntu web services (Node.js + Nginx)**, **Kali pentesting (WSTG-style)**, **Nessus scanning**, and **Wazuh SIEM** — all in a contained VM environment.

[![Email](https://img.shields.io/badge/email-haniframanda106%40gmail.com-blue?style=flat\&logo=gmail)](mailto:haniframanda106@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hanif%20Sebastian-blue?style=flat\&logo=linkedin)](https://www.linkedin.com/in/hanif-sebastian-ramanda-427931328?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Blkcjb3MMSQO5m5yFN1sdNg%3D%3D)

---

## ✨ Overview

Labs designed for **practical, reproducible experimentation** in a controlled VM environment:

* Implementing **basic runtime security controls** on services
* Validating **network and application configurations**
* Collecting **host-level telemetry for SIEM correlation**

**Workflow:**

* Deploy → Test → Scan → Monitor → Report
* Minimal code + clear commands for immediate reproducibility
* Lab scope only — techniques presented in authorized environments only

---

## 📚 Projects (timeline table view)

| Project                          | Description                                                                                                                                                                            |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Network Fundamentals**         | Network topologies, subnetting exercises, packet captures (PCAP), and protocol-to-port mapping. Builds foundation for network understanding and attacker/defender mindset.             |
| **Ubuntu Linux (simple Web service)** | Minimal Node.js app (≤5 pages) deployed behind Nginx. Includes reverse proxy, HTTP security headers, PM2, and structured logging. Serves as primary test target for pentesting.        |
| **Kali WSTG Testing**            | Kali playbooks implementing ≥5 WSTG checklist items (information gathering, authentication, input validation, file handling, session management). Includes PoCs and detection mapping. |
| **Nessus Analysis**              | Nessus scans on Kali with templates and exported reports (PDF/CSV). Findings mapped to CVE/CWE and remediation actions. Combines automated scans with manual verification.             |
| **Wazuh SIEM**                   | Wazuh agent installed on Ubuntu. Collects Nginx and Node.js app logs, demonstrates alerting and dashboard correlation for brute force, fuzzing, and suspicious activity.               |

---


## 🧰 Tools & Badges

### Offensive Testing

![Kali](https://img.shields.io/badge/Kali-1793D1?style=for-the-badge\&logo=kali-linux\&logoColor=white)

### Automated Scanning

![Nessus](https://img.shields.io/badge/Nessus-FF6A00?style=for-the-badge\&logo=tenable\&logoColor=white)

### SIEM & Monitoring

![Wazuh](https://img.shields.io/badge/Wazuh-2F7AE0?style=for-the-badge\&logo=logstash\&logoColor=white)

### Runtime & Web Services

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge\&logo=nginx\&logoColor=white)

---

## 💡 Notes

* Labs are **self-contained** in VM environments.
* Credentials and intentionally exposed endpoints are for **educational purposes only**.
* For production deployments, enable HTTPS, `cookie.secure`, remove demo accounts, and eliminate debug endpoints.

---

**Tip:** Replace `github.com/YOUR_GITHUB/...` placeholders with actual repository URLs.
