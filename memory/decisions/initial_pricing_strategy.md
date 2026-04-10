# Decision: Initial Pricing Strategy

## Decision

Launch `launchpad-lint` at `$0.09` per successful call if it becomes the first public
AgenticMarket listing.

## Date

2026-04-06

## Why

- AgenticMarket uses a fixed per-call price after publish.
- The product is narrow and event-driven, not a heavy recurring workflow.
- The ICP should tolerate a small paid test if the value is legible immediately.
- A two-call first session at `$0.18` is cheap enough to encourage validation without
  signaling that the tool is disposable.

## Packaging Assumption

Do not add tiers, bundles, or freemium logic in V1. Use the marketplace's native
per-call model and learn from real usage first.

## Revisit Trigger

Revisit only if:

- install-to-first-call is healthy but paid continuation is weak,
- users perceive the tool as obviously underpriced or obviously overpriced,
- or the observed first useful session requires substantially more than two calls.
