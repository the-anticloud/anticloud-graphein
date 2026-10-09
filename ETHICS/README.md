# Ethics — GRAPHEIN

**Project:** GRAPHEIN  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `8e82c8a323a21f1d14fc88bccdeed0a36bef777f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5f1c6b9f4b574314ecc775dee615d3c01a4baa98759a13d38f912a280e8f4a6b`  
**Date:** October 2026

## Position

GRAPHEIN is packaged for offline deployment with a verifiable audit trail. The
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
