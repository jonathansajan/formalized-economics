# Formalized Economics

This repository organizes formalized economics work toward a future
Econlib-style Lean 4 library.

The current goal is structure first: one canonical `main` branch, one visible
library skeleton, and clearly separated source archives. Many `Econlib/` files
are placeholders and do not yet contain completed formalizations.

## Repository Layout

- `Econlib/` contains the future Lean 4-facing library structure.
- `docs/` contains the human-readable map, topic notes, source summaries, and roadmap.
- `references/` contains original external papers, source archives, and downloaded code.

Original external code stays under `references/`. Cleaned or rewritten
Econlib-facing Lean 4 work belongs under `Econlib/`.

## Current Domains

- Decision theory / utility theory
- Social choice / voting theory
- Game theory
- Mechanism design / auctions
- Welfare economics / general equilibrium
- Financial economics / DeFi / AMMs
- Econometrics and statistics-adjacent formalization
- Meta sources and source hubs

## Current Status

The project currently contains:

- a domain-level Econlib skeleton,
- placeholder files for the initial 25 mapped formalization sources,
- documentation entries for those sources,
- archived vNM, AMM, and voting-theory source material collected from earlier work.

Lean, Lake, and Elan are not yet configured locally, so this repository should
not yet be treated as a buildable Lean package.

## Next Steps

1. Review the structure and source map for accuracy.
2. Install or choose the Lean 4/Lake toolchain.
3. Decide the first true Lean 4 implementation target.
4. Start with a small decision-theory core: finite outcomes, finite lotteries,
   utility functions, expected utility, and mixture behavior.
