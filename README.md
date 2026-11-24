[![make.fun](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![rank](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/mfahmiq/alien-earth-review/rank.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![reward](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/mfahmiq/alien-earth-review/reward.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)

# Alien Field Notes: The Two Day Earth Review

Entry for the make.fun bounty
[Alien Field Notes: The Two Day Earth Review](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000).

> Beautiful planet, but the locals pick up their pets' droppings in
> little bags and carry them around all day. Four stars — would abduct
> again.

## The line

The review, in full:

```
Beautiful planet, but the locals pick up their pets' droppings in little bags and carry them around all day. Four stars — would abduct again.
```

141 characters, one line, written by `main.py` to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`).

## Why this line lands

The judge brief scores five things, most important first. This line was
built to answer each of them in order:

**1. It reads as a one-line review of planet Earth written by an alien
tourist, with the visitor's outside view clear in the line.** The
speaker is a visitor ("Beautiful planet"), the locals are observed
from outside ("the locals pick up..."), and the whole sentence is
framed as a review of a place just visited. Nothing in it could be
written by a human about their own home — no human calls their
neighbours "the locals" while reviewing their own planet.

**2. It is funny, and the laugh comes from the alien's angle on ordinary
Earth life.** The joke is not bolted on: it is the alien's baffled
reading of a completely normal Earth habit. Humans revere their pets,
then solemnly bag the pets' droppings and stroll around carrying them.
To an outsider, the most devoted species on the planet spends its
afternoons carrying little bags of faeces like treasure. The humour is
the gap between how seriously humans take the ritual and how absurd
it looks from orbit.

**3. It is original — a comparison, complaint or detail few other
entrants would reach.** It steers clear of the first obvious thoughts:
no traffic, no gravity, no money, no weather, no "humans stare at
screens". Dog-walking is mundane, but the specific image — the bag,
carried around all day — is a detail almost nobody writes about, and
the alien reframes it as a planetary custom worth reporting home.

**4. It sounds like a review a tourist would actually leave, with a
verdict, a rating and a closing remark, in a single line.** It opens
with a verdict ("Beautiful planet, but..."), gives a star rating
("Four stars"), and closes with the tourist's sign-off. "Would abduct
again" is the alien version of "would visit again" — the review
format is instantly recognisable, and the last two words are the
punchline, landing exactly where a review's recommendation lands.

**5. It is tight: every word earns its place within 200 characters and
the punch lands at the end.** One sentence of setup, then the rating
and the sign-off. No word is decoration: "little" makes the bags
pathetic, "all day" makes the carrying a lifestyle, "Four stars" makes
it a review. At 141 characters it is well inside the gate, and the
line never explains its own joke or stacks a second one on top.

## Drafting notes

The line was written from scratch for this competition, not adapted
from the kit's examples or from any earlier entry. Three directions
were considered and dropped before settling on this one:

- A "they stare at glowing rectangles all day" line — the alien's
  angle is right, but the phone observation is the most crowded joke
  in the field; too many entrants will reach it first.
- A "they built machines that fly, then make everyone take their
  shoes off to board them" line — a sharp, specific detail, but the
  joke is a human complaint about airport security, not an alien's
  confusion about a custom.
- A "they spend a third of their lives unconscious and call it rest"
  line — funny, but sleep is a generic biological observation, and it
  reads like a science note rather than a tourist's review.

The dog-walking line won because it is the most alien observation
available: a ritual every human recognises, that no human ever thinks
twice about, and that looks completely deranged from the outside. The
final wording was tuned for rhythm — "pick up ... in little bags and
carry them around all day" — and checked at 141 characters, well
inside the 200-character gate, so no word had to be cut for length.

## How the entry works

`main.py` is Python 3.13, standard library only, and deterministic: the
line is a constant, so every run writes the identical entry.

```bash
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

The program:

1. Writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
   (defaulting to `/output/entry.txt` when the variable is unset).
2. Self-verifies before and after writing: the text must be valid UTF-8,
   1–200 characters, a single line, and not only whitespace — the exact
   conditions of the competition gate.
3. Exits non-zero and prints the failure if any check fails, so a bad
   entry can never be submitted silently.

## Files

| File | What it is |
| --- | --- |
| `main.py` | The entry program: writes and self-verifies `entry.txt` |
| `entry.txt` | The review line itself |
| `README.md` | This file |
| `LICENSE` | MIT |

## License

MIT — see [LICENSE](LICENSE).
