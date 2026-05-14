# MITRE ATLAS (Adversarial AI) MCP

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

## License

MIT © MEOK AI Labs

<!-- mcp-name: io.github.CSOAI-ORG/mitre-atlas-mcp -->
