### Security researcher

Binary & protocol reverse engineering · kernel/driver attack-surface auditing · mobile app anti-tamper analysis. Ex-crawler-engineer, full-time independent researcher.

**Disclosures**
- shairport-sync — 4 pre-auth heap-overflow vulnerabilities in the bundled Hammerton ALAC decoder & AirPlay 2 pair-list formatting (CVSS 7.1–8.8, published GHSAs)
- CVE-2026-69973 (Microsoft) — path traversal in Windows in-box libarchive (discovered via fork-diff against upstream)
- OWL / omdrop-owl — remote pre-auth stack overflow in A-MSDU receive path; confirmed & fixed, credited (@memoriaru) — CVE pending via GHSA, CNVD-C-2026-649159
- Apple Product Security — 3 reports under review
- Microsoft MSRC — 4 additional reports under review
- CNVD — 4 reports (1 upstream-confirmed & fixed)

**Open source**
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — RFC #28248: MoE expert cache, decode +84%, bit-exact verified

**Current research**
- macOS/iOS kernel attack-surface audit (IOKit UserClient systematic auditing)
- WebKit JSC differential testbed · V8 embedder attack surface (V8CTF)
- Hardware-enabled attacks (RP2350 malicious USB peripherals)
- AWDL / proximity-protocol security

**Principles**
- Deterministic evidence: same input, same bytes, every time.
- Client photos never leave the machine. Reports never leak details early.
