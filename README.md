<div align="center">

<img width="100%" src="https://raw.githubusercontent.com/abdullah-540/abdullah-540/main/header.svg" alt="Abdullah Shahid — Solutions Architect · Backend · Cloud Infrastructure"/>

<br/>

<a href="https://www.linkedin.com/in/abdullah-shahid-6368a428a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:abdullah.shahid.021001@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-334155?style=flat-square&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Lahore,_Pakistan-Remote_·_Async-334155?style=flat-square&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/Experience-4%2B_years-334155?style=flat-square"/>

</div>

---

### About

I'm a **Solutions Architect and senior engineer** with 4+ years of experience taking systems from a whiteboard sketch to production. I turn business requirements into scalable, secure and cost-efficient architectures, and then build them myself: the APIs, the cloud infrastructure, and the monitoring that keeps it all running.

Currently leading the **FBR e-invoicing integration** at **Crypthon Technologies** and running the Kubernetes platform behind it.

<table>
<tr>
<td width="33%" valign="top">

**🏗️ Architecture & Cloud**

System design · microservices
AWS · Kubernetes · Docker
Autoscaling · ingress · CI/CD
Prometheus · Grafana · ELK

</td>
<td width="33%" valign="top">

**⚙️ Backend**

Python · FastAPI · Django · DRF
PostgreSQL · MySQL · Redis
Celery · async · REST APIs
OAuth2 · JWT · RBAC

</td>
<td width="33%" valign="top">

**⚡ Real-time & Frontend**

WebSockets · Django Channels
Firebase · Twilio · voice AI (VAPI)
LLM integration (Ollama)
React

</td>
</tr>
</table>

---

### How I build platforms

A typical architecture I design and run in production:

```mermaid
flowchart LR
    C([Web & mobile clients]) --> I[Ingress<br/>Nginx / HAProxy]
    subgraph K8S [Kubernetes · HPA autoscaling]
        I --> A[FastAPI / Django<br/>services]
        A --> W[Celery workers]
        A --> RT[WebSocket<br/>gateway]
    end
    A --> DB[(PostgreSQL)]
    A --> R[(Redis)]
    W --> EXT[External APIs<br/>FBR · Twilio · Firebase]
    K8S -.metrics & logs.-> O[Prometheus · Grafana · ELK]
```

**Principles I work by:** make it reliable, then make it scale · design for failure · if it isn't monitored, it isn't in production · write it down so the team can own it too.

---

### Experience

| Role | Company | Period |
|---|---|---|
| **Senior Python Developer**: platform architecture, Kubernetes infrastructure, observability, FBR e-invoicing lead | Crypthon Technologies | Feb 2025 – present |
| **Senior Back-End Developer**: auth architecture (OAuth2/JWT/RBAC), query & pagination optimisation | Enigmatix | Aug 2024 – Jan 2025 |
| **Back-End Developer**: REST APIs (DRF, FastAPI), Redis caching, async high-traffic endpoints | Enigmatix | Jul 2023 – Aug 2024 |
| **Associate Back-End Developer**: real-time features (WebSockets, Channels), test coverage | Enigmatix | Jun 2022 – Jul 2023 |

---

### Selected work

| Platform | What I built | Stack |
|---|---|---|
| ⛽ **OMC Solutions**: multi-station fuel management | Inventory, stock and nozzle services · JWT-based RBAC · real-time alerts | FastAPI · PostgreSQL · Firebase · S3 |
| 💰 **Laen Daen**: digital wallet & khata | Wallet and transaction services · encrypted financial data · eCommerce module | FastAPI · PostgreSQL · Firebase |
| 🍔 **Hunger Delights**: multi-restaurant ordering | Order processing · service hours · live delivery & group-order tracking | FastAPI · PostgreSQL · Firebase · S3 |
| 🛒 **Duty Free**: cross-location item exchange | Order, tracking and reward services · role-based permissions | FastAPI · PostgreSQL · Firebase |
| 🏢 **RentAround** + office & restaurant systems | Rentals, scheduling, reservations, inventory and auth | FastAPI · Django · PostgreSQL · Redis · AWS |

<sub>These are client and company projects, so their source code is private.</sub>

---

### Tech stack

<p>
<img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,react&theme=dark" height="40"/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&theme=dark" height="40"/>
<br/>
<img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,nginx,jenkins,firebase&theme=dark" height="40"/>
<img src="https://skillicons.dev/icons?i=prometheus,grafana,elasticsearch,kibana,git,postman&theme=dark" height="40"/>
</p>

---

<div align="center">

**Open to Solutions Architect, Senior Full-Stack and Cloud/Platform Engineering roles, and to consulting on scalable system design.**

<a href="https://www.linkedin.com/in/abdullah-shahid-6368a428a/">LinkedIn</a> ·
<a href="mailto:abdullah.shahid.021001@gmail.com">Email</a>

</div>
