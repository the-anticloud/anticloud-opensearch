# Ethics — OPENSEARCH

**Project:** OPENSEARCH  
**Category:** SEARCH_ENGINES  
**Upstream:** https://github.com/opensearch-project/OpenSearch.git  
**Pinned commit:** `9b3de135849573cf553083bb9b312835e1085d64`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `353b55f249801631384401427d83d1571652f8d2a0d129c8227953fa07d0756c`  
**Date:** October 2026

## Position

OPENSEARCH is packaged for offline deployment with a verifiable audit trail. The
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
