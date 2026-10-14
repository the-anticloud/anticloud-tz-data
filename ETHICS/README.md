# Ethics — TZ_DATA

**Project:** TZ_DATA  
**Category:** CARBON_CAPTURE  
**Upstream:** see BENCH.json  
**Pinned commit:** `3232221bc55675e2788330e933347d0ae67335f8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `26e0c824912061ee62e11c2e07d42b9f343a571617c3dbb1bc173136ff344001`  
**Date:** October 2026

## Position

TZ_DATA is packaged for offline deployment with a verifiable audit trail. The
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
