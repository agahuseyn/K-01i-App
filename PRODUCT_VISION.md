# YURIS — CEO Review & Complete Product Vision

> Legal intelligence platform. 200+ countries. From library to legal infrastructure.

---

## Part 1: Core Premise

YURIS collects legal acts from 200+ countries and makes them available for use.

**The CEO challenge:** "Collect and make available" is a library, not a product. A library competes on coverage and price. The 10-star YURIS is a **legal intelligence engine** — making legal knowledge across 200 countries as easy as asking a question.

**The key insight:** Legal research is not a search problem. It's a **workflow** problem. Nobody opens a legal database to "find a law." They have a job to be done:
- "Can we sell this product in Brazil?"
- "We're hiring remote workers in Southeast Asia"
- "How does this new EU regulation affect our operations in 12 countries?"

Each of these is a multi-step legal workflow that currently requires identifying jurisdictions, finding applicable laws, understanding them (often in a foreign language), comparing across jurisdictions, assessing risk, and monitoring for changes. YURIS should guide users through legal workflows, not just answer questions.

---

## Part 2: Product Evolution (6 Stages)

### Stage 1: The Library — "Find any law" (Month 0-3)

```
┌─────────────────────────────────────────────────────────┐
│  YURIS                                    [Search...]   │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  Browse by Country          Browse by Domain            │
│                                                         │
│  Afghanistan    Denmark     │  Constitutional Law       │
│  Albania        Ecuador     │  Criminal Law             │
│  Algeria        Egypt       │  Labor & Employment       │
│  ...            ...         │  Tax Law                  │
│  (200+ countries)           │  Data Privacy             │
│                             │  Corporate Law            │
│                             │  ...                      │
│                                                         │
│  Recent additions:                                      │
│  Brazil - Lei 14.993/2024 - AI Regulation Framework     │
│  India - Digital Personal Data Protection Rules 2025    │
│  EU - AI Act Implementing Regulation 2025/123           │
└─────────────────────────────────────────────────────────┘
```

- 200+ countries' legal acts in one place
- Free, SEO-optimized, permanent citeable URLs
- Every legal act has a stable URL that lawyers can cite
- The top-of-funnel: Google sends users here when they search for "Nigeria Companies Act"
- **Moat:** Data coverage

**Why it's not enough:** Users find the law but can't use it — wrong language, don't know if it's been amended, can't tell if it's the right law for their question.

---

### Stage 2: The Translator — "Read any law" (Month 3-5)

```
┌─────────────────────────────────────────────────────────┐
│  Japan — Act on the Protection of Personal Information   │
│  Act No. 57 of 2003 (as amended 2022)                   │
│                                                         │
│  [Original]  [English]  [Side-by-side]                  │
│                                                         │
│  ┌──────────────────┬──────────────────────────────┐    │
│  │  第一条            │  Article 1 (Purpose)          │    │
│  │  この法律は、デジ   │  This Act aims to protect     │    │
│  │  タル社会の進展に   │  the rights and interests     │    │
│  │  伴い個人情報の利   │  of individuals while         │    │
│  │  用が著しく拡大し   │  considering the utility of   │    │
│  │  ていることに鑑み   │  personal information...      │    │
│  │  ...              │                               │    │
│  └──────────────────┴──────────────────────────────┘    │
│                                                         │
│  Legal terms:                                           │
│  個人情報 = "personal information" (defined in Art. 2)   │
│  個人情報取扱事業者 = "personal information handling      │
│  business operator" (defined in Art. 16)                │
│                                                         │
│  This act:                                              │
│  ├── Amended by: Act No. 44 of 2022                    │
│  ├── References: 12 other acts                          │
│  └── Referenced by: 34 acts                             │
└─────────────────────────────────────────────────────────┘
```

- Side-by-side original + translated text
- Legal terminology glossaries per jurisdiction (terms of art, not just translation)
- Amendment chain and related acts panels (powered by graph layer)
- Users start **understanding** laws, not just finding them
- **Moat:** Legal translation quality (domain glossaries)

---

### Stage 3: The Analyst — "Understand any law" (Month 5-8)

