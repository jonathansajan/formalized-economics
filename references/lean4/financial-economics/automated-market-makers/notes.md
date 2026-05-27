# Automated Market Makers Original Material

## Paper

- Title: Formalizing Automated Market Makers in the Lean 4 Theorem Prover
- Authors: Daniele Pusceddu and Massimo Bartoletti
- arXiv: https://arxiv.org/abs/2402.06064
- arXiv PDF: https://arxiv.org/pdf/2402.06064
- arXiv submission date: 2024-02-08
- Published version: https://drops.dagstuhl.de/entities/document/10.4230/OASIcs.FMBC.2024.5
- DOI: 10.4230/OASIcs.FMBC.2024.5
- Downloaded: 2026-05-27

## Code

- Repository: https://github.com/dpusceddu/lean4-amm
- Author-name redirect also works: https://github.com/danielepusceddu/lean4-amm
- Downloaded: 2026-05-27
- Local default-branch path: `references/lean4/financial-economics/automated-market-makers/code/lean4-amm/`
- Default branch: `master`
- Default-branch commit: `707c9cb2d2bc5ec4fce93df5d09822737abdce24`
- Local paper-branch path: `references/lean4/financial-economics/automated-market-makers/code/lean4-amm-paper-branch/`
- Paper branch: `paper`
- Paper-branch commit: `9cd8e62bbacc908f4569241a37bfbcc45478b145`

The paper source links to the GitHub repository using the `paper` branch. The default `master` branch was also preserved because it is the current public repository state.

## Lean and Lake Metadata

- Lean toolchain: `leanprover/lean4:v4.5.0`
- Lake package name: `lean4-amm`
- Lake files present:
  - `lakefile.lean`
  - `lake-manifest.json`
  - `lean-toolchain`
- Main dependency: Mathlib 4 at input revision `v4.5.0`
- Mathlib manifest revision: `feec58a7ee9185f92abddcf7631643b53181a7d3`

## Local Paper Files

- arXiv PDF: `references/lean4/financial-economics/automated-market-makers/paper/arxiv/2402.06064.pdf`
- arXiv source archive: `references/lean4/financial-economics/automated-market-makers/paper/arxiv/2402.06064-source.tar`
- extracted arXiv source: `references/lean4/financial-economics/automated-market-makers/paper/arxiv/source/`
- published Dagstuhl/FMBC PDF: `references/lean4/financial-economics/automated-market-makers/paper/dagstuhl/OASIcs.FMBC.2024.5.pdf`

## Main Lean Files and Folders

- `AMMLib.lean`
- `HelpersLib.lean`
- `AMMLib/State/`
- `AMMLib/Transaction/`
- `AMMLib/Transaction/Swap/`
- `HelpersLib/`

Important topic areas in the original code:

- token and account definitions
- atomic and minted-token wallets
- AMM reserve/state definitions
- price, supply, and net worth
- create, deposit, redeem, swap, and trace transactions
- constant-product swap-rate proofs and arbitrage-related results

## License

- The paper source includes a `LICENSE.md` file for the LaTeX source package and `main.tex` notes a CC-BY publication license.
- The downloaded Lean code repository does not appear to include a `LICENSE` file.
- Before copying or adapting substantial Lean code into `Econlib/`, the code license should be confirmed from the authors or repository maintainers.

## Notes

This folder stores the original downloaded material for the AMM Lean 4 topic. The files here should stay close to the source versions. Cleaned or rearranged Econlib-facing work should happen later under an appropriate `Econlib/` topic area.
