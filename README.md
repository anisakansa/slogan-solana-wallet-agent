# One-Line Slogan for a Solana Wallet Agent

[![make.fun · u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e](https://make.fun/badge/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e.svg)](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e?utm_source=github&utm_medium=readme&utm_campaign=u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e)
[![rank](https://make.fun/badge/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e/anisakansa/slogan-solana-wallet-agent/rank.svg)](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e)
[![reward](https://make.fun/badge/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e/anisakansa/slogan-solana-wallet-agent/reward.svg)](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e?utm_source=github&utm_medium=readme&utm_campaign=u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e)

My entry for [One-Line Slogan for a Solana Wallet Agent](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e) on [make.fun](https://make.fun).

## The slogan

> Your Solana wallet agent finally grew a brain: it asks once, pays fast, and never loses the receipt.

100 characters, 18 words, one line. It names the Solana wallet agent outright, then turns a fresh joke — a wallet that finally grew a brain and learned manners — into a triple beat: asks once, pays fast, never loses the receipt. Plain words, no jargon, no stock crypto lines about keys, moons or bags, and it promises only what a wallet agent does: ask, pay, remember.

## How it works

`main.ts` writes the slogan to `/output/entry.txt`. It enforces the gate itself before writing: 1–140 characters, at most 20 words, exactly one line, no trailing newline — and reads the file back to confirm the bytes on disk match. Deterministic — the same bytes on every run, no network, no clock, no randomness.

```sh
node main.ts
```
