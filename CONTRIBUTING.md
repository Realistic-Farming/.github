# Contributing to Realistic Farming

Thanks for helping improve the **Realistic Farming** suite for Farming Simulator 25.

## Reporting a bug
1. Update to the latest release first.
2. Reproduce with **Debug Mode** on where the mod offers it.
3. Open an issue on the *specific mod's* repository and include:
   - Mod + version, FS25 version, single-player or multiplayer
   - What happened vs. what you expected
   - The relevant lines from `log.txt`
     (`Documents\My Games\FarmingSimulator2025\log.txt`)

## Suggesting a feature
Open an issue describing the idea and how it fits the realism theme. Concrete examples and screenshots help a lot.

## Compatibility reports
If a mod conflicts with another, open an issue naming **both** mods and their versions.

## Pull requests
- Branch from `development`; PRs target `development`, not `main`.
- Keep changes focused and match the surrounding code style.
- FS25 runs **Lua 5.1** — no `goto`, no `continue`.

## Translations
Most mods load `translations/translation_*.xml`. New languages and fixes are always welcome.
