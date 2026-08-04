# Diagon

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

Diagon is a California-based industrial equipment sourcing company building **Albus**, an equipment intelligence platform for manufacturing buyers and sellers. Buyers search across millions of industrial equipment listings, compare models, specifications, pricing and availability, and connect directly with sellers; sellers publish AI-powered catalogs, reach qualified buyer demand, and see live equipment searches in real time. Diagon indexes manufacturing equipment products, suppliers and service providers, bringing hardware, services and financing into a consolidated procurement experience.

- Website: https://diagon.ai/
- Blog: https://diagon.ai/blog
- LinkedIn: https://www.linkedin.com/company/diagon-tech/

Backed by: anthemis (data, tech and infrastructure thesis, early-stage venture)

## API surface

Diagon publishes **no public developer API**. The `/api/` path is an authenticated
first-party application API (Clerk session auth) and is disallowed in `robots.txt`.
No OpenAPI, AsyncAPI, SDKs, CLI, sandbox, changelog or status page were found.

What Diagon *does* publish that matters for agent readiness:

- A real [`/llms.txt`](llms/diagon-llms.txt) describing the platform and its public surfaces (saved verbatim).
- An explicit per-agent `robots.txt` policy naming GPTBot, ChatGPT-User, ClaudeBot,
  anthropic-ai, PerplexityBot, Google-Extended, Cohere-ai and meta-externalagent.
