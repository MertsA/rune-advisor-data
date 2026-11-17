# Rune Advisor data

The tables the Rune Advisor planner reads: drop tables, shops, recipes, equipment, training rates, calculator
tables and the project's hand-written tables. The planner's code is a separate repository, which includes
this one as a submodule at `src/rune_advisor/data/`; the scripts that build these files (`scripts/build_*.py`)
live there.

Signed data packages (`rune-advisor-data-<format>-<version>.tar.xz`) are built from this tree, so a data fix
reaches every platform without a new release of the app. `VERSION`, when present, is the package version the
tree was last released as.

Licences: see `NOTICE.md`.
