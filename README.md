# Frans Studiegids

An interactive French study guide for a Dutch-speaking student following
Belgian French — numbers, flashcards, and a fill-in exercise with per-answer
feedback.

**Belgian French is used on purpose:** `septante` (70) and `nonante` (90)
instead of the French `soixante-dix` and `quatre-vingt-dix`.

## What's inside

Three tabs, all in one page:

### Les nombres
Clean reference tables (French + Dutch) for the tens (10 → 100) and the
hundreds (200 → 1000), with a note about Belgian usage and the `-s` in
`quatre-vingts` / `deux cents`.

### Flashcards
All 19 numbers as flipping cards: the number on the front, `septante /
zeventig` on the back. Shuffle, previous/next, counter and progress bar
included.

Keyboard shortcuts: `←` / `→` navigate, `Space` flips, `S` shuffles.

### Invuloefening
Ten fill-in sentences practising the present tense of **avoir**, **être** and
**s'appeler**:

| # | Zin | Antwoord |
| --- | --- | --- |
| 1 | J'___ 15 ans. | `ai` |
| 2 | Tu ___ un frère ? | `as` |
| 3 | Il ___ un chien. | `a` |
| 4 | Nous ___ une grande famille. | `avons` |
| 5 | Je ___ français. | `suis` |
| 6 | Tu ___ à l'école ? | `es` |
| 7 | Elle ___ ma sœur. | `est` |
| 8 | Nous ___ des jumeaux. | `sommes` |
| 9 | Ils ___ à Asse. | `sont` |
| 10 | Je m'___ Darius. | `appelle` |

**Check Answers** grades every input (case-insensitive, spaces trimmed) and
shows detailed feedback under each one:

- **Correct:** green border + *"Goed gedaan!"*
- **Wrong:** red border, a short shake, and the full correction —
  *"Fout. Het juiste antwoord is: `as`. Uitleg: Bij 'tu' gebruik je 'as' van
  het werkwoord avoir."*

A score pill shows `x / 10 correct` and turns green for a perfect score.
**Opnieuw** clears all answers and feedback, and `Enter` in any field checks
the exercise.

**Accent Helper:** a toolbar of French accents (é è ê ë à â ç ù û î ï ô œ) that
inserts the character at the cursor in the field you last focused — so you can
type `français` on a keyboard without an AZERTY layout.

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
Inter font from Google Fonts. Works offline apart from the font. Light mode,
responsive down to phone width.

## License

Personal school project — see the repo owner.

## Author

[@Qrdz0](https://github.com/Qrdz0)