```
┌─────────────────────────────────────────────────────────┐
│  Q: What are the data breach notification               │
│     requirements in Brazil?                             │
│                                                         │
│  Under Brazil's LGPD (Law No. 13.709/2018), data       │
│  breach notification works as follows:                  │
│                                                         │
│  WHO MUST BE NOTIFIED:                                  │
│  • The ANPD (national authority) — mandatory [1]        │
│  • Affected data subjects — when the breach may cause   │
│    "relevant risk or damage" [2]                        │
│                                                         │
│  TIMELINE:                                              │
│  • 3 business days from knowledge of the breach [3]     │
│                                                         │
│  PENALTIES:                                             │
│  • Up to 2% of revenue in Brazil, capped at             │
│    R$50 million per violation [4]                        │
│                                                         │
│  ───── Citations ─────                                  │
│  [1] LGPD Art. 48, caput    ← click to jump             │
│  [2] LGPD Art. 48, §1°                                 │
│  [3] ANPD Resolution CD/ANPD No. 15/2024, Art. 6       │
│  [4] LGPD Art. 52, item II                              │
│                                                         │
│  Confidence: HIGH — based on explicit statutory text    │
│  Current as of: March 2026                              │
│  [Monitor this topic for changes]                       │
└─────────────────────────────────────────────────────────┘
```

- AI-powered Q&A with verified citations
- Every claim links to the exact article, section, paragraph
- Confidence scoring (high/medium/low)
- Jurisdiction-scoped answers — never mixes laws from different countries without explicit comparison
- **Citation verification:** every cited article checked against stored text before serving
- First paid conversion point (Pro tier)
- **Moat:** Citation verification = trust

---

### Stage 4: The Comparator — "See across borders" (Month 8-10)

```
┌────────────────────────────────────────────────────────────────┐
│  Compare: Data Breach Notification Requirements                │
│  Jurisdictions: [Brazil] [EU/GDPR] [Japan] [California]      │
│                                                                │
│  ┌──────────┬───────────┬───────────┬───────────┬──────────┐  │
│  │          │ Brazil    │ EU (GDPR) │ Japan     │ Calif.   │  │
│  ├──────────┼───────────┼───────────┼───────────┼──────────┤  │
│  │ Notify   │ ANPD +    │ DPA +     │ PPC +     │ AG +     │  │
│  │ whom?    │ subjects  │ subjects  │ subjects  │ subjects │  │
│  ├──────────┼───────────┼───────────┼───────────┼──────────┤  │
│  │ Timeline │ 3 biz days│ 72 hours  │ "Promptly"│ "Most    │  │
│  │          │           │           │           │ expedient│  │
│  ├──────────┼───────────┼───────────┼───────────┼──────────┤  │
│  │ Max fine │ R$50M     │ €20M/4%   │ ¥100M     │ $7,500/  │  │
│  │          │ (~$10M)   │ revenue   │ (~$670K)  │ violation│  │
│  └──────────┴───────────┴───────────┴───────────┴──────────┘  │
│                                                                │
│  KEY DIFFERENCES:                                              │
│  • EU: strictest timeline (72h) and highest penalties          │
│  • Japan: broadest trigger (any leak, no materiality test)     │
│  • California: only one with affected-count threshold (500)    │
│                                                                │
│  [Export as PDF]  [Share]  [Monitor all for changes]           │
└────────────────────────────────────────────────────────────────┘
```

- Cross-jurisdiction comparison tables with citations
- Side-by-side analysis of equivalent laws across countries
- Powered by graph layer (find equivalent legislation) + RAG (extract comparable provisions)
- The feature that triggers enterprise sales calls
- **Moat:** Graph relationships (nobody else has mapped how laws relate across jurisdictions)

---

### Stage 5: The Co-Pilot — "Navigate legal workflows" (Month 10-14)

