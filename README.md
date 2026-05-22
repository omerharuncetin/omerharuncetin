<a href="https://github.com/omerharuncetin">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=24&pause=1000&color=326CE5&center=false&vCenter=false&width=600&lines=Distributed+Systems+Engineer;Platform+Engineer;DevOps+%26+Cloud+Native+Specialist;Building+scalable%2C+self-healing+systems" alt="Typing SVG" />
</a>

```yaml
apiVersion: rbac.authorization.k8s.io/v1
kind: EngineerRole
metadata:
  name: omer-harun-cetin
  namespace: platform-engineering
spec:
  title: "Distributed Systems"
    experience: "5+ years Software Engineering"
  current_focus:
    - Kubernetes
    - Confidential Computing
    - Resource Optimization 
    - Scalable & Robust Systems
```

### ⚙️ Engineering Philosophy & Featured Work

I build secure, automated infrastructure using GitOps and CI/CD principles. My homelab project, **[omer-lab](https://github.com/omerharuncetin/homelab)**, is a production-grade Cloud Native datacenter built entirely from code. 

**Core capabilities implemented in `omer-lab`:**
* **Continuous Reconciliation:** Flux CD state enforcement.
* **Secrets Management:** In-cluster SOPS & age decryption.
* **Smart Scaling:** Sablier scale-to-zero routing to optimize RAM constraints.
* **Resilient Data:** CloudNativePG operator handling Postgres failovers.

<details>
<summary><b>🗺️ Click to view my standard GitOps Architecture</b></summary>

```mermaid
graph TD
    %% GitOps Flow
    Dev["Developer Commit"] -->|Git Push| Git["GitHub / Gitea"]
    Flux["Flux CD"] -->|Poll / Webhook| Git
    Flux -->|Reconcile State| Cluster["k3s Kubernetes Cluster"]

    %% Traffic Flow
    User["User / Client"] -->|HTTPS| LB["Load Balancer / CDN"]
    LB -->|Proxy| Ingress["Traefik Ingress Controller"]
    
    %% Cache, Scaler & Apps
    Ingress -->|Cache Lookup| Cache["Redis Cache"]
    Ingress -->|Scale-to-Zero| Sablier["Sablier Middleware"]
    
    Sablier -->|Route| Pods["Application Pods"]
    Pods -->|Query| Cache
    
    %% Databases
    Pods -->|Read / Write| PrimaryDB["CNPG Primary DB"]
    PrimaryDB -->|Replicate| StandbyDB["CNPG Standby DB"]

    %% Styling
    style Flux fill:#8A2BE2,stroke:#333,stroke-width:1px,color:#fff
    style Cluster fill:#326ce5,stroke:#333,stroke-width:1px,color:#fff
    style LB fill:#F38020,stroke:#333,stroke-width:1px,color:#fff
    style Ingress fill:#24A1C1,stroke:#333,stroke-width:1px,color:#fff
    style Cache fill:#DC382D,stroke:#333,stroke-width:1px,color:#fff
    style PrimaryDB fill:#316192,stroke:#333,stroke-width:1px,color:#fff
```
</details>

---

### 🛠️ Technical Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Languages** | <img src="https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Python-14354C?logo=python&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Bash-121011?logo=gnu-bash&logoColor=white&style=flat"/> |
| **Cloud & OS** | <img src="https://img.shields.io/badge/-AWS-FF9900?logo=amazon-aws&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black&style=flat"/> |
| **Orchestration** | <img src="https://img.shields.io/badge/-Kubernetes-326ce5?logo=kubernetes&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Docker-0db7ed?logo=docker&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Helm-0F1689?logo=helm&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Kustomize-326CE5?logo=kubernetes&logoColor=white&style=flat"/> |
| **GitOps & IaC** | <img src="https://img.shields.io/badge/-Flux%20CD-8A2BE2?logo=flux&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Terraform-5835CC?logo=terraform&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-GitHub%20Actions-2671E5?logo=githubactions&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-GitLab%20CI%2FCD-FC6D26?logo=gitlab&logoColor=white&style=flat"/> |
| **Secrets & Security** | <img src="https://img.shields.io/badge/-SOPS-32CD32?logo=mozilla&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Confidential%20Computing-008080?style=flat"/> |
| **Networking & DBs**| <img src="https://img.shields.io/badge/-PostgreSQL-316192?logo=postgresql&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-CloudNativePG-336791?logo=postgresql&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Traefik-24A1C1?logo=traefik&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Nginx-009639?logo=nginx&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Tailscale-E05A47?logo=tailscale&logoColor=white&style=flat"/> |
| **Observability** | <img src="https://img.shields.io/badge/-Prometheus-E6522C?logo=Prometheus&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white&style=flat"/> |

---

### 📬 Establish Connection

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/omerharuncetin)
[![Email](https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail)](mailto:omerharuncetin@gmail.com)

