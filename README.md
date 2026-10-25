# MONO Marketplace dependencies

Public dependency archives (pruned composer vendor/ trees) downloaded automatically by the MONO web installer during installation.

- One zip per app release, pinned by `install-dependencies.json` (URL + SHA-256) inside the app package.
- These archives contain only open-source composer packages (Laravel framework and friends) — no MONO application code.
- Power users can instead run `composer install --no-dev` from the app package.
