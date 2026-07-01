# G-Cloud Opportunity Briefing — CrozierScott

Prepared for the team, July 2026. Companion to the slide deck `g-cloud-briefing.pptx`.

This brief covers what G-Cloud is, where CrozierScott's current offering fits (strengths and gaps), what evidence and documents we'd need, and a checklist to turn into Jira epics/tasks once agreed.

---

## 1. What is G-Cloud?

G-Cloud is a UK government procurement framework — think of it as a pre-vetted supplier catalogue ("app store") that public sector buyers (central government, councils, NHS, police, etc.) can purchase from directly, without running a full tender for every purchase. It's run by the Crown Commercial Service (CCS) via the [Digital Marketplace](https://www.applytosupply.digitalmarketplace.service.gov.uk/).

Suppliers apply once, during a fixed application window, to get listed. Once listed, any eligible public sector buyer can buy your services directly off the catalogue for the life of the framework.

G-Cloud is organised into five "Lots" (service categories):

| Lot | Covers |
|---|---|
| 1a | Cloud Hosting (IaaS/PaaS) |
| 1b | Cloud Hosting (Above Official — higher security classifications) |
| 2a | Infrastructure Software as a Service (iSaaS) |
| 2b | Software as a Service (SaaS) |
| 3 | **Cloud Support** — consultancy, implementation, migration, integration and ongoing support services |

**CrozierScott's services would sit in Lot 3 (Cloud Support)**, not Lots 1/2 — we're not selling hosting or a software product, we're selling cloud architecture, DevOps, data and AI implementation expertise.

## 2. Important — current timing (verified against gov.uk / Digital Marketplace, July 2026)

This is the most important correction to the ChatGPT research: **the application window for the current framework is already closed.**

- The current framework, **G-Cloud 15**, ran its application window from 23 October 2025 to 30 January 2026. The Digital Marketplace site confirms today: *"G-Cloud 15 is closed for applications. Applications are being reviewed."*
- G-Cloud 15 is expected to go live around September 2026 — but only for suppliers who applied in that window.
- G-Cloud 15 is being run as an **Open Framework** under the new Procurement Act 2023, structured as three terms (18 months + 18 months + 12 months) over its 4-year life. New suppliers get a fresh chance to apply at the start of each new term — so the **next opportunity for a new supplier like us is expected around 18 months after go-live, i.e. roughly early-to-mid 2028** (exact date to be confirmed nearer the time).
- The outgoing framework, G-Cloud 14, has been extended to October 2026 as a bridge, but it is **not open to new suppliers** — it only allows existing G-Cloud 14 suppliers to keep trading.

**What this means for us:** we're not racing to submit something in the next few weeks. We have real runway (~18 months+) to prepare a genuinely strong application — case studies, policies, certifications, service descriptions — rather than rushing. This should be treated as a 2026–2027 preparation project aimed at being ready the moment the window reopens, not a July 2026 deadline.

**A nearer-term alternative — DOS:** Digital Outcomes and Specialists (DOS) is a separate, related framework for bespoke digital outcomes and specialist teams (see section 3). Its latest version, **DOS7, went live 1 April 2026 and reopens every 18 months** for new suppliers. If some of our work (e.g. building a bespoke AI application from scratch, as opposed to configuring an established approach) fits DOS better than G-Cloud, this is a nearer-term route worth scoping in parallel.