```
┌────────────────────────────────────────────────────────────────┐
│  WORKFLOW: Market Entry — Southeast Asia                       │
│  Countries: [SG] [VN] [TH] [PH] [ID] [MY]                   │
│                                                                │
│  Progress: ████████░░░░░░░░░░░░ 40%                           │
│                                                                │
│  [x] 1. Entity Requirements                                   │
│      SG: No local entity needed (EP visa or EOR)              │
│      VN: Local entity OR representative office required       │
│      PH: 60/40 Filipino ownership rule (see RA 11647)         │
│      ID: Local entity required. Min capital IDR 10B           │
│      → Full report with citations saved                       │
│                                                                │
│  [x] 2. Employment Contracts — [See comparison table]         │
│                                                                │
│  [~] 3. Compensation & Benefits  ← YOU ARE HERE               │
│      SG: CPF contributions (employer 17%, employee 20%)       │
│      VN: Social insurance 17.5% employer, mandatory 13th mo  │
│      TH: Social security 5% employer (capped)                │
│      [See full comparison table →]                            │
│                                                                │
│  [ ] 4. Tax Obligations                                       │
│  [ ] 5. Work Permits & Immigration                            │
│  [ ] 6. Termination Requirements                              │
│  [ ] 7. Data Protection (Employee Data)                       │
│  [ ] 8. Regulatory & Licensing Requirements                   │
│                                                                │
│  Final Deliverable: Market Entry Legal Package (PDF/DOCX)     │
│  Monitoring: ON — alerts if any law changes in these countries │
└────────────────────────────────────────────────────────────────┘
```

- Guided, multi-step legal workflow engine
- Templated workflows: Market Entry, M&A Due Diligence, Product Compliance, Data Privacy Compliance, Employment Setup, IP Protection, Anti-Corruption Compliance
- Complete legal analysis packages as deliverables
- Monitoring built in — alerts when relevant law changes
- Users can create custom workflows; law firms can share with clients
- **Moat:** Workflow templates (accumulated legal process knowledge)

---

### Stage 6: The Platform — "Run your legal ops" (Month 14+)

```
┌────────────────────────────────────────────────────────────────┐
│  YURIS DASHBOARD — Acme Corp                                   │
│                                                                │
│  ┌─ Active Workflows ─────────────────────────────────────┐   │
│  │  SE Asia Market Entry ·········· 85% complete          │   │
│  │  GDPR Annual Review ············ Due in 14 days        │   │
│  │  Brazil LGPD Compliance Audit ·· In progress           │   │
│  └────────────────────────────────────────────────────────┘   │
│                                                                │
│  ┌─ Regulatory Alerts (This Week) ────────────────────────┐   │
│  │  CRITICAL: Indonesia — New data localization rules      │   │
│  │    effective April 2026. [View] [Start workflow]       │   │
│  │  MEDIUM: EU — DORA technical standards finalized.       │   │
│  │    [View summary]                                      │   │
│  │  LOW: Japan — Minor APPI guideline clarification.       │   │
│  │    [View]                                              │   │
│  └────────────────────────────────────────────────────────┘   │
│                                                                │
│  ┌─ Compliance Scoreboard ────────────────────────────────┐   │
│  │  Singapore ████████████ 98%  Last reviewed: 3 days     │   │
│  │  Vietnam   █████████░░░ 82%  2 items need attention    │   │
│  │  Thailand  ████████████ 95%  Last reviewed: 1 week     │   │
│  │  EU/GDPR   ██████████░░ 91%  DORA impact pending       │   │
│  │  Brazil    ████████░░░░ 76%  New ANPD regulation       │   │
│  └────────────────────────────────────────────────────────┘   │
│                                                                │
│  ┌─ API Usage ────────────────────────────────────────────┐   │
│  │  12,400 queries this month                             │   │
│  │  Top: /compare (45%), /ask (30%), /monitor (25%)       │   │
│  └────────────────────────────────────────────────────────┘   │
└────────────────────────────────────────────────────────────────┘
```

- Compliance scoreboard across all operating countries
- Team collaboration, API access, embeddable widgets
- The operating system for cross-border legal work
- **Moat:** Customer data + API integrations (switching cost)

---

## Part 3: The Big Insight — Vertical Legal Services

