# Repolex Knowledge Graph of ansible-community/antsibull-fileutils

RDF knowledge graph data for [ansible-community/antsibull-fileutils](https://github.com/ansible-community/antsibull-fileutils), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/antsibull-fileutils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c98c55b82a7f4c3c725a600647346cc018f730bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c98c55b82a7f4c3c725a600647346cc018f730bf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c12bebc6339aa042b0759a37a17bc83ea1b8d5b.nq.gz
│   ├── 11f72e9fdc5429da687696227aa471a25de4491e.nq.gz
│   ├── 17339bbd10153b8b1dfbf8af843de97bb285e618.nq.gz
│   ├── 17606be09236e54e37a44c62eaa87869d71b52f3.nq.gz
│   ├── 18eb07011bc57242a067f571e0fc145240c6a75c.nq.gz
│   ├── 21ecc57c8d0f2d2781e3d317691e7971e66a958b.nq.gz
│   ├── 3582b5eb8b8f131340cd2c591a138f65d084bfe5.nq.gz
│   ├── 3d5e868432a0d6e012e5b1b197cb37c57a056279.nq.gz
│   ├── 455cab545962a5d11480c9e066281b5693bb30f7.nq.gz
│   ├── 490c3bec9ca03db721c35fd14bf009dd2d8dc1cf.nq.gz
│   ├── 4f3d3f278533d665c7c13f43587111895bd2aa55.nq.gz
│   ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
│   ├── 5f9753967cb6c8b1f4bf9623fd47fd34df4e3127.nq.gz
│   ├── 6b9cc7014c72b488532f9f113db585cb7334ae50.nq.gz
│   ├── 6c6828794db4e04720885e5bf0ecea9c50e87601.nq.gz
│   ├── 700436f5635e18bcd6d4509ea004e54cc055ef16.nq.gz
│   ├── 83535b45a3e9232044105c9e6429940a6e7f88ee.nq.gz
│   ├── 8fcdfd634b49e48fe0dcead11cc84a483e1dc1d2.nq.gz
│   ├── 9025dd1d08658bc3307ac7f2026ccafb1479958c.nq.gz
│   ├── 91c1918e7f727f022e2b0b095832b7483a0e2068.nq.gz
│   ├── a8cbed0b0d83d138eee542e0bc89ca07be7ac28c.nq.gz
│   ├── ae395880f991f42f17eeb3d8c27e9ab99e0e272c.nq.gz
│   ├── b4aaeb15545e86fac367127a5e66146dfa8077f9.nq.gz
│   ├── badbf7ff8fdb9586006e0ff149003a253f3def4d.nq.gz
│   ├── cbe5c5057180d433dbde109188c5df49c3a054a0.nq.gz
│   ├── d0714da8548540a888167d5ecccc12ef5899cd14.nq.gz
│   ├── dbfb8ab78ff974cb4ae0d25a7dce39da00962e91.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── f079ad06624a975d6cabb72feeef8466b2ebcb87.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f3668bbd84717af5693e2f7302c2c1b883eb728d.nq.gz
│   └── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c98c55b82a7f4c3c725a600647346cc018f730bf.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 40 files
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

[ansible-community/antsibull-fileutils](https://github.com/ansible-community/antsibull-fileutils)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
