# Bundled pet: Guy Fieri

Issue: #615

## Change

- Add the validated CoS v1 package at `pets/guy-fieri/`.
- Cover `guy-fieri` in the bundled-pet test table so discovery, disabled-by-default state, atlas loading and the 14-animation manifest are exercised.
- Packaging already includes `pets/*/{pet.json,atlas.png,animations.json}` through `electron-builder.yml`; no packaging rule change is required.

## Validation

- The authored source package passed its strict local pet validator before staging: 96 unique frames, the fixed 14 animation slots, hand anchors for frames 69–84 and the exact three-file import bundle.
- This branch is prepared independently from upstream `main` at `4e51a04d8e89a559e16d17fc7df6f547e57d666d`.
- `git diff --check` is run before the branch commit.
