# Awesome-Application-Integration-Connectors

A curated list of application integration connectors, iPaaS (Integration Platform as a Service) solutions, and workflow automation tools.

---

## Sector Overview & Market Dynamics

The global Integration Platform as a Service (iPaaS) market is estimated at **$8.5B to $10.9B** (growing at an annual rate of ~20–30% toward $30B+ by 2030). The sector is **moderately concentrated** at the top tier—dominated by cloud and enterprise titans like Salesforce (MuleSoft), Microsoft, Oracle, and Boomi—while remaining **highly fragmented** across the mid-market and SMB landscape where specialized low-code, open-source, and agentic automation platforms compete aggressively.

---

## SaaS Integration Platforms & Connectors

The table below covers prominent SaaS iPaaS and automation platforms, sorted in descending order by company size (valuation / revenue).

| Vendor / Product | Company Size (Valuation / Revenue) | Starting Pricing (Specific Tier) | Free Tier / Trial Limit | Key Highlights & Architecture |
|---|---|---|---|---|
| **MuleSoft** | **$6.5B acquisition valuation** (Salesforce parent; ~$350M+ ARR) | **$2,000/month** (billed annually for Integration Starter package) | **30-day free trial** (Full Anypoint Platform access; no credit card required) | Full enterprise API lifecycle management, Anypoint Platform, runtime fabric, and MuleSoft Composer for business teams. |
| **Workato** | **$5.7B valuation** (Series E; ~$150M ARR) | **$75/month** (Pro plan base for 2,500 credits; scales to $1,275/mo for 50,000 credits) | **Free tier: 50,000 one-time credits** (never expire; recipe creation & testing) | Enterprise automation, AI orchestration, bot integrations (Workbot), and governed business workflow recipes. |
| **Zapier** | **$5.0B valuation** (~$310M ARR) | **$19.99/month** (Starter plan, billed annually at $239.88/yr for 750 tasks/mo) | **Free forever plan: 100 tasks/month**, unlimited zaps, 15-minute update cycles | Mass-market leader with 7,000+ app connectors, multi-step zaps, built-in tables, and AI workflow generators. |
| **Boomi** | **$4.0B valuation** (~$500M ARR; Francisco Partners / TPG) | **$99/month** (Pay-As-You-Go base tier + $0.05 per Boomi message document) | **30-day free trial** (Full Enterprise Platform access with standard connectors) | Atom runtime engine, hybrid/on-premise connectivity, EDI management, Master Data Hub, and API management. |
| **Zoho Flow** | **~$1.5B annual revenue** (Zoho Corp bootstrapped, profitable) | **$10/month** (Standard plan, billed annually at $120/yr for 10,000 tasks/mo) | **Free forever plan: 100 tasks/month**, 5 flows, 30-day log history | Native bidirectional integration into Zoho CRM/Books suite alongside 600+ external business SaaS webhooks. |
| **Tray.io** (Tray.ai) | **$600M valuation** (Series C; ~$70M ARR) | **$500/month** (Pro plan base tier for 3 workspaces, 7-day log retention) | **30-day free trial** (Full platform trial access with standard connectors) | Low-code enterprise iPaaS, elastic serverless scalability, Merlin AI agent builder, and Tray Helix runtime. |
| **Make** (formerly Integromat) | **~$100M+ acquisition** (Celonis parent $13B valuation; ~$52M ARR) | **$9.00/month** (Core plan, billed annually at $108/yr for 10,000 operations/mo) | **Free forever plan: 1,000 operations/month**, 2 active scenarios, 15-minute interval | Visual drag-and-drop scenario builder, JSON data parsing, router branching, and detailed execution inspectors. |
| **Celigo** | **~$95M ARR** (~$80M total venture funding) | **$600/month** (Standard Edition entry-level base tier) | **Free plan: 2 endpoints & 1 active flow** (plus 30-day unlimited trial) | Deep ERP integration (NetSuite leader), prebuilt integration apps (SmartConnectors), and B2B eCommerce flows. |
| **Pipedream** | **~$80M valuation** (Acquired by Workday; ~$3.1M ARR) | **$29.00/month** (Basic plan, billed annually for 20,000 compute credits/mo) | **Free forever plan: 3 active workflows**, daily credit allowance (~100 credits/mo), 750s/day test runtime | Developer-first serverless execution environment supporting custom Node.js/Python code steps, npm packages, and webhooks. |
| **Integrately** | **~$4.5M annual revenue** (Bootstrapped / private) | **$19.99/month** (Starter plan, billed annually at $239.88/yr for 2,000 tasks/mo) | **Free forever plan: 100 tasks/month**, 5 active 1-step automations, 15-minute update cycle | 1-click ready-made automation templates, millions of pre-mapped workflow pairs, and simple setup for non-technical users. |

---

## Open-Source Integration & Workflow Engines

For self-hosted, air-gapped, or privacy-conscious architectures:

| Project | License | Architecture & Capabilities | Self-Hosting Footprint |
|---|---|---|---|
| **Activepieces** | Open Source (MIT) | Modern Zapier/Make alternative; written in TypeScript, clean UI, modular piece system, and community-contributed pieces. | Lightweight Docker container or Kubernetes cluster. |
| **FlowForge** | AGPL-3.0 | Self-hosted integration & workflow tool tailored for PHP environments; supports 1,690+ apps, AI Builder, MCP tools, and AI voice agents. | Runs on standard LAMP / cPanel / shared hosting with a single cron job. |

---

## Contributing

1. Fork this repository.
2. Create your feature branch (`git checkout -b feature/new-connector`).
3. Commit your changes (`git commit -am 'Add new connector'`).
4. Push to the branch (`git push origin feature/new-connector`).
5. Open a Pull Request.
