# Independent Insurance — RHINO_INSIDE

**Project:** RHINO_INSIDE  
**Category:** ARCHITECTURAL_DESIGN  
**Upstream:** https://github.com/mcneel/rhino.inside  
**Pinned commit:** `69c582bf7f10735b27ba07afd41e6a70b7a7534f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7a11af7231fadbde133dec2a2b29ea94b1d38c3848a86b3a0717abeafd30bd09`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | RHINO_INSIDE with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `7a11af7231fadbde133dec2a2b29ea94b1d38c3848a86b3a0717abeafd30bd09`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
