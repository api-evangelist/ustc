# University of Science and Technology of China

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

The University of Science and Technology of China (USTC, 中国科学技术大学) is a public research university in Hefei, Anhui, founded in 1958 under the Chinese Academy of Sciences, a member of the C9 League and ranked #63 in the QS World University Rankings 2025. USTC publishes no developer portal, no open-data platform and no institutional API program — but it is not the empty profile an earlier pass recorded. Its Network Information Center runs and DOCUMENTS a genuine identity platform: a first-party CAS 3.0 / OAuth 2.0 / OpenID Connect authorization server at id.ustc.edu.cn with an anonymously readable discovery document and JWKS, a developer manual with parameter tables and worked examples at id.ustc.edu.cn/doc/developer/, an enrollment-status query API with a published error table and a public health check, and a self-hosted Shibboleth 5.2.2 identity provider at idp.ustc.edu.cn whose SAML 2.0 metadata is the strongest machine-readable contract in this profile — federating into CARSI, the CAS Science Cloud AAI and eduGAIN. Beyond identity, USTC operates a course catalog with a live JSON API at catalog.ustc.edu.cn (401 to the public, and self-declaring restricted mode), the USTC Open Source Software Mirror on the university's own APNIC allocation, a campus GitLab, a supercomputing centre, and its own DeepSeek-based AI assistant with a published user agreement. Every one of those surfaces is institution-operated; almost every one is gated to campus members, and USTC states plainly that applications outside the ustc.edu.cn domain are not supported. No vendor contract is attributed to USTC in this profile — no Figshare, Pure, Ex Libris, Dataverse or Canvas surface was found under its name.

**Areas:** University · Higher Education · Education · China · C9 League · Chinese Academy of Sciences · Research · Identity Federation · SSO · Course Catalog · Research Computing · Open Source Mirror

## University of Science and Technology of China on APIs.io

Everything profiled for University of Science and Technology of China is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ustc/](https://apis.io/providers/ustc/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [USTC Unified Identity Authentication (id.ustc.edu.cn, formerly Passport SSO)](https://apis.io/apis/ustc/passport/) — USTC's institution-operated authorization server, run by the Network Information Center and the hub every other campus system authenticates against. It…
- [USTC Shibboleth Identity Provider (跨校资源认证中心)](https://apis.io/apis/ustc/idp/) — USTC's self-hosted Shibboleth IdP 5.2.2, publishing a 15KB SAML 2.0 EntityDescriptor for entityID https://idp.ustc.edu.cn/idp/shibboleth with a shibmd:Scope…
- [USTC Course Catalog API (catalog.ustc.edu.cn)](https://apis.io/apis/ustc/catalog/) — The JSON API behind USTC's public course catalog application — semesters, the college tree, program trees, course search, course and lesson detail, exam…
- [USTC Open Source Software Mirror](https://apis.io/apis/ustc/mirrors/) — The USTC Open Source Software Mirror, operated by the campus Linux User Group (LUG @ USTC), is one of the largest open source mirror services among…
- [USTC Campus GitLab](https://apis.io/apis/ustc/gitlab/) — A GitLab instance USTC runs on its own domain at git.ustc.edu.cn, with a second LUG-operated instance at git.lug.ustc.edu.cn. GitLab exposes a…
- [University of Science and Technology of China Health API](https://apis.io/apis/ustc/ustc-health-api/) — Unauthenticated liveness check.
- [University of Science and Technology of China Status API](https://apis.io/apis/ustc/ustc-status-api/) — Enrollment status lookup by person identifier.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [USTC Campus Enrollment Status API schemas](https://apis.io/schemas/ustc/ustc-campus-status-schemas/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ustc Context](https://apis.io/jsonld/ustc/ustc-context/)

#### Examples (2)

Example requests and responses.

- [Ustc Jwks Example](https://apis.io/examples/ustc/ustc-jwks-example/)
- [Ustc Openid Configuration Example](https://apis.io/examples/ustc/ustc-openid-configuration-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ustc Authentication](https://apis.io/security/ustc/ustc-authentication/)
- [Ustc Domain Security](https://apis.io/security/ustc/ustc-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Ustc Scopes](https://apis.io/scopes/ustc/ustc-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ustc Plans Pricing](https://apis.io/plans/ustc/ustc-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ustc Rate Limits](https://apis.io/rate-limits/ustc/ustc-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ustc Finops](https://apis.io/finops/ustc/ustc-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://en.ustc.edu.cn/)
- [Documentation](https://id.ustc.edu.cn/doc/)
- [API reference](https://id.ustc.edu.cn/doc/status-api/)
- [Support](https://ustcnet.ustc.edu.cn/)
- [Blog](https://news.ustc.edu.cn/)
- [GitHub](https://github.com/ustclug)
- [Status](https://mirrors.ustc.edu.cn/status/)

## API Evangelist rating

**Kin Score 27.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 27.0 |
| Contract governance | 3.8 |
| Operational transparency | 23.7 |
| Developer ergonomics | 45.2 |
| Access clarity | 5.3 |

**Agent readiness 21.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
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

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ustc/](https://apis.io/providers/ustc/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Science and Technology of China: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ustc/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
