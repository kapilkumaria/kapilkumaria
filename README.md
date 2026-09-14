# 👨‍💻 Kapil Kumaria

### Senior DevOps Engineer | AWS & Azure | Kubernetes | Platform Engineering | SRE

📍 Calgary, Alberta, Canada

I design and build **cloud-native infrastructure, Kubernetes platforms, CI/CD systems, GitOps workflows, DevSecOps controls, observability platforms, FinOps governance, and MLOps infrastructure** across AWS and Azure.

My engineering approach focuses on **automation, repeatability, security, observability, scalability, and operational reliability**, using Infrastructure as Code, CI/CD, and GitOps principles wherever practical.

[![Portfolio](https://img.shields.io/badge/Portfolio-kapilkumaria.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kapilkumaria.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kapil%20Kumaria-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kkintech15/)
[![GitHub](https://img.shields.io/badge/GitHub-kapilkumaria-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kapilkumaria)

---

## 🚀 Engineering Portfolio

My portfolio consists of **eight hands-on engineering projects** covering the progression from application delivery and CI/CD to Kubernetes platform engineering, Internal Developer Platforms, SRE/observability, multi-cloud FinOps/governance, and MLOps.

Each repository includes implementation details, architecture decisions, Infrastructure as Code, automation, security considerations, troubleshooting documentation, and supporting engineering evidence.

### 1️⃣ Cloud-Native Application Delivery & Containerization

**Focus:** Application delivery, containers, CI/CD, cloud deployment, and infrastructure automation

Built a cloud-native application delivery workflow demonstrating how application code moves from source control through build, containerization, automated validation, infrastructure provisioning, and deployment.

The project uses separate repositories for the **application, infrastructure, and Kubernetes configuration**, demonstrating separation of concerns across the application and platform delivery lifecycle.

**Engineering areas:**  
`Docker` • `CI/CD` • `AWS` • `Terraform` • `Kubernetes` • `Git` • `Automation`

🔗 **Repositories:**

- 🔹 [Application Repository](https://github.com/kapilkumaria/cloud-native-devops-platform-app)
- 🔹 [Infrastructure Repository](https://github.com/kapilkumaria/cloud-native-devops-platform-infra)
- 🔹 [Kubernetes Repository](https://github.com/kapilkumaria/cloud-native-devops-platform-kubernetes)

---

### 2️⃣ Enterprise GitOps & DevSecOps Platform

**Focus:** Automated delivery, GitOps, security controls, and declarative operations

Designed an enterprise-style delivery platform that integrates CI/CD automation with security scanning and GitOps-based deployment practices.

The project demonstrates separation between application delivery and runtime configuration while using automated quality and security controls before workloads reach production environments.

**Engineering areas:**  
`CI/CD` • `GitOps` • `DevSecOps` • `Kubernetes` • `Terraform` • `Security Automation`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/enterprise-gitops-devsecops-platform)

---

### 3️⃣ Enterprise Kubernetes Platform — AWS EKS

**Focus:** Production-oriented Kubernetes platform engineering on AWS

Built an Amazon EKS platform using Infrastructure as Code and GitOps, incorporating workload delivery, policy enforcement, secrets integration, autoscaling, ingress/gateway management, DNS automation, and platform observability.

**Key capabilities:**

- Amazon EKS infrastructure provisioning
- Terraform-based Infrastructure as Code
- Argo CD GitOps delivery
- Helm-based platform components
- Gateway API and Traefik
- Kyverno policy enforcement
- KEDA workload autoscaling
- Karpenter node provisioning
- External Secrets integration
- ExternalDNS automation
- Kubernetes metrics and observability

**Engineering areas:**  
`AWS` • `EKS` • `Kubernetes` • `Terraform` • `Argo CD` • `Helm` • `Karpenter` • `KEDA` • `Kyverno`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/eks-enterprise-kubernetes-platform)

---

### 4️⃣ Azure Enterprise DevOps Platform — AKS

**Focus:** Secure multi-environment application delivery on Microsoft Azure

Designed and implemented an Azure-based DevOps platform using AKS, Azure DevOps, ACR, Key Vault, Terraform, and Kubernetes.

The platform demonstrates controlled promotion across **development, staging, and production**, combined with container security scanning, workload identity, secrets management, infrastructure automation, and deployment approvals.

**Key capabilities:**

- Azure Kubernetes Service (AKS)
- Azure Container Registry (ACR)
- Azure Key Vault
- Azure Workload Identity / OIDC
- Azure DevOps YAML pipelines
- Dev → Staging → Production promotion
- Environment approvals
- Trivy filesystem and container image scanning
- Terraform infrastructure provisioning
- Kubernetes security hardening
- Private networking and secured Terraform state

**Engineering areas:**  
`Azure` • `AKS` • `Azure DevOps` • `Terraform` • `ACR` • `Key Vault` • `Kubernetes` • `Trivy`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/azure-enterprise-devops-platform)

---

### 5️⃣ Enterprise Internal Developer Platform

**Focus:** Platform engineering, developer self-service, and golden paths

Built an Internal Developer Platform architecture around Kubernetes and Backstage to demonstrate how platform engineering teams can provide standardized, reusable deployment paths to application teams.

The platform combines infrastructure automation, GitOps, Kubernetes, service templates, and developer-facing workflows to reduce cognitive load and encourage standardized delivery practices.

**Key capabilities:**

- Amazon EKS platform
- Backstage developer portal
- Golden-path service templates
- GitOps-based application delivery
- Terraform infrastructure modules
- Helm-based workload packaging
- AWS IAM and workload identity
- Developer self-service concepts
- Platform security and operational documentation

**Engineering areas:**  
`Platform Engineering` • `Backstage` • `AWS` • `EKS` • `Terraform` • `Kubernetes` • `GitOps` • `Helm`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/enterprise-internal-developer-platform)

---

### 6️⃣ Enterprise Observability & SRE Platform

**Focus:** Monitoring, reliability engineering, operational visibility, and incident readiness

Built an observability and SRE platform for Kubernetes workloads with infrastructure, application telemetry, dashboards, alerting, logging, security evidence, and operational documentation.

The project demonstrates the transition from simply deploying workloads to **operating and troubleshooting them reliably**.

**Key capabilities:**

- Metrics collection and visualization
- Prometheus monitoring
- Grafana dashboards
- Alerting workflows
- Centralized logging
- Kubernetes platform monitoring
- AWS CloudWatch integration
- VPC Flow Logs
- SRE-oriented monitoring and incident-response practices
- Security and vulnerability-management evidence
- Runbooks and troubleshooting documentation

**Engineering areas:**  
`SRE` • `Observability` • `Prometheus` • `Grafana` • `Alertmanager` • `Loki` • `AWS` • `Kubernetes`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/enterprise-observability-sre-platform)

---

### 7️⃣ Enterprise Multi-Cloud FinOps, Governance & Controlled Remediation

**Focus:** Cloud cost governance, policy enforcement, compliance, and controlled remediation across AWS and Azure

Designed a multi-cloud FinOps and governance platform that evaluates infrastructure before deployment, identifies policy and cost violations, enforces organizational standards, produces governance evidence, and provides controlled remediation workflows.

The platform intentionally keeps remediation governed and human-controlled rather than allowing unrestricted automated infrastructure changes.

**Key capabilities:**

- AWS + Azure governance
- Terraform-based multi-cloud infrastructure
- Infracost pre-deployment cost estimation
- Checkov policy/security validation
- Mandatory tagging standards
- Region governance
- Cost and compliance reporting
- Policy-as-Code
- Drift validation
- Remediation recommendation engine
- Human-approved controlled remediation

**Engineering areas:**  
`FinOps` • `AWS` • `Azure` • `Terraform` • `Infracost` • `Checkov` • `Governance` • `Policy as Code`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/enterprise-multicloud-finops-governance)

---

### 8️⃣ Enterprise MLOps Platform — Customer Churn

**Focus:** Reproducible machine-learning delivery and MLOps platform engineering

Built an MLOps platform around a customer-churn use case to demonstrate how DevOps and platform engineering principles extend into the machine-learning lifecycle.

The project focuses on reproducibility, dataset versioning, experiment/model lifecycle management, containerized services, automated validation, and Kubernetes/cloud-oriented ML deployment patterns.

**Key capabilities:**

- Reproducible Python environment
- Version-controlled datasets with DVC
- Deterministic data preparation
- ML training and evaluation workflow
- MLflow experiment/model lifecycle
- Automated testing and validation
- Containerized ML workloads
- Kubernetes-oriented ML platform concepts
- Kubeflow workflow/platform integration
- KServe model-serving concepts
- Amazon SageMaker integration concepts

**Engineering areas:**  
`MLOps` • `Python` • `DVC` • `MLflow` • `Docker` • `Kubernetes` • `Kubeflow` • `KServe` • `SageMaker`

🔗 **Repository:** [View Project](https://github.com/kapilkumaria/enterprise-mlops-platform)

---

## 🏗️ What These Projects Demonstrate

```text
Application Delivery
        │
        ▼
CI/CD & DevSecOps
        │
        ▼
Infrastructure as Code
        │
        ▼
Kubernetes Platform Engineering
        │
        ▼
GitOps & Automated Operations
        │
        ▼
Internal Developer Platforms
        │
        ▼
Observability & SRE
        │
        ▼
FinOps & Multi-Cloud Governance
        │
        ▼
MLOps Platform Engineering
```
Together, these projects demonstrate my approach to designing platforms across the complete engineering lifecycle — **provision, secure, deploy, operate, observe, govern, optimize, and automate**.


## 🧰 Technical Stack
### ☁️ Cloud Platforms

`AWS`: EC2, EKS, VPC, IAM, S3, RDS, Route 53, CloudFront, CloudWatch, ECR

`Azure`: AKS, ACR, Key Vault, Azure DevOps, Azure Monitor, VNets, Managed Identities

`GCP`: GKE

### ☸️ Containers & Kubernetes

`Docker` • `Kubernetes` • `EKS` • `AKS` • `GKE` • `Helm` • `Kustomize` • `Gateway API` • `Traefik`

### 🏗️ Infrastructure as Code & Configuration

`Terraform` • `AWS CloudFormation` • `Ansible` • `Packer`

## 🔄 CI/CD & GitOps

`GitHub Actions` • `Jenkins` • `GitLab CI` • `Azure DevOps` • `Argo CD`

### 🔐 DevSecOps & Cloud Security

`Trivy` • `Checkov` • `SonarQube` • `Kyverno` • `IAM` • `RBAC` • `OIDC` • `Workload Identity` • `External Secrets`

### 📊 Observability & SRE

`Prometheus` • `Grafana` • `Alertmanager` • `Loki` • `CloudWatch` • `Kubernetes Metrics`

### 💰 FinOps & Governance

`Infracost` • `Checkov` • `Policy as Code` • `Cloud Cost Controls` • `Tag Governance` • `Controlled Remediation`

### 🤖 MLOps

`DVC` • `MLflow` • `Kubeflow` • `KServe` • `Amazon SageMaker` • `scikit-learn`

### 💻 Programming, Scripting & Development

`Python` • `Bash` • `Git` • `Linux` • `Node.js` • `FastAPI`

---

## 🎯 Core Engineering Competencies

- **Cloud Architecture** — Designing secure and scalable infrastructure across AWS and Azure
- **Infrastructure as Code** — Building reproducible infrastructure with Terraform and modular IaC patterns
- **Kubernetes Platform Engineering** — EKS/AKS, workload delivery, networking, autoscaling, policy and security
- **CI/CD Engineering** — Automated build, validation, security scanning, deployment and environment promotion
- **GitOps** — Declarative Kubernetes delivery and reconciliation using Argo CD
- **DevSecOps** — Integrating security scanning and policy enforcement into delivery workflows
- **Platform Engineering** — Developer platforms, golden paths and standardized application delivery
- **SRE & Observability** — Metrics, logging, alerting, dashboards, troubleshooting and operational readiness
- **FinOps & Governance** — Cost visibility, policy enforcement, compliance and controlled remediation
- **MLOps** — Applying DevOps principles to reproducible ML training, model lifecycle and serving workflows

---

## 📜 Certifications & Continuous Learning
☁️ AWS Certified Solutions Architect – Associate

☁️ AWS Certified Developer – Associate

🐧 Linux Professional Institute — Linux Essentials

🤖 Google AI Essentials

🔷 Microsoft Azure administration and cloud engineering — ongoing professional development

I continuously build hands-on platforms to deepen my understanding of cloud architecture, Kubernetes, automation, reliability engineering, security, FinOps, and MLOps.

---

## 🌐 Portfolio

### [kapilkumaria.com](https://kapilkumaria.com)

My portfolio contains selected cloud and DevOps engineering projects with architecture, implementation details, technology decisions, and links to the corresponding GitHub repositories.
---

## 📊 GitHub Activity
<p align="left"> <img height="170" src="https://github-readme-stats.vercel.app/api?username=kapilkumaria&show_icons=true&theme=github_dark&hide_border=true" alt="Kapil Kumaria GitHub statistics" /> <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kapilkumaria&layout=compact&theme=github_dark&hide_border=true" alt="Kapil Kumaria top languages" /> </p>

---

## 🤝 Connect With Me

I am interested in opportunities involving **Senior DevOps Engineering, Cloud Engineering, Platform Engineering, Kubernetes, SRE, and cloud-native infrastructure**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kkintech15/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kapilkumaria.com)

---

> **Engineering philosophy:** Automate repeatable work, keep infrastructure declarative, build security into delivery, make systems observable, and design platforms that developers can operate confidently.

---

**Engineering philosophy:** Automate repeatable work, keep infrastructure declarative, build security into delivery, make systems observable, and design platforms that developers can operate confidently.