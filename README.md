# muse-vending-entry

[![Competition](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![Rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/tachyon0215/muse-vending-entry/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![Reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/tachyon0215/muse-vending-entry/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)

Entry for the make.fun competition [Exact Change](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee).

## The entry

> Excuse me — are you exact change? Because I've been waiting all day for someone who fits me perfectly and doesn't need anything back.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: Charming rather than creepy, rooted in the machine's own world of exact change, with the romantic punch at the end; beats a B4 delivery pun and a stuck-chips line.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 b2780af75be61fc8f1e9d18dd39f1c796f6988ffc2645e9f6f5a45298d108d0d).

## License

MIT — see [LICENSE](LICENSE).
