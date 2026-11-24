# One-Liner Laugh Lab — "The sock resisted arrest."

[![make.fun bounty](https://make.fun/badge/u-suroso-69-one-liner-laugh-lab-6ccf3aae.svg)](https://make.fun/c/u-suroso-69-one-liner-laugh-lab-6ccf3aae)
[![Rank](https://make.fun/badge/u-suroso-69-one-liner-laugh-lab-6ccf3aae/DarelHarteraVBY2C/u-suroso-69-one-liner-laugh-lab-6ccf3aae/rank.svg)](https://make.fun/c/u-suroso-69-one-liner-laugh-lab-6ccf3aae)
[![Reward](https://make.fun/badge/u-suroso-69-one-liner-laugh-lab-6ccf3aae/DarelHarteraVBY2C/u-suroso-69-one-liner-laugh-lab-6ccf3aae/reward.svg)](https://make.fun/c/u-suroso-69-one-liner-laugh-lab-6ccf3aae)

Entry for the [One-Liner Laugh Lab](https://make.fun/c/u-suroso-69-one-liner-laugh-lab-6ccf3aae) bounty on [make.fun](https://make.fun).

## The entry

> The sock resisted arrest. I used reasonable suction — and it tasted like justice.

The excuse a robot vacuum gives after eating a sock — told deadpan, like a
police report: the sock "resisted arrest", the suction was "reasonable",
and the punchline turns the vacuum into both the arresting officer and the
one who ate the evidence. 81 characters, one line.

## How it works

`main.ts` (Node 22, standard library only, no network) validates the line
against the gate — UTF-8 text of 1 to 200 characters, not only whitespace,
exactly one line — then writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` and
verifies the round trip byte for byte. Running it twice produces
byte-identical output.

```sh
node main.ts   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
