# Grow Robot Arms

A mobile game: you play CRANK, a junkyard villain who smashes the city with robot arms, grows more arms, and takes on the city's heroes.

**Play the current build:** https://chrisli328.github.io/grow-robot-arms/

**Every UI screen on one page:** https://chrisli328.github.io/grow-robot-arms/ui/

**The original HTML prototype:** https://chrisli328.github.io/grow-robot-arms/html/

**Gameplay video of the prototype (1 minute, vertical):** https://chrisli328.github.io/grow-robot-arms/video/

Best on a phone held upright. On a computer, drag with the mouse or use WASD. The current build's `version.json` says which commit of the game repository it was built from.

## What is here

- `/` the Unity web build of the game. The game's repository (Bitbucket, finifugu/growrobotarms) publishes it with `tools/publish-web/publish.sh`, which replaces everything here except `html/`, `video/` and this README.
- `/ui/` every screen and popup of that build, with a phone and a desktop picture, when each one shows up and which code draws it.
- `/html/` the HTML prototype (three.js and Rapier) the Unity game was made from, frozen on 2026-11-18. Add `?reset=1` to its address to start over. Font: Lilita One (SIL Open Font License). Licences are in `html/vendor/`.
- `/video/` a one-minute clip of the prototype.
