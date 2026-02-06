# Hi there, I'm Kevin - a Tech Enthusiast with a Business Background! 👋

> **"Preserving tradition, driving technology."**

I am a **Food Management Graduate (B.A.)** who discovered a passion for code while digitizing a family business. What started as a simple Python script during a summer vacation turned into managing a full on-premise production environment and developing full-stack applications.

---

## 🚀 The "Why": My Next Challenge

I have spent the last few years engineering enterprise-grade solutions for our family butcher shop (~20 employees). I've built everything from **AI-orchestrated support bots** to **automated digital signage** and **paperless office systems**.

**So, why look for something new?**
I love building complex automations (like connecting Chatwoot with n8n and AI agents). However, in a small enterprise, these powerful tools are triggered maybe 3 times a day.
👉 **I am looking for scale.** I want to build systems that run 3,000 times a day—or more. I want to apply my skills in an environment where efficiency and automation create massive, measurable impact beyond the boundaries of a local business.

---

## 🛠 Tech Stack

My toolbox combines modern full-stack development with deep system administration and DevOps knowledge.

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=flat&logo=next.js&logoColor=white)
![Payload CMS](https://img.shields.io/badge/Payload%20CMS-000000?style=flat&logo=payloadcms&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)

### ⚙️ DevOps, Infrastructure & Self-Hosting
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![Coolify](https://img.shields.io/badge/Coolify-6B21A8?style=flat&logo=coolify&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat&logo=hetzner&logoColor=white)
![Kopia](https://img.shields.io/badge/Kopia-2196F3?style=flat&logo=archive&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-181818?style=flat&logo=tailscale&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![CI/CD](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

### 🗄️ Database, Storage & Tools
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white)
![S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat&logo=amazon-s3&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)

---
## 🏗️ Featured Projects & Engineering

### 🥩 The "Wild Ride": Enterprise Self-Hosting
I architected a complete on-premise solution to modernize our business operations.
* **Infrastructure:** Run on a dedicated Server via **Proxmox** (LXC Containers + VMs) + NAS.
* **Networking Security:** **Tailscale** serves as the backbone—used not just as a VPN, but as a DNS orchestrator (with Pi-hole sidecars) to ship tools internally via FQDNs. I use Tailscale Funnels to securely share services (like Nextcloud) without dangerous port forwarding.
* **Backup Strategy:** Automated backups via Proxmox Backup Server to NAS ➔ Snapshotted via **Kopia** to a remote location (3-2-1 strategy).
* **The Paperless Office:** Deployed **Paperless-ngx** managing 15,000+ documents.
    * *Custom Python Scripts:* Developed tools to scan directories for missing invoice numbers, generate ASN barcodes, and export CSVs formatted POS-Data specifically for DATEV accounting import.
* **Open Source Contribution:** 🌟 I don't just use tools; I improve them. I contributed the **emergency recovery mode** to [Kopia](https://github.com/kopia/kopia) ([View PR](https://github.com/kopia/kopia/pull/5077)) to allow recovery when repository storage is fully exhausted.

### 💬 Omnichannel Communication Hub
* **Stack:** Self-hosted **Chatwoot** (Hetzner), Nginx Reverse Proxy, Postfix (Mail Relaying).
* **Automation:** Integrated **n8n** via webhooks/API to manage WhatsApp newsletters.
    * *Logic:* Handles subscribes/unsubscribes via contact tags and sends automated welcome coupons.
    * *Scaling:* Implemented **Redis** for rate limiting to ensure stability.
    * *AI:* Currently orchestrating an AI Agent to handle Level 1 customer inquiries.

### 🍽️ Digital Menu Automation (CS50x Final Project)
* **The Problem:** Manually updating menu screens was slow and error-prone.
* **The Solution:** A Python pipeline that extracts data from the central planning Excel, renders it into an HTML template, zips the package, and pushes it via the **PiSignage API** to POS displays.
* **Result:** Zero manual intervention required for daily updates.

### 🎟️ Gutscheineland (Current Fullstack Project)
Building a SaaS-style voucher platform.
* **Tech:** Next.js, PayloadCMS, PostgreSQL, Stripe Payments.
* **Ops:** Deployed via **Coolify** on Hetzner, using S3 for asset storage.
* **Workflow:** Full CI/CD implementation via GitHub Actions.

---

## 📚 Education & Background

> **"I can balance a binary tree, but I prefer building real-world software."**

* **Lecturer:** DHBW Heilbronn (Food Production & Sales) | Member of the Quality Circle for Food Management.
* **Academic:** B.A. Food Management (ECTS classification: A).
* **Computer Science:**
    * **CS50x & CS50w:** Completed Harvard's introduction to CS and Web Programming.
    * **FernUniversität in Hagen:** Guest auditor for **Go (Imperative Programming)** and **Java (Algorithms & Data Structures)** to understand the theoretical underpinnings (Binary Trees, Big O, etc.).
* **Teaching:** Private tutor for Math, Physics, Chemistry & Economics (500+ students).

---

## ⚡ Philosophy

> **"Impossible isn't in my vocabulary."**

The only variables are effort and cost. I believe the best solutions emerge when traditional values meet an innovative mindset. I've learned that with a computer, I can build anything—now I'm ready to build it at scale.

**Let's connect and create something new!** 💡
<!--
**ke-ma-fi/ke-ma-fi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
