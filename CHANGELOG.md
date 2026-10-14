# Changelog

Entries below v1.1 are upstream's. Anything under "Fork" is this fork only and has not been
through upstream review.

## Fork — unreleased

- Forked from [FrankieT19/rg-sp-ds-style](https://github.com/FrankieT19/rg-sp-ds-style) at
  v1.1. Documented the fork's status (personal, vibe coded, unsupported, no releases) in the
  README, the packaged `README.txt`, `CONTRIBUTING.md` and `CREDITS.md`.

## v1.1

- Fixed stock RetroArch core selections for games stored directly in a system folder. The `.setcore` subfolder field was incorrectly treated as a RetroArch flag, so these games could launch with the default core. Core choices now use the matching card and folder context on both TF1 and TF2, for all systems.
- Confirmed the fix on an RG SP. Updated the displayed version and installation package to v1.1.

## v1.0

First public release of DS Style for the Anbernic RG SP stock OS.

Includes the DS Style interface, customisation, stock launch integration, shared favourites/history, search, startup choices, and translations. See the README for features, compatibility and installation instructions.
