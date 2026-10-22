# Awesome-No-Code-Database

## Top No-Code Development Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Visual App Building, Self-Hosted Data Control & AI-Assisted Development*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **No-Code Development Platforms**. These tools enable users to build web applications, internal tools, and business workflows through visual builders, drag-and-drop interfaces, and declarative configuration — without writing traditional code.

**Examples** include Bubble, Retool, Webflow, OutSystems, Mendix, Appian, Microsoft Power Apps, FlutterFlow, Glide, and Betty Blocks (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, visual data modeling, and transparent app generation — ideal for teams prioritizing data sovereignty, avoiding per-user SaaS pricing, and building internal tools they fully control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Bubble** — Full-stack no-code web app builder with database, workflows, and responsive design. **Best for founders and startups** wanting to launch MVPs without engineering resources. Proprietary platform with vendor lock-in.

- **Retool** — Low-code platform for building internal tools with pre-built UI components and database/API connectors. **Best for engineering teams** needing to build admin panels and dashboards quickly. Pricing scales per-user.

- **Webflow** — Visual web development platform generating clean HTML/CSS/JS. **Best for designers** wanting pixel-perfect control without writing code. Not a database-backed app builder — focused on marketing sites and CMS.

- **OutSystems** — Enterprise low-code platform for building and deploying web and mobile applications. **Best for large enterprises** needing governance, multi-cloud deployment, and vendor support.

- **Mendix** — Low-code application development platform with visual modeling and enterprise integration. **Best for enterprises** wanting collaborative development with IT governance.

- **Appian** — Enterprise low-code automation platform with process modeling and case management. **Best for regulated industries** needing workflow automation with compliance controls.

- **Microsoft Power Apps** — Low-code platform for building custom business apps with connectors to Microsoft 365 and Dynamics 365. **Best for organizations already invested in the Microsoft ecosystem.**

- **FlutterFlow** — Visual builder for Flutter mobile apps with Firebase integration and code export. **Best for mobile app developers** wanting visual development with code portability.

- **Glide** — No-code app builder that turns Google Sheets or Airtable data into mobile apps. **Best for operations teams** wanting quick internal apps without database setup.

- **Betty Blocks** — Enterprise no-code platform for building business applications. **Best for organizations** wanting no-code with enterprise governance and support.

## Open-Source GitHub Projects

- **[NocoBase](https://github.com/nocobase/nocobase)**  
  **The most extensible open-source no-code platform for enterprise applications** — **13,000+ GitHub stars**, plugin-based architecture, fully self-hostable . **Written in JavaScript/TypeScript with Node.js and AntDesign**, supporting **PostgreSQL and MySQL** for data storage . **Visual data modeling** through the Main Database plugin, creating tables and fields without code . **AI employees embedded in the system** — AI capabilities seamlessly integrated into interfaces, business workflows, and data contexts . **Block-based UI building**: tables, forms, details, lists, charts, and cards, each linked to collections with independent customization . **Workflow automation** with three trigger types: Collection Event, Scheduled Event, and Post-Action Event, enabling notifications, data insertion, and external API calls . **Extensive plugin library** with free and paid options, plus custom plugin development . **File management, internationalization, mobile support, and theme editing** included . **Best for teams wanting a scalable, plugin-extensible no-code platform** with full self-hosting control.

- **[ToolJet](https://github.com/ToolJet/ToolJet)**  
  **The AI-powered open-source internal tool builder** — **MIT-licensed core**, self-hostable or cloud . **AI app builder generates native pages, queries, and events** from prompts that stay editable in the visual builder . **Connect 100+ data sources** including PostgreSQL, MongoDB, REST APIs, Google Sheets, BigQuery, Salesforce, and more . **Extend with JavaScript or Python** queries and custom components where needed . **ToolJet MCP server** (MIT-licensed) lets Claude Code or Codex compose native ToolJet apps that can still be refined visually . **Built-in ToolJet DB** based on PostgreSQL for teams without an existing database . **Team plan includes SSO, audit logs, and GitSync**; Enterprise adds SCIM and builder BYOK . **SOC 2 and ISO 27001 certified**; data-source credentials encrypted with AES-256-GCM . **Best for teams building internal apps on business data** who need AI generation plus visual editing and centralized governance.

- **[Appsmith](https://github.com/appsmithorg/appsmith)**  
  **The developer-focused open-source low-code platform** — **41,000+ GitHub stars** . **True low-code**: drag-and-drop to start, with JavaScript and SQL flexibility throughout . **Large library of pre-built widgets** (tables, forms, lists) bindable to data instantly . **Strong DB and API connectivity**: MySQL, PostgreSQL, MongoDB, GraphQL, REST APIs, Snowflake, and more . **GitHub and AI copilot integrations** . **Self-hosting puts you in full control** — runs in a single Docker container, deployable to AWS, GCP, Azure, DigitalOcean, Kubernetes, or even a laptop . **Native Git integration** means every low-code app can be version-controlled and integrated into existing CI/CD pipelines like any full-code application . **SOC2, HIPAA, and GDPR certifications** for regulated industries . **Best for engineering teams** wanting low-code speed without sacrificing DevOps practices, version control, or infrastructure control.

- **[Budibase](https://github.com/Budibase/budibase)**  
  **The open-source operations platform for apps, automations, and agents** — **GPL v3 licensed** (client libraries MPL) . **Saves engineers hundreds of hours** building internal tools, workflows, and AI agents . **Self-host on your own infrastructure** with global user management, onboarding, SMTP, groups, theming, and portals . **Connects to PostgreSQL, MySQL, MSSQL, MongoDB, REST APIs** and more . **Role-based access control** and **automations and workflows** for repetitive tasks . **Docker and Kubernetes** deployment support . **Best for operations teams and engineers** wanting a scalable open-source platform for internal tooling with self-hosted control.

- **[Baserow](https://github.com/baserow/baserow)**  
  **The open-source Airtable alternative** — **AGPL-3.0 licensed**, self-hostable or cloud . **Combines spreadsheet simplicity with relational database power** . **Four integrated modules**: **Database Builder** (relational models, 30+ field types, multiple views), **Application Builder** (client portals, dashboards, internal tools), **Automation Builder** (triggers, actions, routers), and **Baserow AI** (build databases and automations in plain language) . **API-first architecture** — automatically generates REST APIs from your database structure . **Real-time collaboration** with row-level comments, @mentions, row history, and permission controls . **Views**: Grid, Gallery, Kanban, Form/Survey, Calendar, and Timeline, each with filtering, sorting, grouping, and color coding . **Best for teams migrating from Airtable or spreadsheets** wanting a familiar interface with self-hosted data ownership.

### Additional Strong Open-Source Options

- **Directus** — Open-source headless CMS and data platform that wraps any SQL database with a no-code data studio, REST/GraphQL APIs, and granular access control. Best for teams wanting a no-code layer over existing databases.
- **Strapi** — Open-source headless CMS with a visual content-type builder and REST/GraphQL APIs. Best for content-heavy applications needing a no-code admin panel.
- **Reflex** — Full-stack Python framework with an AI app builder, allowing visual development and one-click deployment. 28,900+ GitHub stars. Best for Python developers wanting no-code convenience.
- **n8n** — Fair-code workflow automation with visual builder and 500+ integrations. While primarily automation, it can orchestrate data flows that feed no-code apps.

**Frameworks for building custom systems**: Combine **NocoBase** for a plugin-extensible enterprise no-code platform with AI employees and workflow automation, **ToolJet** for AI-assisted internal tool generation with 100+ data sources and MCP integration, **Appsmith** for developer-friendly low-code with Git-based CI/CD and self-hosting control, **Budibase** for operations-focused internal apps with self-hosted user management, and **Baserow** for an Airtable-style database builder with applications and automations — to build a no-code development stack tailored to your team's technical depth, data governance requirements, and deployment constraints.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- No-code development platforms differ significantly in deployment model, data ownership, and extensibility philosophy. **NocoBase is the most plugin-extensible open-source option** with AI employees embedded in workflows, but its plugin-based architecture requires more initial configuration than simpler alternatives . **ToolJet's AI generation produces native app configurations that remain editable** — generated queries and permissions should be reviewed before production use . **Appsmith outputs plain JavaScript that's Git-friendly**, making it the strongest choice for teams wanting low-code that integrates into existing DevOps pipelines . **Budibase is GPL v3 licensed** with client libraries under MPL, so apps you build can be licensed however you like . **Baserow is AGPL-3.0** and API-first, with AI-assisted building in plain language . **Self-hosting shifts operational responsibility to you** — database backups, TLS configuration, and platform upgrades become your job.
- Self-hosted open-source solutions require proper database configuration (PostgreSQL/MySQL for NocoBase, built-in PostgreSQL for ToolJet), Docker or Kubernetes deployment, and monitoring of platform resource usage.

---

**Made for operations teams, internal tool builders, and organizations building applications without traditional coding.**
Let's make no-code development more open, self-hosted, and developer-respecting.
