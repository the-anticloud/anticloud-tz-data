# Build and Test

**Project:** `TZ_DATA`
**Upstream:** https://github.com/transitionzero/tz-data
**License:** Apache 2.0

## Quick Start

```bash
git clone https://github.com/transitionzero/tz-data
cd tz-data
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local process optimization for DAC — air-gapped plant
2. AIOSS tamper-evident carbon credit audit chain (Verra/Gold Standard aligned)
3. AES-256 encryption for all monitoring and reporting data
4. Single-binary plant management system for remote deployments
5. Zero-cloud: all sensor analytics and optimization run locally
6. GPU/CPU equalizer: real-time control on embedded CPU, simulation on GPU
7. Open MRV protocol: machine-readable verification reports without third-party auditor API
8. Offline atmospheric CO2 measurement calibration pipeline

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Primary inference task: <5s on CPU, <1s on GPU |
| Throughput | Batch processing: >100 items/hour on single CPU server |
| Memory | <8GB RAM for standard deployment |
| Accuracy | Task-specific accuracy within 5% of cloud-API baseline |

## Build Status

Not yet measured. Run verified build and record actual figures above.
