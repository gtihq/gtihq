<div align="center">

# GTI HQ

**Infrastructure, tooling and experiments. All in one place.**

[![Org](https://img.shields.io/badge/org-gtihq-2f81f7?style=for-the-badge&logo=github)](https://github.com/gtihq)
[![Repositories](https://img.shields.io/badge/repositories-gtihq-2ea44f?style=for-the-badge&logo=github)](https://github.com/orgs/gtihq/repositories)
[![Infrastructure](https://img.shields.io/badge/infrastructure-gti--infra-6f42c1?style=for-the-badge&logo=terraform)](https://github.com/gtihq/gti-infra)
[![Status](https://img.shields.io/badge/status-active-2ea44f?style=for-the-badge)](https://github.com/gtihq)

</div>

---

## About

**GTI HQ** is a GitHub organization for the infrastructure, automation and internal tooling
that keeps the GTI homelab running. It is the single source of truth for infrastructure code,
deployment pipelines and the small utilities built around them.

Everything here follows one rule: **Git is the source of truth, automation does the rest.**

## Repositories

| Repository | Purpose | Stack |
| --- | --- | --- |
| [gti-infra](https://github.com/gtihq/gti-infra) | Homelab infrastructure, GitOps, monitoring and shared services | Terraform, Docker Swarm, Forgejo Actions, Grafana |
| [gtihq](https://github.com/gtihq/gtihq) | Organization profile and documentation | Markdown |

## How it works

- **Infrastructure as code.** Networks, services, dashboards, alerts and DNS all live in Terraform.
- **GitOps with a human gate.** GitHub holds the code, Forgejo Actions runs the deploys, and a webhook hub connects the two.
- **Observability by default.** Grafana dashboards and alerts are provisioned from git and reconciled automatically.
- **Private by design.** Internal services sit behind Tailscale and are reachable from anywhere in the tailnet.

## Built with

<div align="center">

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Forgejo](https://img.shields.io/badge/Forgejo-486DAA?style=flat-square&logo=gitea&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=flat-square&logo=tailscale&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

## Quick links

- [All repositories](https://github.com/orgs/gtihq/repositories)
- [Infrastructure repo](https://github.com/gtihq/gti-infra)
- [Open an issue](https://github.com/gtihq/gtihq/issues)

---

<div align="center">

Maintained with care by **callmeteus**.

[Back to top](#gti-hq)

</div>
