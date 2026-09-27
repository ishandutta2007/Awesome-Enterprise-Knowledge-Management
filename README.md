# Awesome-Enterprise-Knowledge-Management

# Top Enterprise Knowledge Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Internal Knowledge Bases, Team Wikis, Documentation & Self-Service Support*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Knowledge Management**. These tools help teams capture, organize, verify, and retrieve institutional knowledge through wikis, documentation sites, knowledge bases, and self-service support portals.

**Examples** include Guru, Slab, Document360, Bloomfire, Zendesk Guide, Confluence, Tettra, Helpjuice, KnowledgeOwl, and Panviva (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom knowledge workflows, and transparent data ownership — ideal for teams that want full control over sensitive internal documentation without per-seat SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Guru](https://www.getguru.com/)**  
  AI-powered knowledge management platform that surfaces verified answers directly in Slack, browser, and other work tools. Organizes knowledge into cards, boards, and collections with verification workflows.

- **[Slab](https://slab.com/)**  
  Modern knowledge base platform with a clean editor, unified search across connected tools, and strong integrations with Slack, Google Drive, and GitHub. Focuses on preventing stale docs through verification workflows.

- **[Document360](https://document360.com/)**  
  Knowledge base software for creating public help centers and internal documentation. Features versioning, role-based access, analytics, and multi-language support.

- **[Bloomfire](https://bloomfire.com/)**  
  Knowledge engagement platform with AI-powered search, community Q&A, and content verification. Focused on enterprise knowledge sharing and employee onboarding.

- **[Zendesk Guide](https://www.zendesk.com/)**  
  Knowledge base component within the Zendesk customer support platform. Creates help centers, internal knowledge bases, and AI-powered self-service portals integrated with ticketing.

- **[Confluence](https://www.atlassian.com/software/confluence)**  
  Atlassian's enterprise wiki and documentation platform. Deeply integrated with Jira and the broader Atlassian ecosystem. Available as Cloud and Data Center.

- **[Tettra](https://tettra.com/)**  
  Lightweight internal knowledge base for teams. Integrates deeply with Slack and Microsoft Teams to capture tribal knowledge and turn conversations into permanent documentation.

- **[Helpjuice](https://helpjuice.com/)**  
  Knowledge base software designed for customer support and internal wikis. Rich text editor, AI-powered search, version control, and detailed analytics.

- **[KnowledgeOwl](https://www.knowledgeowl.com/)**  
  Knowledge base software with a focus on simplicity, customization, and customer support. Offers public and private knowledge bases.

- **[Panviva](https://panviva.com/)**  
  Knowledge management platform for guided process execution. Delivers step-by-step workflow guidance to agents and employees in regulated industries.

## Open-Source GitHub Projects

- **[Outline](https://github.com/outline/outline)**  
  Fast, collaborative knowledge base for teams with a polished Notion-like editor. Features real-time collaboration, nested collections, Slack integration, and AI-powered search. Requires external OIDC/SAML for authentication. ~38.8k stars. License: BSL 1.1 .

- **[Docmost](https://github.com/docmost/docmost)**  
  Open-source Confluence and Notion alternative for team wikis. Features real-time collaborative editing (CRDT-based), spaces with nested pages, granular permissions, native diagrams (Draw.io, Excalidraw, Mermaid), and built-in email/password auth. Deploys via Docker Compose. ~21k stars. License: AGPL-3.0 .

- **[WeKnora](https://github.com/Tencent/WeKnora)**  
  Open-source, LLM-powered enterprise knowledge framework by Tencent. Turns raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki. Wiki Mode auto-generates structured, interlinked Markdown pages with a knowledge graph. Supports 20+ LLM providers, 4-tier RBAC, and AES-256-GCM encryption. Written in Go, deploys via Docker/Kubernetes/Helm. License: MIT .

- **[BookStack](https://github.com/BookStackApp/BookStack)**  
  Simple, structured documentation platform organized in a shelves → books → chapters → pages hierarchy. WYSIWYG and Markdown editors, role-based permissions, and full-text search. Built-in email/password authentication. Ideal for non-technical teams. ~16k stars. License: MIT .

- **[Wiki.js](https://github.com/requarks/wiki)**  
  Modern, extensible Node.js wiki with Markdown editing, powerful admin tools, and support for PostgreSQL, MySQL, MariaDB, SQLite, and SQL Server. Optional Git-backed storage makes every page edit a Git commit. ~25k stars. License: AGPL-3.0 .

- **[AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)**  
  Open-source Notion alternative built with Flutter and Rust. Local-first architecture with offline support, kanban boards, databases, and AI integration. Self-hosted sync server available via AppFlowy Cloud. ~66k stars. License: AGPL-3.0 .

- **[Trilium Notes](https://github.com/TriliumNext/Notes)**  
  Hierarchical personal knowledge base with JavaScript scripting inside notes, REST API (ETAPI), and programmable automation. Note: original repo was archived in 2024; community fork TriliumNext is actively maintained. ~28k stars. License: AGPL-3.0 .

- **[DokuWiki](https://github.com/dokuwiki/dokuwiki)**  
  Lightweight, file-based wiki engine requiring no database. Plain-text storage, extensive plugin/template ecosystem, ACL support, and versioning. Popular for simple, low-maintenance knowledge bases. License: GPL-2.0 .

- **[MediaWiki](https://github.com/wikimedia/mediawiki)**  
  The wiki engine behind Wikipedia. Proven scalability to millions of pages, hundreds of extensions, and robust wiki-link syntax. Best for very large, highly interconnected knowledge repositories. License: GPL .

- **[PandaWiki](https://github.com/chaitin/PandaWiki)**  
  Open-source knowledge base system driven by large models, developed by Chaitin. Enables fast building of intelligent documentation, FAQ, and blog centers. Supports multi-source ingestion (web pages, RSS, files), vector retrieval, and RAG pipelines. TypeScript and Go components. License: Open source .

- **[Documize](https://github.com/documize/community)**  
  Modern Confluence alternative designed for internal and external docs, built with Go and EmberJS. Features spaces, labels, search, and enterprise authentication. ~2.1k stars. License: AGPL-3.0 .

### Additional Strong Open-Source Options

- **Knowledge Graph & PKM**: **Logseq** (outliner-first with bidirectional links, plain Markdown files), **Anytype** (local-first, peer-to-peer encrypted), **Notesnook** (end-to-end encrypted notes) .
- **API Documentation**: **Docusaurus** (React-based static docs), **MkDocs** (Python-based static docs), **Read the Docs** (documentation hosting from Git repos) .
- **Q&A & Community Knowledge**: **Answer** (open-source Stack Overflow clone for teams), **Discourse** (forum-based knowledge sharing).
- **Helpdesk & Support**: **Helpy** (knowledgebase + community discussions + support tickets), **FreeScout** (Zendesk/Help Scout alternative), **Peppermint** (ticket management with knowledge base) .

**Frameworks for building custom systems**: Combine **Docmost** or **Outline** for the core wiki, **WeKnora** for AI-powered document ingestion and auto-generated wiki pages, **BookStack** for structured non-technical documentation, and **PostgreSQL + Redis + S3** for persistence. Add **Ollama** for self-hosted AI-powered search and writing assistance.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Knowledge management tools may store sensitive internal documentation; ensure proper access controls and encryption.
- Self-hosted open-source solutions require regular maintenance, security updates, and backup strategies. The license is free; the project is not.

---

**Made for engineering teams, technical writers, product managers, and knowledge workers.**  
Let's make knowledge management more open, transparent, and collaborative.
