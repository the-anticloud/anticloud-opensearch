# OPENSEARCH

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-search_engines-lightgrey)

> Anticloud-hardened packaging of the upstream project `OPENSEARCH` in category **SEARCH ENGINES**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SEARCH ENGINES · **Upstream:** https://github.com/opensearch-project/OpenSearch · **Upstream pin:** `5c53018370b6f069ccd871564122ce8c35a520ba` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<a href="https://opensearch.org/">
  <img src="https://opensearch.org/assets/img/opensearch-logo-themed.svg" height="64px">
</a>

[![License](https://img.shields.io/badge/license-Apache%20v2-blue.svg)](https://github.com/opensearch-project/OpenSearch/blob/main/LICENSE.txt)
[![LFX Health Score](https://insights.linuxfoundation.org/api/badge/health-score?project=opensearch-foundation)](https://insights.linuxfoundation.org/project/opensearch-foundation)
[![LFX Active Contributors](https://insights.linuxfoundation.org/api/badge/active-contributors?project=opensearch-foundation)](https://insights.linuxfoundation.org/project/opensearch-foundation)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/6556/badge)](https://www.bestpractices.dev/projects/6556)
[![Code Coverage](https://codecov.io/gh/opensearch-project/OpenSearch/branch/main/graph/badge.svg)](https://codecov.io/gh/opensearch-project/OpenSearch)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/opensearch-project/OpenSearch?sort=semver)
[![Linkedin](https://img.shields.io/badge/Follow-Linkedin-blue)](https://www.linkedin.com/company/opensearch-project)

- [Welcome!](#welcome)
- [Project Resources](#project-resources)
- [Code of Conduct](#code-of-conduct)
- [Security](#security)
- [License](#license)
- [Copyright](#copyright)
- [Trademark](#trademark)

## Welcome!

OpenSearch is an open-source, enterprise-grade search and observability suite that brings order to unstructured data at scale.

## Project Resources

* [Project Website](https://opensearch.org/)
* [Downloads](https://opensearch.org/downloads/)
* [Documentation](https://docs.opensearch.org/)
* Need help? Try [Forums](https://discuss.opendistrocommunity.dev/) or [Slack](https://opensearch.org/slack/)
* [Contributing to OpenSearch](CONTRIBUTING.md)
* [Maintainer Responsibilities](MAINTAINERS.md)
* [Release Management](RELEASING.md)
* [Admin Responsibilities](ADMINS.md)
* [Testing](TESTING.md)
* [Security](SECURITY.md)

## Code of Conduct

The project's [Code of Conduct](CODE_OF_CONDUCT.md) outlines our expectations for all participants in our community, based on the [OpenSearch Code of Conduct](https://opensearch.org/code-of-conduct/). Please contact [conduct@opensearch.foundation](mailto:conduct@opensearch.foundation) with any additional questions or comments.

## Security
If you discover a potential security issue in this project we ask that you notify OpenSearch Security directly via email to security@opensearch.org. Please do **not** create a public GitHub issue.

## License

This project is licensed under the [Apache v2.0 License](LICENSE.txt).

## Copyright

Copyright OpenSearch Contributors. See [NOTICE](NOTICE.txt) for details.

## Trademark

OpenSearch is a registered trademark of LF Projects, LLC.

OpenSearch includes certain Apache-licensed Elasticsearch code from Elasticsearch B.V. and other source code. Elasticsearch B.V. is not the source of that other source code. ELASTICSEARCH is a registered trademark of Elasticsearch B.V.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Java / Gradle** (manifests: build.gradle; scanned in UPSTREAM_CLONE)
- Top-level source layout: `benchmarks/`, `buildSrc/`, `client/`, `dev-tools/`, `distribution/`, `doc-tools/`, `formal-models/`, `gradle/`, `libs/`, `licenses/`, `modules/`, `plugins/`
- Snapshot size: **2576 files**, **272379 lines of code** (measured; see Benchmarks)
- Primary languages: `.java` (1892), `.txt` (155), `.gradle` (146), `.sha1` (115), `(none)` (66), `.properties` (40)
- Upstream commit pinned for this packaging: `5c53018370b6f069ccd871564122ce8c35a520ba`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
mvn package        # or: ./gradlew build
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

Browse the snapshot layout listed under What This Project Does and follow the upstream run instructions for the detected ecosystem (Java / Gradle).

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![LFX Active Contributors](https://insights.linuxfoundation.org/api/badge/active-contributors?project=opensearch-foundation)](https://insights.linuxfoundation.org/project/opensearch-foundation)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/6556/badge)](https://www.bestpractices.dev/projects/6556)
[![Code Coverage](https://codecov.io/gh/opensearch-project/OpenSearch/branch/main/graph/badge.svg)](https://codecov.io/gh/opensearch-project/OpenSearch)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/opensearch-project/OpenSearch?sort=semver)
[![Linkedin](https://img.shields.io/badge/Follow-Linkedin-blue)](https://www.linkedin.com/company/opensearch-project)

- [Welcome!](#welcome)
- [Project Resources](#project-resources)
- [Code of Conduct](#code-of-conduct)
- [Security](#security)
- [License](#license)
- [Copyright](#copyright)
- [Trademark](#trademark)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Java / Gradle |
| Manifests detected | build.gradle |
| Files in snapshot | 2576 |
| Lines of code | 272379 |
| Dependency references | 0 |
| Upstream license | Apache-2.0 |
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

- [Contributing to OpenSearch](#contributing-to-opensearch)
- [First Things First](#first-things-first)
- [Ways to Contribute](#ways-to-contribute)
    - [Bug Reports](#bug-reports)
    - [Feature Requests](#feature-requests)
    - [Documentation Changes](#documentation-changes)
    - [Contributing Code](#contributing-code)
- [Developer Certificate of Origin](#developer-certificate-of-origin)
- [Review Process](#review-process)
    - [Tips for Success](#tips)
- [Troubleshooting Failing Builds](#troubleshooting-failing-builds)

# Contributing to OpenSearch

OpenSearch is a community project built and maintained by people just like **you**. We're glad you're interested in helping out. There are several different ways you can do it, but before we talk about that, let's talk about how to get started.

## First Things First

1. **When in doubt, open an issue** - For almost any type of contribution, the first step is opening an issue. Even if you think you already know what the solution is, writing down a description of the problem you're trying to solve will help everyone get context when they review your pull request. If it's truly a trivial change (e.g. spelling error), you can skip this step -- but as the subject says, when in doubt, [open an issue](https://github.com/opensearch-project/OpenSearch/issues).

2. **Only submit your own work**  (or work you have sufficient rights to submit) - Please make sure that any code or documentation you submit is your work or you have the rights to submit. We respect the intellectual property rights of others, and as part of contributing, we'll ask you to sign your contribution with a "Developer Certificate of Origin" (DCO) that states you have the rights to submit this work and you understand we'll use your contribution. There's more information about this topic in the [DCO section](#developer-certificate-of-origin).

## Ways to Contribute

**Please note:** OpenSearch is a fork of [Elasticsearch 7.10.2](https://github.com/elastic/elasticsearch). If you do find references to Elasticsearch (outside of attributions and copyrights!) please [open an issue](https://github.com/opensearch-project/OpenSearch/issues).

### Bug Reports

Ugh! Bugs!

A bug is when software behaves in a way that you didn't expect and the developer didn't intend. To help us understand what's going on, we first want to make sure you're working from the latest version. Please make sure you're testing against the [latest version](https://github.com/opense

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `OPENSEARCH` (category: SEARCH ENGINES)
- **Upstream URL:** https://github.com/opensearch-project/OpenSearch
- **Pinned commit (SHA):** `5c53018370b6f069ccd871564122ce8c35a520ba`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`c195cbdecff79b5019e1ea2f668f40a67534895ddabfcb33c1f2da0f28c96570`.

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