**If YURIS knows all immigration law, it can digitalize the visa application process and charge per customer.**

This is the jump from **legal intelligence** to **legal automation**:

```
TRADITIONAL:    Legal question → Lawyer researches → Lawyer advises → Client acts
YURIS INTEL:    Legal question → YURIS answers with citations → Client acts
YURIS AUTO:     Client states goal → YURIS knows the law → YURIS handles the process
                                     ↓
                                     generates forms, checks eligibility,
                                     routes to authority, tracks status
```

Research = $50-500/query. Automation = $50-5,000/transaction. Millions of transactions.

### The Vertical Product Factory

Every vertical follows the same pattern:

```
1. YURIS LEGAL INTELLIGENCE (knows the law)
   ↓
2. DOMAIN TEMPLATE (structures the workflow)
   ↓
3. USER INPUT (specific situation)
   ↓
4. AI + LEGAL DATA (generates personalized output)
   ↓
5. CITED, ACTIONABLE DELIVERABLE
   (roadmap, checklist, comparison, assessment, forms)
   ↓
6. MONITORING (ongoing alerts when relevant law changes)
```

Once the intelligence layer works, each new vertical is mostly a template. The marginal cost of adding verticals drops dramatically. Vertical 1 takes 3 months. Vertical 5 takes 3 weeks. Vertical 10 takes 3 days.

---

### All Verticals

| # | Vertical | What YURIS Does | Revenue Model |
|---|---|---|---|
| 1 | **Immigration & Visas** | Eligibility check, document checklist, form pre-filling, appointment booking, status tracking | $99-499/application |
| 2 | **Company Formation** | Entity type recommendation, name check, constitution generation, filing | $499-2,999/formation |
| 3 | **Trade & Customs** | HS code classification, export license determination, tariff calculation, labeling requirements | $299-999/compliance check |
| 4 | **IP Registration** | Trademark search, classification, filing strategy, application prep, deadline tracking | $199-599/country/app |
| 5 | **Employment & HR** | Compliance checklists, contract templates, payroll parameters, ongoing monitoring | $99/mo/country/employee |
| 6 | **Real Estate** | Foreign ownership eligibility, structure options, due diligence, registration guidance | $499-1,999/transaction |
| 7 | **Contract Intelligence** | Upload contract → flag unenforceable clauses, missing provisions, jurisdiction switching | $49-299/review |
| 8 | **Licensing & Permits** | Complete regulatory maze mapping — every permit needed, in sequence, with prerequisites | $299-999/roadmap |
| 9 | **Sanctions & Export Controls** | Cross-reference OFAC/EU/UK/UN sanctions, dual-use lists, cited risk assessment | $0.10-1.00/screening |
| 10 | **Tax Structuring** | Treaty network analysis, IP box regimes, transfer pricing, BEPS compliance | $999-4,999/analysis |
| 11 | **Dispute Resolution** | Options evaluation, timeline/cost estimates, enforcement analysis, limitation periods | $499-1,999/assessment |
| 12 | **ESG & Sustainability** | Multi-jurisdiction disclosure mapping, reporting deadlines, template reports | $2,999-9,999/year/org |
| 13 | **Personal Legal Navigator** | "TurboTax for legal questions" — divorce, inheritance, tenant rights, consumer complaints | $19-49/navigation |

### Deep Dive: Immigration & Visas (Flagship Vertical)

```
┌────────────────────────────────────────────────────────────────┐
│  YURIS IMMIGRATION                                             │
│                                                                │
│  "I want to work in Germany"                                   │
│                                                                │
│  Nationality: [Turkish]  Purpose: [Employment]                 │
│  Qualifications: [Master's, 5 years experience]                │
│                                                                │
│  ELIGIBLE for:                                                 │
│  ┌────────────────────────────────────────────────────────┐    │
│  │  1. EU Blue Card (recommended)                        │    │
│  │     Basis: §18g AufenthG                              │    │
│  │     Requires: Job offer >= €45,300/yr                 │    │
│  │     Timeline: 4-8 weeks                               │    │
│  │     Path to PR: 27 months (with B1 German)            │    │
│  │     [Start application →]                             │    │
│  ├────────────────────────────────────────────────────────┤    │
│  │  2. Skilled Worker Visa                               │    │
│  │     Basis: §18a/§18b AufenthG                         │    │
│  │     Requires: Recognized qualification                │    │
│  │     [Start application →]                             │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                │
│  [Start application] →                                        │
│  Step 1: Eligibility ✓                                        │
│  Step 2: Document preparation (passport, degree, contract...) │
│  Step 3: Application routing (nearest consulate, wait times)  │
│  Step 4: Status tracking                                      │
│                                                                │
│  $199 per application                                         │
└────────────────────────────────────────────────────────────────┘
```

