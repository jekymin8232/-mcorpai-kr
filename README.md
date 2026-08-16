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
* 🧭 **[Full Code Index (V47_3_Full_Code_index.md)](https://github.com/jekymin8232/vitalguardai-com/blob/main/V47_3_Full_Code_index.md)**
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





아이고, 어딘가에서 복사/붙여넣기 오류가 계속 발생하고 있는 것 같습니다. 안타깝게도 지금 올려주신 내용 역시 직전과 **똑같이 뒷부분이 잘려 있고, `Full Code Index` 링크가 누락되어 있습니다**.

아마 사용 중이신 브라우저나 마크다운 에디터에서 스크롤을 끝까지 내리지 않고 복사하셨거나, 글자 수 제한으로 인해 잘렸을 가능성이 높습니다.

마지막으로 다시 한번, **아래 내용의 첫 줄(`# 🛡️ VitalGuard AI v4.7.3`)부터 맨 마지막 줄(`*For inquiries...*`)까지 단 한 줄도 빠짐없이** 전체를 드래그해서 복사해 주세요.

---

```markdown
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
* 🧭 **[Full Code Index (V47_3_Full_Code_index.md)](https://github.com/jekymin8232/vitalguardai-com/blob/main/V47_3_Full_Code_index.md)**
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

```

---

## ⚠️ Pre-Deployment Notice

> **Distributing an unaudited security tool to people under surveillance is not a neutral act.**
> This project is currently **Pre-Deployment**. It is undergoing evaluation by the USAGM Open Technology Fund (OTF) Security Lab. Until independent audits and remediation cycles are fully complete and published, this tool must not be distributed to or relied upon by individuals in high-risk environments. Accountability begins with independent code verification.

---

## 📄 License

* **VitalGuard AI:** Copyright (c) 2026 Morgan J. (Gyu-min Jeon) — Licensed under the [Apache License 2.0](https://www.google.com/search?q=LICENSE).
* **Embedded QR Generator:** Project Nayuki — MIT License.

*For inquiries, please contact: contact@mcorpai.org*
