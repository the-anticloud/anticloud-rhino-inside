# Educators — RHINO_INSIDE

**Project:** RHINO_INSIDE  
**Category:** ARCHITECTURAL_DESIGN  
**Upstream:** https://github.com/mcneel/rhino.inside  
**Pinned commit:** `69c582bf7f10735b27ba07afd41e6a70b7a7534f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7a11af7231fadbde133dec2a2b29ea94b1d38c3848a86b3a0717abeafd30bd09`  
**Date:** October 2026

## Teaching with RHINO_INSIDE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7a11af7231fadbde133dec2a2b29ea94b1d38c3848a86b3a0717abeafd30bd09` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
