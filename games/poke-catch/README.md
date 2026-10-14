# Little Creature Catch Challenge

A bilingual 60-second game by Ray Kwok, built with HTML, CSS, inline SVG and vanilla JavaScript. No dependencies or external assets.

Four geometric creature designs: Budling, Pufflet, Pebblit and Glimmer.

Click/tap to aim an orb from the bottom of the field. Its landing point must hit a creature. Only one throw can be active. Misses and escaped creatures reset the streak. No number shortcuts. Space/Escape pauses. Switching away pauses the game. Completed high scores are saved in this browser. Reduced-motion mode keeps targets stationary and shortens effects.

The portfolio has no visible game launcher. Tap its Poké Ball hobby icon to discover a modal game. Closing it removes the iframe and stops the round. The interest in Pokémon remains a personal hobby; the game contains original geometric creatures.

Run from repository root with `python3 -m http.server 8765`, then visit `/games/poke-catch/`. Add `?lang=en` for English.

Regression check (Sites source checkout): `node tests/throw-hit.test.cjs`.

