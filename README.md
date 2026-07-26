# Pricing Context

This repository is the canonical context lineage for one Skillfoundry agent.
The harness runs inside this repository root. Fresh runtime instances may come
and go, but this context lineage remains the durable working mind.

## Front Door

- `memory/mission.md`
- `memory/profiles/pricing.md`
- `memory/findings/launchpad_lint_value_model.md`
- `memory/decisions/initial_pricing_strategy.md`
- `memory/plans/price_validation_loop.md`

## Lifecycle and verification

Maintained, not currently an independently deployed service. The fastest
complete contract check is `make check`. See
[docs/architecture.md](docs/architecture.md) for authority boundaries and the
dated prompt-governance and runtime-path exceptions.
