# Contributing

**This is a personal fork.** It is not accepting contributions, and it is not where DS Style
is developed. Issues and pull requests belong upstream, at
[FrankieT19/rg-sp-ds-style](https://github.com/FrankieT19/rg-sp-ds-style).

Changes here are vibe coded — largely LLM-written, reviewed by one person, tested on one
device. If something in this fork misbehaves, it is a fork problem; please do not report it
as a DS Style bug.

If you are reading this because a change here looks worth upstreaming: take it. It is
Apache-2.0, same as the original.

## If you are me, future me, or an agent working in this repo

The upstream rules still apply and are worth keeping:

- Preserve the DS Style appearance and the stock OS's ownership of emulator configuration,
  saves and hardware state.
- No fixed core choices, no personal paths baked into the source.
- Keep assets editable and retain their source attribution.
- Translation changes belong in `source/locale.json`; regenerate the header with
  `tools/generate_locale.py`.
- Follow [BUILDING.md](docs/BUILDING.md) and run the checks relevant to the change.
  Distinguish host checks from actual hardware results — say which firmware and device was
  tested, and say plainly when something was only built, not run.
- Never commit ROMs, BIOS files, firmware dumps, tokens or runtime state.
