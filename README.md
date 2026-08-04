# Finlight

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Finlight is a real-time financial news API that aggregates market-moving news,
earnings reports, analyst upgrades, and corporate announcements for equities,
currencies, and commodities. The platform delivers AI-driven sentiment analysis,
entity extraction, and sub-second latency streaming for developers and enterprises
building financial applications.

The API supports REST, WebSocket, and webhook delivery modes, with official SDKs
for TypeScript/JavaScript and Python. Finlight is trusted by 100+ companies and
maintains 99.9% uptime with bank-grade security compliance.

**API Documentation:** https://docs.finlight.me/v2/
**Website:** https://finlight.me
**Pricing:** https://finlight.me/pricing
**Sign Up:** https://app.finlight.me
**Contact:** info@finlight.me

## APIs

- [Finlight Financial News API](https://docs.finlight.me/v2/)

## Plans

See [plans/plans.yml](plans/plans.yml) for full plan details.

| Plan | Price | Requests/Month |
|---|---|---|
| Launchpad | Free | 5,000 |
| Pro Light | $29/month | 10,000 |
| Pro Standard | $99/month | 50,000 |
| Pro Scale | $249/month | 150,000 |
| Enterprise | Custom | Unlimited |

## Rate Limits

See [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml) for full details.

- 100 requests per minute per API key (all plans)
- Monthly request quotas vary by plan
- 429 Too Many Requests returned when limits are exceeded

## FinOps

See [finops/finops.yml](finops/finops.yml) for cost optimization guidance.

## Maintainers

- [API Evangelist](https://apievangelist.com)
