# Bright Machines

Bright Machines is a San Francisco-based software-defined manufacturing company founded in 2018 by Amar Hanspal and Lior Susan. Its Microfactory pairs modular Bright Robotic Cells with **Brightware**, a platform operating system that orchestrates hardware, runs a machine-vision "Smart Skills" perception stack, and provides manufacturing-execution services for work orders, material management and real-time production KPIs. **Bright Data** unifies component, process and enterprise-system data through secure APIs and auditable data flows, and **Bright Designer** turns product CAD into assembly-ready digital twins using NVIDIA Omniverse on Microsoft Azure. The company has raised roughly $279M from investors including Eclipse, BlackRock, NVIDIA, Microsoft and Jabil.

- Website: https://www.brightmachines.com/
- Platform: https://www.brightmachines.com/platform/
- GitHub: https://github.com/brightmachines
- Secondary market: https://forgeglobal.com/bright-machines_stock/

## API surface

**No public API.** Enrichment pass 2026-08-01 found no developer portal, no API reference, no
OpenAPI/Swagger/AsyncAPI/GraphQL contract, no SDKs on npm/PyPI/crates, no CLI, no hosted MCP
server and no A2A agent card. `api.brightmachines.com` exists in DNS but is a dangling CNAME to a
retired AWS ELB; `app.brightmachines.com` serves no valid certificate — both are customer/internal
tiers, not a public API. Brightware and Bright Data integrations (MES, ERP, Azure) are delivered
under commercial engagement. Full negative-result record in `well-known/`.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `apis.yml` | APIs.json index | — |
| `security/bright-machines-domain-security.yml` | DomainSecurity | probed |
| `well-known/bright-machines-well-known.yml` | discovery probe record | probed |
| `llms/bright-machines-llms.txt` | LLMsTxt | generated |
