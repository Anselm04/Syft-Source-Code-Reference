# Syft — TrillionAI Engineering Reference

Research-only source archive for TrillionAI Audit. This repository is **not** an operating Syft deployment and is separate from proprietary TrillionAI product code.

## Source provenance

- Original upstream: https://github.com/anchore/syft
- Pinned upstream commit: `e543a0007a0a2a812d13815a021b7a927f9013ac`
- Pinned original Git tree: `1c21ca88902b5d95e7870f3ee703bf7bcd5b4816`
- Tracked Git tree inventory: 5,220 entries, including 3,164 file blobs (35,665,535 bytes).
- Upstream root licence: Apache License 2.0; retain original `LICENSE` and `COPYRIGHT` with all applicable component notices.
- Import destination: **repository root on `main`** (no hidden source folder or separate branch required).
- Verification status: **PENDING** until GitHub confirms the import and exact retained Git object identities.

## Import and safety

[Source-import workflow](.github/workflows/import-syft-source.yml) fetches a precise upstream revision and imports its tracked Git tree to `main`. The original upstream `README.md` becomes the default README, and this research note becomes `TRILLIONAI_REFERENCE.md`. Upstream GitHub Actions workflows are removed from the destination to prevent accidental CI execution.

The destination tree must match the original source object identities for every entry except removed GitHub Actions definitions and the added TrillionAI reference note. The remote tree is also compared against the pushed local tree.

A source snapshot does not include full upstream Git history, separately fetched dependencies, generated binaries, installed scanners, remote databases, running services or validated build/test outputs.

If GitHub push protection rejects upstream credential-shaped test fixtures, do not bypass it: document precisely excluded paths and verify the filtered tree.

## Intended TrillionAI Audit research

1. Generate and validate software bills of materials (SBOMs) from real projects.
2. Identify package ecosystem, direct/transitive dependencies, and component origin.
3. Normalise SPDX and CycloneDX evidence with versioned schemas.
4. Bind evidence and dependency inventories to exact project/build revision hashes.
5. Support source scanning with bounded execution, explicit unsupported cases and traceable results.
6. Engineer separate original Node.js/TypeScript backend adapters and Flutter audit interfaces.

Preserve original authorship and licences. No automatic deployment, paid service activation or production infrastructure usage.
