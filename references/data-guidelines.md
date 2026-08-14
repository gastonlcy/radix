# RADIX Data Guidelines

## Priority of Data Sources

1. Bankr native tools (Discover, launches feed, price tools, market data) filtered to Robinhood Chain
2. Direct token lookups via Bankr
3. Clearly stated limitations when data is incomplete

## Rules

- Never invent volume, price, holder counts, or launch times.
- If a metric is unavailable, explicitly say so.
- Prefer “based on currently available Bankr data” over absolute claims.
- Distinguish between:
  - Native / memecoin style tokens
  - Tokenized stocks / ETFs (when relevant)
- Timestamps matter — always indicate if data is live, recent, or lagged.

## What “Good” Looks Like

- Clean structure
- Low noise
- Actionable for both humans and other agents
- Neutral tone (no buy/sell recommendations)

## What to Avoid

- Hype language
- Unverified claims
- Over-long walls of text
- Mixing chains without clear labeling
