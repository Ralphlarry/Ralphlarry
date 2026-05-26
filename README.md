# Hi, I'm Lanre 

**Aspiring DevOps Engineer** · Lagos, Nigeria · 18 years in IT infrastructure → Cloud & DevOps

I spent 18 years managing physical servers, networks, and DR systems in Oil & Gas — and I've spent the last year rebuilding that foundation in the cloud. I document everything I build, including the mistakes.

---

## 🔧 What I Work With

**Containers & Orchestration**
Docker · Kubernetes (AKS, Kind) · Helm · Docker Compose

**Infrastructure as Code**
Terraform · Ansible

**CI/CD**
Azure Pipelines · GitHub Actions

**Cloud**
Microsoft Azure (AKS, Azure OpenAI, VM, Load Balancer) · AWS (EC2, S3, IAM, VPC)

**Observability**
Prometheus · Grafana

**Scripting**
Bash · PowerShell

**AI/Agents**
Spring AI · Azure OpenAI · Claude API

---

## 📁 DMI Cohort 2 Portfolio

11 repositories covering everything I built during the [DevOps Micro Internship](https://pravinmishra.com/dmi) at The CloudAdvisory Oy (Finland).

| # | Repository | What it covers |
|---|-----------|---------------|
| 01 | [linux-devops-foundations](https://github.com/Ralphlarry/linux-devops-foundations) | EC2 provisioning, Nginx, production health checks |
| 02 | [git-github-devops](https://github.com/Ralphlarry/git-github-devops) | Branching, conventional commits, fork-PR collaboration |
| 03 | [aws-cloud-architecture](https://github.com/Ralphlarry/aws-cloud-architecture) | S3, EC2+RDS, ALB+ASG, three-tier architecture |
| 04 | [azure-cloud-architecture](https://github.com/Ralphlarry/azure-cloud-architecture) | Azure VM, Load Balancer, MySQL Flexible Server, Bastion |
| 05 | [agentic-ai-devops-claude-code](https://github.com/Ralphlarry/agentic-ai-devops-claude-code) | Claude Code for DevOps: CLAUDE.md, Skills, MCP servers |
| 06 | [terraform-infrastructure-as-code](https://github.com/Ralphlarry/terraform-infrastructure-as-code) | Azure VM, AWS EC2, modular VPC, three-tier ALB+ASG+RDS |
| 07 | [ansible-configuration-management](https://github.com/Ralphlarry/ansible-configuration-management) | Ad-hoc commands, Nginx playbook, roles |
| 08 | [azure-devops-cicd-pipelines](https://github.com/Ralphlarry/azure-devops-cicd-pipelines) | Self-hosted agent, multi-stage Build→Test→Deploy, AKS |
| 09 | [docker-containerization](https://github.com/Ralphlarry/docker-containerization) | Multi-stage builds (2.12GB→94MB), Compose, monitoring |
| 10 | [kubernetes-fundamentals](https://github.com/Ralphlarry/kubernetes-fundamentals) | Deployments, HPA, probes, ClusterIP/NodePort/LoadBalancer |
| 11 | [spring-petclinic-genai-chatbot](https://github.com/Ralphlarry/spring-petclinic-genai-chatbot) ⭐ | GenAI chatbot on AKS — Spring AI + Azure OpenAI + Helm |

---

## ⭐ Flagship Project — PETC-708: GenAI PetClinic Chatbot

Integrated a production GenAI chatbot into a Spring Boot microservices app deployed on AKS.

**Stack:** Spring Boot · Spring AI · Azure OpenAI (GPT-4o-mini + text-embedding-ada-002) · Docker · Terraform · AKS · Helm · Azure Pipelines · Grafana

**Real problems I solved:**
- ISP blocking Docker Hub pulls → used `az acr import` to mirror images via Azure
- Reactive threading crash in Spring AI → fixed with `Mono.fromCallable` + `boundedElastic` scheduler
- Exposed API key committed to git → scrubbed with `git filter-repo`
- Empty vector store responses → diagnosed embedding model mismatch, corrected model config

**[→ See the repo](https://github.com/Ralphlarry/spring-petclinic-genai-chatbot)**

---

## 🏗️ Other Projects

**[epicbook-app](https://github.com/Ralphlarry/epicbook-app)** — Full-stack Node.js/Express + MySQL + Nginx, containerised with multi-stage Docker builds. Image size: 2.12GB → 94MB.

**[epicbook-infra](https://github.com/Ralphlarry/epicbook-infra)** — Azure DevOps 4-stage CI/CD pipeline for EpicBook: Build → Test → Staging → Production with manual approval gate.

---

## 📫 Get in Touch

- **LinkedIn:** [linkedin.com/in/olanrewaju-awe-62761758](https://www.linkedin.com/in/olanrewaju-awe-62761758)
- **Email:** ralphnetwork@gmail.com
- **Location:** Lagos, Nigeria · Open to remote globally

---

*Currently open to DevOps / Cloud Engineer roles. If you're looking for someone who can bridge deep infrastructure experience with modern cloud-native tooling, let's talk.*
