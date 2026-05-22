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
graph LR
    A[Developer Commit] -->|Git Push| B(GitHub / Gitea)
    B -->|Webhook / Poll| C{Flux CD}
    C -->|Reconcile State| D[k3s Kubernetes]
    D -->|Deploy via Helm| E[CloudNativePG]
    D -->|Scale-to-Zero| F[Sablier Middleware]
    style C fill:#8A2BE2,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#326ce5,stroke:#333,stroke-width:2px,color:#fff
```
</details>

---

### 🛠️ Technical Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Languages** | <img src="https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Python-14354C?logo=python&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Bash-121011?logo=gnu-bash&logoColor=white&style=flat"/> |
| **Cloud & OS** | <img src="https://img.shields.io/badge/-AWS-FF9900?logo=amazon-aws&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black&style=flat"/> |
| **Orchestration** | <img src="https://img.shields.io/badge/-Kubernetes-326ce5?logo=kubernetes&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Docker-0db7ed?logo=docker&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Helm-0F1689?logo=helm&logoColor=white&style=flat"/> |
| **GitOps & IaC** | <img src="https://img.shields.io/badge/-Flux%20CD-8A2BE2?logo=flux&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Terraform-5835CC?logo=terraform&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-GitHub%20Actions-2671E5?logo=githubactions&logoColor=white&style=flat"/> |
| **Networking & DBs**| <img src="https://img.shields.io/badge/-PostgreSQL-316192?logo=postgresql&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Traefik-24A1C1?logo=traefik&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Tailscale-E05A47?logo=tailscale&logoColor=white&style=flat"/> |
| **Observability** | <img src="https://img.shields.io/badge/-Prometheus-E6522C?logo=Prometheus&logoColor=white&style=flat"/> <img src="https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white&style=flat"/> |

---

### 📬 Establish Connection

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/omerharuncetin)
[![Email](https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail)](mailto:omerharuncetin@gmail.com)
```
