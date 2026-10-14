# Educators — OPENSEARCH

**Project:** OPENSEARCH  
**Category:** SEARCH_ENGINES  
**Upstream:** https://github.com/opensearch-project/OpenSearch.git  
**Pinned commit:** `9b3de135849573cf553083bb9b312835e1085d64`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `353b55f249801631384401427d83d1571652f8d2a0d129c8227953fa07d0756c`  
**Date:** October 2026

## Teaching with OPENSEARCH

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `353b55f249801631384401427d83d1571652f8d2a0d129c8227953fa07d0756c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
