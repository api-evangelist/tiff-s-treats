# Tiff's Treats

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

Tiff's Treats is an Austin, Texas cookie company founded in 1999 by Tiffany Taylor and Leon Chen,
built around warm, baked-to-order cookies delivered same-day from roughly 90 bakery-storefronts across
the southern and western United States. It sells through an owned delivery fleet, an online ordering
platform at cookiedelivery.com, iOS and Android apps, and a corporate gifting / catering / e-gift-card
business.

## API surface

**None found.** Contract discovery was run against `www.cookiedelivery.com`, `cookiedelivery.com`,
`api.cookiedelivery.com`, `developer.` / `developers.` / `docs.cookiedelivery.com` and every
`/.well-known/` path in the pipeline. The website answers **HTTP 200 with a byte-identical 1457-byte
single-page-app shell for every unmatched path** (verified against a control path), so no `200` from
that host is evidence of a document. `api.cookiedelivery.com` resolves but returns a bare IIS 404 on
every probed path. There is no developer portal, no OpenAPI/GraphQL/AsyncAPI contract, no MCP server,
no A2A agent card, and no first-party SDK in any public package registry.

What the company *does* publish that is machine-readable is a Cloudflare-managed `robots.txt` carrying
**Content-Signal** directives (`search=yes, ai-train=no, use=reference`) and an explicit deny list for
nine AI crawlers including ClaudeBot and GPTBot — captured verbatim in `well-known/`.

- Website: https://www.cookiedelivery.com/
- Secondary-market listing: https://forgeglobal.com/tiff-s-treats_stock/
