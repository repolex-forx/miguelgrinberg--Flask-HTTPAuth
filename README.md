# Repolex Knowledge Graph of miguelgrinberg/Flask-HTTPAuth

RDF knowledge graph data for [miguelgrinberg/Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth), parsed by [repolex](https://repolex.ai).

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
rlex download miguelgrinberg/Flask-HTTPAuth
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9ff38c687513d7395764bc66ffd47350d4447687
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9ff38c687513d7395764bc66ffd47350d4447687
│           └── chunk-001.nq.gz
├── blob
│   ├── 06c6939ac2e31fe7ee813b2adb39231bb8df6307.nq.gz
│   ├── 07c392100ab95825a9fc02e4dbf28697d2c60137.nq.gz
│   ├── 0900d356895adb5d22e4ca5571948f7a8e5dfea7.nq.gz
│   ├── 10dd5123f09ac5e739bbc1f760ce5d6b798a83e5.nq.gz
│   ├── 18c720f804c6f034cdb1ee02a616cc1e271a4007.nq.gz
│   ├── 190a689391c9ce13de5f5c8f43de7e023e2539c5.nq.gz
│   ├── 195b4f1fc6a61e596f658e03af123c164a3c8a54.nq.gz
│   ├── 1c9701284d765fe2ceaf38edaf6d7e4a9e744561.nq.gz
│   ├── 20f9bd52df3d136de73b371f3c34d858300237dc.nq.gz
│   ├── 2448fd2665df720101cf6662b17bfdfbda3e7cc3.nq.gz
│   ├── 250f570e6e94706459402810dd05090ea476a264.nq.gz
│   ├── 2b4774c2047127d4d73412822ff4ac4a63afd9e7.nq.gz
│   ├── 2b5b058439b3c7b3f678f318f4995c4e3c640009.nq.gz
│   ├── 2e5ff60899fc17bfb47782d5786e655e349b8b46.nq.gz
│   ├── 2fac03dd4547a08780942871705865b1c06486f3.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 459d46f6dbdb7a925e287dbcd8abdfe83be20595.nq.gz
│   ├── 4efa027a81b6e393d8a891660f2310221396a6f6.nq.gz
│   ├── 51f1c31a1d7824925767de0401acd3c55ae3ec62.nq.gz
│   ├── 52d86b27ca45f9cae00a762e55efd6bc41ed90fc.nq.gz
│   ├── 542b462515db7875ea5813c33181870ae06edff7.nq.gz
│   ├── 5906e751b7a9c21a5c295e3779b0fbe7541c02cb.nq.gz
│   ├── 5bfb7ec7d9deda4e5b58489cff716e5fb573217f.nq.gz
│   ├── 5ef66102162c795f37f007cd28f792d837d7a4a6.nq.gz
│   ├── 6239577c663af635a72b7d38b1787635f5795a30.nq.gz
│   ├── 692b213d8e2716913998982f7c073e783ccc19fa.nq.gz
│   ├── 6a6491fb2f201f310b8188ef89febd0a5d57ca72.nq.gz
│   ├── 751aafe82afa285599afafc0ab549852f66b31eb.nq.gz
│   ├── 76377458d55d3dc8bde47f46e81b6dda7c5a9f81.nq.gz
│   ├── 7f578c2cf023f7383cb3951e595b265314cc916e.nq.gz
│   ├── 828c8cd3cbfd70000af584ae6a2ded4000289e1a.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 8f0243c1a32ef8ca0188a506b43084d6712b94fd.nq.gz
│   ├── 972fa1c2a0b55afc01422d3d74200785138e89b6.nq.gz
│   ├── 9bb7caf49b6afc29eaab4396ebc6dc983816a227.nq.gz
│   ├── 9c3f0d42d6877e3a6e87fe59f200181403b3f24b.nq.gz
│   ├── 9e2d1d14b3f555ab3cc52bbe023d2effb40ec177.nq.gz
│   ├── a34c99cc768355edd12ecf0472caa1375d52de98.nq.gz
│   ├── a6f580238ac4feda83e5110f5e34fb1c81f34a6f.nq.gz
│   ├── ad6e64cf415bded7f337c12ab76a2b34674ab2da.nq.gz
│   ├── b032eff9313689ada1a9a29e3cc87c9e3dd980a0.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b56d7bcd1d87d8c4bf485c253ab3ba0078cc6109.nq.gz
│   ├── bbd4465b03bc1c2ce88b0aba342cf5c9e46667a0.nq.gz
│   ├── c0a2facb9e7af276aea3cb4c91dc526eee2c05aa.nq.gz
│   ├── c1a83cf0077ff680f8a040165942e985944a0a5d.nq.gz
│   ├── d17ea55fe850b184c0f2d0250623c3c8eeb7b8cc.nq.gz
│   ├── e2d21430a2d7575dca5ea09edd4f6bd27a333ba4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── fdb0b0da72f59f6d090b167a12e4a30c761dbce1.nq.gz
│   └── fe2141c565e6976b6a2a5b73f318ad7c6dc3d58b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9ff38c687513d7395764bc66ffd47350d4447687.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[miguelgrinberg/Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
