# Hi 👋 I'm Muhammad Zeeshan Sarwar

**🚀 DevOps Engineer | CI/CD, AWS, Terraform, Docker & Kubernetes**

DevOps engineer focused on automating the path from commit to running infrastructure across CI/CD pipelines, Infrastructure as Code, containers, Linux servers, and observability[cite: 2, 3]. Backed by 3+ years of hands-on infrastructure, system administration, and networking experience, plus AZ-900 and CCNA certifications[cite: 2, 3].

### 🧑‍💻 About Me
- 💻 **3+ years** in Linux/Windows Server administration, networking, firewalls, and IT support[cite: 2, 3].
- ☁️ **Cloud & IaC:** Provisioning AWS infrastructure (EC2, VPC, Security Groups) with **Terraform** and configuring hosts with **Ansible**[cite: 2, 3].
- 🔁 **CI/CD Pipelines:** Building multi-stage automation in **GitLab CI/CD** and **GitHub Actions** with container registries, artifacts, and manual approval gates[cite: 2, 3].
- 🐳 **Containers & K3s:** Deploying multi-container stacks and Kubernetes workloads with **Docker**, **Docker Compose**, and **K3s** on Ubuntu[cite: 2, 3].
- 📊 **Observability & Recovery:** Instrumenting Ubuntu servers with **Grafana Alloy**, **Prometheus**, and **Grafana Cloud**, and recovering servers from full-disk outages[cite: 2, 3].

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

**🔹 End-to-End Kubernetes (K3s) Delivery Pipeline**[cite: 2]
- **Pipeline:** Four-stage **GitLab CI/CD** pipeline taking an application from commit to a running Kubernetes workload[cite: 2].
- **Infrastructure & Cluster:** **Terraform** provisions the AWS EC2 instance and passes its IP as a pipeline artifact; **Ansible** sets up **K3s** over SSH and applies manifests[cite: 2].
- **Registry & Teardown:** Publishes **Docker** images to GitLab Container Registry, with a manual-gate destroy stage to avoid lingering cloud costs[cite: 2].

**🔹 Multi-Container Application Delivery Pipeline**[cite: 2]
- **Infrastructure:** **Terraform** provisions AWS EC2 and per-service Security Group rules[cite: 2].
- **Configuration & Stack:** **Ansible** installs Docker and Compose and ships config to the host to run a three-service stack (**React**, **MongoDB**, **Mongo-Express**) with persistent volumes across redeploys[cite: 2].
- **Troubleshooting:** Resolved real deployment issues including Docker port conflicts and Terraform dependency errors[cite: 2].

**🔹 Server Monitoring & Production Incident Recovery**[cite: 2]
- **Observability:** Instrumented Ubuntu servers with **Grafana Alloy** to ship **Prometheus** metrics and system logs to **Grafana Cloud**, keeping agents running via `systemd`[cite: 2].
- **Incident Recovery:** Diagnosed (`journalctl`, `systemctl`, `du`, `df`) and resolved 100% disk utilization outages by pruning Docker build cache, resizing swap, and scheduling log rotation[cite: 2].

**🔹 Zero-Touch Deployment for a React Application**[cite: 3]
- **Automation:** **GitHub Actions** workflow that builds and deploys a React app to Ubuntu on **AWS EC2** on every push to `main`, served via **Apache** without manual steps[cite: 3].

---

### 📫 Let's Connect!
- 📧 Email: mzeeshansarwar14@gmail.com[cite: 2]
- 💼 LinkedIn: https://www.linkedin.com/in/muhammad-zeeshan-sarwar-37874a341[cite: 2]
- 🐙 GitHub: https://github.com/mzeeshansarwar14-creator[cite: 2]
