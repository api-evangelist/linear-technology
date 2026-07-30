# Linear Technology

Linear Technology Corporation was an American semiconductor company founded in 1981 by Robert H. Swanson Jr.
and Robert C. Dobkin, headquartered in Milpitas, California. It designed and manufactured high-performance
analog integrated circuits — data conversion, signal conditioning, power management, interface, RF,
oscillators, and space/military ICs — across a catalog of more than 7,500 products.

**Status: acquired.** Analog Devices agreed to acquire Linear Technology in July 2016 for approximately
$14.8 billion in cash and stock; the deal closed on March 10, 2017. The Linear name survives only as the
"Power by Linear" product brand.

## Enrichment findings (2026-07-19)

Linear Technology has **no independent API surface**. It is retained in the network as an archived company
profile, with pointers to its successor.

- `www.linear.com` still resolves, but every probed path returns **HTTP 301** to the Analog Devices
  "ADI + Linear combine" landing page — including `/.well-known/security.txt`,
  `/.well-known/openid-configuration`, `/.well-known/oauth-authorization-server`,
  `/.well-known/api-catalog`, `/.well-known/ai-plugin.json`, `/llms.txt`, and `/openapi.json`.
- No GitHub organization, no OpenAPI/AsyncAPI, no MCP server, no first-party packages, no developer portal.
- No vulnerability-disclosure program or trust center found on the legacy domain.
- The npm package `@linear/sdk` belongs to **Linear (linear.app)**, an unrelated issue-tracking company,
  and is deliberately **not** associated with this repo.

**Developer-facing successor: [`analog-devices`](https://github.com/api-evangelist/analog-devices)** —
that repo carries the live API artifacts (libiio, PyADI-IIO, and the rest of the ADI developer surface).

## Artifacts

| Path | Type | Method |
|---|---|---|
| `security/linear-technology-domain-security.yml` | DomainSecurity | probed |

Backed by: kleiner-perkins (inherited from the VC-portfolio stub; not independently verified).
