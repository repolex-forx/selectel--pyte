# Repolex Knowledge Graph of selectel/pyte

RDF knowledge graph data for [selectel/pyte](https://github.com/selectel/pyte), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download selectel/pyte
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0718fa80887dc646c2121b6706b362cc8c594032
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0718fa80887dc646c2121b6706b362cc8c594032
│           └── chunk-001.nq.gz
├── blob
│   ├── 066dcc418e0a071ab3685a7f31edfa78e45a26e3.nq.gz
│   ├── 097e0921a2238d2a4f41f8ac9b597f068ddd9297.nq.gz
│   ├── 0a0e31f2df77143df9c993f0c8584c78e2831eed.nq.gz
│   ├── 0ef768f3f6728a58b9acc82a8f24858b730de2cc.nq.gz
│   ├── 12a3e669cc1c8f59961c4e0c89f9512d99521d75.nq.gz
│   ├── 12bf30729f19ce71bbe0ce80fdf60b513f040bfc.nq.gz
│   ├── 13131943bd5429e231d2398c636c384a183e62a2.nq.gz
│   ├── 174a7b3385a00e1bfaaef929d9adbd2895dfe063.nq.gz
│   ├── 23eb357735a86f435f514e85c3cf6e12067a9229.nq.gz
│   ├── 23f78a163d05dfdc07ea515d0b818be2eee20eee.nq.gz
│   ├── 29218964a1432e7c1b92144823955551fb1bf0ea.nq.gz
│   ├── 2c2a19243580af5a9c7723de94f5a21dedebb033.nq.gz
│   ├── 30ea6e6daf5797aadb6f3dda30a814fc4937b0cb.nq.gz
│   ├── 32e613087f7e8c72d8595b64830a57444edcd118.nq.gz
│   ├── 416de94091e61e84813104b4b2d437ef34ff27e9.nq.gz
│   ├── 4d25c0393353afddecc5cfc4ffb93760d9f95afa.nq.gz
│   ├── 5cf7e1f317b96732fc5c2102cf0eedecd85e109b.nq.gz
│   ├── 5f5755dad5c0285ddd6b6426b1242bb1a55fb23b.nq.gz
│   ├── 6490783d4986bc6e7e2b716ad2c1a7c8fea52550.nq.gz
│   ├── 65c5ca88a67c30becee01c5a8816d964b03862f9.nq.gz
│   ├── 784a1be0f74ee9a07fbd4bb289e4dba00077841f.nq.gz
│   ├── 7dfd6b8a10dbea9767c00779e032e4324a4675ee.nq.gz
│   ├── 7ef3542f4e36ad9e357bf55dbbed2a9b6d385431.nq.gz
│   ├── 815124a95c62d44e83bf7840aba69ec9785d9e5b.nq.gz
│   ├── 818433ecc0e094a4db1023c68b33f24344643ad8.nq.gz
│   ├── 847cad5e43c4bcd8557278eac6cc66a0b2a53320.nq.gz
│   ├── 8f37be9f491c10064e3143a58e7a275ff484ec12.nq.gz
│   ├── 9224fc1e581e81890cc36a1ca251e8204b4f0f83.nq.gz
│   ├── 93bc7de40794ed51268a1b4e8e412d6e88d6406f.nq.gz
│   ├── 973cc1a873edd63d2e3a911f997a0f9c1442ead6.nq.gz
│   ├── a8bc6456f0c75dc0b4dae37bb8068eae8b146c20.nq.gz
│   ├── b106bcee30413f0c3e8097b2f7cbd85a0f15f590.nq.gz
│   ├── b24cb04383b5350cf52fb3551fc7203996a8c028.nq.gz
│   ├── b881419658728f2822778a7d9710b47aed9f85e3.nq.gz
│   ├── b983169150efc39ef338c8869bed4493a97ceded.nq.gz
│   ├── bb713e3ef2dc449416c16c8ddc535465e45d0796.nq.gz
│   ├── bf06475a12241350d4a9ad0d2c4d3b981afbc118.nq.gz
│   ├── c247bfcba05c2d9d731d7eb9392aec3052b2347a.nq.gz
│   ├── c8477b2e2665ea672da10318042b408351f7974c.nq.gz
│   ├── ca69d7ad2889c088b907e34556ea7a7b28857f13.nq.gz
│   ├── ce7d7a5d72100165f58170c93049bd67cbd9fbc7.nq.gz
│   ├── d13195be17f72b173019a952fa33a151b4060fdd.nq.gz
│   ├── d6c5f48c7917bae3cd89fd14a28922e380380820.nq.gz
│   ├── d757bcba133fa43868a2870b16ceab22d5b1b495.nq.gz
│   ├── d8523585ab25681ec5ffd3db58a652bd74ae5ede.nq.gz
│   ├── dcbdba52061a8fb296bf70e846911d8ea174b4ee.nq.gz
│   ├── e51035ecf91c3fd586df4a80084cc9c8d5a3476b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eda587fd2f29cd05e0deb1de2db8609e717e176e.nq.gz
│   ├── f1eff525cdd8dd1654b3adf82ba5aef33942a6af.nq.gz
│   ├── f72878007d451439f47246d08a5f23bd03fbf803.nq.gz
│   └── fc57b26bb420226580ee1b65b74f6f1c68f4b105.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0718fa80887dc646c2121b6706b362cc8c594032.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[selectel/pyte](https://github.com/selectel/pyte)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
