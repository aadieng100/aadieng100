# Abdoul Aziz Dieng
### Cloud Enablement / Platform DevSecOps Engineer
Dakar, Senegal - Open to Remote & International Opportunities

I build AWS cloud delivery workflows that help engineering teams ship reliably with reusable infrastructure patterns, CI/CD automation, secure defaults, observability, and clear developer documentation.

My work sits at the intersection of software engineering, cloud infrastructure, DevSecOps, and developer enablement. I focus on making cloud environments repeatable, auditable, and developer-friendly through Terraform, GitHub Actions, AWS IAM/OIDC access patterns, security validation gates, and practical troubleshooting documentation.

---

## Core Technologies

| Category | Stack |
| :--- | :--- |
| Cloud Platform | AWS VPC, EC2, ALB, Auto Scaling Groups, RDS PostgreSQL, S3, KMS, IAM, Secrets Manager, Route 53, Elastic Beanstalk, Amplify |
| Infrastructure as Code | Terraform, reusable modules, remote S3 backend, environment roots, infrastructure hardening |
| CI/CD & Developer Enablement | GitHub Actions, AWS CodePipeline, OIDC Federation, branch protection gates, deployment documentation, self-service workflows |
| Security Guardrails | Semgrep, Trivy, Checkov, OWASP ZAP, Gitleaks, Trufflehog, SAST/SCA/DAST/IaC scanning |
| Backend & Runtime | Java, Spring Boot, PostgreSQL, Docker, Docker Compose, Linux, Bash |
| Observability & Troubleshooting | Prometheus, Grafana, VPC Flow Logs, health checks, runtime logs, pipeline debugging |

---

## Featured Projects

### 01. Multi-Tier AWS Cloud Platform & Terraform Pattern Library
**Repository:** [devsecops_project02](https://github.com/aadieng100/devsecops_project02)  
**Focus:** AWS platform engineering, Terraform modules, developer self-service, OIDC, ALB/ASG/RDS

A cloud enablement project for a headless e-commerce API built around reusable Terraform modules, dev/staging environment roots, OIDC-based AWS authentication, ALB + private Auto Scaling Group + isolated RDS architecture, encrypted artifact staging, VPC Flow Logs, runbooks, and developer self-service documentation.

Key work:

- Refactored Terraform into a reusable IaC pattern library with bootstrap, network, IAM, database, compute, and observability modules.
- Built dev/staging environment roots to support repeatable AWS application environments.
- Configured OIDC-based keyless AWS authentication for GitHub Actions.
- Designed private application networking behind an internet-facing ALB with RDS PostgreSQL in isolated database subnets.
- Implemented encrypted S3 artifact staging with KMS, blocked public access, lifecycle expiry, and EC2 user-data bootstrapping.
- Added self-service documentation, Terraform module usage docs, runbooks, and troubleshooting guides.

---

### 02. Ephemeral AWS Developer Platform & Observability Pipeline
**Repository:** [devsecops_project01](https://github.com/aadieng100/devsecops_project01)  
**Focus:** PR-triggered AWS environments, CI/CD guardrails, security validation, Prometheus/Grafana observability

A platform-style DevSecOps project that gives developers fast, repeatable feedback before merge. Every pull request triggers a GitHub Actions workflow that provisions a temporary AWS environment with Terraform, validates the live Spring Boot service, runs security and quality gates, captures telemetry, and automatically destroys the infrastructure after execution.

Key work:

- Built PR-triggered GitHub Actions workflows for ephemeral AWS staging environments.
- Integrated five validation gates: secret scanning, SAST, SCA/container scanning, IaC compliance checks, and OWASP ZAP DAST validation.
- Managed AWS infrastructure as code including VPC, subnets, route tables, security groups, EC2, encrypted EBS, IAM roles/policies, IAM instance profiles, and Secrets Manager.
- Implemented runtime secret retrieval through EC2 IAM Instance Profile and AWS Secrets Manager.
- Added Prometheus/Grafana dashboards for JVM memory, HTTP request rate, database connection pool activity, and runtime health validation.
- Documented troubleshooting for pipeline failures, cloud-init/user-data issues, health checks, and runtime diagnostics.

---

### 03. GuardianPy - Local Security Guardrails for Developers
**Focus:** Python automation, local security checks, developer feedback

A Python security automation project that helps developers run repeatable local checks before pushing code or triggering CI/CD workflows. The goal is to catch common security issues earlier, improve developer feedback, and support secure SDLC habits from the local development environment.

---

## Professional Background

- Technical Co-Founder & Lead Engineer at KaartSante
- 3-Year Software Engineering Program - Zone01 Dakar / 01Edu Framework
- Bachelor's Degree in Computer Engineering & Software Engineering - UNIVERSAT
- Google Cybersecurity Professional Certificate
- EF SET English C1 Advanced

---

## Engineering Principles

- **Developer enablement:** the secure path should also be the easiest path.
- **Infrastructure as Code:** cloud infrastructure should be version-controlled, reviewable, repeatable, and documented.
- **Automation first:** CI/CD, validation gates, and runbooks reduce manual operational risk.
- **Secure defaults:** IAM/OIDC, encryption, private networking, and scanning should be built into workflows early.
- **Troubleshooting culture:** every difficult fix should become clearer documentation for the next developer.

---

## Current Focus

- AWS Associate certification preparation
- ECS/Fargate deployment patterns with Terraform
- Deeper platform engineering, observability, and developer self-service workflows

---

## Connect With Me

- LinkedIn: [linkedin.com/in/aadieng](https://linkedin.com/in/aadieng)
- GitHub: [github.com/aadieng100](https://github.com/aadieng100)
- Email: [diengabdoulaziz110@gmail.com](mailto:diengabdoulaziz110@gmail.com)
