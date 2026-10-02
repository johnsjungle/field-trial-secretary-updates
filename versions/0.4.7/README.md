# HALO v0.4.7 beta

Offline lure coursing trial management for Windows, Ubuntu, and macOS.

This release introduces the HALO identity in remembrance of Halo, explains the HALO workflow, and adds practical guidance for preparing to use the program at a field trial. Existing installations can install it with **Admin > Updates & Versions > Check for Updates**, then **Update Program to v0.4.7**. The updater backs up the current database, updates only program files, and restarts the application.

Manual installers are also available below. Existing trial data remains in its current data directory.

See [release notes](RELEASE_NOTES.md).

## Ubuntu

- **AppImage:** Download `HALO-0.4.7-x86_64.AppImage`, make it executable, and open it. This portable version supports HALO's verified automatic program updater.
- **Debian package:** Download `HALO-0.4.7-Ubuntu-amd64.deb` and install it with Ubuntu's Software app or `sudo apt install ./HALO-0.4.7-Ubuntu-amd64.deb`.

Ubuntu trial data is stored separately from the application under `~/.local/share/HALO`, so replacing or reinstalling the program does not overwrite the database.
