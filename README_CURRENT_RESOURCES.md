# Gravar v0.6.204 Current Resources

Current standalone Gravar release: **v0.6.204 — Default Code System**.

## Files

- `Gravar_v0.6.204_Default_Code_System.html` — named standalone application.
- `index.html` — identical copy for GitHub Pages/static hosting.
- `CHANGELOG.md` — cumulative version changelog.
- `CHANGELOG_BY_DATE.md` — date-organized changelog.
- `ARCHITECTURE_AUDIT_v0.6.197.md` — modularity/efficiency audit and refactoring roadmap.
- `gravar-shared-symbols.json` — expanded default reusable Symbols set.
- `gravar-shared-codes.json` — default reusable Coding palette supplied for v0.6.204.
- `Gravar_v0.6.204_SHA256.txt` — checksums for the resource files.

## v0.6.204 behavior

Fresh Gravar sessions now use the supplied shared Code system as the built-in Coding palette. The default contains **18 Codes plus 5 section headers** organized as **DEAN**, **Todd minspeak (home dev)**, **Linda (home dev)**, **Pre-emptive & Transition**, and **Embodied**.

Gravar automatically upgrades only the exact former built-in `question / answer / repair / overlap` palette. Genuinely customized project Code palettes remain project-specific and are not overwritten.

Code persistence and legacy migration are now owned by the Coding subsystem through an `XProjectState` adapter, consistent with the modular/message-passing architecture.

All v0.6.203 Project-menu spacing, expanded default Symbols, Option/Alt contextual web tips, long-video waveform calibration, and verified manual Save-location behavior are preserved.
