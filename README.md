# Qiqing Huang

**Vulnerability research** — finding and reporting memory-safety and protocol flaws in firmware, network protocols, and systems software, carried from analysis through vendor remediation and standards-body action.

Deepest work to date is on cellular: over-the-air attacks against 4G/5G basebands and base stations.

Ph.D. in Computer Science and Engineering, **University at Buffalo (SUNY)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-qiqing--huang-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/qiqing-huang)
![Focus](https://img.shields.io/badge/focus-vulnerability%20research%20%7C%20firmware%20RE%20%7C%20protocols-1f6feb?style=flat)

---

## 📄 Publications

- **Correct in Isolation, Broken in Translation: Exploiting Cross-Schema Vulnerabilities in LTE and 5G Base Stations**
  Qiqing Huang, Xingyu Wang, Xiaofeng Chen, Hongxin Hu
  *IEEE Symposium on Security and Privacy (**S&P 2027**), Montreal* — **first author**

- **Semantics Over Syntax: Uncovering Pre-Authentication 5G Baseband Vulnerabilities**
  Qiqing Huang, Xingyu Wang, Wanda Guo, Guofei Gu, Hongxin Hu
  *35th **USENIX Security Symposium** (2026), Baltimore* — **first author**
  🏅 Artifact Evaluation: **Available · Functional · Reproduced**
  [![USENIX](https://img.shields.io/badge/USENIX-990000?style=flat-square)](https://www.usenix.org/conference/usenixsecurity26/presentation/huang-qiqing) [![arXiv](https://img.shields.io/badge/arXiv-2604.04283-b31b1b?style=flat-square)](https://arxiv.org/abs/2604.04283) [![Artifact](https://img.shields.io/badge/Artifact-Zenodo-1682D4?style=flat-square)](https://doi.org/10.5281/zenodo.18424200)

- **Towards LLM-Assisted Vulnerability Detection and Repair for Open-Source 5G UE Implementations**
  Qiqing Huang\*, Rupam Patir\*, Keyan Guo, Wanda Guo, Guofei Gu, Haipeng Cai, Hongxin Hu
  *FutureG Workshop, **NDSS 2025***

- **Understanding and Detecting Remote Infection on Linux-based IoT Devices**
  Qiqing Huang\*, Hongda Li\*, Fei Ding, Hongxin Hu, Long Cheng, Guofei Gu, Ziming Zhao
  *ACM **AsiaCCS 2022**, Nagasaki* — 🏆 **Best Paper Award**
  [![DOI](https://img.shields.io/badge/DOI-10.1145%2F3488932.3517423-0066cc?style=flat-square)](https://doi.org/10.1145/3488932.3517423)

- **A Zero-Trust Architecture for Connected and Autonomous Vehicles**
  Qiqing Huang\*, John Anderson\*, Long Cheng, Hongxin Hu
  *IEEE **Internet Computing**, 27(5), 2023*
  [![DOI](https://img.shields.io/badge/DOI-10.1109%2FMIC.2023.3304893-0066cc?style=flat-square)](https://doi.org/10.1109/MIC.2023.3304893)

- **BYOZ: Protecting BYOD Through Zero Trust Network Security**
  John Anderson, Qiqing Huang, Long Cheng, Hongxin Hu
  *IEEE **NAS 2022***

<sub>\* equal contribution / co-first authorship</sub>

---

## 🛡️ CVEs

Over-the-air vulnerabilities in commercial 5G basebands, LTE base stations, and open-source cellular stacks.

| CVE | Target | Severity *(as rated by)* | Details |
|---|---|---|---|
| CVE-2026-55306 | Samsung Shannon baseband — Google Pixel 8a | 🔴 **Critical** *(Google Android Security Team)* | Assigned; pending public disclosure |
| CVE-2026-56990 | Samsung Shannon baseband — Google Pixel 8a | 🟠 **High** *(Google Android Security Team)* | Assigned; pending public disclosure |
| [CVE-2026-96274](https://www.cisa.gov/news-events/ics-advisories/icsa-26-272-04) | Baicells Nova 430H eNodeB — **LTE base station** | 🟠 **8.3 High** *(CISA, CVSS v4.0; v3.1 7.4)* | CISA advisory **ICSA-26-272-04**, Sep 2026 · CWE-248 |
| [CVE-2026-20527](https://nvd.nist.gov/vuln/detail/CVE-2026-20527) | MediaTek 5G baseband — modem | 🟠 **High** *(MediaTek PSB)* | Oct 2026 · CWE-129 improper array index validation · **57 chipsets** |
| [CVE-2026-20504](https://nvd.nist.gov/vuln/detail/CVE-2026-20504) | MediaTek 5G baseband — modem | 🟠 **High** *(MediaTek PSB)* | Sep 2026 · CWE-617 reachable assertion · 19 chipsets |
| [CVE-2026-20503](https://nvd.nist.gov/vuln/detail/CVE-2026-20503) | MediaTek 5G baseband — modem | 🟠 **High** *(MediaTek PSB)* | Sep 2026 · CWE-617 reachable assertion · **57 chipsets** |
| [CVE-2025-54628](https://nvd.nist.gov/vuln/detail/CVE-2025-54628) | HarmonyOS / EMUI communication module | 🟠 **7.5 High** *(NVD, CVSS v3.1)* | Huawei security bulletin, Aug 2025 · CWE-118 |
| [CVE-2025-20703](https://nvd.nist.gov/vuln/detail/CVE-2025-20703) | MediaTek 5G baseband — modem | 🟠 **High** *(MediaTek PSB)* | Sep 2025 · CWE-125 out-of-bounds read |
| [CVE-2025-20666](https://nvd.nist.gov/vuln/detail/CVE-2025-20666) | MediaTek 5G baseband — modem | 🟠 **High** *(MediaTek PSB; NVD 7.5)* | May 2025 · CWE-617 reachable assertion |
| [CVE-2025-20644](https://nvd.nist.gov/vuln/detail/CVE-2025-20644) | MediaTek 5G baseband — modem | 🟠 **High** *(MediaTek PSB)* | Mar 2025 |
| [CVE-2025-47384](https://nvd.nist.gov/vuln/detail/CVE-2025-47384) | Qualcomm 5G baseband | **6.5 Medium** *(Qualcomm, CNA)* | Pre-authentication RRC reachable assertion; patched · CWE-617 |
| [CVE-2025-63356](https://nvd.nist.gov/vuln/detail/CVE-2025-63356) | OpenAirInterface 5G UE | — | Upstream patch merged |

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
