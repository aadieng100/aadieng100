# Abdoul Aziz Dieng

### Software Engineer & Founder of AADSec
Dakar, Senegal · Open to Remote & International Opportunities

I build useful software — from a Go constraint-satisfaction solver optimized 3,500×
(36s → under 10ms) to **AADSec**, a local-first DevSecOps audit tool now in private
beta, and reproducible CI/CD platforms on AWS.

My focus: algorithms, performance, debugging, and systems that are secure and
deterministic by design.

🌐 **AADSec:** [aadsec.xyz](https://aadsec.xyz) — actionable DevSecOps audits without
uploading your source code.

---

## Core Stack

| Area | Tools |
| :--- | :--- |
| Languages | Go, Java, Python, TypeScript, Rust |
| Backend & Data | Spring Boot, NestJS, Prisma, PostgreSQL, REST APIs |
| Algorithms & Testing | Data structures, backtracking/DFS, search pruning, unit testing, edge-case validation, debugging |
| Containers & CI/CD | Docker, Docker Compose, Kubernetes, Helm, GitHub Actions, AWS CodePipeline, ArgoCD |
| Cloud & IaC | AWS (EKS, EC2, ALB, RDS, S3, IAM, KMS), Terraform, Linux, Bash |
| Security | SAST, SCA, DAST, secret scanning, Semgrep, Trivy, Checkov, Gitleaks, OWASP ZAP |
| Observability | Prometheus, Grafana, logging, health checks, runbooks |

---

## Featured Projects

### 01. AADSec — Local-First DevSecOps Audit Tool (Founder)

**Website:** [aadsec.xyz](https://aadsec.xyz) · **Repository:** [aadsec-public](https://github.com/aadieng100/aadsec-public)  
**Focus:** Product Engineering, Security Tooling, CLI Design, Docker, CI/CD

A proprietary local-first audit CLI that orchestrates trusted open-source scanners (Gitleaks, Trivy, Semgrep, Checkov) over a codebase, prioritizes findings, and produces actionable reports — without uploading source code.

- Runs scans in ephemeral containers with read-only source mounts; nothing leaves the machine.
- Generates dual-view reports: executive risk view (P0–P3) and developer view with concrete fixes.
- Ships as signed binaries with SHA-256 verification, CycloneDX SBOM, and multi-platform installers.
- Currently in private beta — live demo report available on the repo.

---

### 02. Tetris Optimizer — Go Algorithmic Optimization Engine

**Repository:** [tetris-optimizer](https://github.com/aadieng100/tetris-optimizer)  
**Focus:** Go, Algorithms, Backtracking, Performance Optimization, Testing

A high-performance constraint-satisfaction solver that packs tetrominoes into the smallest possible square.

- Reduced solver runtime from 36s to under 10ms (>3,500× speedup) using symmetry breaking, cell-first backtracking DFS, and empty-space pruning.
- Starts from the mathematically minimal board size and prunes search branches that exceed the maximum allowed empty cells.
- Validated correctness with an exhaustive test suite covering standard, complex, and edge-case boards plus negative test cases.

---

### 03. AI Evaluation Task Manager — LLM Benchmarking Platform

**Repository:** [AI_Evaluation_Task_Manager](https://github.com/aadieng100/AI_Evaluation_Task_Manager)  
**Focus:** TypeScript, NestJS, Prisma, PostgreSQL, React 18, Terraform

A full-stack platform for benchmarking and scoring LLM outputs side-by-side with strict evaluation workflows.

- Built a modular NestJS REST API with DTO validation, dependency injection, and Swagger/OpenAPI documentation.
- Enforced atomic evaluation submissions with `prisma.$transaction`, so review submission and task state transition can never be left inconsistent.
- Stored flexible multi-criteria metrics (Accuracy, Safety, Latency, Conciseness) in PostgreSQL JSONB without schema migration overhead.
- Wrote Terraform-ready AWS infrastructure (VPC, RDS PostgreSQL, App Runner) for reproducible deployment.

---

### 04. GPU Kernel Benchmark Suite — C++ Performance Engineering

**Repository:** [gpu-kernel-benchmark-suite](https://github.com/aadieng100/gpu-kernel-benchmark-suite)  
**Focus:** C++20, CUDA, Performance Tuning, Profiling

A GPU kernel optimization suite for GEMM workloads across C++20, CUDA, and WebGPU/WGSL.

- Implemented SRAM tiling and float4 SIMD optimizations with Nsight Compute profiling.
- Structured benchmarks for reproducible, comparable performance measurements.

---

### 05. Multi-Tier CI/CD Platform — Automated Delivery Workflows

**Repository:** [devsecops_project02](https://github.com/aadieng100/devsecops_project02)  
**Focus:** GitHub Actions, AWS, Terraform, Java, Spring Boot, Docker

A production-inspired CI/CD platform for automated build, test, security, and deployment workflows.

- Built a GitHub Actions pipeline with automated testing, secret scanning, SAST, IaC checks, container scans, DAST, deployment, and teardown.
- Designed a multi-tier AWS architecture with public ALB, private Auto Scaling Groups, and isolated RDS PostgreSQL.
- Implemented OIDC-based keyless AWS authentication and reusable Terraform modules.

---

### 06. GuardianPy — Python CLI Tooling

**Repository:** [guardianpy](https://github.com/aadieng100/guardianpy)  
**Focus:** Python, CLI Design, Policy-as-Code, CI/CD Gating

A local-first CLI tool that detects Dockerfile and Terraform misconfigurations before code reaches CI/CD.

- Built modular scanners for Dockerfile, Terraform, and AWS S3/IAM posture checks.
- Designed POSIX exit codes so the tool acts as a deterministic CI/CD gate.
- Generated Markdown reports and Slack/Discord notifications for developer feedback.

---

## Additional Projects

- [KubeSecure-GitOps](https://github.com/aadieng100/KubeSecure-GitOps) — Security-hardened GitOps platform on AWS EKS with Helm, ArgoCD, and Terraform.
- [devsecops_project01](https://github.com/aadieng100/devsecops_project01) — Ephemeral AWS developer environments with Terraform, GitHub Actions, Prometheus, Grafana, and automated teardown.

---

## Professional Background

- Founder & Creator of AADSec — local-first DevSecOps audit tool ([aadsec.xyz](https://aadsec.xyz))
- Technical Co-Founder & Lead Engineer at KaartSanté — digital health platform, Java/Spring Boot backend on AWS
- Software Engineering Program — Zone01 Dakar / 01Edu Framework (contract-based, project-driven, 50+ projects delivered)
- B.Sc. Computer Engineering & Software Engineering — UNIVERSAT
- Google Cybersecurity Professional Certificate
- EF SET English C1 Advanced

---

## Current Focus

- Growing AADSec from private beta to public launch
- Backend systems, algorithms, and performance optimization
- Developer tooling, CLI design, and reproducible engineering environments
- Secure software delivery and AI evaluation workflows

---

## Contact

- Website: [aadsec.xyz](https://aadsec.xyz)
- LinkedIn: [linkedin.com/in/aadieng](https://linkedin.com/in/aadieng)
- Email: [diengabdoulaziz110@gmail.com](mailto:diengabdoulaziz110@gmail.com)