---

## Part 4: The Endgame — "Stripe for Law"

The most valuable endgame is **legal infrastructure as a service.** Not consumer-facing vertical apps — but the API layer that powers everyone else's legal compliance.

```
POST /api/v1/eligibility
{
  "domain": "immigration",
  "from_country": "TR",
  "to_country": "DE",
  "purpose": "employment",
  "profile": { "education": "masters", "experience_years": 5 }
}
→ Returns: visa types, requirements, documents, timelines, citations

POST /api/v1/compliance/check
{
  "domain": "data_privacy",
  "operation": "store_customer_data",
  "data_origin": "EU",
  "storage_location": "SG"
}
→ Returns: applicable laws, requirements, risk level, citations

POST /api/v1/formation/requirements
{
  "entity_type": "subsidiary",
  "country": "BR",
  "industry": "fintech",
  "foreign_ownership": 100
}
→ Returns: requirements, restrictions, timeline, estimated cost, citations
```

Every fintech needs compliance checks. Every HR platform needs employment law. Every e-commerce platform needs trade regulations. Every travel platform needs visa information. They all build it in-house, badly, with static content that goes stale. YURIS replaces all of it with one API call that's always current.

### The Marketplace Play (Stage 7)

Once the vertical factory is proven, open it up:

- Law firms publish workflow templates ("Cross-Border M&A Due Diligence" by Baker McKenzie)
- Domain experts publish specialized navigators ("Digital Nomad Visa Comparison")
- Consulting firms publish compliance frameworks ("Global Indirect Tax" by EY)
- YURIS takes 20-30% revenue share per transaction
- Network effects: more templates → more users → more creators → more coverage

---

## Part 5: Architecture

### Four-Layer Stack

```
┌─ APPLICATION LAYER ──────────────────────────────────────────┐
│  Web app, vertical apps, REST/GraphQL API, alerts, widgets   │
├─ INTELLIGENCE LAYER ─────────────────────────────────────────┤
│  RAG engine, comparison engine, translation, change monitor, │
│  risk assessment, workflow engine                            │
├─ DATA LAYER (Hybrid) ───────────────────────────────────────┤
│  PostgreSQL+JSONB (acts) + Neo4j (relationships) + pgvector  │
├─ INGESTION LAYER ───────────────────────────────────────────┤
│  Per-country scrapers → Parser → Normalizer → Deduplicator   │
└──────────────────────────────────────────────────────────────┘
```

### Data Model: Hybrid Document + Graph

**PostgreSQL + JSONB** for legal acts:
- Universal columns: `id`, `jurisdiction_code`, `title`, `enacted_date`, `effective_date`, `status` (active/repealed/amended), `hierarchy_level`, `language`, `full_text`, `source_url`, `ingested_at`, `version`
- JSONB `metadata` column for per-jurisdiction fields (article structure, gazette number, signing authority, etc.)
- JSONB `structure` column for parsed document tree (parts → chapters → sections → articles → paragraphs)
- Immutable versioned records — amendments create new versions, never overwrite

**Neo4j** for relationships:
- `(Act)-[:AMENDS]->(Act)` with effective_date
- `(Act)-[:REPEALS]->(Act)`
- `(Act)-[:REFERENCES]->(Act)`
- `(Act)-[:IMPLEMENTS]->(Directive/Treaty)`
- `(Act)-[:SUPERSEDED_BY]->(Act)`
- `(Act)-[:BELONGS_TO]->(LegalDomain)`
- `(Act)-[:ENACTED_BY]->(Institution)`

