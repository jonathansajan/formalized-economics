# Roadmap

## Stage 1: Structure

- Keep `main` as the canonical repository.
- Add the full source-language-first Econlib skeleton.
- Add one documentation entry per mapped source.
- Preserve collected source material under `references/`.

## Stage 2: Source Review

- Check source links, licenses, build files, and theorem-prover versions.
- Mark which projects are reusable, which need porting, and which are only
  background references.

## Stage 3: Lean 4 Setup

- Choose and install the Lean 4/Lake toolchain.
- Add build metadata only after the toolchain choice is clear.
- Keep source archives separate from buildable Econlib files.
- Treat non-Lean-4 placeholders as translation or adaptation targets, not as
  completed Lean 4 code.

## Stage 4: First Formalization

- Start with finite outcomes.
- Define finite lotteries.
- Define utility functions.
- Define expected utility.
- Prove basic mixture behavior.
- Treat full vNM representation as a later target.
