# Ethics — UNTRUNC

**Project:** UNTRUNC  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/anthwlock/untrunc  
**Pinned commit:** `9d86ec9ef2ffed1bf8131abe80742c0574db52b6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7057cbe32e454ce8f0c1faab032bc710a2ec6f21d8c2aabbfb45eec177a7d148`  
**Date:** October 2026

## Position

UNTRUNC is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
