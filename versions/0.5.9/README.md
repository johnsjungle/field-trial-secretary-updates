# HALO v0.5.9

HALO v0.5.9 fixes AKC Specials missing from the worker-sheet stake counts and corrects alphabetical record packets to print Open, Specials, then Veteran. AKC worker sheets now label the column Specials. Expanded automatic checks help catch these reporting problems in future changes.

Existing entries and draws do not need rebuilding. After updating, reprint the affected sheets.

Use **Admin > Updates & Versions** to update. HALO backs up and preserves the local trial database while replacing program files and restarting.

Installers are available from the [v0.5.9 release](https://github.com/johnsjungle/field-trial-secretary-updates/releases/tag/v0.5.9):

- Windows: extract the portable ZIP and run **Start HALO.vbs**.
- Apple Silicon Mac: use the **arm64** DMG.
- Intel Mac: use the **x86_64** DMG.
- Ubuntu: install the **amd64.deb** or make the **x86_64.AppImage** executable and run it.

New installations include a blank starter database template and no live trial data. On first launch, choose to create a new database or restore an existing one.

See [RELEASE_NOTES.md](RELEASE_NOTES.md) for details.
