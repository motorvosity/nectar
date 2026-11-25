# Nectar Run

A daily, Wordle-style typing game: visit 10 flowers, type an answer that fits the category and starts with the letter.
Rarer answers (compared with a simulated crowd) earn more nectar, and a quick answer earns a ⚡ bonus.

- `index.html` - the whole game in one file (open it, or serve it with GitHub Pages).
- `pipeline/` - the list-building pipeline (see `pipeline/README.md`). `python3 nectar.py build` regenerates the game from the seed lists;
  copy `pipeline/out/nectar-run.html` over `index.html` to ship new lists.

Daily mode is solo; the rival/party code is behind `PARTY` in the game template. Movies, Books and TV Shows are disabled until their lists grow.
