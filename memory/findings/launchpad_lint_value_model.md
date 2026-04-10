# Launchpad Lint Value Model

## Product

`launchpad-lint`

## User Situation

The target user already has a working MCP server but is uncertain whether it is ready
for a public marketplace launch.

Their real pain is not "write prettier copy." It is:

- unclear launch blockers,
- uncertainty about whether the package is legible enough to submit,
- and wasted time rewriting descriptions, prompts, and limits from scratch.

## Value Event

The core value event is a builder getting to a credible launch package in one short
session instead of manually iterating across README, listing copy, and missing details.

That suggests the relevant unit is not "ongoing monthly access." It is a small number
of high-value calls around a launch event.

## Price Sensitivity

The chosen ICP is technical and cost-aware, but not allergic to paying for clear
workflow leverage.

Pricing should therefore avoid two failure modes:

- too low, which makes the tool look trivial or noisy
- too high, which suppresses first-use experimentation before trust exists

## Recommended Pricing Frame

For the first launch, price per successful call rather than trying to force a larger
package structure too early.

Assume the most common first workflow is:

1. one `audit_launch_readiness` call
2. one `draft_launch_package` call

That means the effective "first useful session" cost should feel easy to try without
approval overhead.

## Initial Recommendation

- target per-call price: `$0.09`
- expected first useful session cost: `$0.18`

## Why This Number

- above pure novelty pricing
- below the threshold where a first-use builder hesitates
- consistent with the product being useful but still unproven
- leaves room to revisit packaging later if retained value is real
