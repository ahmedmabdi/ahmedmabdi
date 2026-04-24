# Hi there, I'm Ahmed

I'm a DevOps Engineer with hands-on experience designing, automating, and deploying scalable cloud infrastructure on AWS. I work extensively with Terraform, Docker, Kubernetes, and GitHub Actions — building production-style CI/CD pipelines and infrastructure that prioritise reliability, security, and automation.

I enjoy solving real problems through clean infrastructure design and turning ideas into deployable systems that follow modern DevOps practices.

---

## About Me

- 2x AWS Certified — Cloud Practitioner & Solutions Architect Associate
- Hands-on experience deploying and managing cloud infrastructure on AWS
- Passionate about sustainability and leveraging cloud computing for efficient, environmentally conscious solutions
- Currently building real-world DevOps projects involving containerised workloads, IaC, GitOps workflows, and automated CI/CD pipelines
- Dedicated to continuous learning in cloud architecture, DevOps tooling, and scalable systems

---

## Tech Stack

**Cloud & Infrastructure:**
AWS (EKS, ECS, Fargate, EC2, DynamoDB, RDS, ALB, WAF, CloudFront, CodeDeploy, ECR, IAM, SSM, Route 53, VPC, VPC Endpoints, ACM, SNS, CloudWatch)

**DevOps & Automation:**
Docker · Kubernetes · Helm · Terraform · GitHub Actions · AWS CodeDeploy · CI/CD Pipelines

**Observability & Security:**
Prometheus · Grafana · CloudWatch · Container Insights · Trivy · WAF · OIDC Auth

**Development & Tools:**
Git · GitHub · Bash · Linux · VS Code · FastAPI · Python

---

## Projects

### [URL Shortener — Production AWS Deployment](https://github.com/ahmedmabdi/url-short-ecs)

A production-ready URL shortener API deployed on AWS ECS Fargate, built to demonstrate what a proper cloud deployment looks like — not just a working app, but a professionally architected one.

**Key highlights:**
- Private subnet ECS tasks with **no NAT Gateway** — all AWS service traffic routed through VPC Interface Endpoints (saving ~$32/month)
- **OIDC-based CI/CD** via GitHub Actions — no static AWS credentials stored anywhere
- **Blue/green deployments** with CodeDeploy and automatic rollback on health check failure
- **WAF at two layers** — attached to both CloudFront (global) and ALB (regional)
- Least-privilege IAM — task role scoped to a single DynamoDB table

`ECS Fargate` `DynamoDB` `CodeDeploy` `CloudFront` `WAF` `VPC Endpoints` `Terraform` `GitHub Actions`

---

### [EKS Web Analytics Platform](https://github.com/ahmedmabdi/eks-anyalytics-tool)

A production-style deployment of a full analytics application on Amazon EKS.

**Key highlights:**
- Secure infrastructure provisioned with Terraform
- Helm chart deployments with GitHub Actions pipelines
- Pod Identity / IRSA for fine-grained AWS permissions
- Prometheus and Grafana monitoring stack

`EKS` `Helm` `Terraform` `Prometheus` `Grafana` `IRSA` `GitHub Actions`

---

### [ECS Umami Web Analytics App](https://github.com/ahmedmabdi/ecs-umami-app)

A containerised analytics solution deployed on AWS ECS Fargate using Terraform and CI/CD pipelines.

**Key highlights:**
- Automated environment provisioning and secure networking
- Service discovery and continuous delivery pipeline

`ECS Fargate` `Terraform` `Docker` `GitHub Actions` `CI/CD`

---

I love turning **ideas into deployable, real-world systems** — and I'm always looking to work on projects that blend **cloud engineering, DevOps, and sustainability**.
