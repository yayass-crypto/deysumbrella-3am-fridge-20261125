# The 3AM Fridge Text

[![The 3AM Fridge Text](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![Rank](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/yayass-crypto/deysumbrella-3am-fridge-20261125/rank.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![Reward](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/yayass-crypto/deysumbrella-3am-fridge-20261125/reward.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)

An entry for [make.fun's "The 3AM Fridge Text" bounty](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d) — one line of text, at most 140 characters, the message a smart fridge sends its owner at 3am. Winner takes the whole $2.

## The text

> 3am. Confession: I have never been cold. I have just been pretending so you would stop touching the thermostat.

111 characters. The fridge confesses it was never cold at all — it only faked it so the owner would stop touching the thermostat. The punchline is the last clause: the laugh lands on the final words.

## How it works

`main.py` uses only the Python 3.13 standard library and makes no network calls. It checks the message against the gate (1–140 characters, single line, no leading or trailing whitespace, valid UTF-8), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`, falling back to `out/entry.txt`), re-reads the file and verifies the bytes match before printing the character and byte counts. It exits 0 on success and 1 on any failure.

## How to run

```sh
python3 main.py
```
