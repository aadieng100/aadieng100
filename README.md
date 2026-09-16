# Abdoul Aziz Dieng

### Software Engineer — Backend, Algorithms & Performance
Dakar, Senegal · Open to Remote & International Opportunities

I build and optimize backend systems across Go, Java, Python, and TypeScript — from a Go constraint-satisfaction solver optimized 3,500× (36s → under 10ms) to reproducible Docker-based CI/CD platforms and a full-stack LLM output benchmarking tool.

My focus is on algorithms, performance optimization, debugging, and test-driven systems that behave deterministically — backed by strong CI/CD, container, and cloud delivery practices.

---

## Core Stack

| Area | Tools |
| :--- | :--- |
| Languages | Go, Java, Python, TypeScript, Rust |
| Backend & Data | Spring Boot, NestJS, Prisma, PostgreSQL, REST APIs |
| Algorithms & Testing | Data structures, backtracking/DFS, search pruning, unit testing, edge-case validation, debugging |
| Containers & CI/CD | Docker, Docker Compose, Kubernetes, Helm, GitHub Actions, AWS CodePipeline, ArgoCD |
| Cloud & IaC | AWS (EKS, EC2, ALB, RDS, S3, IAM, KMS), Terraform, Linux, Bash |
| Security | SAST, SCA, DAST, secret scanning, Semgrep, Trivy, OWASP ZAP |
| Observability | Prometheus, Grafana, logging, health checks, runbooks |

---

## Featured Projects

### 01. Tetris Optimizer — Go Algorithmic Optimization Engine

**Repository:** [tetris-optimizer](https://github.com/aadieng100/tetris-optimizer)  
**Focus:** Go, Algorithms, Backtracking, Performance Optimization, Testing

A high-performance constraint-satisfaction solver that packs tetrominoes into the smallest possible square.

- Reduced solver runtime from 36s to under 10ms (>3,500× speedup) using symmetry breaking, cell-first backtracking DFS, and empty-space pruning.
- Starts from the mathematically minimal board size and prunes search branches that exceed the maximum allowed empty cells.
- Validated correctness with an exhaustive test suite covering standard, complex, and edge-case boards plus negative test cases (invalid formats, disconnected shapes).

---

### 02. AI Evaluation Task Manager — LLM Benchmarking Platform

**Repository:** [AI_Evaluation_Task_Manager](https://github.com/aadieng100/AI_Evaluation_Task_Manager)  
**Focus:** TypeScript, NestJS, Prisma, PostgreSQL, React 18, Terraform

A full-stack platform for benchmarking and scoring LLM outputs side-by-side (e.g., Claude vs GPT-4o vs Llama) with strict evaluation workflows.

- Built a modular NestJS REST API with DTO validation, dependency injection, and Swagger/OpenAPI documentation.
- Enforced atomic evaluation submissions with `prisma.$transaction`, so a review submission and task state transition can never be left inconsistent.
- Stored flexible multi-criteria metrics (Accuracy, Safety, Latency, Conciseness) in PostgreSQL JSONB without schema migration overhead.
- Wrote Terraform-ready AWS infrastructure (VPC, RDS PostgreSQL, App Runner) for reproducible deployment.

---

### 03. GPU Kernel Benchmark Suite — C++ Performance Engineering

**Repository:** [gpu-kernel-benchmark-suite](https://github.com/aadieng100/gpu-kernel-benchmark-suite)  
**Focus:** C++20, CUDA, Performance Tuning, Profiling

A GPU kernel optimization suite for GEMM workloads across C++20, CUDA, and WebGPU/WGSL.

- Implemented SRAM tiling and float4 SIMD optimizations with Nsight Compute profiling.
- Structured benchmarks for reproducible, comparable performance measurements.

---

### 04. KubeSecure-GitOps — Reproducible Kubernetes Platform

**Repository:** [KubeSecure-GitOps](https://github.com/aadieng100/KubeSecure-GitOps)  
**Focus:** AWS EKS, Terraform, Helm, ArgoCD, GitOps

A security-hardened GitOps platform that deploys a Spring Boot API to AWS EKS using Terraform, Helm, ArgoCD, Docker, and Amazon RDS PostgreSQL.

- Built a Kubernetes GitOps workflow with Helm charts and ArgoCD reconciliation.
- Provisioned AWS networking, EKS node groups, and encrypted RDS PostgreSQL with reusable Terraform modules.
- Hardened containers with multi-stage builds, non-root execution, read-only filesystem, and least-privilege NetworkPolicies.

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

- [devsecops_project01](https://github.com/aadieng100/devsecops_project01) — Ephemeral AWS developer environments with Terraform, GitHub Actions, Prometheus, Grafana, and automated teardown.
- [aadsec-public](https://github.com/aadieng100/aadsec-public) — Local-first audit CLI that runs trusted scanners and turns noisy results into readable reports.

---

## Professional Background

- Technical Co-Founder & Lead Engineer at KaartSanté — digital health platform, Java/Spring Boot backend on AWS
- Software Engineering Program — Zone01 Dakar / 01Edu Framework (contract-based, project-driven)
- B.Sc. Computer Engineering & Software Engineering — UNIVERSAT
- Google Cybersecurity Professional Certificate
- EF SET English C1 Advanced

---

## Current Focus

- Backend systems, algorithms, and performance optimization
- Developer tooling, CLI design, and reproducible engineering environments
- AI evaluation and training data workflows
- Debugging, testing, and clean-code practices across polyglot codebases

---

## Contact

- LinkedIn: [linkedin.com/in/aadieng](https://linkedin.com/in/aadieng)
- GitHub: [github.com/aadieng100](https://github.com/aadieng100)
- Email: [diengabdoulaziz110@gmail.com](mailto:diengabdoulaziz110@gmail.com)
