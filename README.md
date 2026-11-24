# Humayun Jawad

Full-stack and platform engineer at [Datum Labs](https://github.com/datumlabsio). I build data platforms on Kubernetes, the CI/CD and security around them, and AI agents for engineering teams. Before that I spent years shipping production React and Next.js apps, and I still build the front ends.

## What I'm working on

- **A self-hosted data platform on Kubernetes.** dlt for ingestion, ClickHouse as the warehouse, dbt for transforms and Dagster to orchestrate them, deployed with Argo CD. It has an MCP server so AI assistants can query it, and a Kubernetes operator (kopf) that gives each person their own access to the warehouse and the tools around it, behind SSO.
- **An AI agent that works in Slack and Google Chat.** It reviews pull requests and runs coding tasks in sandboxes. Its request planner is tested against an evaluation set of 162 cases in English, Roman Urdu and Urdu.
- **Shared CI and supply-chain security for a GitHub org** ([datumlabsio/actions](https://github.com/datumlabsio/actions)): reusable workflows, multi-arch container builds that publish only the image that was scanned, secret and code scanning, and self-hosted runners with failover.
- **Kubernetes clusters on demand** with Cluster API and Kamaji on Proxmox, and the apps installed on them.
- **Products and side projects:** a hiring and assessment platform, a QR print kiosk for print shops (phone upload, owner approval, a Windows print agent), and [Munshi](https://github.com/humayun-1/munshi), a sticky-note task app for the desktop with Slack reminders that understands times written in Roman Urdu.

## Open source

- [libredb/libredb-studio#2283](https://github.com/libredb/libredb-studio/pull/2283): the Dashboard tab now draws each saved chart the way it was saved. Merged.

## Stack

| Area | Tools |
|---|---|
| Data | ClickHouse, dbt, dlt, Dagster, Airflow, DuckDB, PostgreSQL |
| Platform | Kubernetes, Argo CD, Helm, Cluster API, Proxmox, Terraform, AWS, Docker, GitHub Actions |
| Backend | Python, TypeScript, Node.js, Prisma, Supabase |
| Frontend | React, Next.js, Tailwind CSS, shadcn/ui, Electron |
| AI | Claude, MCP (FastMCP), agent evaluations, LibreChat |

## Earlier work

Several years of product front ends: multi-chain wallet connections and crypto payments (Wagmi, WalletConnect), a drag-and-drop visual builder, real-time SaaS dashboards with role-based access, Mapbox and D3 data visualisation, and Three.js scenes.

## Contact

[Email](mailto:muhammadhumayunjawad@gmail.com) · [LinkedIn](https://www.linkedin.com/in/humayun-jawad/) · [humayunjawad.com](https://humayunjawad.com/)
