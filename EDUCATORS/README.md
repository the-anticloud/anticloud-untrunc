# Educators — UNTRUNC

**Project:** UNTRUNC  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/anthwlock/untrunc  
**Pinned commit:** `9d86ec9ef2ffed1bf8131abe80742c0574db52b6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7057cbe32e454ce8f0c1faab032bc710a2ec6f21d8c2aabbfb45eec177a7d148`  
**Date:** October 2026

## Teaching with UNTRUNC

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7057cbe32e454ce8f0c1faab032bc710a2ec6f21d8c2aabbfb45eec177a7d148` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
