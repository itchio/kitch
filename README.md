# kitch

kitch is the beta version of the [itch app](https://itch.io/app). It can
be installed in parallel without conflicting with the stable version.
## Download links

  * [Install using kitch-setup](https://itchio.itch.io/kitch-setup) (Recommended for autoupdates to kitch) 
  * [Download kitch archive directly](https://itchio.itch.io/kitch)

## Q & A

  * What is the canary release / kitch?
    * <https://docs.itch.ovh/itch/master/installing/canary.html>
  * Why is this repo empty / where's the source?
    * Source is here: <https://github.com/itchio/itch>
    * This repo is used to be for storing releases, but we now use butler to deploy releases directly to itch.io
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

