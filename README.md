# Eclipse Companion Android Releases

The latest signed Android installer is **Eclipse Companion 1.1.2** (version code 27).

- [Download the latest APK directly](https://raw.githubusercontent.com/brawlstarswewe111-arch/eclipse-companion-releases/main/Eclipse-Companion.apk)
- [Browse release history](https://github.com/brawlstarswewe111-arch/eclipse-companion-releases/releases)
- Update manifest: latest.json

Version 1.1.2 repairs corrupted English and Arabic interface strings, restores the camera guide copy, adds the missing Arabic translations, and sets NASA Mission Control as the default theme. The home screen now presents one featured eclipse map and five operational rows. The 20 additional interface languages are bundled as offline chunks and load only when selected, reducing the startup JavaScript bundle to about 444.57 KB. Existing astronomy, camera, planning, learning and safety features remain included.

The in-app updater checks latest.json, verifies the APK checksum, package, version and signing certificate, then opens Android's installer. Android still requires the user to confirm installation.

SHA-256: c7c1f09f92e66a2bf892ac923aef3a369f137c6864a8d0e229821472eb8bc27c
