# KPMG (kpmg)

KPMG is one of the Big Four professional services organizations, operating through a global network of independent member firms affiliated with KPMG International Limited — a private English company limited by guarantee that itself does not provide services to clients. The network spans more than 276,000 partners and employees across 138 countries and territories. KPMG organizes delivery across six service lines (Audit & Assurance, Tax, Legal, Advisory, ESG, and AI) and serves six industries. AI is a first-class service line built on the **KPMG Trusted AI framework**, anchored at the firm's USD 450 million **KPMG Lakehouse** learning-and-innovation campus in Lake Nona, Orlando. KPMG does not publish a public developer API or corporate developer portal at the network level; the single discoverable KPMG-branded public REST API is **KPMG Origins**, the Australian Integrated Waste Tracking System (IWTS).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kpmg/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=kpmg-api-evangelist&utm_content=repo)

## Tags

Consulting, Audit, Tax, Legal, Professional Services, Big Four, Advisory, AI, Trusted AI, ESG, Sustainability, Risk, Regulation, Cybersecurity, Strategy, Technology, Workforce, Research, Insights, Industry Analysis, Transformation, Pillar Two, Waste Tracking

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

KPMG does not publish a public developer API or corporate developer portal at the network level. There is no enumerable public GitHub organization at `github.com/kpmg`. APIs KPMG builds inside client engagements are client- or partner-branded and live outside the KPMG developer surface.

The one publicly discoverable KPMG-branded REST API is:

| API | Description | Auth | Surface |
|---|---|---|---|
| **KPMG Origins (IWTS)** — Movements | Submit / query waste-movement records for the NSW Integrated Waste Tracking System (and other Australian jurisdictions). | API key (operator-generated) | Swagger UI: production `app.kpmgorigins.com/client-api/swagger/`, sandbox `sandbox.app.kpmgorigins.com/client-api/swagger/` |
| **KPMG Origins (IWTS)** — Registries | Manage Organisations and Locations entities used by the Movements API. | API key (operator-generated) | Swagger UI: production `app.kpmgorigins.com/cr/client-api/swagger/`, sandbox `sandbox.app.kpmgorigins.com/cr/client-api/swagger/` |

## Service Lines

| Service Line | Notes |
|---|---|
| Audit & Assurance | "Objective assurance over data on which investors rely." |
| Tax | Corporate tax, indirect tax, international tax, transfer pricing, tax technology; flagship Fit for Pillar Two series. |
| Legal | Legal advisory and managed legal services across the network. |
| Advisory | Management and technology consulting — risk, regulation, deal advisory, strategy, customer, technology, operations. |
| ESG | Sustainability reporting, climate strategy, regulated sustainability disclosure (anchors the KPMG Origins product). |
| AI | Trusted-AI-anchored service line with five solutions (Jumpstart, Strategy, Trust, Workforce, Technology). |

## Industries Served

| Industry |
|---|
| Consumer, Retail & Leisure |
| Energy, Natural Resources & Chemicals |
| Financial Services |
| Healthcare |
| Government & Public Sector |
| Private Enterprise |

## KPMG Trusted AI Framework

"KPMG Trusted AI is our strategic approach and framework to designing, building, deploying and using AI strategies and solutions in a responsible and ethical manner so we can accelerate value with confidence."

The framework is built on **ten trust pillars**:

| # | Pillar | Description |
|---|---|---|
| 1 | Reliability | Consistent operation at intended precision. |
| 2 | Security | Safeguarding against threats and adverse events. |
| 3 | Safety | Protecting people, businesses, and property from harm. |
| 4 | Privacy | Compliance with data protection regulations. |
| 5 | Sustainability | Energy efficiency and emissions reduction. |
| 6 | Explainability | Clear reasoning for AI conclusions. |
| 7 | Integrity | Data quality and regulatory compliance. |
| 8 | Transparency | Stakeholder disclosure throughout AI lifecycle. |
| 9 | Fairness | Reducing bias against individuals and groups. |
| 10 | Accountability | Human oversight across the lifecycle. |

### KPMG AI Solutions

- **KPMG AI Jumpstart** — packaged starting point for enterprise AI adoption
- **KPMG AI Strategy** — business cases, operating models, roadmaps
- **KPMG AI Trust** — assurance, governance, and risk management for AI in production (operationalizes Trusted AI)
- **KPMG AI Workforce** — workforce augmentation and reskilling
- **KPMG AI Technology** — platform, MLOps, data, and engineering delivery

### Alliances

**Microsoft, Oracle, Salesforce, SAP, ServiceNow, Workday**, with collaboration noted with the **World Economic Forum**.

## KPMG Lakehouse

