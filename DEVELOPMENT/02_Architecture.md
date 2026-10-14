# Technical Architecture — TZ_DATA

**Upstream:** [https://github.com/transitionzero/tz-data](https://github.com/transitionzero/tz-data)
**License:** Apache 2.0
**Category:** CARBON_CAPTURE
**Anticloud Integration:** PAX L5 Narrow L2 General 27B + AIOSS + Offline-First

## Upstream Description

Energy transition carbon data

## Anticloud Architectural Changes

1. PAX L5 Narrow L2 General 27B local process optimization for DAC — air-gapped plant
2. AIOSS tamper-evident carbon credit audit chain (Verra/Gold Standard aligned)
3. AES-256 encryption for all monitoring and reporting data
4. Single-binary plant management system for remote deployments
5. Zero-cloud: all sensor analytics and optimization run locally
6. GPU/CPU equalizer: real-time control on embedded CPU, simulation on GPU
7. Open MRV protocol: machine-readable verification reports without third-party auditor API
8. Offline atmospheric CO2 measurement calibration pipeline

## Integration Points

- **PAX Inference Socket:** Local HTTP endpoint at `127.0.0.1:11434/v1/chat` — same OpenAI-compatible API, zero cloud
- **AIOSS Hook:** Every write operation calls `aioss_append(event, payload)` before commit
- **Encryption Layer:** All file I/O routed through `anticloud_crypto.encrypt_at_rest()`
- **Single Binary Build:** `pyinstaller anticloud_tz_data.spec` or `go build -o tz_data`

## Deployment Modes

| Mode | Hardware | Notes |
| --- | --- | --- |
| Edge CPU | Raspberry Pi 4 / Intel NUC | Full feature set, PAX on CPU |
| Desktop GPU | RTX 3060 / A10 | PAX GPU inference, <1s latency |
| Server | 2× A100 | Full batch throughput |
| Air-gapped | Any x86/ARM | Zero network dependency |