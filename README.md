# Lakera (lakera)

Lakera is an AI security company building runtime defenses for generative AI applications. Its flagship Lakera Guard API screens prompts and responses for prompt injection, jailbreaks, PII leakage, unsafe content, and policy violations, while Lakera Red provides automated red teaming and risk assessment for GenAI systems. Lakera follows an API-first architecture with a managed SaaS platform, regional endpoints, self-hosted deployments for regulated environments, and a free Gandalf training game that has driven much of the prompt injection research community.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lakera/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lakera/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI Security
- LLM Security
- Prompt Injection
- Guardrails
- Red Teaming
- GenAI
- API

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Lakera Guard

Lakera Guard is a low-latency screening API that inspects text content sent to or from LLMs and flags threats including prompt injection, jailbreaks, PII, profanity, and policy violations. The /guard endpoint returns a flagged decision plus optional detector breakdowns via /guard/results, and the platform exposes /policies and /projects endpoints for managing detection logic. Available as a managed SaaS at api.lakera.ai/v2 with regional endpoints (US, EU, APAC) and as a self-hosted deployment for regulated environments.

- **Human URL:** [https://docs.lakera.ai/docs/api](https://docs.lakera.ai/docs/api)

#### Tags

- AI Security
- Prompt Injection
- PII Detection
- Content Moderation
- LLM Guardrails

#### Properties

- [API Reference](https://docs.lakera.ai/docs/api)
- [Getting Started](https://docs.lakera.ai/docs/quickstart)
- [Changelog](https://platform.lakera.ai/docs/changelog)
- [Postman Collection](collections/lakera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lakera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lakera Red

Lakera Red is an automated red teaming product that probes GenAI applications for jailbreaks, prompt injection, data leakage, and other adversarial failures, then produces a risk-based remediation report. Designed for security teams evaluating AI applications prior to production deployment and for ongoing assurance of agentic systems.

- **Human URL:** [https://www.lakera.ai/ai-red-teaming](https://www.lakera.ai/ai-red-teaming)

#### Tags

- Red Teaming
- AI Security
- Vulnerability Assessment
- GenAI Testing

#### Properties

- [Documentation](https://www.lakera.ai/ai-red-teaming)
- [Postman Collection](collections/lakera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lakera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gandalf

Gandalf is Lakera's free interactive game that teaches prompt injection by challenging players to extract a secret from an LLM across progressively harder defenses. It has become a primary research and training environment for the prompt injection community and a public funnel into the Lakera Guard ecosystem.

- **Human URL:** [https://gandalf.lakera.ai/](https://gandalf.lakera.ai/)

#### Tags

- Education
- Prompt Injection
- Training
- Research

#### Properties

- [Documentation](https://gandalf.lakera.ai/)
- [Postman Collection](collections/lakera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lakera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.lakera.ai/)
- [Documentation](https://docs.lakera.ai/)
- [API Reference](https://docs.lakera.ai/docs/api)
- [Getting Started](https://docs.lakera.ai/docs/quickstart)
- [Changelog](https://platform.lakera.ai/docs/changelog)
- [Blog](https://www.lakera.ai/blog)
- [Pricing](https://www.lakera.ai/pricing)
- [Login](https://platform.lakera.ai/login)
- [Sign Up](https://platform.lakera.ai/)
- [GitHub Organization](https://github.com/lakeraai)
- [LinkedIn](https://www.linkedin.com/company/lakeraai/)
- [Events](https://www.lakera.ai/events)
- [Game](https://gandalf.lakera.ai/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.lakera.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
