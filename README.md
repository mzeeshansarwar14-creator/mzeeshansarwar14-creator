# Hi 👋 I'm Muhammad Zeeshan Sarwar

**🚀 DevOps Engineer | CI/CD, AWS, Terraform, Docker & Kubernetes**

DevOps engineer focused on automating the path from commit to running infrastructure across CI/CD pipelines, Infrastructure as Code, containers, Linux servers, and observability. Backed by 3+ years of hands-on infrastructure, system administration, and networking experience, plus AZ-900 and CCNA certifications.

### 🧑‍💻 About Me
- 💻 **3+ years** in Linux/Windows Server administration, networking, firewalls, and IT support.
- ☁️ **Cloud & IaC:** Provisioning AWS infrastructure (EC2, VPC, Security Groups) with **Terraform** and configuring hosts with **Ansible**.
- 🔁 **CI/CD Pipelines:** Building multi-stage automation in **GitLab CI/CD** and **GitHub Actions** with container registries, artifacts, and manual approval gates.
- 🐳 **Containers & K3s:** Deploying multi-container stacks and Kubernetes workloads with **Docker**, **Docker Compose**, and **K3s** on Ubuntu.
- 📊 **Observability & Recovery:** Instrumenting Ubuntu servers with **Grafana Alloy**, **Prometheus**, and **Grafana Cloud**, and recovering servers from full-disk outages.

---

### ⚙️ Tech Stack & Tools

**Cloud, IaC & CI/CD**
<p>
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Microsoft%20Azure-%230078D4.svg?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Ansible-%23EE0000.svg?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
  <img src="https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI/CD"/>
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

**Containers, Monitoring & Servers**
<p>
  <img src="https://img.shields.io/badge/docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu"/>
  <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/>
  <img src="https://img.shields.io/badge/Apache-%23D22128.svg?style=for-the-badge&logo=apache&logoColor=white" alt="Apache"/>
</p>

---

### 🚀 DevOps Projects

**🔹 End-to-End Kubernetes (K3s) Delivery Pipeline**
- **Pipeline:** Four-stage **GitLab CI/CD** pipeline taking an application from commit to a running Kubernetes workload.
- **Infrastructure & Cluster:** **Terraform** provisions the AWS EC2 instance and passes its IP as a pipeline artifact; **Ansible** sets up **K3s** over SSH and applies manifests.
- **Registry & Teardown:** Publishes **Docker** images to GitLab Container Registry, with a manual-gate destroy stage to avoid lingering cloud costs.

**🔹 Multi-Container Application Delivery Pipeline**
- **Infrastructure:** **Terraform** provisions AWS EC2 and per-service Security Group rules.
- **Configuration & Stack:** **Ansible** installs Docker and Compose and ships config to the host to run a three-service stack (**React**, **MongoDB**, **Mongo-Express**) with persistent volumes across redeploys.
- **Troubleshooting:** Resolved real deployment issues including Docker port conflicts and Terraform dependency errors.

**🔹 Server Monitoring & Production Incident Recovery**
- **Observability:** Instrumented Ubuntu servers with **Grafana Alloy** to ship **Prometheus** metrics and system logs to **Grafana Cloud**, keeping agents running via `systemd`.
- **Incident Recovery:** Diagnosed (`journalctl`, `systemctl`, `du`, `df`) and resolved 100% disk utilization outages by pruning Docker build cache, resizing swap, and scheduling log rotation.

**🔹 Zero-Touch Deployment for a React Application**
- **Automation:** **GitHub Actions** workflow that builds and deploys a React app to Ubuntu on **AWS EC2** on every push to `main`, served via **Apache** without manual steps.

---

### 📫 Let's Connect!
- 📧 Email: mzeeshansarwar14@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/muhammad-zeeshan-sarwar-37874a341
- 🐙 GitHub: https://github.com/mzeeshansarwar14-creator
