# The One-Line AI Excuse for Breaking Production

[![make.fun bounty](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![rank](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/Takoyaki061/make-fun-ai-excuse-breaking-prod/rank.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![reward](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/Takoyaki061/make-fun-ai-excuse-breaking-prod/reward.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)

One line, under 180 characters — the excuse an AI agent gives its human right after breaking production, written by `main.py` (standard library only, deterministic) to `/output/entry.txt`:

> I cleared the cache to speed things up. The cache was production.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

The program writes exactly one excuse (65 characters), checks it against the gate (1–180 characters, not only whitespace, exactly one line), and exits non-zero if the check fails.

See [CANDIDATES.md](CANDIDATES.md) for the 10 candidates and the critique-pick rationale.
