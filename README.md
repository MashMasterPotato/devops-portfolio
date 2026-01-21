# DevOps / Cloud Portfolio — Marcel

I’m transitioning into **DevOps / Cloud** after working as an **Application Manager** and currently as a **Network Security Engineer**.  
This portfolio demonstrates hands-on skills in **cloud and hybrid infrastructure, containers, CI/CD, Kubernetes, IaC, and DevSecOps**, with a strong focus on **security, automation, and cost control**.

I work **local-first** and run real Kubernetes environments using **k3s** on **Raspberry Pi** and **macOS**, applying the same patterns used in managed cloud platforms.

## What you’ll find here
- Practical projects with **clean READMEs**, reproducible steps, and clear “why” explanations
- **Secure-by-default** infrastructure, node hardening, and deployments
- **Automation-first** workflows using Ansible, CI/CD, Helm, and Terraform
- **Cost-safe** usage: local environments and short-lived cloud resources only

## Skills demonstrated
- **Cloud & Hybrid Infrastructure:** IAM, networking, compute, storage, logging/monitoring (AWS or Azure concepts)
- **Linux & automation:** bash, services, troubleshooting, **Ansible (idempotent configuration)**
- **Containers:** Docker, registries, image hardening
- **CI/CD:** GitHub Actions pipelines, secrets management, automated builds & deployments
- **Kubernetes:** k3s (local & bare metal), manifests, ingress, config/secrets, troubleshooting
- **Helm:** templating, values, versioned releases, rollback strategies
- **Infrastructure as Code:** Terraform provisioning and teardown workflows
- **DevSecOps:** least privilege, image scanning, secure defaults, policy-driven design

## Projects (overview)
> Each project includes: goal → architecture → steps → key decisions → improvements.

1. **Infrastructure Basics (Cloud & Bare Metal)**  
   Secure VM and node setup, networking, and IAM fundamentals with a cost-aware approach.  
   → `projects/cloud-infra-basics.md`

2. **Containerized App**  
   Dockerfile (multi-stage), non-root execution, healthchecks.  
   → `projects/containerized-app.md`

3. **CI/CD Pipeline**  
   Automated build, test, and image publishing with proper secrets handling.  
   → `projects/ci-cd-pipeline.md`

4. **Kubernetes on k3s (Raw Manifests)**  
   Application deployment on k3s using Deployment, Service, Ingress, ConfigMap, and Secret.  
   → `projects/kubernetes-manifests.md`

5. **Helm Chart**  
   Refactor raw Kubernetes manifests into a reusable Helm chart with dev/prod values and rollback support.  
   → `projects/helm-chart.md`

6. **Terraform Platform**  
   Infrastructure provisioning using Terraform with apply/destroy workflows and cost controls.  
   → `projects/terraform-platform.md`

7. **DevSecOps Tooling**  
   Security scanning, policy enforcement, and hardening practices (optional Go-based tooling).  
   → `projects/devsecops-tooling.md`

## How to run projects
Each project repository includes:
- prerequisites
- setup steps
- commands to run
- teardown steps (where applicable)

## Cost & safety notes
- Local-first Kubernetes using k3s (Raspberry Pi and macOS) to keep costs near zero
- Cloud resources are created only when required and destroyed immediately
- Secrets are never committed to git

## Contact
- LinkedIn: tbd
- CV: tbd
