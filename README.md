# Repolex Knowledge Graph of dask/zict

RDF knowledge graph data for [dask/zict](https://github.com/dask/zict), parsed by [repolex](https://repolex.ai).

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
rlex download dask/zict
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7e5dafedcf016a4ac61286badbf1f8da3741d2d3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7e5dafedcf016a4ac61286badbf1f8da3741d2d3
│           └── chunk-001.nq.gz
├── blob
│   ├── 02324b1a42c268e423d7188dbef84e17c7c906c0.nq.gz
│   ├── 19bbf447f70af66a80597953a307ec44f18c5a3d.nq.gz
│   ├── 1a7899fb855e08f008b045d17bf98dfb0ed9e1cb.nq.gz
│   ├── 1bc2065f7bdeb22c1ac276aa9a8411812072605e.nq.gz
│   ├── 258ac5fa5db878f24b2c69ccecc5817709b2b540.nq.gz
│   ├── 2641f4552507bab811326e5fb18c4c01568c349f.nq.gz
│   ├── 2cfaa12df505bbab475138a64d3f6a163d979ed9.nq.gz
│   ├── 34732302b71d75512ec51eaa66a5fba91e520a6a.nq.gz
│   ├── 395e7f5b121a4ce6d8ba6df35a6c9848027a9c97.nq.gz
│   ├── 3fb6e8ca36c745ae9cd986ba70fbc9671efd9932.nq.gz
│   ├── 4414fcf416fa592585e64991428cc834d419c1a0.nq.gz
│   ├── 47af8f7589e3862af6829a6381fc3610071a96f3.nq.gz
│   ├── 49ee47edd7608ffc6aac79137f7cf46c70b510bf.nq.gz
│   ├── 4ac4e3fa3ad1074a53b60f74e160f120eb7c455a.nq.gz
│   ├── 4b6080ea49ddca0e34cbbdb15cd0c8519989e402.nq.gz
│   ├── 4d7a2b80b02dea2c0358764bd36528ac2a4e679f.nq.gz
│   ├── 4db649c823bc214c714e0bae0348155d2c8f6711.nq.gz
│   ├── 5165faf114a93337c5091be4121406bdcf6b1e33.nq.gz
│   ├── 5a18152d8cae6b8f6d8619a89b5a7fcd9c95de91.nq.gz
│   ├── 5a233b19b730fe24697e25df884e22f40fb86ae2.nq.gz
│   ├── 60564daf289ac9cd1a24cdfafc6caabe04b7d3af.nq.gz
│   ├── 63d25e4970fe8c7ba8311bf71a97d038a6d528e9.nq.gz
│   ├── 6769b79fc7d48d7e967ba6ca1abfc34b12c483a7.nq.gz
│   ├── 6981f353e898077f5f7ff40440aae8092d032e11.nq.gz
│   ├── 6f53d5034ab42ccf8a68b2d5de6ee9b38ffd6597.nq.gz
│   ├── 70c61e6de8ff942f27bea943581636835a77aa5d.nq.gz
│   ├── 71b1005c5ba0318fd9f04bd2a441b703ff099235.nq.gz
│   ├── 729f2dc8930ca3ff6f485eb4b09d3993ac5e77f5.nq.gz
│   ├── 72a843da6cbecc336cc53d79a753de60e548c9f8.nq.gz
│   ├── 9da41f5b40c8cd21d5c8a723adb8494771228586.nq.gz
│   ├── a2954e3184d712187766018da8c9007e86d424a7.nq.gz
│   ├── aa4281f79e0fec03bc788ecf9fc5344677ad4111.nq.gz
│   ├── afa43d1efd9fed8a411c7dfed74ca8c395b91320.nq.gz
│   ├── b11140c8dfde5b95910bd3c102e4cf0272e1c08f.nq.gz
│   ├── b5d23bdd3c8c73117bd6a57df764b3dcb33b019c.nq.gz
│   ├── beda28e821662c8d9fdefee034d83a5d75f9c023.nq.gz
│   ├── bf6168db5ba1d673eee0b70b4e37df98cfa41a17.nq.gz
│   ├── c3f8b428fb24edea716b77109944c9bbef874436.nq.gz
│   ├── c5d470e40497d095a37cb2c657b73840c4306e7b.nq.gz
│   ├── d6e8dfa9a524aca6276f77dcddc6be1cbdc20e96.nq.gz
│   ├── df9181594c87dc77fbc123af9c786efa2c432208.nq.gz
│   ├── e3bc41b388bf5d92f9d8612dd88b30fecd94afbe.nq.gz
│   ├── e5693d1c784ac08ab291f0c0baaa75c3a1167f13.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f30b1e4c76276c389e6dbd04b345106eae315402.nq.gz
│   ├── f3dad4c43e5b89212910b1a67a40e95132ba9cb2.nq.gz
│   ├── f6becef0617decb9f893a68f93aea4f2e8af5c5f.nq.gz
│   ├── f81f66789e4698b6a031a6785c5e2f46fe62fdbc.nq.gz
│   └── fafb3ef5670618e2ce47b2cadd16e149f2a75f62.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7e5dafedcf016a4ac61286badbf1f8da3741d2d3.nq.gz
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

[dask/zict](https://github.com/dask/zict)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
