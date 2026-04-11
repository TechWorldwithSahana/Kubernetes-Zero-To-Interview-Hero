<div align="center">

# 🚀 Kubernetes — Zero to Interview Hero

### A free, structured Kubernetes course for engineers preparing for DevOps interviews

[![YouTube](https://img.shields.io/badge/YouTube-TechWorld_with_Sahana-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn)
[![Topmate](https://img.shields.io/badge/Topmate-Buy_Chapter_Notes-6C47FF?style=for-the-badge&logo=bookstack&logoColor=white)](https://topmate.io/sahana_ghosh/1974847)

> If this helped you, drop a ⭐ — it helps others find this resource!

</div>

---

## 📚 Course Index

| # | Chapter | Topics | Notes |
|---|---------|--------|-------|
| 01 | [Introduction to Kubernetes](#-chapter-1--introduction-to-kubernetes) | Containers, Architecture, Pods, Services | [📖 Buy eBook](https://topmate.io/sahana_ghosh/1974847) |
| 02 | [Architecture](#-chapter-2--architecture) | Control Plane, Worker Node, etcd, kubelet | Coming soon |
| 03 | [Pods Deep Dive](#-chapter-3--pods-deep-dive) | Lifecycle, Init Containers, Multi-container, YAML | Coming soon |
| 04 | [ReplicaSets & Deployments](#-chapter-4--replicasets--deployments) | Rolling updates, Rollbacks, Blue-Green, Canary | Coming soon |
| 05 | [Services & DNS](#-chapter-5--services--dns) | ClusterIP, NodePort, LoadBalancer, CoreDNS | Coming soon |
| 06 | [Commands & Output](#-chapter-6--commands--output) | Pod, Deployment, Service commands | Coming soon |
| 07 | [Ingress & HTTP Routing](#-chapter-7--ingress--http-routing) | Path/Host routing, TLS, Rate limiting, CORS | Coming soon |
| 08 | [ConfigMaps & Secrets](#-chapter-8--configmaps--secrets) | Env vars, Volume mounts, Base64, Immutable | Coming soon |
| 09 | [Persistent Volumes & Storage](#-chapter-9--persistent-volumes--storage) | PV, PVC, Static/Dynamic provisioning, Access Modes | Coming soon |
| 10 | [StatefulSets](#-chapter-10--statefulsets) | Pod Identity, Stable Storage, Scaling | Coming soon |
| 11 | [Node Affinity, Taints & Tolerations](#-chapter-11--node-affinity-taints--tolerations) | NodeSelector, Affinity, Zonal spread | Coming soon |
| 12 | [DaemonSets](#-chapter-12--daemonsets) | YAML, Node Selectors, Update Strategies | Coming soon |
| 13 | [Jobs & CronJobs](#-chapter-13--jobs--cronjobs) | Parallelism, Failure handling, History limits | Coming soon |

---

## 📘 Chapter 1 — Introduction to Kubernetes

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=FBgQOy4ZR4w&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn) [![eBook](https://img.shields.io/badge/Chapter_Notes-Buy_eBook_%2413-6C47FF?style=flat-square&logo=bookstack)](https://topmate.io/sahana_ghosh/1974847)

</div>

**20 interview questions covered:**

1. What is Kubernetes, and why is it needed in modern infrastructure?
2. What are containers, and how do they differ from virtual machines?
3. What are the benefits of using Kubernetes in a production environment?
4. What is the difference between Docker and Kubernetes?
5. What are the main components of the Kubernetes architecture?
6. Explain the concept of a pod in Kubernetes.
7. What is a Kubernetes cluster, and how does it work?
8. What is a deployment in Kubernetes, and how does it help in managing applications?
9. What is the role of the Kubernetes scheduler?
10. What is a Kubernetes service, and how does it ensure connectivity to pods?
11. What are labels and selectors in Kubernetes, and how do they help in managing resources?
12. What are ConfigMaps and Secrets in Kubernetes, and how are they used to manage configurations?
13. What is a replica set in Kubernetes, and how does it ensure the desired number of pod replicas?
14. Explain the concept of namespaces in Kubernetes.
15. What are taints and tolerations in Kubernetes, and how do they work?
16. How does Kubernetes handle persistent storage for containers?
17. How does Kubernetes handle rolling updates and rollbacks?
18. What is the role of an Ingress in Kubernetes?
19. What is the significance of auto-scaling in Kubernetes, and how does it work?
20. What is the difference between stateful and stateless applications in Kubernetes, and how are StatefulSets and Deployments used to manage them?

---

## 📘 Chapter 2 — Architecture

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=WceShXPOWrY&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=2)

</div>

**Topics:** Control Plane · Worker Node · What is a Pod · How Kubernetes Works · Simple Analogy

**15 architecture interview questions:**

1. What is Kubernetes and why do we use it?
2. What are the main components of the Kubernetes architecture?
3. What is the role of the API Server in Kubernetes?
4. What does the Scheduler do in Kubernetes?
5. What is etcd and why is it important in Kubernetes?
6. What is the Controller Manager responsible for?
7. What is a Node in Kubernetes?
8. What is the difference between a Master Node and a Worker Node?
9. What is a kubelet and what is its role?
10. What is the function of the Container Runtime?
11. What is a Pod in Kubernetes?
12. How is a Pod different from a Container?
13. Can a Pod have more than one container? Why or why not?
14. What happens when a Pod crashes or fails?
15. How do the Control Plane and Worker Nodes communicate in Kubernetes?

---

## 📘 Chapter 3 — Pods Deep Dive

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=lFjKGd3PoDc&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=3)

</div>

**Topics covered:**

- What is a Pod
- Lifecycle of a Pod
- What are Init Containers & their Lifecycle
- Multi-container Pods
- Basic Pod YAML Structure
- Pod Networking in Kubernetes
- Pod Affinity and Anti-affinity
- Real World Pod YAML

---

## 📘 Chapter 4 — ReplicaSets & Deployments

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=K5_6nDyPJz8&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=4)

</div>

**Topics covered:**

- What is a ReplicaSet
- How Deployments use ReplicaSets
- Deployment YAML walkthrough
- Rolling updates · Rollbacks · Revision history
- Pause / resume rollout
- Blue-Green strategy (manual in Kubernetes)
- Canary strategy (manual in Kubernetes)
- Image updates · Scaling Deployments

---

## 📘 Chapter 5 — Services & DNS

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=-aYxWOM8DsI&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=5)

</div>

**Topics covered:**

- Why Services Exist
- ClusterIP · NodePort · LoadBalancer · Headless Service
- Service with and without a Selector
- Endpoint Object
- CoreDNS · Service Discovery
- 10 Real World Kubernetes Service Examples

---

## 📘 Chapter 6 — Commands & Output

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=c7ccpmkuBS0&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=6)

</div>

**Topics covered:**

- Kubernetes Basic Commands
- Pod Commands · Deployment Commands · Service Commands

---

## 📘 Chapter 7 — Ingress & HTTP Routing

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=2aSdormhraA&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=7)

</div>

**Topics covered:**

- Ingress Resource · Ingress Controller (NGINX on-prem)
- Path-Based Routing · Host-Based Routing
- TLS Termination with Secret · HTTP → HTTPS Redirect
- Wildcard Domains · Default Backends · Rewrite Rules
- Rate Limiting · CORS Handling · Ingress Troubleshooting

---

## 📘 Chapter 8 — ConfigMaps & Secrets

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=yGOSK7qhOhU&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=8)

</div>

**Topics covered:**

- ConfigMap — creation, env vars, volume mounts
- Secret creation — env injection, mounting as files
- Base64 encoding / decoding
- Immutable ConfigMap · Update strategy

---

## 📘 Chapter 9 — Persistent Volumes & Storage

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=YW3BFbXIB9U&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=9)

</div>

**Topics covered:**

- Volumes vs Persistent Volumes
- PV & PVC Deep Dive
- Static Provisioning · Dynamic Provisioning
- Access Modes (RWO, RWX) · Reclaim Policies · Volume Lifecycle

---

## 📘 Chapter 10 — StatefulSets

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=BTmiBi4gDMI&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=10)

</div>

**Topics covered:**

- Stateless vs Stateful Applications
- Why StatefulSets? (Real-World Scenario)
- Pod Identity (DNS & Hostname) · Stable Storage
- StatefulSet YAML · Scaling · Upgrade Strategies

---

## 📘 Chapter 11 — Node Affinity, Taints & Tolerations

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=bTl4fOMl5pM&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=11)

</div>

**Topics covered:**

- Node Labels · NodeSelector vs Affinity
- Node Affinity: Required vs Preferred rules
- Taints overview · Tolerations in Pod YAML
- NoSchedule · PreferNoSchedule · NoExecute
- Anti-affinity · Zonal pod spread

---

## 📘 Chapter 12 — DaemonSets

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=jUhBaz6b57U&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=12)

</div>

**Topics covered:**

- What is a DaemonSet · DaemonSet YAML Structure
- DaemonSets and Node Selectors
- DaemonSets and Taints / Tolerations
- Update Strategies · Delete Strategies
- DaemonSets vs Deployments

---

## 📘 Chapter 13 — Jobs & CronJobs

<div align="right">

[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=De8D-K4tyRI&list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn&index=13)

</div>

**Topics covered:**

- What is a Job? · Job YAML Structure
- Job Completion & Parallelism
- What is a CronJob? · CronJob YAML Structure
- Jobs vs CronJobs · `activeDeadlineSeconds`
- Suspend and Resume CronJobs
- Job Failure Handling — Restart Policies
- CronJob History Limits · Missed Jobs Handling

---

<div align="center">

📌 **More chapters are on the way.**
Star ⭐ this repo and subscribe on [YouTube](https://www.youtube.com/playlist?list=PL8h_iS3fGq0KYUn8JfXF86pAzssaH_Frn) to stay updated.

<br/>

Made with ❤️ by [Sahana Ghosh](https://topmate.io/sahana_ghosh)

<br/>

Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — free to share with credit, not for commercial use.

</div>
