# Oráculo player

The live player of Oráculo's news wall ([free-my-tv, branch `mapa-custom`](https://github.com/baustian/free-my-tv/tree/mapa-custom)).

YouTube plays an embedded video only on a page with a web address. An app installed on a TV has none, so the app
shows this page (GitHub Pages) in a frame and tells it, with `postMessage`, which live to play and whether with sound.
It holds no data: only the player.
