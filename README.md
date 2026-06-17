# Abdoul Aziz Dieng
### Software Engineer & Technology Entrepreneur • DevSecOps & Cloud Infrastructure Specialist

Backend Engineer and Technology Entrepreneur with an elite focus on building secure-by-design distributed systems, high-availability cloud infrastructure, and fully automated DevSecOps pipelines. Grounded in advanced defensive security methodologies and backed by the **Google Cybersecurity Professional Certification**, I specialize in shifting security left—integrating automated SAST/SCA/IaC scanning, dynamic fuzzing, and rigid IAM access controls directly into the engineering lifecycle.

---

### 🛠️ Core Engineering & Security Stack

| Layer | Technologies & Frameworks |
| :--- | :--- |
| **Backend & Systems** | Java (Spring Boot 3), PostgreSQL, Linux (Bash), REST APIs |
| **Cloud & Infrastructure** | AWS (VPC, EC2, ALB, S3, RDS), Infrastructure as Code (Terraform) |
| **DevSecOps & Automation** | Docker, CI/CD Pipelines, Git GitHub Actions, Pre-Commit Framework |
| **Security Automation** | Semgrep (SAST), Trivy (SCA), Checkov (IaC), OWASP ZAP (DAST), Gitleaks, Trufflehog |

---

### 🚀 Featured DevSecOps Portfolio Projects

#### 01. Ephemeral Cloud Security Pipeline (Entry-Level Archetype)
🔗 **[Source Code & Pipeline](https://github.com/aadieng100/devsecops_project01)** | 🛠️ **[CI/CD Workflow Configuration](https://github.com/aadieng100/devsecops_project01/tree/master/.github/workflows)**
An automated, isolated test-and-destroy AWS pipeline engineering a secure runtime environment for a modern Java application, prioritizing programmatic secrets management and comprehensive vulnerability feedback loops.

* **Architecture & Flow:** Deployed a Java/Spring Boot 3 application coupled with a Dockerized PostgreSQL database on an AWS instance. Implemented strict IAM Instance Profiles to dynamically extract runtime credentials from AWS Secrets Manager, eliminating hardcoded environment variables.
* **Security Automation Gate:** Integrated a multi-layered scanning suite into the pipeline execution phase:
  * **SAST & SCA:** Executed **Semgrep** for source-code analysis and **Trivy** for container vulnerability assessment.
  * **IaC Auditing:** Utilized **Checkov** to enforce security compliance on Terraform manifests prior to deployment.
  * **Live DAST Fuzzing:** Orchestrated a live web application scan using **OWASP ZAP** against the active container runtime.
* **Feedback & Teardown:** Engineered an automated failure mechanism that parses security scan outputs, programmatically generates structured threat logs directly to **GitHub Issues**, and executes a fail-safe `terraform destroy` sequence to minimize attack surface and cloud spend.

#### 02. High-Availability Multi-Tier E-Commerce Cluster (Intermediate-Level Archetype)
🔗 **[Source Code](https://github.com/aadieng100/devsecops_project02)** | 📐 **[Terraform Architecture Files](https://github.com/aadieng100/devsecops_project02/tree/main/terraform)**
A resilient, highly available headless E-Commerce REST API cluster built on an immutable infrastructure model, enforcing absolute network isolation and edge-to-core security.

* **Infrastructure-as-Code (IaC):** Architected a production-grade AWS environment using an immutable **Terraform** codebase. Managed environments via a **dual-track S3 Remote State** architecture, completely separating volatile staging workspaces from persistent production state files.
* **Network Isolation & Scalability:** Designed an isolated VPC architecture hosting application nodes within **zero-inbound private subnets**. Inbound traffic is strictly funneled through an internet-facing **AWS Application Load Balancer (ALB)** acting as the secure edge gateway.
* **Data Layer Security:** Provisioned a highly available, replicated **Amazon RDS PostgreSQL** cluster. Enforced encryption-at-rest across the database tier using **AWS KMS Customer Managed Keys (CMK)** with strict key rotation policies.
* **Shift-Left Shift-Right Security:**
  * **Local Pre-Commit Guardrails:** Established a localized **pre-commit framework** across developer environments running **Gitleaks** and **Trufflehog** to block accidental credential leaks before they ever reach the remote repository.
  * **Edge DAST Profiling:** Configured targeted **OWASP ZAP** fuzzing routines pointing directly at the ALB edge gateway to stress-test routing rules and application layers against complex web vectors.

---

### 📊 Professional Metrics & Impact Focus
* **Zero Trust Architectures:** Enforcing least-privilege access patterns across AWS IAM policies and database connection strings.
* **Immutable Infrastructure:** Eliminating configuration drift by treating infrastructure as code, ensuring predictability from local staging up to production environments.
* **Vulnerability Remediation:** Accelerating feedback loops for software engineers by embedding vulnerability payloads natively into development workflows.

---

### 📬 Connect With Me
* **LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)
* **Email:** [your.email@example.com](mailto:your.email@example.com)
* **Location:** Dakar, Senegal (Open to local, hybrid, and international remote opportunities)
