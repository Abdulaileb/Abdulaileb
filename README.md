<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║  Zero-Trust Boot Protocol · ECCS 2026 · Vienna              ║
║  Behavioral Anomaly Detection for IoT · MSc Thesis 2027     ║
║  ISO 27001 Lead Auditor · LebSec Technologies               ║
╚══════════════════════════════════════════════════════════════╝
```

</div>


# Abdulai Tamba Lebbie

**Cloud Security Engineer · DevSecOps · AI Security Research**

I design and build security-hardened cloud infrastructure, secure CI/CD pipelines, and AI security systems. My work spans from published protocol-level security research to production platform engineering.

📍 Udine, Italy (EU resident) · Open to relocation · `a1lebbie@edu.aau.at`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulai-tamba-lebbie-9556919b/)
[![ECCS 2026](https://img.shields.io/badge/ECCS_2026-Published-00C48C?style=flat)](https://africanalyzer.com)
[![ISO 27001](https://img.shields.io/badge/ISO_27001-Lead_Auditor-blue?style=flat)]()

---

## What I actually build

**Security infrastructure** — zero-trust architectures, IAM frameworks, hardened cloud environments (AWS, Azure), and network security controls deployed as code.

**DevSecOps pipelines** — CI/CD pipelines with SAST (Semgrep), secret scanning (Gitleaks), container scanning (Trivy), IaC scanning (Checkov), SBOM generation (Syft), and keyless image signing (Cosign). Deployment only on green.

**AI security systems** — adversarial ML evaluation using IBM ART, LLM security hardening against OWASP LLM Top 10, and ML-based anomaly detection for network security.

**Security research** — designed and published the Zero-Trust Boot Protocol (ZTBP), eliminating the router boot-time default-credential vulnerability window. Evaluated against real attack scenarios. 0% attack success rate.

---

## Published Research

**A Zero-Trust Boot Protocol for Eliminating Router Boot-Time Vulnerability Windows**  
ECCS 2026 — European Conference on Cyber Security · Vienna, June 2026 · Paper ID: AC6013  
Supervised by Prof. Dr. Peter Schartner · University of Klagenfurt

> Designed a fail-closed boot protocol for IoT routers that eliminates the 42–48 second default-credential exposure window at first power-on. Evaluated against Mirai-style credential stuffing and Shodan-style discovery attacks. 0.4s overhead. No hardware changes required. Aligns with EU Cyber Resilience Act, UK PSTI Act, and NIST SP 800-207.

**Current Thesis (2027)**  
*Server-Side Behavioral Anomaly Detection for IoT Device Authentication: A Machine Learning Approach to Zero-Trust Boot-Time Trust Scoring*  
University of Klagenfurt / University of Udine · Supervisors: Prof. Dr. Schartner, Prof. Miculan

> Building the first publicly labeled dataset of IoT boot-time behavioral telemetry (4 device classes: healthy, Mirai-variant, firmware-tampered, replay-attack). Evaluating RF, XGBoost, and LSTM classifiers. Adversarial evasion analysis via IBM ART (RQ4). Target: Zenodo DOI release.

---

## Current Focus

| Area | Status |
|------|--------|
| ☁️ **Azure Security** | AZ-104 in progress · Azure Sentinel, Defender for Cloud, Entra ID PIM hands-on |
| 🔬 **MSc Thesis** | Behavioral anomaly detection · Adversarial ML evaluation with IBM ART |
| 🏗️ **AKEP Platform** | Multi-tenant SaaS · AWS ECS/Fargate · Terraform · Preparing production deployment |
| 🔒 **LebSec Technologies** | NIS2 compliance tooling for Austrian SMEs · Build! Gründungszentrum Carinthia incubator |
| 🎯 **CTF Research** | SMART CYBERTRAINING study · TU Wien & University of Klagenfurt · AI-assisted offensive security |

---

## Stack

**Cloud & IaC**
```
AWS (ECS Fargate · RDS · VPC · IAM · GuardDuty · CloudTrail · WAF · KMS · Secrets Manager)
Azure (Entra ID · Defender for Cloud · Sentinel · Key Vault · Azure Policy)
Terraform · Ansible · Bash
```

**DevSecOps Pipeline**
```
GitHub Actions (OIDC→AWS, zero long-lived credentials)
SAST: Semgrep · Bandit
Secrets: Gitleaks · detect-secrets
IaC: Checkov · tfsec
Container: Trivy · Syft (SBOM) · Cosign (keyless signing) · SLSA L2
DAST: OWASP ZAP
```

**Security & AI**
```
IBM Adversarial Robustness Toolbox (ART)
OWASP LLM Top 10 · MITRE ATT&CK · MITRE ATLAS
Garak (LLM vulnerability scanner)
scikit-learn · PyTorch · XGBoost · pgvector
ISO 27001 Lead Auditor · SOC 2 (Drata)
```

**Languages**
```
Python (FastAPI · SQLAlchemy · scikit-learn · pytest)
Bash · SQL · HCL (Terraform) · KQL (Azure Sentinel)
```

---

## Projects

### 🔐 AKEP Platform
Multi-tenant university management SaaS with integrated AI services · `akepapp.com`

- AWS ECS Fargate · RDS PostgreSQL 15 · Terraform · GitHub Actions OIDC
- Security pipeline: Semgrep → Gitleaks → Checkov → Trivy → Syft → Cosign → deploy
- AI layer: Ollama local LLM · pgvector semantic search · prompt injection defence
- Directed a team of 3 engineers (frontend, backend, API) as technical lead
- Preparing for first production deployment

### 🛡️ AfricAnalyzer / LebSec
Security monitoring platform for SME and institutional networks · `africanalyzer.com`

- Log ingestion · anomaly detection · NIS2 compliance mapping
- Directed a team of 3 engineers (backend/API, AI/ML, security)
- Currently evaluating NIS2-aligned pivot for Austrian/European SME market
- Accepted into Build! Gründungszentrum Carinthia · Silicon Alps Cluster

### 🔬 Zero-Trust Boot Protocol (ZTBP)
[→ Published ECCS 2026]

- OpenWrt 23.05.2 · VLAN 802.1Q · Argon2id · fail-closed state machine
- Testbed: QEMU/KVM on GCP + physical TP-Link Archer A7 and TL-WR841N
- Attack simulation: Hydra (credential stuffing) · Nmap (discovery) · tcpdump

---

## Credentials

| Credential | Detail |
|---|---|
| MSc AI & Cybersecurity | University of Klagenfurt / University of Udine · Expected 2027 |
| ISO 27001 Lead Auditor | Certified February 2026 |
| ECCS 2026 Publication | Peer-reviewed · All 8 evaluation criteria: Yes |
| Falling Walls Lab Finalist | Austria 2026 |
| AWS SAA | In progress |
| AZ-104 | In progress |

---

## Currently open to

Junior to mid-level **Cloud Security Engineer**, **DevSecOps Engineer**, or **Security Engineer** roles in Europe — Germany, Netherlands, Austria, Spain, or remote EMEA.

I bring published security research, hands-on production infrastructure, ISO 27001 governance depth, and a direct line between academic adversarial ML research and real deployed systems.

---

<div align="center">
<sub>Building in public · Last updated July 2026</sub>
</div>
