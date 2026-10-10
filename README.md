# Repolex Knowledge Graph of agronholm/mqttproto

RDF knowledge graph data for [agronholm/mqttproto](https://github.com/agronholm/mqttproto), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/mqttproto
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2c416ad1d17b4e0aa0e945fb147e57aa63acdfb9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2c416ad1d17b4e0aa0e945fb147e57aa63acdfb9
│           └── chunk-001.nq.gz
├── blob
│   ├── 04cca641e70bcd81b985b634ab60fe42ba141583.nq.gz
│   ├── 0a74a5afc3c7e8279dc1fcd4eac58c58b8eadd34.nq.gz
│   ├── 0fccb06e8e3e34f997aef2f30da807cd1d922be5.nq.gz
│   ├── 12c822b12a8c06ec9f55c63130f35438bdb8f942.nq.gz
│   ├── 18d3c067d5932298a62b0acbfb35be4713c93368.nq.gz
│   ├── 1aa36f9264f27ab50380a40ad4beb13eac7c87bc.nq.gz
│   ├── 269f481f87f14ad2e8df76d0d8766750de87ae1c.nq.gz
│   ├── 2960e8f7f3039940c674c1c99be2513e6d9e0340.nq.gz
│   ├── 2a655a63a6b85ceea1b4ad05b6c03ef0582536c1.nq.gz
│   ├── 2c965b714de201e4d8c1f03c1661e040bc0bc444.nq.gz
│   ├── 2caf1aa20faa2d83e184d9da4ef46b26bb1a6a63.nq.gz
│   ├── 30c9b6a260ca0b4d559b65351435f240c74e8f88.nq.gz
│   ├── 30ecae8863dbd756d6b1633535814b66b6dc0f16.nq.gz
│   ├── 390eb0f087532b7d7d098935ff8c23882136e17a.nq.gz
│   ├── 3fff4a8a634bfdc904213d624cc41ea452fb47eb.nq.gz
│   ├── 48ac4e1dc57fc0d2d6718a8fab56c98bfdff35d3.nq.gz
│   ├── 4a37819f576278002b75a3edbfea485eefbeafb5.nq.gz
│   ├── 4dd1af645264c4622fab36fb6cb7fef26b298e1d.nq.gz
│   ├── 5cfafe9ddeb375f75bba88665985ad5fcb3ae88b.nq.gz
│   ├── 5dcbbc7c7ec3ecbde90a7b3edd2730c93714a2fe.nq.gz
│   ├── 6fd25035ca1370be5eacd40b4f9182e23e1d837a.nq.gz
│   ├── 70752c8b06c39fa87a1f2af7e16d533b991c11a9.nq.gz
│   ├── 80c29f331c6b60732261a996aea019c835c9385c.nq.gz
│   ├── 8386301a07f74622588772700b4c489eaf3e364c.nq.gz
│   ├── 857eac05df02004f397697c0596ffec7ad7c3d30.nq.gz
│   ├── 8b1dd39982aaf54220f0c684d37ec1f2d49ed7de.nq.gz
│   ├── 8ba0002e3e271e851777c19f4776501d0272e1e2.nq.gz
│   ├── 8d7181a401b4b4225e7a5c28a3411c078aefe74b.nq.gz
│   ├── 90e878af8ccb68db000ae1ff88f67fe150a9d8cf.nq.gz
│   ├── 92bbd0d445b0f489b264ade2230614284fbff4af.nq.gz
│   ├── 9722b9020864b55b37c27e66d05e63c2b0e41277.nq.gz
│   ├── 9bc9bef0f8ba5b01d8b63e00a54f88b25048cbd0.nq.gz
│   ├── 9bf1f18a1ac3ea08bb5439263a076859174e8652.nq.gz
│   ├── 9eebfb70d3201232c0ced601048581659e161116.nq.gz
│   ├── a0554612e78ed41e1c364fbd53ad18ca0343634d.nq.gz
│   ├── a18bafe28c4c7d53559b954ee99d476aaf103034.nq.gz
│   ├── b0d38e533e10368743694f770d8b537ca73890f1.nq.gz
│   ├── b83f3f67a572593374c102e08c65facacd69f68a.nq.gz
│   ├── b9fa2052b2642db8ba4becdd38041daf2864bc2b.nq.gz
│   ├── ba663f4d5a2b5a60db3f34327d79bb195265d5df.nq.gz
│   ├── be9a9177a1d47c62075130154508b1a14877912c.nq.gz
│   ├── c944e6576087961490eb85003e2527137cf9ef93.nq.gz
│   ├── d584000fc6213540c853668de2848185f6c6605b.nq.gz
│   ├── da6891affce681f4c818fa8fa653a463766880c6.nq.gz
│   ├── e33ef5b0cf346be96d283eec3e0f644ed4fb49bd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d8998a746c374cf6c002cf6c6b4b5005b728c7.nq.gz
│   ├── f6fb364fdfb848f12b272c0abca3a6e6b800a80e.nq.gz
│   └── f8ef451cfe4b153da1030028730a6bdbf1485af5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2c416ad1d17b4e0aa0e945fb147e57aa63acdfb9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[agronholm/mqttproto](https://github.com/agronholm/mqttproto)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
