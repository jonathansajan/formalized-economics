# Formalized Economics

This repository organizes formalized economics work toward a future
Econlib-style library in modern Lean 4.

The current goal is structure first: one canonical `main` branch, one visible
source-language-first library skeleton, and clearly separated source archives.
Many `Econlib/` files are placeholders and do not yet contain completed
formalizations.

Long term, the aim is to translate or adapt the useful material into a clean
Lean 4 Econlib. Short term, the repo keeps each source ecosystem visible so the
project does not pretend older Lean, Isabelle/HOL, Coq/Rocq, Mizar, or other
formal-methods sources are already modern Lean 4.

## Repository Layout

- `Econlib/` contains source-language-first placeholders for future Econlib work.
- `docs/` contains the human-readable map, topic notes, source summaries, and roadmap.
- `references/` contains original external papers, source archives, and downloaded code.

Original external code stays under `references/`. Cleaned or rewritten
Econlib-facing work is planned under `Econlib/`, with Lean 4 as the final target.

## Current Source Systems

- `Econlib/Lean4/`: material already identified as Lean 4.
- `Econlib/Lean3/`: older or not-yet-confirmed Lean material.
- `Econlib/IsabelleHOL/`: Isabelle/HOL sources and AFP entries.
- `Econlib/CoqRocq/`: Coq/Rocq sources.
- `Econlib/Mizar/`: Mizar sources.
- `Econlib/Other/`: relevant formal-methods sources that do not fit the above.

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

- a source-language-first Econlib skeleton,
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
