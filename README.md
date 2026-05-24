# MITRE ATLAS (Adversarial AI) MCP


> ## Buy Starter — £29/mo
> **Signed attestations + unlimited audits + email support.**
> 👉 **[Subscribe at meok.ai](https://buy.stripe.com/28E8wRbcw0024c5fL28k90f)** — instant HMAC signing key + Stripe-managed billing.
>
> Free tier remains MIT-licensed and zero-config. Upgrade only when you need signed compliance artefacts for audit.

[![PyPI](https://img.shields.io/pypi/v/mitre-atlas-mcp)](https://pypi.org/project/mitre-atlas-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

MITRE ATLAS — Adversarial Threat Landscape for AI Systems. Tactics + techniques for attacking AI/ML, case studies, mitigations.

## Install

```bash
pip install mitre-atlas-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `query_atlas_technique` | ATLAS technique lookup (AML.Txxxx) |
| `list_atlas_tactics` | All 14 ATLAS tactics for AI/ML adversarial attacks |
| `case_study_lookup` | ATLAS case studies (real-world ML attacks) |
| `mitigation_for_technique` | Mitigations per ATLAS technique |
| `map_to_owasp_llm` | Cross-map ATLAS techniques to OWASP LLM Top 10 |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## Wire it up — full stack

Pair this with the MEOK chain that turns one agent action into ONE signed compliance event:

1. **bft-progress-council-mcp** — anti-loop guardrail
2. **agent-token-budget-mcp** — hard spend cap
3. **agent-prompt-injection-firewall-mcp** — OWASP LLM01 scan
4. **agent-audit-logger-mcp** — hash-chained evidence
5. **a2a-governance-bridge-mcp** — fold N attestations → 1 signed event
6. **agent-incident-relay-mcp** — broadcast incidents to 5 regimes simultaneously

See [meok.ai/mcp-stack](https://meok.ai/mcp-stack) for the architecture and [meok.ai/mcp-stack/demo](https://meok.ai/mcp-stack/demo) for the live in-browser demo.

## License

MIT © MEOK AI Labs

<!-- mcp-name: io.github.CSOAI-ORG/mitre-atlas-mcp -->
