# Price Validation Loop

## Goal

Turn the initial pricing decision into a falsifiable learning loop.

## Initial Hypothesis

At `$0.09` per successful call, `launchpad-lint` will feel cheap enough to try and
expensive enough to imply non-trivial value.

## Metrics To Watch

- install to first paid call
- first useful session completion
- effective calls per first session
- repeat usage within the first launch cycle
- qualitative complaints about price vs usefulness

## Fast Failure Signals

- users abandon before the first paid call
- users complete one call but do not proceed to the second tool
- users consistently need too many calls to get value
- feedback says the output feels generic relative to price

## Follow-up Actions

- If activation is weak, consider lower-friction copy before changing price.
- If perceived value is high and usage repeats, consider whether a future higher price
  or more opinionated package is justified.
- If the tool needs too many calls for one useful session, reduce workflow steps before
  changing price.
