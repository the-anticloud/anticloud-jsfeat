# Educators — JSFEAT

**Project:** JSFEAT  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/antimatter15/jsfeat  
**Pinned commit:** `70c8a59c71913934b854f15f6f16eadd6c72db77`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dab8f3f09211b97cb5fc2ba0dd5d8a2303dc82d7a9c980c125438b4ee27188cd`  
**Date:** October 2026

## Teaching with JSFEAT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `dab8f3f09211b97cb5fc2ba0dd5d8a2303dc82d7a9c980c125438b4ee27188cd` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
