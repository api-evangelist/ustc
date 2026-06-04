# University of Science and Technology of China (ustc)

The University of Science and Technology of China (USTC, 中国科学技术大学) is a public research university in Hefei, Anhui, China, founded in 1958 under the Chinese Academy of Sciences and ranked #63 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ustc/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ustc-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, China, Open Source Mirror

## APIs

- **USTC Open Source Software Mirror** — one of the largest university open source mirror services in mainland China (Debian, Ubuntu, Fedora, Arch, CentOS, and more), consumed over standard package-manager protocols. Docs: https://mirrors.ustc.edu.cn/help/ — Status: https://mirrors.ustc.edu.cn/status/
- **USTC Unified Identity Authentication (Passport SSO)** — campus single sign-on at https://passport.ustc.edu.cn/ ; gated to institution members, no public developer documentation.

## Plans, Rate Limits & FinOps

- Plans: [plans/ustc-plans-pricing.yml](plans/ustc-plans-pricing.yml)
- Rate Limits: [rate-limits/ustc-rate-limits.yml](rate-limits/ustc-rate-limits.yml)
- FinOps: [finops/ustc-finops.yml](finops/ustc-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://en.ustc.edu.cn/
- GitHub (LUG @ USTC, community): https://github.com/ustclug
- LinkedIn: https://www.linkedin.com/school/university-of-science-and-technology-of-china/
- Status: https://mirrors.ustc.edu.cn/status/
- Authentication: https://passport.ustc.edu.cn/
- Review: [review.yml](review.yml)

## Notes

- USTC publishes no centralized public developer portal or documented institutional REST API. The mirror service is consumed over package-manager protocols rather than a formal REST API spec.
- No data.* open-data portal, course/SIS API, library (Alma/Primo/IIIF/OAI-PMH), or institutional-repository API was confirmed as openly documented.
- There is no single official USTC GitHub organization; only community and lab orgs exist (e.g., `ustclug`). The LinkedIn page returns 999 to automated probes (bot blocking) but is a valid, live page.
- All URLs were probed live on 2026-06-03; nothing was fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
