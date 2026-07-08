# Abdoul Aziz Dieng

### DevSecOps & Cloud Platform Engineer  
Dakar, Senegal · Open to Remote & International Opportunities

I build secure cloud platforms and DevSecOps workflows across AWS, Kubernetes, Terraform, CI/CD, Docker, Linux, and security automation.

My work focuses on making cloud environments repeatable, auditable, secure-by-default, and developer-friendly. I enjoy building infrastructure patterns, CI/CD security gates, Kubernetes deployment workflows, observability foundations, and clear technical documentation that help teams ship software more reliably.

---

## Core Technologies

| Category | Stack |
| :--- | :--- |
| Cloud Platform | AWS VPC, EKS, EC2, ALB, Auto Scaling Groups, RDS PostgreSQL, S3, IAM/OIDC, KMS, Secrets Manager, Route 53, Elastic Beanstalk, Amplify |
| Kubernetes & Platform Engineering | Kubernetes, Helm, ArgoCD, Docker, ECR, Kind, NetworkPolicies, GitOps workflows, multi-environment infrastructure patterns |
| Infrastructure as Code | Terraform, reusable modules, remote S3 backend, environment roots, infrastructure hardening |
| CI/CD & DevSecOps Automation | GitHub Actions, AWS CodePipeline, OIDC Federation, branch protection gates, SAST, SCA, DAST, IaC compliance, secret scanning |
| Security Tooling | Semgrep, Trivy, Checkov, OWASP ZAP, Gitleaks, Trufflehog, vulnerability management, security quality gates |
| Backend & Runtime | Java, Spring Boot, Maven, PostgreSQL, Docker Compose, Linux, Bash |
| Observability & SRE Practices | Prometheus, Grafana, application health checks, runtime logs, pipeline debugging, troubleshooting, runbooks |

---

## Featured Projects

### 01. KubeSecure-GitOps — Kubernetes DevSecOps Platform on AWS EKS

