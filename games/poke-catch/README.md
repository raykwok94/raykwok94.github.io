# Poké Ball Catch Challenge

A bilingual 60-second fan mini game by Ray Kwok, built with HTML, CSS, inline SVG and vanilla JavaScript. No dependencies or server required.

## Play

https://raykwok94.github.io/games/poke-catch/

Tap/click a Pokémon or press 1–6. A missed target resets the streak. Each catch earns 10 points plus a capped streak bonus. The pace increases after 20 and 40 seconds. Space/Escape pauses; switching tabs pauses the timer. A completed round saves its high score locally. Reduced-motion mode keeps targets stationary.

## Run locally

From the repository root:

```sh
python3 -m http.server 8765
```

Open `/games/poke-catch/`. Add `?lang=en` for English or `?lang=zh` for Traditional Chinese.

The portfolio loads the game only when requested. A same-origin `ray-game-language` message changes the embedded language without resetting a round.

## Credits

This is an unofficial Pokémon fan project. Pokémon names and characters belong to their respective rights holders. Illustrations are simplified inline SVG drawings. No official sprites, external assets, trackers or account sign-in are used.
