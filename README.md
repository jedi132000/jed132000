# Hey Everyone 👋\! I'm Oladimeji Oladipo

### Lead Site Reliability & Platform Engineer @ TCS | Kubernetes · GPU Infrastructure · AI Inference Platforms   Scaling multi-cloud platforms and bringing that same reliability discipline to GPU/AI workloads

## 🚀 About Me

I'm a **Lead Site Reliability & Platform Engineer** with 12+ years across AWS, Azure, and GCP, currently leading platform and production reliability at **TCS** across **20+ EKS/AKS/GKE clusters** supporting **50+ engineering teams** and **100+ microservices** against a **99.95% availability target**. Over the last year I've been applying that same production discipline to **GPU-aware Kubernetes and AI model-serving infrastructure** — NVIDIA GPU Operator, DCGM telemetry, MIG partitioning, and inference-as-a-service patterns using vLLM, Triton, KServe, and NVIDIA NIM.

**Recent Impact (TCS):**

- 📉 Cut Sev1 incidents by **\~35%** through SLI/SLO and error-budget policies tied directly to release and remediation decisions  
- 🏗️ Reduced configuration drift by **\~80%** via reusable Terraform modules and ArgoCD GitOps reconciliation  
- 🤖 Built Python/Bash remediation automation classifying CrashLoopBackOff, readiness failures, and resource pressure — auto-resolving low-risk cases, escalating the rest with diagnostic context  
- 🔧 Designed Groovy-based Jenkins shared libraries standardizing build → test → security approval → deploy → rollback across 50+ teams

**Before this (Robert Half, EPAM, Cognizant):**

- ⏱️ Cut production deployment downtime by **\~45%** modernizing legacy apps into Kubernetes microservices  
- 📈 Reduced incident resolution time by **\~25%** through Prometheus/Grafana/Datadog/ELK monitoring tied to runbooks and postmortems  
- 🌐 Designed high-availability Azure architectures serving **500,000+ daily active users**  
- 🚀 Automated greenfield infrastructure provisioning with Terraform, cutting environment setup from days to minutes

---

## 🎯 What I Do

- **Site Reliability Engineering (SRE):** Production reliability, Sev1/Sev2 incident command, SLIs/SLOs, error budgets  
- **AI Infrastructure & GPU Platforms:** GPU-aware Kubernetes, NVIDIA GPU Operator, DCGM telemetry, MIG partitioning, GPU capacity planning  
- **AI Inference & Model Serving:** vLLM, NVIDIA Triton Inference Server, KServe, NVIDIA NIM, canary rollout, inference SLOs  
- **Cloud Infrastructure:** Multi-cloud platform engineering across AWS, Azure, and GCP  
- **Infrastructure as Code (IaC):** Terraform, Ansible, CloudFormation, Bicep/ARM  
- **CI/CD & GitOps:** Jenkins/Groovy shared libraries, GitLab CI, GitHub Actions, ArgoCD  
- **Observability:** Prometheus, Grafana, OpenTelemetry, Datadog, ELK, CloudWatch, and DCGM/inference telemetry  
- **Security & Governance:** Least-privilege IAM, Kubernetes RBAC, HashiCorp Vault, SOC 2/HIPAA-aligned controls

---

## 💻 Tech Stack

## 💻 Tech Stack
## 💻 Tech Stack

