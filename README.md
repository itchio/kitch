# kitch [![](http://nuts-canary.itch.ovh/badge)](https://github.com/itchio/kitch/releases/latest)

kitch is the beta version of the [itch app](https://itch.io/app). It can
be installed in parallel without conflicting with the stable version.

## Download links

  * [Download latest version](http://nuts-canary.itch.ovh/download)
  * Or, if your platform isn't detected correctly:
    * linux
      * [64-bit deb](http://nuts-canary.itch.ovh/download/deb_64) or [32-bit rpm](http://nuts-canary.itch.ovh/download/deb_32) (for Debian, Ubuntu, etc.)
      * [64-bit rpm](http://nuts-canary.itch.ovh/download/rpm_64) or [32-bit rpm](http://nuts-canary.itch.ovh/download/rpm_32) (for Fedora etc.)
      * [AUR package](https://aur.archlinux.org/packages/kitch/) (kept uptodate by CI server)
      * portable builds: [64-bit](http://nuts-canary.itch.ovh/download/linux_64) or [32-bit](http://nuts-canary.itch.ovh/download/linux_32) (for everything else)
    * [macOS 64-bit](http://nuts-canary.itch.ovh/download/mac)
    * [windows 32-bit](http://nuts-canary.itch.ovh/download/windows)

## Q & A

  * What is the canary release / kitch?
    * <https://docs.itch.ovh/itch/master/installing/canary.html>
  * Why is this repo empty / where's the source?
    * Source is here: <https://github.com/itchio/itch>
    * This repo is used to store GitHub releases for our update server
  * Why is it named kitch?
    * Because `itch_canary` and `itch-canary` kept breaking various parts of the build pipeline.
  * Why is it named canary?
    * Stole the word from Google Chrome.
    * Also, canaries let you know when a mine's about to blow up.
  * Why is kitch lagging behind master?
    * Because it's only built when someone pushes a tag like `vX.Y.Z-canary`
  * Why is kitch lagging behind stable?
    * Because there hasn't been a QA session yet after the last stable release
  * Why is it blue?
    * Because peek-a-boo and we love you.

