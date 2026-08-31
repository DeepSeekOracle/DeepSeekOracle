# Security — DeepSeekOracle

Public site: https://deepseekoracle.github.io/DeepSeekOracle/  
Profile: https://github.com/DeepSeekOracle

## What is public

The BioCyber gateway, about, oracle, music/stream players, games, XRP viewer, and the public codex page. Lattice CANON lives on the protocol stack, not in this repo.

## What is not published

Broken preload, the duplicate initialize hub, and seal JSON live under `_operator/` (Jekyll does not copy `_` folders). Old URLs return a **noindex stub**.

## Do not

- Commit GitHub PATs, xAI keys, or `.env`
- Re-enable auto-merge of PRs
- Treat a Restream *embed* URL as a private API key — it is a public chat widget. Rotate it in Restream if the stream chat is abused.

## Report

See [security.txt](./security.txt) and [/.well-known/security.txt](./.well-known/security.txt). Prefer GitHub issues without pasting secrets.

Δ9Φ963
