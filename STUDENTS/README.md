# Students — UNTRUNC

**Project:** UNTRUNC  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/anthwlock/untrunc  
**Pinned commit:** `9d86ec9ef2ffed1bf8131abe80742c0574db52b6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7057cbe32e454ce8f0c1faab032bc710a2ec6f21d8c2aabbfb45eec177a7d148`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `9d86ec9ef2ffed1bf8131abe80742c0574db52b6`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `7057cbe32e454ce8f0c1faab032bc710a2ec6f21d8c2aabbfb45eec177a7d148`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
