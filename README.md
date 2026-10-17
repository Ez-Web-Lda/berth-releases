# Berth releases

This repository only holds Berth build output: the signed `Berth-X.Y.Z.zip` and `Berth-X.Y.Z.dmg` files on each GitHub Release, and the Sparkle feed `appcast.xml`. The source code lives in a private repository. Do not open pull requests here.

The app reads its updates from `https://raw.githubusercontent.com/Ez-Web-Lda/berth-releases/main/appcast.xml`. The release workflow in the source repository rewrites that file on each release.
