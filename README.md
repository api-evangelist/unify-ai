# Unify (unify-ai)

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
