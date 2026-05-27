# Structure

The repository separates three different jobs.

## `Econlib/`

The working Econlib skeleton. The final goal is Lean 4, but the current layout
is source-language-first:

- `Lean4/`
- `Lean3/`
- `IsabelleHOL/`
- `CoqRocq/`
- `Mizar/`
- `Other/`

Inside each source-system folder, files are organized by economics domain and
are currently mostly placeholders.

## `docs/`

Human-readable explanation: topic maps, source summaries, open questions, and
roadmap notes.

## `references/`

Original external material: downloaded code, papers, arXiv source archives, and
license/provenance notes. This material is preserved for study and should not be
confused with cleaned Econlib code.

## Rule

Folders represent economics structure. Branches represent temporary work.
Topics should live on `main` as files and folders, not as permanent branches.
