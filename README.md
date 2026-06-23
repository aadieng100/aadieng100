# Abdoul Aziz Dieng
### DevSecOps Engineer | Cloud Infrastructure | Application Security
📍 Dakar, Senegal • 🌍 Open to Remote & International Opportunities

Software Engineer focused on DevSecOps, cloud infrastructure, and application security. I design and implement secure AWS environments, automate infrastructure provisioning with Terraform, and integrate security controls throughout the software delivery lifecycle.

My work centers on building secure-by-default systems by combining Infrastructure as Code (IaC), CI/CD automation, cloud-native security controls, container hardening, and continuous security validation.

Recently completed the **Google Cybersecurity Professional Certificate** and developed hands-on DevSecOps projects focused on cloud security, CI/CD automation, observability, and infrastructure as code.

Hands-on experience building and securing cloud-native workloads on AWS through Infrastructure as Code, automated CI/CD pipelines, security testing, and observability practices.

---

### 📋 Professional Background

* **Bachelor's Degree in Computer Engineering**
* **3-Year Software Engineering Program (01 Edu)**
* **Google Cybersecurity Professional Certificate**
* **EF SET English Certificate (C1 Advanced)**

---

### 🛠️ Core Technologies

| Category | Stack |
| :--- | :--- |
| **Cloud & Infrastructure** | AWS (VPC, EC2, ALB, RDS, S3, KMS, IAM, Secrets Manager), Terraform |
| **DevSecOps & Automation** | GitHub Actions, Docker, CI/CD pipelines, OIDC Federation, Checkov, Pre-Commit Framework |
| **Security Engineering** | Semgrep (SAST), Trivy (SCA & Container Scanning), OWASP ZAP (DAST), Gitleaks, Trufflehog |
| **Backend Engineering** | Java, Spring Boot, PostgreSQL (RDS & Containerized), REST APIs |
| **Monitoring & Reliability** | Prometheus, Grafana, Linux, Bash |

---

### 🚀 Featured Projects

#### 01. Secure Application Delivery Pipeline on AWS
🔗 **[Source Code](https://github.com/aadieng100/devsecops_project01)** | 🛠️ **[Pipeline Workflow](https://github.com/aadieng100/devsecops_project01/tree/master/.github/workflows)**

**Overview** Designed and implemented an automated DevSecOps delivery pipeline for a Java application running on AWS. The platform integrates multiple security validation layers directly into the development workflow, ensuring vulnerabilities are detected before deployment.

**Key Capabilities & Security Highlights**
* **Infrastructure as Code:** Complete infrastructure provisioning handled declaratively through **Terraform**.
* **Static Analysis & SCA:** Embedded **Semgrep** for application source-code analysis and **Trivy** for deep software composition analysis and container scanning.
* **Policy enforcement:** Utilized **Checkov** to execute static security validation on Terraform manifests prior to cloud deployment.
* **Dynamic Testing & Feedback:** Automated **OWASP ZAP** dynamic scans against the active runtime environment, engineering automated issue creation and security reporting.
* **Lifecycle Management:** Orchestrated an ephemeral test environment using automated deployment and destruction workflows to minimize attack surface and reduce cloud spend.
* **Pipeline Security:** CI/CD workflows protected through GitHub Secrets management and environment isolation controls.

#### 02. Secure Multi-Tier E-Commerce Platform on AWS
🔗 **[Source Code](https://github.com/aadieng100/devsecops_project02)** | 📐 **[Terraform Architecture](https://github.com/aadieng100/devsecops_project02/tree/main/terraform)**

**Overview** Architected a multi-tier AWS environment designed around secure networking principles, infrastructure immutability, and encrypted data services.

**Key Capabilities & Security Highlights**
* **State Isolation:** Infrastructure fully managed through **Terraform** utilizing a multi-environment deployment strategy backed by remote state management via **Amazon S3**.
* **Identity & Access:** Configured secure, keyless AWS authentication utilizing **GitHub OIDC federation** to eliminate long-lived credentials.
* **Network Segregation:** Designed a strict private subnet architecture, placing application nodes and database layers behind an internet-facing **AWS Application Load Balancer (ALB)**.
* **Data Protection:** Provisioned a highly available **Amazon RDS PostgreSQL** deployment with encryption-at-rest enforced via **AWS KMS Customer-Managed Keys**.
* **Shift-Left Guardrails:** Enforced strict repository security policies by implementing the local **pre-commit framework** running **Gitleaks** and **Trufflehog** to stop secret leaks before code commits.
* **Dynamic Security Validation:** Conducted targeted **OWASP ZAP** security profiling directly against exposed load balancer endpoints.

---

### 🧠 Engineering Principles

* **Security by Design:** Security controls are integrated from development through deployment rather than added after implementation.
* **Infrastructure as Code:** Cloud infrastructure is version-controlled, repeatable, and auditable through Terraform.
* **Automation First:** Manual operational processes are minimized through CI/CD pipelines, policy enforcement, and automated validation.
* **Observability:** Systems are monitored using metrics, dashboards, and alerts to support reliability and rapid troubleshooting.

---

### 🎓 Education & Professional Development

* **3-Year Software Engineering Program (01 Edu)** | Zone01 Dakar Completed  
  *Three-year project-based software engineering program emphasizing Linux systems, networking, backend engineering, peer code review, and autonomous problem solving.*
* **Bachelor's Degree in Computer Engineering** | UNIVERSAT Dakar (Graduated 2021)

#### Core Credentials & Certifications
* **Google Cybersecurity Professional Certificate** (Coursera)
* **EF SET English Certificate (C1 Advanced)**
* Google Project Management Foundations

---

### 📬 Connect With Me

* **LinkedIn:** [linkedin.com/in/aadieng](https://linkedin.com/in/aadieng)
* **GitHub:** [github.com/aadieng100](https://github.com/aadieng100)
* **Email:** [diengabdoulaziz110@gmail.com](mailto:diengabdoulaziz110@gmail.com)
