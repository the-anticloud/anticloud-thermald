# Students — THERMALD

**Project:** THERMALD  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b8b0fabc8c32ba04bb3e4dad517b78bf4fb3d23d2eed1d67c54c49dfe2fce09a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `see BENCH.json`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b8b0fabc8c32ba04bb3e4dad517b78bf4fb3d23d2eed1d67c54c49dfe2fce09a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
