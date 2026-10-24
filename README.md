<h1 align="center">Arjun More</h1>

<p align="center">
  <b>Cloud &amp; DevOps Engineer</b><br/>
  I build cloud infrastructure that is automated, secure by default, and tested before it ships.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/arjun-more-473557285/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:Arjunmorepatil88@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Location-Pune%2C%20India-555555?style=flat-square&logo=googlemaps&logoColor=white" alt="Pune, India"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS Certified Solutions Architect – Associate"/>
  <img src="https://img.shields.io/badge/Microsoft%20Certified-Azure%20Administrator%20(AZ--104)-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure Administrator AZ-104"/>
</p>

---

### About

IT Infrastructure Engineer transitioning into Cloud and DevOps, with a background in server management, hardware validation and Linux administration. I treat infrastructure like software: defined as code, reviewed in Git, validated in CI, and documented with runbooks so the next engineer can operate it.

**Focus areas:** AWS & Azure infrastructure · Infrastructure as Code · Containers · CI/CD · Linux operations · Cost and security hygiene
**Currently learning:** Kubernetes (EKS/AKS) · Ansible · GitOps

---

### Featured Projects

#### ☁️ [aws-lab](https://github.com/Arjunmore88/aws-lab) — Highly available web platform on AWS
`CloudFormation` `Python` `boto3` `Lambda` `CloudWatch` `IAM`
- Multi-AZ VPC, Application Load Balancer and Auto Scaling group across 4 modular CloudFormation stacks
- CloudWatch alarms and dashboard with SNS alerting for 5xx errors, unhealthy hosts and CPU
- Lambda automation: office-hours EC2 scheduler and a weekly cost-hygiene report (idle EBS, EIPs, old snapshots)
- Least-privilege IAM policies, private instances accessed via SSM (no SSH), unit tests with moto

#### 🏗️ [terraform-lab](https://github.com/Arjunmore88/terraform-lab) — Modular AWS infrastructure with Terraform
`Terraform` `AWS` `GitHub Actions` `TFLint`
- Reusable VPC, EC2 and S3 modules composed per environment
- Secure defaults: IMDSv2, encrypted storage, S3 public-access block, SSM instead of SSH
- CI runs `fmt`, `validate` and TFLint on every push; remote state with S3 locking ready to enable

#### 🐳 [docker-lab](https://github.com/Arjunmore88/docker-lab) — Production-ready containerised API
`Docker` `Compose` `Nginx` `PostgreSQL` `Trivy` `GHCR`
- Multi-stage, non-root images with health checks; Nginx reverse proxy with security headers
- Isolated networks so the database is never exposed; health-gated startup order
- CI pipeline: lint → test → build → Trivy vulnerability scan → publish to GitHub Container Registry

#### 🐧 [linux-admin-lab](https://github.com/Arjunmore88/linux-admin-lab) — Linux fleet baseline for Ubuntu & RHEL
`Bash` `systemd` `Ubuntu` `Rocky Linux` `Bats`
- Idempotent scripts for user on/offboarding, SSH hardening (validated with auto-rollback), firewall and backups
- Health checks run by a hardened systemd timer; runbooks for disk-full, high load, SSH lockout, LVM extend
- Blameless incident postmortem; 49 automated tests across Ubuntu 22.04, 24.04 and Rocky Linux 9

---

### Tech Stack

| | |
|---|---|
| **Cloud** | AWS (EC2, VPC, S3, IAM, ALB, Auto Scaling, CloudWatch, Lambda, SSM) · Azure |
| **IaC & Config** | Terraform · CloudFormation · Ansible |
| **Containers** | Docker · Docker Compose · Kubernetes |
| **CI/CD** | GitHub Actions · Jenkins |
| **OS & Systems** | Linux (Ubuntu, Debian, RHEL/Rocky) · systemd · VMware · Hyper-V |
| **Scripting** | Bash · Python · PowerShell |
| **Web & Data** | Nginx · Apache · PostgreSQL · MySQL |
| **Security & Quality** | IAM least privilege · Trivy · ShellCheck · TFLint · pytest |

---

### Engineering Principles

- **Automate the second time** — repeated work becomes a script, module or pipeline
- **Secure by default** — least privilege, encryption on, no secrets in code
- **Prove it in CI** — every change is linted and tested before it merges
- **Write it down** — clear READMEs, runbooks and blameless postmortems

---

<p align="center">
  <b>Open to Cloud Engineer, DevOps Engineer and Linux/Cloud Operations roles.</b><br/>
  <a href="https://www.linkedin.com/in/arjun-more-473557285/">LinkedIn</a> · <a href="mailto:Arjunmorepatil88@gmail.com">Email</a>
</p>
