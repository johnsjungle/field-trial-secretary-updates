# HALO v0.4.10 beta

Offline lure coursing trial management for Windows, Ubuntu, and macOS.

This release corrects AKC placement and event-number printing and ensures AKC and ASFA record sheets document hounds that were lame, absent, scratched, excused, dismissed, disqualified, in season, forfeited, pulled, or given no score. Existing installations can install it with **Admin > Updates & Versions > Check for Updates**, then **Update Program to v0.4.10**. The updater backs up the current database, updates only program files, and restarts the application.

Manual installers are also available on the [HALO v0.4.10 release page](https://github.com/johnsjungle/field-trial-secretary-updates/releases/tag/v0.4.10). Existing trial data remains in its current data directory.

See [release notes](RELEASE_NOTES.md).

## Ubuntu

- **AppImage:** Download HALO-0.4.10-x86_64.AppImage, make it executable, and open it. This portable version supports HALO's verified automatic program updater.
- **Debian package:** Download HALO-0.4.10-Ubuntu-amd64.deb and install it with Ubuntu's Software app or sudo apt install ./HALO-0.4.10-Ubuntu-amd64.deb.

Ubuntu trial data is stored separately from the application under ~/.local/share/HALO, so replacing or reinstalling the program does not overwrite the database.
