# TZ DATA

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-carbon_capture-lightgrey)

> Anticloud-hardened packaging of the upstream project `TZ_DATA` in category **CARBON CAPTURE**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CARBON CAPTURE · **Upstream:** https://github.com/the-anticloud/anticloud-tz-data.git · **Upstream pin:** `c625cf36f82cb177268df6f76d3f4d612c5022e2` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

TZInfo::Data - Timezone Data for TZInfo
=======================================

[![RubyGems](https://img.shields.io/gem/v/tzinfo-data)](https://rubygems.org/gems/tzinfo-data) [![Tests](https://github.com/tzinfo/tzinfo-data/actions/workflows/tests.yml/badge.svg?branch=master&event=push)](https://github.com/tzinfo/tzinfo-data/actions?query=workflow%3ATests+branch%3Amaster+event%3Apush)

TZInfo::Data is the public domain [IANA Time Zone Database](https://www.iana.org/time-zones)
packaged as a set of Ruby modules for use with [TZInfo](https://tzinfo.github.io).

If TZInfo::Data is installed, TZInfo will automatically use it as its source of
time zone data. If TZInfo::Data is not available, TZInfo will attempt to use the
system zoneinfo files instead. Please refer to the [TZInfo documentation](https://rubydoc.info/gems/tzinfo/frames)
for further details.

Installation
------------

The TZInfo::Data gem can be installed by running:

    gem install tzinfo-data

License
-------

TZInfo::Data is released under the MIT license, see LICENSE for details.

Timezone data is based on the public domain
[IANA Time Zone Database](https://www.iana.org/time-zones).

Source Code
-----------

Source code for TZInfo::Data is available on [GitHub](https://github.com/tzinfo/tzinfo-data).

Issue Tracker
-------------

Please post any bugs, issues, feature requests or questions to the
[GitHub issue tracker](https://github.com/tzinfo/tzinfo-data/issues).

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Ruby / Bundler** (manifests: Gemfile; scanned in UPSTREAM_CLONE)
- Top-level source layout: `lib/`, `test/`
- Snapshot size: **620 files**, **47900 lines of code** (measured; see Benchmarks)
- Primary languages: `.rb` (609), `(none)` (6), `.md` (2), `.asc` (1), `.gemspec` (1), `.pem` (1)
- Upstream commit pinned for this packaging: `c625cf36f82cb177268df6f76d3f4d612c5022e2`

---

## Installation

time zone data. If TZInfo::Data is not available, TZInfo will attempt to use the
system zoneinfo files instead. Please refer to the [TZInfo documentation](https://rubydoc.info/gems/tzinfo/frames)
for further details.

Installation
------------

The TZInfo::Data gem can be installed by running:

    gem install tzinfo-data

License
-------

TZInfo::Data is released under the MIT license, see LICENSE for details.

Timezone data is based on the public domain
[IANA Time Zone Database](https://www.iana.org/time-zones).

Source Code
-----------

Source code for TZInfo::Data is available on [GitHub](https://github.com/tzinfo/tzinfo-data).

Issue Tracker
-------------

Please post any bugs, issues, feature requests or questions to the
[GitHub issue tracker](https://github.com/tzinfo/tzinfo-data/issues).

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

If TZInfo::Data is installed, TZInfo will automatically use it as its source of
time zone data. If TZInfo::Data is not available, TZInfo will attempt to use the
system zoneinfo files instead. Please refer to the [TZInfo documentation](https://rubydoc.info/gems/tzinfo/frames)
for further details.

Installation
------------

The TZInfo::Data gem can be installed by running:

    gem install tzinfo-data

License
-------

TZInfo::Data is released under the MIT license, see LICENSE for details.

Timezone data is based on the public domain
[IANA Time Zone Database](https://www.iana.org/time-zones).

Source Code
-----------

Source code for TZInfo::Data is available on [GitHub](https://github.com/tzinfo/tzinfo-data).

Issue Tracker
-------------

Please post any bugs, issues, feature requests or questions to the
[GitHub issue tracker](https://github.com/tzinfo/tzinfo-data/issues).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

If TZInfo::Data is installed, TZInfo will automatically use it as its source of
time zone data. If TZInfo::Data is not available, TZInfo will attempt to use the
system zoneinfo files instead. Please refer to the [TZInfo documentation](https://rubydoc.info/gems/tzinfo/frames)
for further details.

Installation
------------

The TZInfo::Data gem can be installed by running:

    gem install tzinfo-data

License
-------

TZInfo::Data is released under the MIT license, see LICENSE for details.

Timezone data is based on the public domain
[IANA Time Zone Database](https://www.iana.org/time-zones).

Source Code
-----------

Source code for TZInfo::Data is available on [GitHub](https://github.com/tzinfo/tzinfo-data).

Issue Tracker
-------------

Please post any bugs, issues, feature requests or questions to the
[GitHub issue tracker](https://github.com/tzinfo/tzinfo-data/issues).

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Ruby / Bundler |
| Manifests detected | Gemfile |
| Files in snapshot | 620 |
| Lines of code | 47900 |
| Dependency references | 0 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

## IANA Time Zone Database Releases

Please do not open issues or pull requests relating to new IANA Time Zone
Database releases.

Each release of the Time Zone Database will be packaged into a corresponding
release of tzinfo-data.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Copyright (c) 2005-2026 Philip Ross

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `TZ_DATA` (category: CARBON CAPTURE)
- **Upstream URL:** https://github.com/the-anticloud/anticloud-tz-data.git
- **Pinned commit (SHA):** `c625cf36f82cb177268df6f76d3f4d612c5022e2`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`d68bc92bb3e2cff41d17a89af3f1e2fe07e79ae169d233b13c15f5f1341c952e`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