KPMG's USD 450 million **state-of-the-art learning and innovation center** at **9301 Lake Nona Blvd, Orlando, FL 32827**. Designed as "KPMG on its best day," an innovative campus where professionals "spark curiosity, inspire one another, and explore the future." It is the firm's cultural home and a major hub for training a new generation of professionals to navigate generative AI as a core component of professional service. Used for client innovation sessions across Generative AI, ESG, and Talent and Culture strategy.

## KPMG Insights (Research Surface)

"Fresh insights are essential to strategic thinking and business innovation."

**Topic categories:** AI and Technology, ESG, Operations, Risk and Regulation, Transformation, Value Creation, Workforce, Public Policy & Regulatory Change, Business Transformation, Audit & Assurance, Tax Services, Advisory Services, Sustainability, Technology & Data, Transactions.

**Flagship reports / series observed:**

| Series / Report | Notes |
|---|---|
| KPMG 2026 US Technology Survey Report | Annual US enterprise technology survey. |
| KPMG 2026 M&A Deal Market Study | Annual deal-market study. |
| KPMG Global Third-Party Risk Management Survey | Annual global TPRM survey. |
| Fit for Pillar Two | Multi-part Tax series on OECD Pillar Two implementation. |
| AI Governance Principles for Boards | Board-level AI oversight guidance. |
| Banking transformation: The new agenda | Featured Insights piece on banking transformation. |
| Trust, attitudes and use of artificial intelligence: A global study 2025 | Global AI trust study. |
| Global tech report 2026 | Annual global tech research. |

**Distribution surfaces:** the KPMG Insights site (global + US), the **US Subscription Center** (newsletters including **Opportunity (In)sight** — KPMG US's monthly C-suite newsletter), KPMG Australia's **Business Insights podcast** (Blubrry RSS feed), and per-page RSS feeds across member-firm pages (KPMG does not publish a single consolidated network-wide RSS index; users discover feeds page-by-page via orange RSS icons).

## KPMG Origins (Public API Footnote)

KPMG Origins is "a digital tool that enables waste operators to track and report on hazardous and regulated waste," implementing the NSW Integrated Waste Tracking System (IWTS). It is the single discoverable KPMG-branded public REST API surface. NSW is operational; Queensland and additional Australian jurisdictions are in scope for nationally consistent adoption.

- **Help center:** https://help.kpmgorigins.com/en/
- **Integration guide:** https://help.kpmgorigins.com/en/articles/1850-integrating-with-origins
- **API versioning:** https://help.kpmgorigins.com/en/articles/36081-api-versioning
- **Auth model:** API keys generated by operators in account settings (not OAuth)

## Common Properties

- [Website](https://kpmg.com/)
- [About — KPMG Global Organization](https://kpmg.com/xx/en/about.html)
- [What We Do (Services)](https://kpmg.com/xx/en/what-we-do.html)
- [KPMG Insights (Global)](https://kpmg.com/xx/en/our-insights.html)
- [KPMG Insights and Resources (US)](https://kpmg.com/us/en/insights-and-resources.html)
- [KPMG AI Services](https://kpmg.com/xx/en/what-we-do/services/ai/ai-services.html)
- [KPMG Trusted AI Framework](https://kpmg.com/xx/en/what-we-do/services/ai/trusted-ai-framework.html)
- [KPMG AI Trust (US)](https://kpmg.com/us/en/capabilities-services/ai/trusted-ai.html)
- [KPMG Lakehouse](https://kpmg.com/us/en/capabilities-services/kpmg-innovation-services/lakehouse.html)
- [US Subscription Center](https://kpmg.com/us/en/subscription.html)
- [KPMG Account / Newsletter Registration](https://kpmg.com/xx/en/account/register.html)
- [How to use KPMG RSS feeds](https://kpmg.com/us/en/home/misc/how-to-use-rss-feeds.html)
- [KPMG Careers — All RSS feeds (Talent-Soft)](https://kpmg-career.talent-soft.com/job/all-rss-feeds.aspx)
- [KPMG Australia Business Insights Podcast (Blubrry RSS)](https://feeds.blubrry.com/feeds/kpmg_au_bi.xml)
- [KPMG Origins (product site)](https://kpmgorigins.com/)
- [LinkedIn](https://www.linkedin.com/company/kpmg)
- [X / Twitter](https://x.com/KPMG)
- [YouTube](https://www.youtube.com/user/KPMG)
- [Client Stories](https://kpmg.com/xx/en/client-stories.html)
- [Careers](https://kpmg.com/xx/en/careers.html)

## Generated Artifacts

- [JSON-LD context](json-ld/kpmg-context.jsonld)
- [Vocabulary](vocabulary/kpmg-vocabulary.yml)
- [Plans](plans/kpmg-plans-pricing.yml)
- [Rate limits](rate-limits/kpmg-rate-limits.yml)
- [FinOps](finops/kpmg-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
