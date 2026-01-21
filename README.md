# DevOps / Cloud Portfolio — Marcel

I’m transitioning into **DevOps / Cloud** after working as an **Application Manager** and currently as a **Network Security Engineer**.  
This portfolio demonstrates hands-on skills in **cloud infrastructure, containers, CI/CD, Kubernetes, IaC, and DevSecOps** with a strong focus on **security and cost control**.

## What you’ll find here
- Practical projects with **clean READMEs**, reproducible steps, and “why” explanations
- A focus on **secure-by-default** infrastructure and deployments
- **Cost-safe** usage (local-first, short-lived cloud resources)

## Skills demonstrated
- **Cloud:** IAM, networking, compute, storage, logging/monitoring (AWS or Azure)
- **Linux & scripting:** bash, services, troubleshooting
- **Containers:** Docker, registries, image hardening
- **CI/CD:** GitHub Actions pipelines, secrets, automated builds/deployments
- **Kubernetes:** manifests, ingress, config/secrets, troubleshooting
- **Helm:** templating, values, versioned releases, rollback
- **IaC:** Terraform provisioning and teardown workflows
- **DevSecOps:** least privilege, scanning, secure configs

## Projects (overview)
> Each project has: goal → architecture → steps → key decisions → improvements.

1. **Cloud Infrastructure Basics**  
   Secure VM + networking + IAM fundamentals (cost-safe).  
   → `projects/cloud-infra-basics.md`

2. **Containerized App**  
   Dockerfile (multi-stage), non-root, healthchecks.  
   → `projects/containerized-app.md`

3. **CI/CD Pipeline**  
   Automated build/test/push with secrets handling.  
   → `projects/ci-cd-pipeline.md`

4. **Kubernetes Manifests (Raw YAML)**  
   Deploy app with Deployment/Service/Ingress/ConfigMap/Secret.  
   → `projects/kubernetes-manifests.md`

5. **Helm Chart**  
   Refactor raw manifests into Helm with dev/prod values + rollback.  
   → `projects/helm-chart.md`

6. **Terraform Platform**  
   Provision infra with Terraform; apply + destroy workflows.  
   → `projects/terraform-platform.md`

7. **DevSecOps Tooling**  
   Scanning, policies, and security enhancements (optional Go tooling).  
   → `projects/devsecops-tooling.md`

## How to run projects
Each project repo includes:
- prerequisites
- setup steps
- commands to run
- teardown steps (where applicable)

## Cost & safety notes
- Local-first approach for Kubernetes (kind/minikube) to keep costs near zero
- Cloud resources are created only when needed and destroyed immediately
- Secrets are never committed to git

## Contact
- LinkedIn: <LINK>
- Email: <EMAIL>
- CV: <LINK if you have one>