[![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com)
[![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com)
[![GCP](https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com)
[![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com)
[![ArgoCD](https://img.shields.io/badge/ArgoCD-%23EF7B4D.svg?style=for-the-badge&logo=argo&logoColor=white)](https://argoproj.github.io/)
[![NVIDIA NIM](https://img.shields.io/badge/NVIDIA%20NIM-%2376B900.svg?style=for-the-badge&logo=nvidia&logoColor=white)](https://developer.nvidia.com/nvidia-nim)
[![Slurm](https://img.shields.io/badge/Slurm-%23000000.svg?style=for-the-badge&logo=linux&logoColor=white)](https://slurm.schedmd.com/)
[![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)

**Core Skills:** Kubernetes | AWS | Azure | GCP | Terraform | ArgoCD | GitOps | CI/CD Pipelines | Docker | ArgoCD | Python | Bash | Prometheus | Grafana | OpenTelemetry | NVIDIA GPU Operator | vLLM | Triton | KServe | NVIDIA NIM

---

## 🛠️ Featured Projects

### **GPU-Accelerated Inference Platform**

Designed and validated a GPU-backed Kubernetes reference platform with dedicated accelerator node pools, NVIDIA GPU Operator lifecycle patterns, DCGM Exporter telemetry, taints/tolerations, affinity, priority classes, and ResourceQuota controls. Defined inference reliability signals spanning endpoint availability, p95/p99 latency, time-to-first-token, queue depth, and GPU utilization/memory pressure.

- **Tech:** NVIDIA GPU Operator, DCGM Exporter, vLLM, NVIDIA Triton, KServe, NVIDIA NIM, Kubernetes  
- **Impact:** Production-grade inference reliability model — readiness checks, autoscaling, canary traffic, rollback  
- 🔗 [View Project](https://github.com/jedi132000/gpu-kubernetes-platform)

### **Inference-as-a-Service & Multi-Tenant AI Runtime**

Designed a GitOps-driven service model where teams select an approved model runtime, GPU resource profile, endpoint policy, and autoscaling rule through versioned configuration — with namespace/RBAC isolation, workload identity, secrets, network policy, and tenant-scoped auditability.

- **Tech:** GitOps, Kubernetes RBAC, HashiCorp Vault, ResourceQuota, Progressive Delivery  
- **Impact:** SLO/error-budget controls for model-serving endpoints with release gates and canary validation  
- 🔒 Private reference implementation — details on request

---

## 📂 Other Projects

### **GPU Observability Stack**

GPU observability reference using NVIDIA DCGM, Prometheus, Grafana and Kubernetes operational telemetry.

- 🔗 [View Project](https://github.com/jedi132000/gpu-observability-stack)

### **GPU Kuberenetes Platform**

GPU-aware Kubernetes infrastructure reference with Terraform, NVIDIA GPU Operator, scheduling controls and operational validation.

- 🔗 [View Project](https://github.com/jedi132000/gpu-kubernetes-platform)

### **GPU Scheduler Capacity Lab**

Python GPU scheduling and capacity-planning toolkit for workload placement, multi-tenant quotas and accelerator resource analysis.

- 🔗 [View Project](https://github.com/jedi132000/gpu-scheduler-capacity-lab)

---

## 🎓 Certifications & Training

- **AWS Solutions Architect – Professional** — Amazon Web Services  
- **Multicloud Network Associate** — Aviatrix (valid to Oct 2027\)  
- **GitOps at Scale Certificate** — Codefresh  
- **Cilium Host Firewall** — ISOVALENT  
- **Cilium LoadBalancer IPAM and BGP Service Advertisement** — ISOVALENT  
- **Cilium Multi Networking** — ISOVALENT
- **NVIDIA Certified Associate - AI Infrastructure & Operations** — NVIDIA

---

## 📊 GitHub Stats

[![Oladimeji's GitHub stats](https://github-readme-stats.vercel.app/api?username=jedi132000&show_icons=true&theme=dark)](https://github-readme-stats.vercel.app/api?username=jedi132000&show_icons=true&theme=dark)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jedi132000&layout=compact&theme=dark)](https://github-readme-stats.vercel.app/api/top-langs/?username=jedi132000&layout=compact&theme=dark)

---

## 💡 What I'm Focused On

- 🔍 **AI Infrastructure Reliability:** Bringing SRE discipline — SLOs, error budgets, incident response — to GPU and inference workloads  
- 🤖 **Automation:** Eliminating manual toil through remediation automation and IaC  
- 📈 **Observability:** Extending production telemetry (Prometheus, Grafana, OpenTelemetry) to GPU/DCGM and inference metrics  
- 🚀 **Model Serving at Scale:** vLLM, Triton, KServe, and NVIDIA NIM as production-grade inference runtimes  
- 📚 **Continuous Learning:** Staying current with GPU platform engineering and AI infrastructure patterns

---

## 🌐 Connect with Me
## 🌐 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oladimeji-oladipo) [![Gmail](https://img.shields.io/badge/Gmail-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:oladimeji.oladipo.a@gmail.com)
(https://www.linkedin.com/in/oladimejioladipo-k8s-cloud-platform-gen-aiengineer) [![Gmail][image1]](mailto:oladimeji.oladipo.a@gmail.com)

---

## 📫 Get In Touch

- **Email:** [oladimeji.oladipo.a@gmail.com](mailto:oladimeji.oladipo.a@gmail.com)  
- **LinkedIn:** [Oladimeji Oladipo](https://www.linkedin.com/in/oladimejioladipo-k8s-cloud-platform-gen-aiengineer)  
- **Location:** Lexington, Kentucky, United States

---

## 🎯 Open To

- **Senior/Lead AI Infrastructure & Platform Engineering Roles** — particularly where GPU or inference workloads are part of the picture  
- **SRE Opportunities** — organizations focused on reliability, automation, and production excellence  
- **Collaboration** — GPU infrastructure, model-serving architecture, technical discussions

---

*"Reliability isn't an accident — it's a discipline you apply everywhere, including to the hardest problems in AI infrastructure."* 🚀

[image1]: <data:image/png;base64,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5zeWFt/W1sBYF6tMs+9HvntjZWFlqxv6rSf+mWAm8wTiBQJAfz1ztXCsB1PS1rIbhssLHx4uDfYf3fsv/lGsfxJyaO/e7xn9FsHS4MITA4YWLnli2uA1w+XB7Vv/u7rRrkBMH+wdiRcHAD33xOsCYj0YQ1uDVp+oSdecqFELl4xq1lbtasf1trUs1jcRERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERERkb7l/wOb8Wr2LNeaNgAAAABJRU5ErkJggg==>
