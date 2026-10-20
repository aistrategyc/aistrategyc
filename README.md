<img src="https://raw.githubusercontent.com/aistrategyc/aistrategyc/main/assets/kyrylo-prolieiev.jpg" width="145" align="right" alt="Kyrylo Prolieiev">

# Kyrylo Prolieiev

**Software Architect · Full-Stack Developer · Data & Applied AI**

I design and build SaaS platforms, web and native iOS applications, data pipelines and AI-assisted workflows.

My work usually connects several parts of a business: orders and payments, documents and accounting, team tasks and metrics, or customer conversations and CRM. I also bring experience leading operations across a multi-location business. The case studies describe my responsibility in each project.

[Portfolio](https://proleev.com/en) · [Engineering services](https://aisolutionsbi.pl/en) · [Planerix](https://planerix.com/en)

<br clear="right">

## Public engineering examples

Small, runnable projects with PostgreSQL, failure tests and CI. Each focuses on a specific engineering problem and uses synthetic data.

| Repository | Start here if you want to review… |
|---|---|
| [Reliable webhooks](https://github.com/aistrategyc/reliable-webhook-lab) | Payment idempotency, transactional outbox, worker leases and recovery after a crash |
| [Tenant access](https://github.com/aistrategyc/tenant-access-lab) | API authorization, revoked membership, cross-tenant access tests and concurrent edits |
| [Analytics pipeline](https://github.com/aistrategyc/analytics-pipeline-lab) | Incremental ETL, late data, source revisions and reconciled reporting |
| [Source-aware RAG](https://github.com/aistrategyc/source-aware-rag-lab) | Source revalidation, cited context and user-confirmed actions |

These are independent reference implementations. Their READMEs explain the trade-offs and the remaining work before deployment. Production repositories stay private.

## Work I take on

- **Business platforms:** organizations, roles, shared work, documents and operational workflows.
- **Products and commerce:** customer journeys connected to payments, subscriptions and fulfilment.
- **Data foundations:** API ingestion, ETL, attribution, warehouse models and management reporting.
- **Applied AI:** source-based answers, scoped retrieval and actions people can review.

## Selected work

| Project | Business problem | Engineering focus |
|---|---|---|
| [Planerix](cases/planerix.md) | Connect team execution with KPI/OKR context | Shared web/iOS model, scoped retrieval, reviewed AI actions |
| [LEG](cases/biuro.md) | Bring documents, finance and accounting follow-up together | Scanning, invoice parsing, company permissions, financial records |
| [REST](cases/rest.md) | Connect guest communication with restaurant operations | Guest 360, native inbox, location analytics, menu and staff learning |
| [WODAO](cases/wodao.md) | Run subscriptions from payment to physical delivery | Stripe event handling, checkout locks, workers, customer/courier apps |
| [IT STEP](cases/itstep.md) | Give marketing and management consistent reporting | API/ETL, PostgreSQL raw/DWH/semantic layers, attribution |
| [SEOULAB](cases/seoulab.md) | Build a storefront and its operating tools | Commerce API, stock reservations, order integrity and administration |

[All 10 case studies](cases/README.md) include Ninja Group, Loveepil, VEAN and the URBAN white-label deployment.

## Technology in context

| Layer | Tools I use | What they support |
|---|---|---|
| Web | TypeScript, React, Next.js | Workspaces, storefronts and administration |
| Backend | Python, FastAPI; Node.js, Express | APIs, domain rules and integrations |
| Native mobile | Swift, SwiftUI | Team work, document capture, communications and delivery |
| Data | PostgreSQL, SQL, SQLite | Transactional records, migrations, ETL and analytical models |
| AI and automation | Qdrant, n8n, LLM APIs | Scoped retrieval, source context and reviewed workflows |
| Delivery | Docker, GitHub Actions | Service boundaries, validation and controlled releases |

Integration work includes Stripe, Google Ads, Meta, GA4, Telegram, Instagram, Syrve/iiko, ChoiceQR, Altegio, KSeF and InsERT. The case pages explain the role and activation boundaries of each integration.

## Engineering choices

- Keep the authoritative record separate from derived analytics and retrieval indexes.
- Recheck access at the API and source record, including after retrieval.
- Make payment, order and background-delivery states explicit.
- Test failure paths such as retries, stale versions, rollback and duplicate callbacks.
- Make the operating process understandable to the team that will use it.

[Integration and delivery work](engineering/practices.md) · [Architecture decisions](engineering/decisions.md) · [Verification notes](engineering/evidence.md)

This repository contains case studies, architecture diagrams and approved interface examples. Client data covered by NDA is omitted; demo and prototype screens are labelled.

For project enquiries, use [proleev.com](https://proleev.com/en) or [AISOLUTIONS](https://aisolutionsbi.pl/en).