**Vector store** (pgvector → dedicated at scale):
- Chunked by article/section
- Embedded in multiple languages
- Metadata filters: jurisdiction, legal domain, date range, hierarchy level

### Ingestion Pipeline

```
SOURCE (gazette, API, PDF)
  ↓
FETCHER (per-source connector)
  ↓ raw HTML/PDF/JSON
PARSER (extract text, structure, metadata)
  ↓ parsed document
NORMALIZER (map to canonical schema)
  ↓ normalized act
DEDUPLICATOR (detect existing / amendment)
  ├── NEW ACT ────► INSERT + embed + add to graph
  └── AMENDMENT ──► NEW VERSION + update graph + trigger alerts
```

Per-source health monitoring: last successful fetch, last new document, error rate, stale-data alerts.

### Critical Design Principles

1. **Immutable versioned records** — amendments create new versions, never overwrite
2. **Citation verification** — every AI claim checked against stored text before serving
3. **Per-source health monitoring** — stale-data detection, error rate tracking
4. **Always show provenance** — every answer traces to exact article in original language
5. **Repealed/superseded acts prominently flagged** — never served as current law

### Tech Stack

| Layer | Technology | Why |
|---|---|---|
| Backend API | Python (FastAPI) | Fast iteration, strong AI/ML ecosystem |
| Database | PostgreSQL + JSONB | Flexible schema, mature, excellent FTS |
| Graph DB | Neo4j | Industry standard for relationship-heavy data |
| Vector Store | pgvector → dedicated at scale | Start simple, migrate when needed |
| LLM | Claude API | Best reasoning for legal analysis, long context |
| Translation | DeepL API + domain glossaries | Highest quality machine translation |
| Search | PostgreSQL FTS + vector similarity | Hybrid keyword + semantic |
| Frontend | Next.js / React | Fast, SEO-friendly |
| Queue/Jobs | Redis + worker framework | Ingestion pipeline, alert processing |
| Monitoring | Prometheus + Grafana | Per-source ingestion health dashboards |

### Project Structure

```
yuris/
├── docker-compose.yml          # PostgreSQL + Neo4j + Redis
├── src/
│   ├── api/                    # FastAPI routes
│   │   ├── search.py
│   │   ├── acts.py
│   │   ├── compare.py
│   │   └── ask.py
│   ├── models/
│   │   ├── act.py              # SQLAlchemy + JSONB
│   │   └── schemas.py          # Pydantic schemas
│   ├── ingestion/
│   │   ├── pipeline.py         # Orchestrator
│   │   ├── fetchers/           # Per-source connectors
│   │   ├── parsers/            # PDF, HTML parsers
│   │   ├── normalizer.py
│   │   └── deduplicator.py
│   ├── graph/
│   │   ├── client.py           # Neo4j connection
│   │   └── queries.py          # Cypher templates
│   ├── intelligence/
│   │   ├── rag.py              # RAG engine
│   │   ├── citations.py        # Citation verification
│   │   ├── compare.py          # Cross-jurisdiction comparison
│   │   └── translate.py        # Translation service
│   ├── monitoring/
│   │   ├── health.py           # Per-source health checks
│   │   └── alerts.py           # Change detection + notifications
│   └── config.py
├── frontend/                   # Next.js
├── tests/
├── migrations/
└── scripts/seed/               # Dev/test data
```

---

## Part 6: Critical Failure Modes

| Failure Mode | Severity | Mitigation |
|---|---|---|
| AI cites repealed/amended act as current | CRITICAL | Graph layer tracks amendment chains; always check act status |
| AI hallucinates nonexistent article | CRITICAL | Citation verification: compare claim against stored text |
| Wrong jurisdiction classification | CRITICAL | Multi-signal classification + human review queue for low confidence |
| Missed amendment (change monitor fails) | CRITICAL | Multiple source monitoring; stale-data alerts |
| Legal term mistranslation | CRITICAL | Domain-specific glossaries; flag terms of art |
| Scraper breaks silently | HIGH | Per-source health checks; stale-data detection |
| Duplicate act ingested | MEDIUM | Dedup by jurisdiction + title + date + content hash |

