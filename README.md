# KPMG (kpmg)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

KPMG is one of the Big Four professional services organizations, operating through a global network of independent member firms affiliated with KPMG International Limited, a private English company limited by guarantee that itself does not provide services to clients. The network spans more than 276,000 partners and employees across 138 countries and territories. KPMG organizes delivery across six service lines — Audit & Assurance, Tax, Legal, Advisory, ESG, and AI — and serves six industries: Consumer / Retail / Leisure; Energy, Natural Resources & Chemicals; Financial Services; Healthcare; Government & Public Sector; and Private Enterprise. AI is a first-class service line built on the KPMG Trusted AI framework — a ten-pillar approach covering Reliability, Security, Safety, Privacy, Sustainability, Explainability, Integrity, Transparency, Fairness, and Accountability — and packaged through five AI solutions: KPMG AI Jumpstart, AI Strategy, AI Trust, AI Workforce, and AI Technology. Alliances anchoring the AI delivery surface include Microsoft, Oracle, Salesforce, SAP, ServiceNow, and Workday, with collaboration noted with the World Economic Forum. KPMG Lakehouse, the firm's USD 450 million learning-and-innovation campus in Lake Nona, Orlando, is the cultural and AI-upskilling hub for the US firm and a venue for client innovation sessions in generative AI, ESG, and talent strategy. Insights is KPMG's research-publishing surface, organized across topic categories including AI and Technology, ESG, Operations, Risk and Regulation, Transformation, Value Creation, Workforce, Public Policy & Regulatory Change, Business Transformation, Audit & Assurance, Tax, Advisory, Sustainability, and Transactions, with flagship series such as the KPMG US Technology Survey Report, the KPMG Global Third-Party Risk Management Survey, the KPMG M&A Deal Market Study, Fit for Pillar Two, and AI Governance Principles for Boards. KPMG does not publish a public developer API or corporate developer portal at the network level; the firm has no enumerable public GitHub organization at `github.com/kpmg`. The one meaningful public API surface inside the KPMG brand is KPMG Origins (`kpmgorigins.com`) — an Australian regulated-waste tracking platform (initially the NSW Integrated Waste Tracking System / IWTS, with Queensland and other jurisdictions in scope) that exposes two REST APIs (Movements + Registries) over Swagger with API-key authentication, intended for integration with waste-operator software rather than as a general-purpose KPMG developer surface. Distribution to readers and client stakeholders flows through the Insights site, the US Subscription Center (Opportunity (In)sight monthly newsletter), KPMG Australia's Business Insights podcast, and per-page RSS feeds offered on individual KPMG member-firm pages.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kpmg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kpmg/refs/heads/main/apis.yml)

## Tags

- Consulting
- Audit
- Tax
- Legal
- Professional Services
- Big Four
- Advisory
- AI
- Trusted AI
- ESG
- Sustainability
- Risk
- Regulation
- Cybersecurity
- Strategy
- Technology
- Workforce
- Research
- Insights
- Industry Analysis
- Transformation
- Pillar Two
- Waste Tracking

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### KPMG Origins (IWTS)

KPMG Origins is the public-facing platform implementing the NSW Integrated Waste Tracking System (IWTS) and is the single discoverable public REST API surface inside the KPMG brand. It exposes two APIs — Movements (waste-movement reporting) and Registries (organisations and locations) — over Swagger, with API-key authentication generated by operators in their account settings. The system supports waste reporting automation and regulatory reporting for industry participants and software providers integrating waste data from their existing tooling, with the explicit goal of eliminating double-entry of regulatory data. NSW is currently operational with Queensland and additional Australian jurisdictions in scope.

- **Human URL:** [https://help.kpmgorigins.com/en/articles/1850-integrating-with-origins](https://help.kpmgorigins.com/en/articles/1850-integrating-with-origins)
- **Base URL:** `https://app.kpmgorigins.com/client-api/`

#### Tags

- Waste Tracking
- Sustainability
- ESG
- Regulatory Reporting
- Australia

#### Properties

- [Documentation](https://help.kpmgorigins.com/en/articles/1850-integrating-with-origins)
- [Swagger U I](https://app.kpmgorigins.com/client-api/swagger/)
- [Swagger U I](https://sandbox.app.kpmgorigins.com/client-api/swagger/)
- [Swagger U I](https://app.kpmgorigins.com/cr/client-api/swagger/)
- [Swagger U I](https://sandbox.app.kpmgorigins.com/cr/client-api/swagger/)
- [Authentication](https://help.kpmgorigins.com/en/articles/1850-integrating-with-origins)
- [Help Center](https://help.kpmgorigins.com/en/)
- [Versioning](https://help.kpmgorigins.com/en/articles/36081-api-versioning)
- [Postman Collection](collections/kpmg.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kpmg.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://kpmg.com/)
- [About](https://kpmg.com/xx/en/about.html)
- [Services](https://kpmg.com/xx/en/what-we-do.html)
- [Knowledge Center](https://kpmg.com/xx/en/our-insights.html)
- [Knowledge Center](https://kpmg.com/us/en/insights-and-resources.html)
- [Hub](https://kpmg.com/xx/en/what-we-do/services/ai/ai-services.html)
- [Framework](https://kpmg.com/xx/en/what-we-do/services/ai/trusted-ai-framework.html)
- [Service](https://kpmg.com/us/en/capabilities-services/ai/trusted-ai.html)
- [Facility](https://kpmg.com/us/en/capabilities-services/kpmg-innovation-services/lakehouse.html)
- [Newsletter](https://kpmg.com/us/en/subscription.html)
- [Registration](https://kpmg.com/xx/en/account/register.html)
- [Help](https://kpmg.com/us/en/home/misc/how-to-use-rss-feeds.html)
- [R S S](https://kpmg-career.talent-soft.com/job/all-rss-feeds.aspx)
- [Podcast](https://feeds.blubrry.com/feeds/kpmg_au_bi.xml)
- [Product](https://kpmgorigins.com/)
- [LinkedIn](https://www.linkedin.com/company/kpmg)
- [X (Twitter)](https://x.com/KPMG)
- [YouTube](https://www.youtube.com/user/KPMG)
- [Client Stories](https://kpmg.com/xx/en/client-stories.html)
- [Careers](https://kpmg.com/xx/en/careers.html)
- [Press Room](https://kpmg.com/xx/en/about/press-releases.html)
- [L L Ms Txt](https://kpmg.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
