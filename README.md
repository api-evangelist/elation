# Elation Health

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

Elation Health provides a primary care EHR platform with a REST API for managing patient profiles, clinical encounters, orders, results, prescriptions, and direct secure messaging in ambulatory settings. The API enables interoperability by integrating patient data from third-party sources, supporting patient engagement, clinical operations, scheduling, pharmacy management, and practice administration through OAuth2-secured REST endpoints.

## Links

- **Website**: https://www.elationhealth.com/
- **API Documentation**: https://docs.elationhealth.com/reference/api-overview
- **Developer Platform**: https://www.elationhealth.com/developer-platform/
- **Developer Sandbox**: https://www.elationhealth.com/contact-us/sandbox/
- **GitHub Organization**: https://github.com/elationemr
- **Blog**: https://www.elationhealth.com/resources/blogs
- **Pricing**: https://www.elationhealth.com/contact-us/pricing/
- **Status Page**: https://elationhealth.statuspage.io
- **X / Twitter**: https://x.com/elationhealth
- **LinkedIn**: https://www.linkedin.com/company/elationhealth

## APIs

- **Elation Health REST API** — RESTful API (v2.0) for the full Elation EHR platform. Covers patient management, clinical documentation, lab and imaging orders, referrals, appointments, pharmacy, insurance, billing, messaging, and practice administration.

## Authentication

All API requests require OAuth2 Bearer tokens using the client credentials grant type. Separate credentials are required for sandbox and production environments.

- Sandbox base URL: `https://sandbox.elationemr.com/api/2.0/`
- Production base URL: `https://app.elationemr.com/api/2.0/`

## Key Resources

- Patients and patient profiles
- Visit notes and clinical documentation
- Problems, allergies, immunizations, vitals
- Lab orders, imaging orders, referrals
- Medications, prescriptions, pharmacy
- Appointments and scheduling
- Insurance and billing
- Direct secure messaging
- Webhooks and event subscriptions
- Practice and staff management

## Maintainer

**Kin Lane** — kin@apievangelist.com
