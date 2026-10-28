# Amazon Data Lifecycle Manager

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

Amazon Data Lifecycle Manager provides an automated way to manage the lifecycle of your AWS resources. Using lifecycle policies, you can automate the creation, retention, and deletion of Amazon EBS snapshots and EBS-backed AMIs, reducing storage costs and simplifying backup management. Policies target EBS volumes and EC2 instances using tags, execute on configurable schedules, and apply flexible retention rules based on count or age.

**Areas:** AWS · Backup · EBS Snapshots · Lifecycle Management · Storage · Automation · Compliance

## Amazon Data Lifecycle Manager on APIs.io

Everything profiled for Amazon Data Lifecycle Manager is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/amazon-data-lifecycle-manager/](https://apis.io/providers/amazon-data-lifecycle-manager/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Amazon Data Lifecycle Manager Lifecycle Policies API](https://apis.io/apis/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-lifecycle-policies-api/) — Operations for managing EBS snapshot and AMI lifecycle policies
- [Amazon Data Lifecycle Manager Tags API](https://apis.io/apis/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-tags-api/) — Operations for managing resource tags

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (6)

Multi-step workflows that chain operations into a business task.

- [Amazon Data Lifecycle Manager Decommission Policy](https://apis.io/arazzos/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-decommission-policy-workflow/)
- [Amazon Data Lifecycle Manager Disable Policy](https://apis.io/arazzos/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-disable-policy-workflow/)
- [Amazon Data Lifecycle Manager Provision Policy](https://apis.io/arazzos/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-provision-policy-workflow/)
- [Amazon Data Lifecycle Manager Reconfigure Schedule](https://apis.io/arazzos/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-reconfigure-schedule-workflow/)
- [Amazon Data Lifecycle Manager Tag Policy Resource](https://apis.io/arazzos/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-tag-policy-resource-workflow/)
- [Amazon Data Lifecycle Manager Untag Policy Resource](https://apis.io/arazzos/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-untag-policy-resource-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Amazon Data Lifecycle Manager Agentic Access](https://apis.io/agentic-access/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-agentic-access/)

#### JSON Schema (15)

The data models the API reads and writes.

- [Create Lifecycle Policy Request](https://apis.io/schemas/amazon-data-lifecycle-manager/create-lifecycle-policy-request/)
- [Create Lifecycle Policy Response](https://apis.io/schemas/amazon-data-lifecycle-manager/create-lifecycle-policy-response/)
- [Create Rule](https://apis.io/schemas/amazon-data-lifecycle-manager/create-rule/)
- [Error](https://apis.io/schemas/amazon-data-lifecycle-manager/error/)
- [Get Lifecycle Policies Response](https://apis.io/schemas/amazon-data-lifecycle-manager/get-lifecycle-policies-response/)
- [Get Lifecycle Policy Response](https://apis.io/schemas/amazon-data-lifecycle-manager/get-lifecycle-policy-response/)
- [Lifecycle Policy](https://apis.io/schemas/amazon-data-lifecycle-manager/lifecycle-policy/)
- [Lifecycle Policy Summary](https://apis.io/schemas/amazon-data-lifecycle-manager/lifecycle-policy-summary/)
- [List Tags for Resource Response](https://apis.io/schemas/amazon-data-lifecycle-manager/list-tags-for-resource-response/)
- [Policy Details](https://apis.io/schemas/amazon-data-lifecycle-manager/policy-details/)
- [Retain Rule](https://apis.io/schemas/amazon-data-lifecycle-manager/retain-rule/)
- [Schedule](https://apis.io/schemas/amazon-data-lifecycle-manager/schedule/)
- [Tag](https://apis.io/schemas/amazon-data-lifecycle-manager/tag/)
- [Tag Resource Request](https://apis.io/schemas/amazon-data-lifecycle-manager/tag-resource-request/)
- [Update Lifecycle Policy Request](https://apis.io/schemas/amazon-data-lifecycle-manager/update-lifecycle-policy-request/)

#### JSON Structure (15)

Data models expressed in JSON Structure.

- [Create Lifecycle Policy Request Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/create-lifecycle-policy-request-structure/)
- [Create Lifecycle Policy Response Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/create-lifecycle-policy-response-structure/)
- [Create Rule Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/create-rule-structure/)
- [Error Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/error-structure/)
- [Get Lifecycle Policies Response Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/get-lifecycle-policies-response-structure/)
- [Get Lifecycle Policy Response Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/get-lifecycle-policy-response-structure/)
- [Lifecycle Policy Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/lifecycle-policy-structure/)
- [Lifecycle Policy Summary Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/lifecycle-policy-summary-structure/)
- [List Tags For Resource Response Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/list-tags-for-resource-response-structure/)
- [Policy Details Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/policy-details-structure/)
- [Retain Rule Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/retain-rule-structure/)
- [Schedule Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/schedule-structure/)
- [Tag Resource Request Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/tag-resource-request-structure/)
- [Tag Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/tag-structure/)
- [Update Lifecycle Policy Request Structure](https://apis.io/json-structure/amazon-data-lifecycle-manager/update-lifecycle-policy-request-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Amazon Data Lifecycle Manager Context](https://apis.io/jsonld/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Amazon Data Lifecycle Manager Vocabulary](https://apis.io/vocabularies/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-vocabulary/)

#### Examples (15)

Example requests and responses.

- [Create Lifecycle Policy Request Example](https://apis.io/examples/amazon-data-lifecycle-manager/create-lifecycle-policy-request-example/)
- [Create Lifecycle Policy Response Example](https://apis.io/examples/amazon-data-lifecycle-manager/create-lifecycle-policy-response-example/)
- [Create Rule Example](https://apis.io/examples/amazon-data-lifecycle-manager/create-rule-example/)
- [Error Example](https://apis.io/examples/amazon-data-lifecycle-manager/error-example/)
- [Get Lifecycle Policies Response Example](https://apis.io/examples/amazon-data-lifecycle-manager/get-lifecycle-policies-response-example/)
- [Get Lifecycle Policy Response Example](https://apis.io/examples/amazon-data-lifecycle-manager/get-lifecycle-policy-response-example/)
- [Lifecycle Policy Example](https://apis.io/examples/amazon-data-lifecycle-manager/lifecycle-policy-example/)
- [Lifecycle Policy Summary Example](https://apis.io/examples/amazon-data-lifecycle-manager/lifecycle-policy-summary-example/)
- [List Tags For Resource Response Example](https://apis.io/examples/amazon-data-lifecycle-manager/list-tags-for-resource-response-example/)
- [Policy Details Example](https://apis.io/examples/amazon-data-lifecycle-manager/policy-details-example/)
- [Retain Rule Example](https://apis.io/examples/amazon-data-lifecycle-manager/retain-rule-example/)
- [Schedule Example](https://apis.io/examples/amazon-data-lifecycle-manager/schedule-example/)
- [Tag Example](https://apis.io/examples/amazon-data-lifecycle-manager/tag-example/)
- [Tag Resource Request Example](https://apis.io/examples/amazon-data-lifecycle-manager/tag-resource-request-example/)
- [Update Lifecycle Policy Request Example](https://apis.io/examples/amazon-data-lifecycle-manager/update-lifecycle-policy-request-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [Amazon Data Lifecycle Manager API](https://apis.io/collections/amazon-data-lifecycle-manager/open-amazon-data-lifecycle-manager/)
- [Amazon Data Lifecycle Manager Lifecycle Policies API](https://apis.io/collections/amazon-data-lifecycle-manager/open-amazon-data-lifecycle-manager-lifecycle-policies-api/)
- [Amazon Data Lifecycle Manager Lifecycle Policies Tags API](https://apis.io/collections/amazon-data-lifecycle-manager/open-amazon-data-lifecycle-manager-tags-api/)
- [Amazon Data Lifecycle Manager API](https://apis.io/collections/amazon-data-lifecycle-manager/postman-amazon-data-lifecycle-manager/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Amazon Data Lifecycle Manager — jsonschema rules](https://apis.io/rules/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-jsonschema-spectral-rules/)
- [Amazon Data Lifecycle Manager API Rules](https://apis.io/rules/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Amazon Data Lifecycle Manager Authentication](https://apis.io/security/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-authentication/)
- [Amazon Data Lifecycle Manager Domain Security](https://apis.io/security/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-domain-security/)
- [Amazon Data Lifecycle Manager Trust Center](https://apis.io/security/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-trust-center/)
- [Amazon Data Lifecycle Manager Vulnerability Disclosure](https://apis.io/security/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Amazon Data Lifecycle Manager Plans Pricing](https://apis.io/plans/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Amazon Data Lifecycle Manager Rate Limits](https://apis.io/rate-limits/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Amazon Data Lifecycle Manager Finops](https://apis.io/finops/amazon-data-lifecycle-manager/amazon-data-lifecycle-manager-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://aws.amazon.com/ebs/data-lifecycle-manager/)
- [Documentation](https://docs.aws.amazon.com/dlm/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Terms of service](https://aws.amazon.com/service-terms/)
- [Privacy policy](https://aws.amazon.com/privacy/)
- [GitHub](https://github.com/aws)
- [Status](https://health.aws.amazon.com/health/status)

## API Evangelist rating

**Kin Score 54.7** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 65.5 |
| Contract governance | 27.3 |
| Operational transparency | 36.8 |
| Developer ergonomics | 63.1 |
| Access clarity | 43.4 |

**Agent readiness 30.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/amazon-data-lifecycle-manager/](https://apis.io/providers/amazon-data-lifecycle-manager/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Amazon Data Lifecycle Manager: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/amazon-data-lifecycle-manager/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
