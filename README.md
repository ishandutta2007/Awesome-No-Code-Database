# Awesome-No-Code-Database

# Awesome-No-Code-Database

## Top No-Code Database Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on PostgreSQL-Native Storage, AI-Assisted App Building & Self-Hosted Data Control*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **No-Code Databases**. These tools combine the familiar spreadsheet grid with relational database structure — linked records, typed fields, views, and automations — letting operations teams build internal tools and track data without writing SQL or deploying custom software.

**Examples** include Teable, Baserow, NocoDB, Grist, Airtable, Smartsheet, Monday.com, ClickUp, Quickbase, Caspio, Coda, Notion Databases, Kintone (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, PostgreSQL-native storage, and transparent licensing — ideal for teams escaping per-seat pricing and record caps while keeping their data in a database they control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Airtable** — The reference no-code database with the largest template ecosystem and polish. **Free tier caps at 1,000 records per base**; Team at **$20/seat/month**, Business at **$45/seat/month** (annual) [citation:14]. **Trade-offs**: per-seat pricing scales steeply, records live on Airtable's servers, and there is **no way to point the interface at a database you already run** [citation:14]. **Best for teams wanting maximum polish and templates** who accept cloud dependency.

- **Smartsheet** — Enterprise work management with spreadsheet-style grids, Gantt views, and automation. **Best for project and program management** with compliance-oriented controls.

- **Monday.com** — Work OS with customizable boards, automations, and dashboards. Broader than pure relational data — focused on workflow tracking.

- **Quickbase** — Enterprise no-code platform for building custom business applications with relational databases and workflow automation.

- **Caspio** — No-code platform for building database-driven applications with forms, reports, and workflows on a managed cloud database.

- **Coda** — Doc-platform with tables, formulas, buttons, and automations. Strong formula language blending document and database paradigms.

- **Notion Databases** — Databases within the Notion workspace with relations, rollups, and multiple views. **Weaker relational integrity than dedicated database tools** — better for lightweight structured content.

- **Kintone** — No-code application platform with customizable databases, forms, and workflow automation for team collaboration.

## Open-Source GitHub Projects

- **[Teable](https://github.com/teableio/teable)**  
  **The Postgres-native no-code database with real SQL underneath** — **AGPL-3.0 licensed Community Edition**, self-hostable for free with no license fee; you pay only your own infrastructure [citation:2][citation:6]. **Every field is a physical PostgreSQL column** — no JSON blobs, no proprietary lock-in, and you can query the same data directly with pgAdmin or DBeaver without interference [citation:8]. **The full self-hosted deployment bundles four platforms in one**: a database collaboration platform (tables, views, permissions, API), an **AI chat and agent sandbox** where every session runs in its own isolated container, an **App Builder** that deploys apps to their own URL in one click, and an **AI workflow engine** reacting to record changes, schedules, and webhooks [citation:6]. **Grid, Form, Kanban, Gallery, and Calendar views**; formulas, filtering, grouping, and aggregation; comments, record history, undo/redo, and real-time collaboration [citation:6]. **Handles millions of rows without breaking a sweat** and includes a **built-in SQL editor** for joins, CTEs, and materialized views [citation:6]. **Licensing caveat**: the **standalone Docker image omits AI features and App Builder** — only the full deployment includes them [citation:6]. **Self-hosted premium plans charge per seat** ($10–$20/seat/month billed yearly) — the community has publicly pushed for instance-based pricing without success [citation:8]. **Best for teams wanting Airtable-like collaboration with genuine PostgreSQL performance** on large datasets, accepting the youngest-product maturity trade-off [citation:8].

- **[Baserow](https://github.com/baserow/baserow)**  
  **The closest self-hosted Airtable replacement with the most permissive licence** — **MIT Expat licensed Open Source Edition** (OSI-approved), self-hosted with **unlimited rows, storage, and databases** [citation:7][citation:8]. **Brings its own database** and behaves like Airtable does, making it the easier switch when Airtable is your system of record rather than a view onto something else [citation:8]. **Real-time collaborative editing is better than NocoDB's**, with row-level comments and notifications [citation:8]. **Application Builder** lets you put a front end on your data, publishable to a custom domain — covering the portal use case that usually sends Airtable users to buy Softr or Noloco on top [citation:8]. **Full REST API** reflecting every table and field, with Docker Compose deployment. **Django/Postgres/Redis stack wants roughly 2 vCPU and 4GB RAM** [citation:8]. **Trade-offs**: **premium/ and enterprise/ directories carry separate licences** — some views (reportedly Kanban and calendar) sit behind a paid Premium licence even when self-hosting [citation:3][citation:8]; **no native mobile app**, only responsive web [citation:8]. **Best for teams wanting an OSI-approved licence** with the least disruption from Airtable, especially when you need an application builder without buying a separate portal tool.

- **[NocoDB](https://github.com/nocodb/nocodb)**  
  **The UI layer over the database you already run** — **most-starred Airtable clone at ~62,000 GitHub stars** [citation:14]. **Connects to existing PostgreSQL, MySQL, MariaDB, SQL Server, or SQLite** — your data stays where it is, and you point NocoDB at a replica for a working internal tool in minutes [citation:14]. **Self-hosted has no row cap and no per-seat charge**; cloud caps billing per workspace at around **$108/month with unlimited seats above that** [citation:14]. **Critical licence caveat**: the Community edition ships under the **Sustainable Use License 1.0 (fair-code, source-available, not OSI-approved)** — self-hosting for internal use is fine, but **offering NocoDB as a hosted service to third parties may require a commercial licence** [citation:4][citation:11]. **SSO, audit logs, and row-level security sit behind paid self-hosted licences**, and reviewers have flagged data-safety gaps worth testing before trusting it with critical data [citation:14]. **Best for engineering teams wanting a friendly collaborative skin over an existing database** — but not for teams needing genuine OSI-approved open source.

- **[Grist](https://github.com/gristlabs/grist-core)**  
  **The Python-formula hybrid with granular permissions** — **Apache 2.0 core**, self-hostable, with **Python formulas** that are real code rather than a proprietary formula language [citation:8]. **Access rules go down to the row, column, and table level** — better than anything else in the category for mixed-trust datasets where a contractor should see some rows and not others [citation:8]. **Pricing surprise**: individuals and organizations with **less than $1 million in total annual income** (revenue plus funding) can request a **free activation key** — essentially every indie hacker [citation:5][citation:8]. **Trade-offs**: **Python formulas are a superpower if you code and a wall if you don't**; **no front-end app or portal builder**; **automations gated to the Business plan** with a five-seat minimum [citation:8]. **Best for technical solo founders and analysts** needing real permission control over sensitive data.

### Additional Strong Open-Source Options

- **SoupTable** — Open-source spreadsheet-database storing **every field as a physical PostgreSQL column**, with **visual Row-Level Security that compiles to native PostgreSQL RLS policies** and a **1-Click Multi-Tenant SaaS Guard** for database-kernel-level tenant isolation. AES-256-GCM field encryption, immutable audit logging, and REST/columnar APIs. Next.js 16 + Payload CMS + PostgreSQL 16 + BullMQ. **Best for multi-tenant SaaS builders** wanting database-enforced security rather than app-level permissions.
- **Directus** — Open-source headless data platform wrapping any SQL database with a no-code data studio, REST/GraphQL APIs, and granular access control. **Best for teams wanting a no-code layer over existing databases** with role-based access.

**Frameworks for building custom systems**: Combine **Baserow** for the most permissive OSI-approved licence with an application builder and unlimited self-hosted rows, **Teable** for PostgreSQL-native performance on large datasets with AI app building and SQL access, **NocoDB** for a UI layer over an existing production database where the licence permits internal use, and **Grist** for Python-powered formulas with row-and-column-level permissions on sensitive data — to build a no-code database stack tailored to your licensing requirements, data ownership needs, and team technical depth.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- No-code databases differ significantly in licensing, data ownership, and performance ceiling. **Baserow's MIT Expat licence is the most permissive on the list** — but premium/ and enterprise/ directories carry separate terms, and some views sit behind a paid licence even when self-hosting [citation:3][citation:8]. **Teable is the most PostgreSQL-native option** — every field is a real column and the full deployment bundles AI app building and agent sandboxes — but its **standalone Docker image omits AI and App Builder**, and self-hosted premium tiers still charge per seat despite community pushback [citation:6][citation:8]. **NocoDB's Sustainable Use License is not OSI-approved** — offering it as a hosted service may require a commercial licence, and SSO/RLS sit behind paid self-hosted tiers [citation:4][citation:14]. **Grist's Python formulas are a wall for non-coders**, and its free activation key requires under $1M annual income [citation:5][citation:8]. **Self-hosting shifts operational responsibility to you** — database backups, TLS configuration, and upgrades become your job.
- Self-hosted open-source solutions require proper PostgreSQL configuration, Docker or Kubernetes deployment, and awareness that row caps and premium features may differ between cloud and self-hosted editions.

---

**Made for operations teams, internal tool builders, and organizations building no-code databases they can own and control.**
Let's make no-code databases more open, PostgreSQL-native, and licence-transparent.