**Repository:** [KubeSecure-GitOps](https://github.com/aadieng100/KubeSecure-GitOps)  
**Focus:** Kubernetes, Helm, ArgoCD, AWS EKS, Terraform, RDS, Docker, GitOps, security hardening

A security-hardened GitOps platform that deploys a Spring Boot API to AWS EKS using Helm, ArgoCD, Docker, Terraform, and Amazon RDS PostgreSQL.

Key work:

- Built a Kubernetes GitOps deployment workflow with Helm charts, ArgoCD reconciliation, and AWS EKS infrastructure.
- Provisioned a three-tier AWS architecture with public NAT, private EKS node groups, and isolated encrypted RDS PostgreSQL.
- Hardened containers with multi-stage builds, distroless runtime images, non-root execution, read-only filesystem, and resource limits.
- Applied Kubernetes NetworkPolicies with a least-privilege posture and restricted pod egress.
- Validated workloads locally with Kind before promoting to a production-representative AWS environment.
- Structured Terraform into reusable modules for network, IAM, compute, and database infrastructure.

---

### 02. Multi-Tier DevSecOps CI/CD Platform

**Repository:** [devsecops_project02](https://github.com/aadieng100/devsecops_project02)  
**Focus:** AWS, Terraform, GitHub Actions, Java, Spring Boot, Maven, Docker, OIDC, security gates

A production-inspired DevSecOps platform for a headless commerce API, focused on secure CI/CD automation, reusable AWS infrastructure, and developer self-service documentation.

Key work:

- Built a 6-job GitHub Actions DAG pipeline with secret scanning, SAST, IaC compliance, Maven build verification, Trivy SCA/container scans, ephemeral AWS deployment, OWASP ZAP DAST, teardown, and branch gates.
- Designed a multi-tier AWS architecture with public ALB, private Auto Scaling Groups, and isolated RDS PostgreSQL.
- Implemented OIDC-based keyless AWS authentication for CI/CD workflows.
- Refactored Terraform into reusable modules for bootstrap, network, IAM, database, compute, and observability.
- Added encrypted S3 artifact staging with KMS, blocked public access, lifecycle expiry, and EC2 user-data bootstrapping.
- Created developer self-service guides, Terraform module documentation, runbooks, and troubleshooting procedures.

---

### 03. GuardianPy — Policy-as-Code Security Gatekeeper

**Repository:** [guardianpy](https://github.com/aadieng100/guardianpy)  
**Focus:** Python, policy-as-code, Dockerfile checks, Terraform checks, AWS posture validation, CI/CD gating

A local-first security automation tool that helps developers detect common misconfigurations before code reaches CI/CD.

Key work:

- Built modular scanners for Dockerfile and Terraform misconfigurations.
- Added simulated AWS posture checks for S3 and IAM security patterns.
- Designed POSIX exit codes so the tool can act as a CI/CD security gate.
- Generated Markdown security reports for developer feedback.
- Added Slack and Discord ChatOps notifications for security findings.

---

### 04. Ephemeral AWS Developer Platform & Observability Pipeline

**Repository:** [devsecops_project01](https://github.com/aadieng100/devsecops_project01)  
**Focus:** PR-triggered AWS environments, Terraform, GitHub Actions, Docker, Prometheus, Grafana, automated teardown

A DevSecOps project that provisions temporary AWS environments on pull requests, validates the live service, captures telemetry, and destroys infrastructure automatically after execution.

Key work:

- Built PR-triggered GitHub Actions workflows for ephemeral AWS staging environments.
- Integrated validation gates for secret scanning, SAST, SCA/container scanning, IaC compliance, and OWASP ZAP DAST.
- Managed AWS infrastructure with Terraform, including VPC, subnets, route tables, security groups, EC2, encrypted EBS, IAM roles, IAM instance profiles, and Secrets Manager.
- Implemented runtime secret retrieval through EC2 IAM Instance Profile and AWS Secrets Manager.
- Added Prometheus and Grafana dashboards for JVM memory, HTTP request rate, database connection pool activity, and runtime health validation.
- Documented troubleshooting for pipeline failures, cloud-init issues, health checks, and runtime diagnostics.

---

### 05. Tetris Optimizer

**Repository:** [tetris-optimizer](https://github.com/aadieng100/tetris-optimizer)  
**Focus:** Go, algorithms, optimization, recursion, search pruning

A Go-based algorithmic optimizer that demonstrates structured problem solving, recursive search, pruning, and performance-aware implementation.

---

## Professional Background

- Technical Co-Founder & Lead Engineer at KaartSanté
- Software Engineering Program — Zone01 Dakar / 01Edu Framework
- B.Sc. Computer Engineering & Software Engineering — UNIVERSAT
- Google Cybersecurity Professional Certificate
- EF SET English C1 Advanced

---

## Engineering Principles

- **Secure defaults:** security should be built into infrastructure and delivery workflows from the beginning.
- **Developer enablement:** the secure path should also be the easiest path for developers.
- **Infrastructure as Code:** cloud infrastructure should be version-controlled, reviewable, repeatable, and documented.
- **Automation first:** CI/CD gates, validation workflows, and runbooks reduce manual operational risk.
- **Operational clarity:** every difficult fix should become clearer documentation for the next engineer.

---

## Current Focus

- DevSecOps engineering and CI/CD security automation
- Kubernetes, Helm, GitOps, and platform engineering workflows
- AWS cloud infrastructure with Terraform
- SRE practices, observability, troubleshooting, and developer self-service documentation
- Preparing for security and cloud certifications

---

## Connect With Me

- LinkedIn: [linkedin.com/in/aadieng](https://linkedin.com/in/aadieng)
- GitHub: [github.com/aadieng100](https://github.com/aadieng100)
- Email: [diengaboulaziz110@gmail.com](mailto:diengaboulaziz110@gmail.com)
