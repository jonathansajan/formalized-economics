# Voting Theory in Lean Original Material

## Paper

- Title: Voting Theory in the Lean Theorem Prover
- Authors: Wesley H. Holliday, Chase Norman, and Eric Pacuit
- arXiv: https://arxiv.org/abs/2110.08453
- arXiv PDF: https://arxiv.org/pdf/2110.08453
- arXiv submission date: 2021-10-16
- Downloaded: 2026-05-27

## Code

- Repository: https://github.com/chasenorman/Formalized-Voting
- Downloaded: 2026-05-27
- Local path: `references/lean3/social-choice/voting-theory/code/Formalized-Voting/`
- Branch: `main`
- Commit: `de04e630b83525b042db166670ba97f9952b5691`

The paper source states that all project code is available at the repository above.

## Lean Metadata

- System: Lean 3
- Lean toolchain from `leanpkg.toml`: `leanprover-community/lean:3.28.0`
- Package name: `Formalized-Voting`
- Package version: `0.1`
- Source path: `src`
- Project metadata present:
  - `leanpkg.toml`
  - `.gitignore`
- Lake metadata is not present.
- Mathlib dependency from `leanpkg.toml`: `https://github.com/leanprover-community/mathlib`
- Mathlib revision: `2ecd65e6de2939f09df9d964782f8ec7ba4aeb5c`

This is Lean 3-era material and should not be treated as Econlib-ready Lean 4 code.

## Local Paper Files

- arXiv PDF: `references/lean3/social-choice/voting-theory/paper/2110.08453.pdf`
- arXiv source archive: `references/lean3/social-choice/voting-theory/paper/2110.08453-source.tar`
- extracted arXiv source: `references/lean3/social-choice/voting-theory/paper/source/`

## Main Lean Files

- `src/main.lean`
- `src/cycles.lean`
- `src/relation.lean`
- `src/condorcet.lean`
- `src/split_cycle.lean`
- `src/clones.lean`
- `src/monotonicity.lean`
- `src/pareto.lean`
- `src/reversal.lean`
- `src/stability.lean`
- `src/involvement.lean`
- `src/lori2021/lori.lean`

Important topic areas in the original code:

- profiles
- majority preference and margins
- social choice correspondences
- variable-election social choice correspondences
- collective choice rules
- graph cycles, walks, and paths
- Condorcet-related concepts
- Split Cycle
- independence of clones
- monotonicity, Pareto, reversal, stability, and involvement properties

## License

- The downloaded Lean code repository does not appear to include a `LICENSE` file.
- The arXiv source package does not appear to include a separate license file.
- Before copying or adapting substantial Lean code into `Econlib/`, the code license should be confirmed from the authors or repository maintainers.

## Notes

This folder stores the original downloaded material for the Voting Theory in Lean topic. The files here should stay close to the source version. Any future Econlib-facing work should happen separately, likely as a Lean 4 port or adaptation under a social-choice area.
