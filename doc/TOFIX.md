# TOFIX

Findings from a code scan on 2026-10-04.

## Medium

- `config/project.lua:3` - the repo is described as "Buildroot demos" but contains no demos at all (only `README.md`, `config/project.lua` and shared fleet files); either add the Buildroot content (defconfigs, external tree, notes) or retire the repo.

## Low

- `README.md:1` - README is only the title; once content exists, describe it (and add `rsconstruct.toml`, `pyproject.toml` and the fleet `build.yml` like the other repos so it is linted in CI - today nothing is checked).
