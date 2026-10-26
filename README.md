# Unify (unify-ai)

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

Unify is an LLM routing and model gateway platform that enables developers to access 100+ large language model providers through a single unified REST API and API key. The platform dynamically routes each prompt to the optimal model based on user-defined preferences across quality, speed, and cost dimensions, using live runtime benchmarks updated continuously across providers including OpenAI, Anthropic, Mistral, Together AI, Replicate, Groq, DeepSeek, Vertex AI, and many more. Developers can benchmark models on their own prompts, switch providers without rewriting application code, and monitor cost and performance through the observability dashboard at console.unify.ai.

APIs.json: https://raw.githubusercontent.com/api-evangelist/unify-ai/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=unify-ai-api-evangelist&utm_content=repo

## Tags

- LLM
- AI
- Large Language Models
- LLM Routing
- Model Gateway
- AI Gateway
- OpenAI
- Anthropic
- Mistral
- Benchmarking
- Model Comparison
- AI Infrastructure
- Machine Learning

## APIs

| Name | Description | Base URL |
|------|-------------|----------|
| Unify Universal API | Single REST endpoint for routing LLM requests to 100+ model providers using Bearer token auth and model@provider syntax | https://api.unify.ai/v0 |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/unify-ai-plans-pricing.yml](plans/unify-ai-plans-pricing.yml) |
| Rate Limits | [rate-limits/unify-ai-rate-limits.yml](rate-limits/unify-ai-rate-limits.yml) |
| FinOps Framework | [finops/unify-ai-finops.yml](finops/unify-ai-finops.yml) |

**Pricing summary:** New users receive $50 in free credits. Beyond that, pricing is pay-as-you-go and consumption-based, with costs flowing from the underlying LLM providers plus Unify's routing overhead. Enterprise custom benchmark services available on request.

**Rate limits:** Limits are tier-dependent and credit-balance gated. Provider-level limits depend on the upstream model chosen; BYOK (bring your own provider API keys) is supported to use your own provider quotas.

**FinOps:** Unify's optimizer routing is itself a FinOps tool, automatically selecting the cheapest provider meeting quality and latency thresholds. Cost tagging, caching, fallback routing, and BYOK are primary optimization levers.

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-12 |
| Modified | 2026-06-12 |

## Common

| Type | URL |
|------|-----|
| Website | https://unify.ai |
| Documentation | https://docs.unify.ai |
| GitHub Org | https://github.com/unifyai |
| LinkedIn | https://uk.linkedin.com/company/letsunifyai |
| Blog | https://unify.ai/blog |
| Pricing | https://unify.ai/pricing |
| Status Page | https://statusgator.com/services/unify |
| X (Twitter) | https://x.com/letsunifyai |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
