# Frans Studiegids

An interactive French study guide for learning the numbers (les nombres),
made for a Dutch-speaking student following Belgian French.

**Belgian French is used on purpose:** `septante` (70) and `nonante` (90)
instead of the French `soixante-dix` and `quatre-vingt-dix`.

## What's inside

- **Les nombres** — clean two-column reference tables (French + Dutch) for the
  tens (10 → 100) and the hundreds (200 → 1000), with a note about Belgian
  usage and the `-s` in `quatre-vingts` / `deux cents`.
- **Flashcards** — all 19 numbers as flipping cards: number on the front,
  `septante / zeventig` on the back. Shuffle, previous/next, and progress bar
  included.

Keyboard shortcuts on the flashcards: `←` / `→` navigate, `Space` flips,
`S` shuffles.

## Run it

No build step, no dependencies:

```bash
# just open the file
start index.html

# or serve it
npx serve .
```

## Stack

Single self-contained `index.html` — vanilla HTML, CSS and JavaScript, with the
Inter font from Google Fonts. Works offline apart from the font.

## License

Personal school project — see the repo owner.

## Author

[@Qrdz0](https://github.com/Qrdz0)