---

## Part 7: Revenue Model

### By Tier

```
FREE:         Browse acts. Basic search. The SEO hook.
PRO:          AI Q&A, translation, comparison, alerts. Per-seat. ($50-500/mo)
ENTERPRISE:   Workflows, templates, team, API, dashboards. Per-org. ($10K-100K/yr)
VERTICALS:    Per-transaction fees across 13+ verticals.
API:          Usage-based. "Stripe for Law." ($0.01-1/call)
MARKETPLACE:  20-30% revenue share on third-party templates.
```

### By Business Model Stage

```
Stage 1: RESEARCH PLATFORM         Subscriptions          TAM ~$10B
Stage 2: INTELLIGENCE ENGINE       Subscriptions + API     TAM ~$30B
Stage 3: VERTICAL SERVICES         Per-transaction         TAM ~$200B+
Stage 4: LEGAL INFRASTRUCTURE      Platform fees + API     TAM ~$1T
```

---

## Part 8: Moat Deepening Over Time

| Stage | Moat | Why It's Hard to Replicate |
|---|---|---|
| 1 | Data coverage (200+ countries) | Years of scraper/connector development |
| 2 | Legal translation quality | Domain glossaries built iteratively |
| 3 | Citation verification / trust | Verified citation corpus grows over time |
| 4 | Graph relationships | Nobody else has mapped how laws relate globally |
| 5 | Workflow templates | Accumulated legal process knowledge |
| 6 | Customer data + integrations | Switching cost — embedded in operations |
| 7 | Marketplace / network effects | Two-sided platform lock-in |

---

## Part 9: Delight Opportunities (Quick Wins)

1. **"Explain Like I'm Not a Lawyer" toggle** — switch between legal-precise and plain-language
2. **Citation deep-links** — every claim links to exact article, section, paragraph
3. **Jurisdiction quick-cards** — one-page summary of any country's legal system
4. **"What changed this week"** — weekly digest of legal changes
5. **Side-by-side original + translation** — source language and user's language simultaneously
6. **Amendment diff view** — see exactly what changed between versions (git diff for laws)
7. **"Related acts" sidebar** — powered by graph layer

---

## Part 10: What's NOT in Scope (Deferred)

- Case law / judicial decisions (different data model, Phase 2+)
- Legal forms / document generation (different product category)
- Lawyer marketplace / referrals (different business model)
- Offline access / mobile app (web-first)
- Custom jurisdictions / private law libraries (enterprise, post-PMF)
- Predictive analytics ("this law is likely to change based on...")
- Collaborative annotations (law firms annotating for their teams)
- Real-time legislative tracking (bills in progress, not just enacted law)

---

## Part 11: Build Sequence

### Phase 1: Foundation (Month 1-3)
- Data model (PostgreSQL + JSONB + Neo4j)
- Ingestion pipeline for first high-demand jurisdictions
- Basic search (full-text + filters)
- Web app: browse, search, read acts
- Act versioning and amendment chain tracking

### Phase 2: Intelligence (Month 3-6)
- Vector embeddings + semantic search
- RAG-powered Q&A with citation verification
- Translation service with legal glossaries
- Cross-jurisdiction comparison (basic)

### Phase 3: Scale & Monitor (Month 6-9)
- Expand to 100+ jurisdictions
- Change monitoring + alert system
- User accounts, saved searches, subscriptions
- API for programmatic access

### Phase 4: Premium Intelligence (Month 9-12)
- Workflow engine + first templates
- Risk assessment engine
- Weekly legal change digests
- Advanced comparison tools

### Phase 5: Vertical Factory (Month 12-18)
- Immigration vertical (flagship)
- Company formation vertical
- API productization ("Stripe for Law")
- Enterprise dashboard

### Phase 6: Platform & Marketplace (Month 18+)
- Open workflow template marketplace
- Third-party template creation tools
- Revenue share model
- Network effect flywheel
