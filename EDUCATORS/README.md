# Educators — TZ_DATA

**Project:** TZ_DATA  
**Category:** CARBON_CAPTURE  
**Upstream:** see BENCH.json  
**Pinned commit:** `3232221bc55675e2788330e933347d0ae67335f8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `26e0c824912061ee62e11c2e07d42b9f343a571617c3dbb1bc173136ff344001`  
**Date:** October 2026

## Teaching with TZ_DATA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `26e0c824912061ee62e11c2e07d42b9f343a571617c3dbb1bc173136ff344001` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
