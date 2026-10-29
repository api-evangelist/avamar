# Avamar

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

> **Acquired or rebranded.** This company was acquired, merged or renamed. Its API, if it still exists, is offered under another name. This profile is kept as a historical record and is not maintained or rated.

Avamar is enterprise backup and recovery software built on client-side global data deduplication, founded in Irvine, California and backed by Lightspeed Venture Partners before EMC acquired the company in November 2006 for approximately $165 million. Avamar now ships as Dell Avamar, part of the Dell Technologies data protection portfolio, and is deployed as a customer-hosted appliance or virtual edition rather than as a public SaaS. It exposes a REST API on the Avamar server for programmatic backup, restore, client, domain, dataset, policy and activity management, secured with OAuth 2.0 access tokens and optional OIDC single sign-on, and documented through a Swagger UI served from the appliance itself. A first-party Management Console Command Line Interface (mccli) and the avtar/avmaint command set provide the scripted administrative surface alongside the API.

**Areas:** Company · Backup · Data Protection · Deduplication · Disaster Recovery · Storage · Enterprise Software · Infrastructure · Dell Technologies · On-Premises

## Avamar on APIs.io (historical record)

Everything profiled for Avamar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/avamar/](https://apis.io/providers/avamar/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Avamar REST API](https://apis.io/apis/avamar/avamar-rest-api/) — The Avamar REST API provides a framework to develop applications and tools that interact with a stand-alone Avamar server. It exposes backup, restore,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Avamar Authentication](https://apis.io/security/avamar/avamar-authentication/)
- [Avamar Domain Security](https://apis.io/security/avamar/avamar-domain-security/)
- [Avamar Trust Center](https://apis.io/security/avamar/avamar-trust-center/)
- [Avamar Vulnerability Disclosure](https://apis.io/security/avamar/avamar-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Avamar Scopes](https://apis.io/scopes/avamar/avamar-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.dell.com/)
- [Documentation](https://www.dell.com/support/home/en-us/product-support/product/avamar-rest-api/docs)
- [Getting started](https://www.delltechnologies.com/asset/en-us/products/data-protection/technical-support/docu89854.pdf)
- [API reference](https://www.dell.com/support/product-details/en-us/product/avamar-rest-api/resources/manuals)
- [Support](https://www.dell.com/support/home/en-us/product-support/product/avamar-server/overview)
- [Security](https://www.dell.com/support/contents/en-us/article/product-support/self-support-knowledgebase/security-antivirus/alerts-vulnerabilities/dell-vulnerability-response-policy)
- [Compliance](https://www.dell.com/en-us/dt/about-us/security-and-trust-center/compliance-service-organization-control-overlay.htm)
- [GitHub](https://github.com/dell)

## API Evangelist rating

**Not rated** — this company is recorded as acquired or rebranded, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Avamar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/avamar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
