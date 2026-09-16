# Abdoul Aziz Dieng

### DevSecOps & Cloud Platform Engineer  
Dakar, Senegal · Open to Remote & International Opportunities

I build secure cloud platforms and DevSecOps workflows across AWS, Kubernetes, Terraform, CI/CD, Docker, Linux, and security automation.

My focus is on secure-by-default infrastructure, repeatable deployments, CI/CD security gates, cloud automation, and documentation that helps engineering teams ship software more reliably.

---

## Core Stack

| Area | Tools |
| :--- | :--- |
| Cloud | AWS, EKS, EC2, ALB, RDS PostgreSQL, S3, IAM, KMS, Route 53 |
| Containers & Kubernetes | Docker, Kubernetes, Helm, ArgoCD, ECR, Kind |
| Infrastructure as Code | Terraform, reusable modules, remote S3 backend |
| CI/CD & DevSecOps | GitHub Actions, AWS CodePipeline, OIDC, SAST, SCA, DAST, secret scanning |
| Security Tools | Semgrep, Trivy, Checkov, OWASP ZAP, Gitleaks, Trufflehog |
| Backend & Scripting | Java, Spring Boot, PostgreSQL, Bash, Linux |
| Observability | Prometheus, Grafana, logs, health checks, runbooks |

---

## Featured Projects

### 01. KubeSecure-GitOps

**Repository:** [KubeSecure-GitOps](https://github.com/aadieng100/KubeSecure-GitOps)  
**Focus:** AWS EKS, Terraform, Helm, ArgoCD, GitOps, Kubernetes Security

A security-hardened GitOps platform that deploys a Spring Boot API to AWS EKS using Terraform, Helm, ArgoCD, Docker, and Amazon RDS PostgreSQL.

- Built a Kubernetes GitOps workflow with Helm charts and ArgoCD reconciliation.
- Provisioned AWS networking, EKS node groups, and encrypted RDS PostgreSQL.
- Hardened containers with multi-stage builds, non-root execution, read-only filesystem, and resource limits.
- Applied Kubernetes NetworkPolicies for least-privilege traffic control.
- Structured Terraform into reusable infrastructure modules.

---

### 02. Multi-Tier DevSecOps CI/CD Platform

**Repository:** [devsecops_project02](https://github.com/aadieng100/devsecops_project02)  
**Focus:** AWS, Terraform, GitHub Actions, Java, Spring Boot, Security Gates

A production-inspired DevSecOps platform for secure CI/CD automation, reusable AWS infrastructure, and developer self-service workflows.

- Built a GitHub Actions pipeline with secret scanning, SAST, IaC checks, SCA/container scans, DAST, deployment, and teardown.
- Designed a multi-tier AWS architecture with public ALB, private Auto Scaling Groups, and isolated RDS PostgreSQL.
- Implemented OIDC-based keyless AWS authentication for CI/CD workflows.
- Refactored Terraform into reusable modules for network, IAM, database, compute, and observability.
- Added encrypted S3 artifact staging with KMS and secure EC2 bootstrapping.

---

### 03. GuardianPy

**Repository:** [guardianpy](https://github.com/aadieng100/guardianpy)  
**Focus:** Python, Policy-as-Code, Dockerfile Checks, Terraform Checks, CI/CD Gating

A local-first security automation tool that helps developers detect common misconfigurations before code reaches CI/CD.

- Built modular scanners for Dockerfile and Terraform misconfigurations.
- Added AWS posture checks for S3 and IAM security patterns.
- Designed POSIX exit codes so the tool can act as a CI/CD security gate.
- Generated Markdown security reports for developer feedback.
- Added Slack and Discord notifications for security findings.

---

## Additional Projects

- [devsecops_project01](https://github.com/aadieng100/devsecops_project01) — Ephemeral AWS developer environments with Terraform, GitHub Actions, Prometheus, Grafana, and automated teardown.
- [tetris-optimizer](https://github.com/aadieng100/tetris-optimizer) — Go-based algorithmic optimizer using recursion, search pruning, and performance-aware implementation.

---

## Professional Background

- Technical Co-Founder & Lead Engineer at KaartSanté
- Software Engineering Program — Zone01 Dakar / 01Edu Framework
- B.Sc. Computer Engineering & Software Engineering — UNIVERSAT
- Google Cybersecurity Professional Certificate
- EF SET English C1 Advanced

---

## Current Focus

- DevSecOps engineering and CI/CD security automation
- Kubernetes, Helm, GitOps, and platform engineering workflows
- AWS cloud infrastructure with Terraform
- Cloud-native security, observability, and SRE practices
- Preparing for advanced cloud and security certifications

---

## Contact

- LinkedIn: [linkedin.com/in/aadieng](https://linkedin.com/in/aadieng)
- GitHub: [github.com/aadieng100](https://github.com/aadieng100)
- Email: [diengabdoulaziz110@gmail.com](mailto:diengabdoulaziz110@gmail.com)
