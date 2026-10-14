# Students — TZ_DATA

**Project:** TZ_DATA  
**Category:** CARBON_CAPTURE  
**Upstream:** see BENCH.json  
**Pinned commit:** `3232221bc55675e2788330e933347d0ae67335f8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `26e0c824912061ee62e11c2e07d42b9f343a571617c3dbb1bc173136ff344001`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `3232221bc55675e2788330e933347d0ae67335f8`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `26e0c824912061ee62e11c2e07d42b9f343a571617c3dbb1bc173136ff344001`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
