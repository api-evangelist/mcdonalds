# McDonald's (mcdonalds)

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

McDonald's is the world's leading global foodservice retailer, operating and franchising fast food restaurants serving hamburgers, chicken, breakfast items, soft drinks, milkshakes, and desserts in countries around the world. McDonald's does not operate a public developer program or publish open API documentation. Its digital surface — the Global Mobile App, MyMcDonald's Rewards loyalty, mobile order & pay, kiosks, and drive-thru personalization — runs on internal platforms, and integrations with delivery marketplaces (DoorDash, Uber Eats, Grubhub) and technology partners (Google Cloud, Dynamic Yield) are bilateral and gated to approved partners and franchisees.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mcdonalds/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Delivery, Fast Food, Loyalty, Mobile Ordering, Ordering, Restaurants

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-06-02

## APIs

### McDonald's API
McDonald's does not expose a public, self-service API. Ordering, delivery integration, menu data, loyalty, and restaurant information flow through bilateral partner integrations rather than open developer endpoints. The api.mcdonalds.com and developer.mcdonalds.com hosts do not resolve to public documentation (both refuse connections as of the profiling date). Any API access is negotiated per partnership with delivery marketplaces, payment processors, loyalty integrators, and franchisee technology vendors.

**Human URL:** [https://corporate.mcdonalds.com/corpmcd/our-stories/digital.html](https://corporate.mcdonalds.com/corpmcd/our-stories/digital.html)

#### Tags:

 - Delivery, Fast Food, Loyalty, Mobile Ordering, Ordering, Restaurants

#### Properties

- [x-status](https://corporate.mcdonalds.com/corpmcd/our-stories/digital.html) — No public developer portal or open API documentation as of 2026-06.

## Common Properties

- [Website](https://www.mcdonalds.com)
- [Corporate](https://corporate.mcdonalds.com)
- [Blog](https://medium.com/mcdonalds-technical-blog)
- [Plans](plans/mcdonalds-plans-pricing.yml)
- [RateLimits](rate-limits/mcdonalds-rate-limits.yml)
- [FinOps](finops/mcdonalds-finops.yml)

## Features

| Name | Description |
|------|-------------|
| No Public Developer Program | McDonald's publishes no open API documentation and offers no self-service developer signup. Integration is bilateral and partner-gated. |
| Global Mobile App | McDonald's Global Mobile App delivers mobile order & pay, deals, and MyMcDonald's Rewards on a unified platform spanning app, kiosk, and loyalty surfaces, deployed across markets beginning in 2024. |
| MyMcDonald's Rewards | Loyalty program targeting 250M 90-day active members and $45B in annual systemwide sales from loyalty members by the end of 2027. |
| Drive-Thru Personalization | Dynamic Yield powers personalized digital menu boards and automated upselling across thousands of drive-thru lanes. |
| Generative AI Platform | Strategic Google Cloud partnership applying generative AI and Google Distributed Cloud edge compute across restaurants for crew tools, analytics, and customer experiences. |

## Use Cases

| Name | Description |
|------|-------------|
| Delivery Marketplace Listing | Surfacing McDonald's menus, pricing, and fulfillment to consumers via DoorDash, Uber Eats, and Grubhub through bilateral marketplace integrations. |
| Franchisee Restaurant Technology | POS, kiosk, kitchen, and back-of-house systems integrated per franchisee and market under McDonald's technology standards rather than a public API. |

## Integrations

| Name | Description |
|------|-------------|
| Google Cloud | Strategic partnership for cloud, edge (Google Distributed Cloud), and generative AI across restaurants worldwide. |
| Dynamic Yield | Personalization engine driving drive-thru digital menu boards and automated upsell recommendations. |
| DoorDash | Delivery marketplace integration for on-demand fulfillment. |
| Uber Eats | Delivery marketplace integration for on-demand fulfillment. |
| Grubhub | Delivery marketplace integration for on-demand fulfillment. |

## Plans, Rate Limits & FinOps

Commercial-surface artifacts describing the partner-gated economics (no public per-API pricing).

- [Plans & Pricing](plans/mcdonalds-plans-pricing.yml)
- [Rate Limits](rate-limits/mcdonalds-rate-limits.yml)
- [FinOps](finops/mcdonalds-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
