# Students — JSFEAT

**Project:** JSFEAT  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/antimatter15/jsfeat  
**Pinned commit:** `70c8a59c71913934b854f15f6f16eadd6c72db77`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dab8f3f09211b97cb5fc2ba0dd5d8a2303dc82d7a9c980c125438b4ee27188cd`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `70c8a59c71913934b854f15f6f16eadd6c72db77`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `dab8f3f09211b97cb5fc2ba0dd5d8a2303dc82d7a9c980c125438b4ee27188cd`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
