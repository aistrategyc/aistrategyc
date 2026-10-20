# Evidence and selected verification

The case studies describe implemented scope and the owner's stated responsibilities. Architecture diagrams explain system boundaries; they are not captures of private infrastructure. Client-specific records and credentials are omitted.

## Selected checks — 18 October 2026

| Reference | Checks passed | What was exercised | Environment |
|---|---:|---|---|
| WODAO | 32 | Checkout lock lifecycle and late payment events | Database/provider doubles |
| LEG | 40 | Financial calculations, XML parsing and calendars | Local fixtures; network blocked |
| Planerix | 13 | Scoped graph IDs, replay and evidence ranking | Synthetic graph data |
| Planerix / REST | 13 | Period analysis, revenue decomposition and scope checks | Fixtures and mocked access |
| SEOULAB | 19 | Reservations, rollback, idempotency and release modes | Local HTTP and in-memory SQLite |

These 117 selected passing tests are a dated engineering review, not full-suite coverage, a penetration test or a live-payment audit. Separately, 30 n8n templates passed structural validation; that is not proof that every workflow ran against live providers.

## Interface provenance

- **Planerix:** native demonstration capture from build 18. Later reviewed-action releases are described separately.
- **LEG and REST:** actual application interfaces with demonstration company or guest data.
- **WODAO:** customer interface with demonstration orders.
- **SEOULAB and Ninja Group:** public storefront/restaurant website captures; protected administration and private CRM data are not published here.
- **Loveepil:** retained project frontend, visually refined with demonstration data. The delivered scope includes internal ERP and Altegio integration; private internals remain under NDA.
- **VEAN:** a separate BeautyCRM prototype illustrates an interface approach. It is not evidence of a historical VEAN production deployment.
- **IT STEP and URBAN:** explanatory architecture rather than private client dashboards.

Repository statistics do not establish personal authorship. Roles distinguish product architecture, direct implementation and operational leadership. No unverified revenue growth, throughput, uptime or AI accuracy is claimed.

All image files in this repository were already published in the approved portfolio websites. Project and technology names identify the work; they do not imply endorsement or certification.
