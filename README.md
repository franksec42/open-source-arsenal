# open-source-arsenal
# 🛡️ Security Arsenal & Knowledge Base

A curated collection of security tools, frameworks, and resources for Enumeration, Cloud Security, Static Analysis, Threat Intelligence, and more. This repository serves as a central reference for penetration testers, security engineers, and researchers.

## 📋 Table of Contents

- [Enumeration & Reconnaissance](#enumeration--reconnaissance)
- [Static Application Security Testing (SAST) & SCA](#static-application-security-testing-sast--sca)
- [Cloud Security (AWS, Azure, GCP)](#cloud-security-aws-azure-gcp)
- [Container & Kubernetes Security](#container--kubernetes-security)
- [Secrets Detection](#secrets-detection)
- [Threat Intelligence & Vulnerability Management](#threat-intelligence--vulnerability-management)
- [Malware Analysis](#malware-analysis)
- [Visualization & Reporting](#visualization--reporting)
- [Learning, CTFs & Vulnerable Apps](#learning-ctfs--vulnerable-apps)
- [Microsoft Toolset](#microsoft-security-toolset)

---

## 🔍 Enumeration & Reconnaissance

Tools for discovery, domain search, and external attack surface mapping.

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **Amass** | In-depth attack surface mapping and asset discovery. | [Link](https://github.com/OWASP/Amass) |
| **Netcraft** | Site report and background information on domains. | [Link](https://sitereport.netcraft.com/) |
| **DNSCan** | DNS scanner for network infrastructure. | [Link](https://github.com/rbsec/dnscan) |
| **Shodan** | Search engine for Internet-connected devices. | [Link](https://www.shodan.io/) |
| **Nettacker** | Automated penetration testing and information gathering. | [Link](https://github.com/zdresearch/OWASP-Nettacker) |
| **Nuclei** | Fast and customizable vulnerability scanner based on templates. | [Link](https://github.com/projectdiscovery/nuclei) |
| **Censys** | Search engine for finding devices and networks. | [Link](https://censys.io/) |
| **crt.sh** | Certificate Transparency search. | [Link](https://crt.sh/) |
| **Google Dorks** | Advanced Google search operators for recon. | [Link](https://www.exploit-db.com/google-hacking-database) |

---

## 💻 Static Application Security Testing (SAST) & SCA

Tools to analyze source code for vulnerabilities and manage open-source dependencies.

| Tool Name | Language/Focus | Link |
| :--- | :--- | :--- |
| **Semgrep** | Lightweight static analysis for many languages. | [Link](https://semgrep.dev/) |
| **SAST-Scan** | Integrated SAST scanning solution. | [Link](https://github.com/ShiftLeftSecurity/sast-scan) |
| **Dependency-Check** | Detects publicly disclosed vulnerabilities in dependencies. | [Link](https://github.com/jeremylong/DependencyCheck) |
| **SastSweep (Chebuya)** | Identifies vulnerabilities in open source at scale. | [Link](https://github.com/chebuya/sastsweep) |
| **Bandit** | Security linter for Python code. | [Link](https://github.com/PyCQA/bandit) |
| **Brakeman** | Static analysis tool for Ruby on Rails. | [Link](https://brakemanscanner.org/) |
| **Code to Graph** | Visualizes code relationships. | [Link](https://github.com/crubier/code-to-graph) |
| **npm audit** | Native security auditing for Node.js. | [Link](https://docs.npmjs.com/cli/v8/commands/npm-audit) |
| **CodeQL** | Semantic code analysis engine (GitHub Native). | [Link](https://codeql.github.com/) |
| **AppScan CodeSweep** | VS Code plugin for on-the-fly security scanning. | [Link](https://marketplace.visualstudio.com/items?itemName=HCLTechnologies.hcl-appscan-codesweep) |

---

## ☁️ Cloud Security (AWS, Azure, GCP)

Assessment, auditing, and hardening tools for cloud environments.

A more detailed repo on all cloud security tools: Francesco Security toolset. | [Link](https://github.com/franksec42/my-arsenal-of-aws-security-tools) |

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **Prowler** | AWS security assessment, auditing, and hardening. | [Link](https://github.com/prowler-cloud/prowler) |
| **ScoutSuite** | Multi-cloud security-auditing tool. | [Link](https://github.com/nccgroup/ScoutSuite) |
| **CloudMapper** | AWS visualization and auditing tool. | [Link](https://github.com/duo-labs/cloudmapper) |
| **CloudTracker** | Helps define least-privilege IAM roles. | [Link](https://github.com/duo-labs/cloudtracker) |
| **Parliament** | AWS IAM linting library. | [Link](https://github.com/duo-labs/parliament) |
| **Cartography** | Maps infrastructure assets and relationships. | [Link](https://github.com/lyft/cartography) |
| **CNAPPgoat** | Vulnerable-by-design cloud environment for testing. | [Link](https://github.com/ermetic-research/cnappgoat) |
| **CloudQuery** | Cloud asset inventory and configuration with SQL. | [Link](https://www.cloudquery.io/) |
| **Forseti Security** | Security tools for Google Cloud Platform (GCP). | [Link](https://github.com/forseti-security) |
| **Aardvark** | Multi-account AWS IAM Access Advisor API. | [Link](https://github.com/Netflix-Skunkworks/aardvark) |
| **Repokid** | IAM Least Privilege (uses Aardvark). | [Link](https://github.com/Netflix/repokid) |
| **Nimbostratus** | Fingerprinting and exploiting Amazon cloud infrastructures. | [Link](https://github.com/andresriancho/nimbostratus) |

---

## 📦 Container & Kubernetes Security

Tools for securing Docker containers, Kubernetes clusters, and supply chains.

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **Trivy** | Comprehensive container and filesystem scanner. | [Link](https://github.com/aquasecurity/trivy) |
| **Falco** | Cloud Native Runtime Security. | [Link](https://falco.org/) |
| **Kyverno** | Kubernetes Native Policy Management. | [Link](https://kyverno.io/) |
| **Hadolint** | Haskell Dockerfile Linter. | [Link](https://github.com/hadolint/hadolint) |
| **Terrascan** | Static code analysis for IaC (Terraform). | [Link](https://github.com/tenable/terrascan) |
| **Syft** | CLI tool and library for generating a Software Bill of Materials (SBOM). | [Link](https://github.com/anchore/syft) |
| **Grype** | Vulnerability scanner for container images and filesystems. | [Link](https://github.com/anchore/grype) |
| **Clair** | Vulnerability Static Analysis for Containers. | [Link](https://github.com/quay/clair) |
| **BotB** | "Break out the Box" container analysis tool. | [Link](https://github.com/brompwnie/botb) |
| **Amicontained** | Container introspection tool. | [Link](https://github.com/genuinetools/amicontained) |

---

## 🔑 Secrets Detection

Identify hardcoded secrets, keys, and credentials in source code.

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **Gitleaks** | Audit git repos for secrets. | [Link](https://github.com/zricethezav/gitleaks) |
| **TruffleHog** | Searches for high entropy strings and secrets in git history. | [Link](https://github.com/trufflesecurity/trufflehog) |
| **Kingfisher** | Fast secret scanner written in Rust. | [Link](https://github.com/mongodb/kingfisher) |
| **Driftwood** | Private key verification for TruffleHog. | [Link](https://github.com/trufflesecurity/driftwood) |

---

## 🧠 Threat Intelligence & Vulnerability Management

Aggregation, tracking, and management of vulnerabilities and threat data.

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **IntelOwl** | Threat Intelligence Orchestration. | [Link](https://github.com/intelowlproject/IntelOwl) |
| **DefectDojo** | Vulnerability Management and DevSecOps Orchestration. | [Link](https://github.com/DefectDojo/django-DefectDojo) |
| **OpenCTI** | Open Cyber Threat Intelligence Platform. | [Link](https://github.com/OpenCTI-Platform/opencti) |
| **Attack Flow** | Visualizing attack paths (Mitre). | [Link](https://github.com/center-for-threat-informed-defense/attack-flow) |
| **CISA KEV** | Known Exploited Vulnerabilities Catalog. | [Link](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) |
| **Google Project Zero** | Zero-day vulnerability research. | [Link](https://googleprojectzero.blogspot.com/) |
| **Vuls** | Agentless vulnerability scanner for Linux/FreeBSD. | [Link](https://github.com/future-architect/vuls) |
| **ArcherySec** | Vulnerability assessment and management. | [Link](https://github.com/archerysec/archerysec/) |
| **Seccubus** | Automated vulnerability scanning and reporting. | [Link](https://github.com/schubergphilis/Seccubus) |
| **ICHI — Internet Cyber Health Index** | Free daily internet cyber-health barometer aggregating security news, telemetry, and advisories; source-transparent. | [Link](https://ichi.global) |

---

## 🦠 Malware Analysis

Tools for analyzing binaries and malware samples.

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **YARA** | The pattern matching swiss knife for malware researchers. | [Link](https://virustotal.github.io/yara/) |
| **Open Source Malware** | Repository of malware samples. | [Link](https://opensourcemalware.com/) |
| **Tara (Reference)** | *Often refers to YARA or Triage Analysis (Verify context).* | [Link](https://lnkd.in/g7g-ST6w) |

---

## 📊 Visualization & Reporting

Tools to visualize security data and metrics.

| Tool Name | Description | Link |
| :--- | :--- | :--- |
| **Swiftness** | Note-taking and target-tracking for pentesters. | [Link](https://github.com/ehrishirajsharma/Swiftness) |
| **Dradis** | Reporting and collaboration for InfoSec teams. | [Link](https://dradisframework.com/ce/) |
| **Faraday** | Collaborative Penetration Test and Vulnerability Management. | [Link](https://github.com/infobyte/faraday) |
| **Threat Maps** | Various live threat maps (Checkpoint, Fortinet, etc.). | [Link](https://threatmap.checkpoint.com) |

---

## 🎓 Learning, CTFs & Vulnerable Apps

Resources for practicing penetration testing and cloud security.

| Resource | Description | Link |
| :--- | :--- | :--- |
| **WebGoat** | Deliberately insecure web application (Java). | [Link](https://github.com/WebGoat/WebGoat) |
| **CloudGoat** | Vulnerable-by-design AWS deployment. | [Link](https://github.com/RhinoSecurityLabs/cloudgoat) |
| **AWSGoat** | Vulnerable AWS infrastructure for learning. | [Link](https://github.com/ine-labs/AWSGoat) |
| **VulnHub** | Virtual machines for hands-on security training. | [Link](https://www.vulnhub.com/) |
| **OWASP Juice Shop** | Modern vulnerable web app. | [Link](https://github.com/juice-shop/juice-shop) |
| **PoC-in-GitHub** | Collection of Proof of Concept exploits. | [Link](https://github.com/nomi-sec/PoC-in-GitHub) |

---

## 🏗️ Microsoft Security Toolset

Open source tools maintained by Microsoft for secure development.

| Tool | Description |
| :--- | :--- |
| **CredScan** | Identify credential leaks in source code. |
| **BinSkim** | Analyzes binaries for SDL compliance. |
| **DevSkim** | IDE extension for inline security analysis. |
| **Attack Surface Analyzer** | Highlights changes in system state (Windows/Linux/MacOS). |
| **Application Inspector** | Analyzes source code to identify interesting features. |
