# Diagon

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
