# Pocket Arcade · صالة ألعاب الجيب

A collection of 14 browser games in **English and Arabic**: quick brain games, word and logic puzzles, an arcade game, and two live multiplayer games to play with friends.

مجموعة من 14 لعبة متصفح **بالعربية والإنجليزية**: ألعاب ذكاء سريعة، وألغاز كلمات ومنطق، ولعبة أركيد، ولعبتان جماعيتان مباشرتان للعب مع الأصدقاء.

## Play online

| Game | Link |
|---|---|
| Pocket Arcade (all games) | https://claude.ai/artifact/6cADi2YUmej2ti4PEcU1MK |
| Comet Party (multiplayer) | https://claude.ai/artifact/5YkW3XXrJTenh7RE4d6bge |
| Time Thread (multiplayer, learning) | https://claude.ai/artifact/1BgcLi9h9xsC3Wmsh4ESc6 |
| Orbit Keeper | https://claude.ai/artifact/BCmwHVig8JW1eJVe5mZk3X |

## Files

| File | What it is |
|---|---|
| `index.html` | **Pocket Arcade**, the game shelf with 11 built-in games: Dots & Boxes, Colour Clash, Pattern Recall, Odd Shade, Quick Sums, Word Scramble, Bigger or Smaller, Lock Pick, Pair Up, Number Hunt and Reflex Check |
| `comet-party.html` | **Comet Party**: steer a comet and grab sparks in 60-second rounds, live with friends using a room code |
| `time-thread.html` | **Time Thread**: place 86 historical events in order on your timeline, solo or racing friends |
| `orbit-keeper.html` | **Orbit Keeper**: turn the shield to block red shards and charge a nova |

## Run locally

No build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then go to http://localhost:8000.

Add `#ar` to any game's address to open it in Arabic, for example `time-thread.html#ar`. Each game also has an English / العربية switch.

## Notes

- **Multiplayer** (Comet Party rooms and Time Thread races) uses the live room feature of Claude artifacts, so it only works on the claude.ai links above. Opened from this repo, both games still work in solo mode with bots.
- Best scores are saved in the browser's local storage.
- Fonts load from Google Fonts. Everything else is plain HTML, CSS and JavaScript in each file.
