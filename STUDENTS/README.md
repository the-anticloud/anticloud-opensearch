# Students — OPENSEARCH

**Project:** OPENSEARCH  
**Category:** SEARCH_ENGINES  
**Upstream:** https://github.com/opensearch-project/OpenSearch.git  
**Pinned commit:** `9b3de135849573cf553083bb9b312835e1085d64`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `353b55f249801631384401427d83d1571652f8d2a0d129c8227953fa07d0756c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `9b3de135849573cf553083bb9b312835e1085d64`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `353b55f249801631384401427d83d1571652f8d2a0d129c8227953fa07d0756c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
