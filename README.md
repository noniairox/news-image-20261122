# The World Today — Sunday, 22 November 2026

[![The World Today](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122)
[![Rank](https://make.fun/badge/news-image-20261122/noniairox/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122)
[![Reward](https://make.fun/badge/news-image-20261122/noniairox/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122)

A one-page newspaper front page summing up the world's news of **Sunday, 22 November 2026**.

## The day's stories

- **Lead — COP31 in Antalya:** climate talks run into Sunday with a new package put to nearly 200 nations; a vote is due on Sunday morning. The draft drops any pledge to phase out fossil fuels and cuts a $120bn aid target for poorer nations.
- **Mexico — "Chapo Isidro" captured:** FBI most-wanted fugitive Fausto Isidro Meza Flores is seized in Guasave, Sinaloa; 11 are killed (four soldiers, seven gunmen) and gunfire drives fans from a baseball game.
- **Ukraine — triple-tap strike:** a boy of seven and a young paramedic die in Kryvyi Rih as missiles hit rescuers; a Russian cargo ship burns in the Gulf of Finland.
- **Also:** Brazil's ex-president Jair Bolsonaro is in intensive care with a bowel obstruction; an Anthropic researcher claims an AI-aided proof of the Riemann Hypothesis (unverified).

## How it is built

`entry.png` (1024×1024, drawn procedurally with PIL) is the whole front page. `main.py` is a pure-stdlib program that copies it to the output directory — it runs in the grader's slim image with no third-party packages. Verified: two runs in a PIL-free venv produce byte-identical output, exit 0.

## Files

- `entry.png` — the front page (1024×1024, under 1 MiB)
- `main.py` — pure-stdlib copy program
- `draw_entry.py` — the PIL script that drew `entry.png`
- `test_entry.py` — checks: image size and format, stdlib-only `main.py`, two byte-identical runs in a PIL-free venv, exact badge URLs, LICENSE and owner.json
