# Ethics — JSFEAT

**Project:** JSFEAT  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/antimatter15/jsfeat  
**Pinned commit:** `70c8a59c71913934b854f15f6f16eadd6c72db77`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dab8f3f09211b97cb5fc2ba0dd5d8a2303dc82d7a9c980c125438b4ee27188cd`  
**Date:** October 2026

## Position

JSFEAT is packaged for offline deployment with a verifiable audit trail. The
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
