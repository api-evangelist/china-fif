# Fortune Technology (China FIF)

Fortune Technology is listed by Qiming Venture Partners as one of the largest commercial factoring companies in China, historically operating at `china-fif.com`. It was surfaced as a Qiming portfolio company and added to the API Evangelist network as an enrichment lead.

**Enrichment result (2026-07-20): no API surface. No artifacts written.**

- The company publishes no public API, developer portal, documentation, or machine-readable specification.
- `china-fif.com` no longer serves the company. Port 443 is closed (no TLS at all); plain HTTP returns an unrelated Chinese Premier League sports-streaming site running EmpireCMS.
- Every discovery path probed returned 404: `/.well-known/security.txt`, `/.well-known/openid-configuration`, `/.well-known/oauth-authorization-server`, `/.well-known/api-catalog`, `/.well-known/ai-plugin.json`, `/llms.txt`, `/openapi.json`, `/swagger.json`.
- No SPF, DMARC, CAA, or MX records are published for the domain.

This record is retained as an honest negative result rather than deleted. Commercial factoring is not an API-first business, and no successor developer surface was located. See `apis.yml` `x-notes` for the full probe log.

Backed by: qiming — http://www.china-fif.com (repurposed)
