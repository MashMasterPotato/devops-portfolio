# DevOps / Cloud Portfolio — Marcel

I’m transitioning into **DevOps / Cloud / Platform Engineering** after working as an **Application Manager** and currently as a **Network Security Engineer**.  
This portfolio demonstrates hands-on experience across **infrastructure fundamentals, automation, Kubernetes platforms, CI/CD, and DevSecOps**, with a strong focus on **security, reliability, and cost control**.

I follow a **local-first, automation-driven** approach and run real Kubernetes environments using **k3s** on **Raspberry Pi** and **macOS**, applying the same design principles used in managed cloud platforms.

---

## What you’ll find here
- Practical projects with **clean READMEs**, diagrams, and clear “why” explanations  
- **Infrastructure-first thinking** before automation and platforms  
- **Configuration management** using Ansible for repeatable node bootstrapping  
- **Kubernetes platform engineering** using k3s, Helm, and CI/CD  
- **Security-by-default** and **cost-aware** design choices  

---

## Skills demonstrated
- **Infrastructure fundamentals:** networking, access models, firewalling, resource constraints (cloud & bare metal)
- **Linux & automation:** bash, services, troubleshooting, **Ansible (idempotent configuration)**
- **Containers:** Docker, image hardening, registries
- **CI/CD:** GitHub Actions pipelines, secrets management, automated build & deploy workflows
- **Kubernetes:** k3s (local & bare metal), manifests, ingress, config/secrets, troubleshooting
- **Helm:** templating, environment-specific values, versioned releases, rollback strategies
- **Infrastructure as Code:** Terraform concepts, modular design, apply/destroy workflows
- **DevSecOps:** least privilege, image scanning, secure defaults, policy-aware design

---

## Project roadmap
> Each project includes: **goal → architecture → implementation → key decisions → improvements**

1. **Infrastructure Basics (Cloud & Bare Metal)**  
   Core infrastructure concepts: networking, access, firewalling, and cost-aware design.  
   → `projects/infra-basics.md`

2. **Ansible Node Bootstrap**  
   Automated, idempotent Linux node preparation and hardening for Kubernetes.  
   → `projects/ansible-node-bootstrap.md`

3. **k3s Kubernetes Cluster**  
   Building and operating a lightweight Kubernetes platform on prepared nodes.  
   → `projects/k3s-cluster.md`

4. **Containerized Application**  
   Application containerization with secure Docker practices.  
   → `projects/containerized-app.md`

5. **CI/CD Pipeline**  
   Automated build, test, and image publishing with proper secrets handling.  
   → `projects/ci-cd-pipeline.md`

6. **Kubernetes Manifests (Raw YAML)**  
   Application deployment on k3s using core Kubernetes primitives.  
   → `projects/kubernetes-manifests.md`

7. **Helm Chart**  
   Refactoring raw manifests into reusable, versioned Helm charts with rollback support.  
   → `projects/helm-chart.md`

8. **Terraform Platform (Optional / Cloud)**  
   Infrastructure provisioning concepts using Terraform with cost controls and teardown workflows.  
   → `projects/terraform-platform.md`

9. **DevSecOps Tooling**  
   Security scanning, hardening, and policy-driven improvements across the platform.  
   → `projects/devsecops-tooling.md`

---

## How to run projects
Each project repository includes:
- prerequisites
- setup steps
- commands to run
- teardown steps (where applicable)

---

## Cost & safety notes
- **Local-first Kubernetes** using k3s on Raspberry Pi and macOS to minimize cost
- Cloud resources are created only when required and destroyed immediately
- Secrets are never committed to git

---

## Design philosophy
- Infrastructure before automation
- Automation before platforms
- Platforms before applications
- Security and least privilege by default
- Cloud-native patterns that also work on bare metal

---

## Contact
- LinkedIn: tbd
