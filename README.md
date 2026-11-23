# Make the Judge Smile

make.fun bounty — prize $5, deadline 12:50 WIB WIB, 24 Nov 2026.
Bounty page: https://make.fun/bounty/u-gentle-badger-68-make-the-judge-smile-9228676d

## The entry

```
The old man at the warung slipped an extra krupuk into my bag and winked like we'd planned a heist.
```

Constraint: single line, at most 200 characters. Entry length: 99 characters, 20 words — within the limit.

## Brief (live, read 24 Nov 2026 ~06:45 WIB)

Judging: Judge model, pairwise: subject first, then warmth, surprise, one concrete detail, fresh wording.

Top-entry pattern (followed, line is original): Top patterns: 'The lady in seat three had already paid his fare', 'A mango on the doorstep' — small kindness + one concrete detail; mine is original, same shape.

## Run

```sh
python3 main.py
```

Writes `entry.txt` to `$MAKEFUN_OUTPUT_DIR` when set, otherwise to
`/output/entry.txt`. Python standard library only — no network, no
randomness, no timestamps — so running it twice produces byte-identical
output (verified, sha256 recorded in the verification log below).

## Determinism

See `VERIFY.txt` for the two-run sha256 comparison.
