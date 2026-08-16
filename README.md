# 🛡️ VitalGuard AI v4.7.3

**An offline-first, zero-dependency device protection framework for environments under strict information controls and network shutdowns.**

![Status: OTF Security Lab Review](https://img.shields.io/badge/Status-OTF_Security_Lab_Review-1a365d?style=for-the-badge&logo=shield&logoColor=white)
![100% Offline](https://img.shields.io/badge/Network-100%25_Offline-2ecc71?style=for-the-badge)
![Zero Dependency](https://img.shields.io/badge/Dependencies-0-orange?style=for-the-badge)
![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue?style=for-the-badge)

## 📌 Executive Summary
**VitalGuard** is a browser-resident, single-file HTML application designed to protect sensitive data on a person's device during deliberate network shutdowns or under pervasive surveillance. 

It is **NOT** a circumvention tool (like a VPN) and does not restore access to the open internet. Instead, it provides a secure, encrypted local workspace and passive proximity awareness (BLE) for the critical days when connectivity is completely severed and the device itself becomes the primary risk surface.

### Core Architectural Facts
* **Zero Egress (No Network Traffic):** Enforced before application code runs. Replaces and locks APIs like `fetch`, `XHR`, `WebSocket`, and `WebRTC`. There is no traffic to intercept and no server to compel.
* **Zero Dependency:** Runs entirely locally. No build step, no bundler, no `node_modules`. 
* **No Account or Installation Record:** Leaves no app-store footprint or subscriber identity, protecting users in contexts where possession of circumvention software is itself criminalized.
* **At-Rest Encryption:** AES-GCM-256 through the Web Crypto API, keys derived with PBKDF2-SHA-256 at 600,000 iterations.
* **Single-Action Removal:** A full wipe clears stored state and the encrypted vault instantly.

---

## 🗂️ Documentation Hub

To keep this repository organized and accessible, detailed information is strictly separated by its intended audience. Please refer to the specific documents below:

### 1. For Security Auditors & Engineers
* 🗺️ **[Security Audit Scope Map (V47_3_Audit_Scope_Map.md)](https://github.com/jekymin8232/vitalguardai-com/blob/main/V47_3_Audit_Scope_Map.md)**
  * *Read this first.* Contains the threat model, residual risks, and exact line ranges (approx. 1,856 lines) for the core security logic (WP1~WP7).
 
  * * 🧭 **[Full Code Index (V47_3_Full_Code_index.md)](https://github.com/jekymin8232/vitalguardai-com/blob/main/V47_3_Full_Code_index.md)**
  * A complete physical table of contents and alphabetical identifier index for the 13,294-line source file.

### 2. For Partners, Governments & NGOs
* 🌍 **[Vision & Partnership Deck (VISION.md)](https://github.com/jekymin8232/vitalguardai-com/blob/main/VISION.md)**
  * Details on humanitarian deployments, Official Development Assistance (ODA) strategy, desert greening, offline early warning systems, and strategic investment opportunities.

---

## 🔒 Verification & Integrity

Because VitalGuard is a single HTML file, **byte-for-byte verification of the distributed file is the reproducibility check.** Do not trust the file without verifying its hash through an independent, trusted channel.

**Target Artifact:** `VitalGuard_AI_complete_V47_3.html`
**SHA-256 Digest:**
```text
b81c067f5523bc68728ae84f2fc93ce05077705ae4cb7e882f1c859885f47615

