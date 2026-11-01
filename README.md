# Qiqing Huang

**Vulnerability research** — finding and reporting memory-safety and protocol flaws in firmware, network protocols, and systems software, carried from analysis through vendor remediation and standards-body action.

Deepest work to date is on cellular: over-the-air attacks against 4G/5G basebands and base stations.

Ph.D. in Computer Science and Engineering, **University at Buffalo (SUNY)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-qiqing--huang-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/qiqing-huang)
![Focus](https://img.shields.io/badge/focus-vulnerability%20research%20%7C%20firmware%20RE%20%7C%20protocols-1f6feb?style=flat)
![CVEs](https://img.shields.io/badge/published%20CVEs-10-brightgreen?style=flat)

---

## 📄 Publications

- **Correct in Isolation, Broken in Translation: Exploiting Cross-Schema Vulnerabilities in LTE and 5G Base Stations**
  *IEEE Symposium on Security and Privacy (S&P), 2027* — **first author**
  Qiqing Huang, Xingyu Wang, Xiaofeng Chen, Hongxin Hu

- **Semantics Over Syntax: Uncovering Pre-Authentication 5G Baseband Vulnerabilities**
  *USENIX Security Symposium, 2026* — **first author**
  🏅 Artifact Evaluation: **Available · Functional · Reproduced** (all three badges)
  Qiqing Huang, Xingyu Wang, Wanda Guo, Guofei Gu, Hongxin Hu

- **Towards LLM-Assisted Vulnerability Detection and Repair for Open-Source 5G UE Implementations**
  *FutureG Workshop, NDSS, 2025*
  Qiqing Huang\*, Rupam Patir\*, Keyan Guo, Wanda Guo, Guofei Gu, Haipeng Cai, Hongxin Hu

- **Understanding and Detecting Remote Infection on Linux-based IoT Devices**
  *ACM AsiaCCS, 2022* — 🏆 **Best Paper Award**
  Qiqing Huang\*, Hongda Li\*, Fei Ding, Hongxin Hu, Long Cheng, Guofei Gu, Ziming Zhao

- **A Zero Trust Architecture for Connected and Autonomous Vehicles**
  *IEEE Internet Computing, 2023*
  Qiqing Huang\*, John Anderson\*, Long Cheng, Hongxin Hu

- **BYOZ: Protecting BYOD Through Zero Trust Network Security**
  *IEEE NAS, 2022*
  John Anderson, Qiqing Huang, Long Cheng, Hongxin Hu

<sub>\* equal contribution / co-first authorship</sub>

---

## 🛡️ CVEs

Over-the-air vulnerabilities in commercial 5G basebands, LTE base stations, and open-source cellular stacks.

| CVE | Target | Status |
|---|---|---|
| CVE-2026-55306 | Samsung Shannon baseband (Google Pixel 8a) | 🔴 **Critical** — confirmed by the Google Android Security Team; assigned, pending public disclosure |
| CVE-2026-56990 | Samsung Shannon baseband (Google Pixel 8a) | 🟠 **High** — confirmed by the Google Android Security Team; assigned, pending public disclosure |
| [CVE-2026-96274](https://www.cisa.gov/news-events/ics-advisories/icsa-26-272-04) | Baicells Nova 430H eNodeB — **LTE base station** | CVSS v4.0 **8.3** / v3.1 7.4, CWE-248. Published by CISA as **ICSA-26-272-04**, Sep 2026 — *"Qiqing Huang reported this vulnerability to CISA."* |
| [CVE-2026-20527](https://nvd.nist.gov/vuln/detail/CVE-2026-20527) | MediaTek 5G baseband | Published, MediaTek Product Security Bulletin, Oct 2026 |
| [CVE-2026-20504](https://nvd.nist.gov/vuln/detail/CVE-2026-20504) | MediaTek 5G baseband | Published, MediaTek PSB, Sep 2026 |
| [CVE-2026-20503](https://nvd.nist.gov/vuln/detail/CVE-2026-20503) | MediaTek 5G baseband | Published, MediaTek PSB, Sep 2026 |
| [CVE-2025-54628](https://nvd.nist.gov/vuln/detail/CVE-2025-54628) | HarmonyOS / EMUI communication module | CVSS 7.5, Huawei security bulletin, Aug 2025 |
| [CVE-2025-47384](https://nvd.nist.gov/vuln/detail/CVE-2025-47384) | Qualcomm 5G baseband | Pre-authentication RRC reachable assertion; patched, in NVD |
| [CVE-2025-20703](https://nvd.nist.gov/vuln/detail/CVE-2025-20703) | MediaTek 5G baseband | Patched |
| [CVE-2025-20666](https://nvd.nist.gov/vuln/detail/CVE-2025-20666) | MediaTek 5G baseband | Patched |
| [CVE-2025-20644](https://nvd.nist.gov/vuln/detail/CVE-2025-20644) | MediaTek 5G baseband | Patched |
| [CVE-2025-63356](https://nvd.nist.gov/vuln/detail/CVE-2025-63356) | OpenAirInterface 5G UE | Upstream patch merged |

---

## 📡 Standards

- **GSMA CVD-2026-0123** — accepted by the GSMA Coordinated Vulnerability Disclosure panel; **Liaison Statement issued to 3GPP RAN2**
- **GSMA CVD-2025-0110**

---

## 🎤 Talks

- **DEF CON 34** (2026), Main Stage — *The Compiler That Can't Read: Crashing Every 5G Phone With One Byte*

---

## 🧩 Service

**IEEE TDSC** · **USENIX Security Artifact Evaluation** (Summer & Fall) · **USENIX ATC** Extended Review Committee · TrustCom · ACM CODASPY · VehicleSec · ASONAM · IWQoS (×2) · IEEE GLOBECOM

---

## 🔧 Interests

Firmware and binary reverse engineering · protocol security and stateful fuzzing · specification–implementation gap analysis · memory safety in native code · OS and systems security · LLM-assisted vulnerability discovery

**Certifications:** OSCP · CEH · Security+

---

## 📚 Currently

Going deeper on **reverse engineering** and **code auditing** — Windows internals and the access-control model, source-level C/C++ review, and the boundary between a crash and exploitable memory corruption.