*Sources: [Digital Marketplace](https://www.applytosupply.digitalmarketplace.service.gov.uk/), [Computer Weekly — G-Cloud 15](https://www.computerweekly.com/feature/UK-governments-G-Cloud-15-framework-Everything-you-need-to-know), [PublicTechnology — G-Cloud 14 extension](https://www.publictechnology.net/2025/07/29/business-and-industry/g-cloud-14-extended-to-october-2026-to-give-time-to-prep-replacement/), [Burges Salmon — G-Cloud 15 changes](https://www.burges-salmon.com/articles/102lzf5/g-cloud-15-g15-framework-key-changes-for-uk-public-sector-cloud-suppliers/).*

## 3. G-Cloud vs DOS — which of our work fits where

A common misconception (repeated in a webinar Eddie attended) is "G-Cloud is only for off-the-shelf products, use DOS for anything bespoke." The reality is more nuanced:

- **G-Cloud (Lot 3) sells a repeatable *service*** — e.g. "AI Analytics Pipeline Implementation using Amazon Bedrock / Azure OpenAI." Every client's data, prompts and outputs differ, but the service itself (the approach, the technology stack, the methodology) is repeatable. This is what most of CrozierScott's cloud/data/AI implementation work looks like.
- **DOS sells a bespoke outcome** — e.g. "build us a new AI-powered planning application case management system from scratch." This is a unique digital product, delivered by a team, not a catalogue service.

Working example from our own history: if a client asked us to build a brand-new bespoke audit platform from the ground up, that's a DOS-shaped engagement. Once that platform exists and we're repeating a similar implementation approach for other clients (e.g. "AI Document Assessment Platform Implementation"), that becomes a legitimate G-Cloud catalogue service.

**Recommendation:** treat this as complementary, not either/or — G-Cloud for our repeatable cloud/data/AI implementation services, DOS as the route for genuinely bespoke build projects. Longer term it's worth being on both.

## 4. Where CrozierScott fits — capability review

*Note: the strengths/case-study material below reflects the team's own account of past delivery work (from internal discussion), not independently verified by Claude. Before publishing anything externally, these should be validated, quantified and signed off by whoever delivered the work.*

Based on the internal review, CrozierScott's delivery work over the past year clusters into eight capability areas:

| Capability | Typical technologies | Maps to G-Cloud service |
|---|---|---|
| Cloud Data Platforms | AWS, Snowflake, dbt, S3 | Data Platform Engineering |
| AI & LLM Integration | Bedrock, Claude, ChatGPT, Azure OpenAI | AI Platform Implementation |
| Data Engineering | ELT/ETL, APIs, automation | Data Pipeline Engineering |
| Cloud Architecture | AWS, Azure, networking, IAM | Cloud Architecture & Landing Zones |
| DevOps & Automation | GitHub, Jenkins, CI/CD | DevOps & CI/CD |
| Infrastructure as Code | Terraform, Bicep, CloudFormation | Infrastructure as Code |
| Data Governance | OpenMetadata, lineage, glossaries | Data Governance Services |
| Analytics Platforms | Power BI, semantic models | Analytics Platform Implementation |

### Proposed initial G-Cloud service catalogue (6, not 20)

Buyers respond better to a small, focused, easy-to-evidence catalogue than a long generic one. Proposed starting list:

1. Cloud Architecture & Platform Design (landing zones, governance, networking, identity)
2. DevOps & CI/CD Pipeline Engineering
3. Infrastructure as Code Implementation (Terraform, Bicep, CloudFormation)
4. Data Engineering Pipeline Development (ETL/ELT, integration, analytics pipelines)
5. AI Platform Implementation (Bedrock, Azure OpenAI, model integration/orchestration)
6. Generative AI Integration Services (enterprise AI workflows)

### Strengths

- Genuine, varied delivery history across cloud architecture, DevOps, data engineering, governance and AI integration — not just one narrow skill.
- The work is naturally "repeatable service, bespoke delivery" — exactly the model G-Cloud buyers expect from consultancies.
- Existing project examples (as described internally) that could become case studies: a data platform build, an index/analytics platform, an AI-powered document assessment build, and a metadata/governance implementation.
- Bespoke pricing model (day rates) is entirely normal for this type of supplier — not a weakness.

### Gaps to close before applying

- **No published rate card yet** — day rates exist informally but aren't structured into a SFIA-style hierarchy (see section 5).
- **No formal case studies written up** — the underlying project experience exists, but nothing is packaged into the 1–2 page "problem → approach → outcome → benefit" format buyers expect.
- **Certification status needs confirming** — do we currently hold Cyber Essentials, ISO 27001, or cyber/data-protection equivalents? (Cyber Essentials is now mandatory for G-Cloud — see section 6.)
- **No consolidated policy set** — information security, data protection/GDPR, incident response, business continuity, etc. (list in section 6).
- **Service descriptions don't exist yet** in G-Cloud's expected style (plain, compliance-focused, buyer-outcome language — not marketing copy).
- **No reusable bid library** (standard answers on security, accessibility, onboarding/offboarding, support model, business continuity, disaster recovery) — worth building once, reusable across G-Cloud, DOS and direct bids.

## 5. Pricing approach — SFIA day rates

G-Cloud requires transparent, published pricing that can't be increased for the life of the framework (though it can be discounted). For a bespoke consultancy like us, the standard model is a small SFIA-aligned rate card rather than fixed-price products.

Recommended: 4–6 roles, not the 10–15 many suppliers copy from templates (harder to evidence, invites awkward questions).

| SFIA level | Suggested role title | Typical market day rate (indicative only) |
|---|---|---|
| Level 3 – Apply | Cloud Platform Engineer | £500–£700 |
| Level 4 – Enable | Senior Platform Engineer / DevOps Engineer | £700–£950 |
| Level 5 – Ensure & Advise | Cloud Architect / AI Platform Consultant | £900–£1,250 |
| Level 6 – Initiate & Influence | Principal Cloud Architect | £1,200–£1,600+ |

These figures are illustrative market ranges, not official CCS rates (there is no fixed price list) — our actual rates need to be set deliberately, since they're locked for the framework term once published.

Also needed alongside the rate card: expenses policy, definition of a "working day," minimum engagement terms, VAT statement.

## 6. Evidence, documents & prerequisites checklist

### Mandatory application documents (per CCS/Digital Marketplace guidance)
- [ ] Pricing document (day rates, unit prices, any volume discounts)
- [ ] Service definition document per service (what it covers, onboarding/offboarding, service constraints, support model, security approach, exit/data access)
- [ ] Terms and conditions (one set, can't be modified while the framework is live)
- [ ] Company registration / Digital Marketplace supplier account set up

### Certifications
- [ ] **Cyber Essentials — now mandatory for G-Cloud 15.** For Lot 3 (our lot), suppliers without it get a 12-month grace period from contract award before suspension risk — but we should confirm our current status now, since it takes time to certify properly. *(Confirmed via CCS announcement, 5 Dec 2025.)*
- [ ] ISO 27001 (not mandatory, but strengthens the bid if held)
- [ ] Confirm Professional Indemnity / Public Liability insurance is current

### Minimum policy set to have ready
- [ ] Information Security Policy
- [ ] Data Protection / GDPR Policy
- [ ] Incident Response Procedure
- [ ] Backup & Recovery Policy
- [ ] Business Continuity Plan
- [ ] Equality & Diversity Policy
- [ ] Environmental / Sustainability Policy
- [ ] Modern Slavery Statement

### Case studies (priority 1 — biggest differentiator for a small consultancy)
Aim for quality over quantity — 4–5 excellent examples beats 15 thin ones. Each should cover: client challenge, our approach, technologies used, outcomes delivered, business benefits, and which service(s) it evidences. Candidate projects to write up (pending internal validation):
- [ ] Data platform build (AWS/Snowflake/dbt) — 1–2 pages
- [ ] AI-powered document assessment / audit platform — 1–2 pages
- [ ] Analytics/index platform (ingest → transform → model → publish) — 1–2 pages
- [ ] Data governance / metadata implementation (OpenMetadata) — 1–2 pages

### Technical artefacts (priority 2)
- [ ] Reference architecture diagrams
- [ ] Example Terraform module structure
- [ ] Pipeline workflow diagrams
- [ ] Security & governance approach document
- [ ] Handover / documentation templates

### Reusable bid library (worth building once, reused everywhere)
- [ ] Security approach
- [ ] Accessibility approach
- [ ] Service management approach
- [ ] Onboarding / offboarding process
- [ ] Knowledge transfer approach
- [ ] Business continuity / disaster recovery
- [ ] Support model

## 7. Recommended strategy

**Dual-track, not sequential:**

1. **Track A — G-Cloud 15 readiness (target: ready well before the ~2028 reopening).** Build the service catalogue, rate card, policies, certifications and case studies at a sensible pace over the next 12–18 months, so we're first in line the moment applications reopen. No need to rush.
2. **Track B — DOS7 scoping (nearer-term, live now, reopens every 18 months).** Assess whether any of our more bespoke build-from-scratch work (e.g. a brand-new AI application for a specific client) would be better suited to a DOS submission sooner, since DOS7 is open now.

## 8. Checklist for Jira epics/tasks

Suggested epic breakdown — for Eddie/Scott to review and adjust before creating in Jira:

- [ ] **Epic: Service catalogue & definitions** — draft the 6 service descriptions in buyer-outcome language
- [ ] **Epic: Pricing & rate card** — agree SFIA levels, set day rates, write pricing document, expenses/working-day/minimum-engagement terms
- [ ] **Epic: Certifications** — confirm Cyber Essentials status and start/renew certification; confirm insurance currency
- [ ] **Epic: Policy set** — draft or update the 8 minimum policies listed in section 6
- [ ] **Epic: Case studies** — validate project details internally, write up 4–5 case studies to template
- [ ] **Epic: Technical artefacts** — produce reference architecture diagrams, Terraform structure examples, security/governance write-up
- [ ] **Epic: Reusable bid library** — draft standard answers for security, accessibility, service management, onboarding/offboarding, BCP/DR, support model
- [ ] **Epic: DOS7 scoping** — assess candidate bespoke projects against DOS suitability, decide go/no-go on a nearer-term DOS submission
- [ ] **Epic: G-Cloud 15 application** — assemble and submit once the next application window opens (~2028, to be confirmed)

## Sources

- [Digital Marketplace](https://www.applytosupply.digitalmarketplace.service.gov.uk/) — confirms G-Cloud 15 closed for applications; DOS7 live
- [GOV.UK — G-Cloud buyers' guide](https://www.gov.uk/guidance/g-cloud-buyers-guide)
- [Computer Weekly — G-Cloud 15 framework guide](https://www.computerweekly.com/feature/UK-governments-G-Cloud-15-framework-Everything-you-need-to-know)
- [PublicTechnology — G-Cloud 14 extended to October 2026](https://www.publictechnology.net/2025/07/29/business-and-industry/g-cloud-14-extended-to-october-2026-to-give-time-to-prep-replacement/)
- [Burges Salmon — G-Cloud 15 key changes](https://www.burges-salmon.com/articles/102lzf5/g-cloud-15-g15-framework-key-changes-for-uk-public-sector-cloud-suppliers/)
- [Net Sec Group — Cyber Essentials mandatory for G-Cloud 15](https://netsecgroup.io/guides/g-cloud-15-cyber-essentials-required)
- [PublicTechnology — DOS7 preview](https://www.publictechnology.net/2025/04/07/business-and-industry/ccs-previews-digital-and-outcomes-specialists-7-framework-with-six-year-term-and-14-4bn-value/)
- Internal source material: two ChatGPT conversations provided by Eddie (July 2026), used for CrozierScott capability/strengths context — treated as unverified internal input, not an external source
