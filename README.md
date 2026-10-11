# Repolex Knowledge Graph of pytest-dev/pytest-xprocess

RDF knowledge graph data for [pytest-dev/pytest-xprocess](https://github.com/pytest-dev/pytest-xprocess), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-xprocess
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8aa836bc3e9fbdde3ddececdc0cfde0200e81054
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8aa836bc3e9fbdde3ddececdc0cfde0200e81054
│           └── chunk-001.nq.gz
├── blob
│   ├── 005a0f7ebd0a72e60eda66a331577217825fd419.nq.gz
│   ├── 023dd9473fcb9bb6c8ade0921a77fe6bfbcb7b57.nq.gz
│   ├── 03a7c497228b18caf16d8656454ab397b47c76f5.nq.gz
│   ├── 0df85f4756f905f1f360c4f5b3ab63550c741edf.nq.gz
│   ├── 1d8aa2e780228912cc9e5358e5f24579c2275c1a.nq.gz
│   ├── 2c701a9044bfb7dd8f07e7196a267b17c1bfef04.nq.gz
│   ├── 2cf440b58ee02211af46a4a5d6bc3abf0d835203.nq.gz
│   ├── 2ffa70cebacab86249067a3e85923866d4bb1987.nq.gz
│   ├── 398da03e5f3cb2d1a4319f56203afb74f3d16551.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3c844f1c6e30e7d21e6d76251c1fa1a306dc5544.nq.gz
│   ├── 415454a6603b4296acafd8560812c18f872caef1.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 6408fc0023af73c2f4a01fb7a8dbf2f683740ef2.nq.gz
│   ├── 77d938b458b58c6640ccaa20c9479678b7823c06.nq.gz
│   ├── 7a92b4a530d2183013a0d32e1879f235ee342bc4.nq.gz
│   ├── 7bb26269e80fb6f81f1bc0643c777101fc26ba79.nq.gz
│   ├── 7bd870e76dc00f484ed63aaa0449aadded8b9c31.nq.gz
│   ├── 7f20beb888ffbb92e8d1186927f37eb34ac61a53.nq.gz
│   ├── 8194406493d99ad9a42d798d61e106ad28a1df43.nq.gz
│   ├── 82eb3806c4ab23f200811f7f741b5da21a82922b.nq.gz
│   ├── 8596273b1ec39750ed6ccc7204b835d46e21166f.nq.gz
│   ├── 8fe2302e7146d1213490ea25351faee97551f62e.nq.gz
│   ├── 9a5bf6fff3e75f98e6ff446ca40461c167eeaf82.nq.gz
│   ├── 9eb2a343649883f7007c98b3160aadf68974078b.nq.gz
│   ├── a17cc37873f2912ba664f0b4f318ca8ecff71f4c.nq.gz
│   ├── b2ae8a7059a62fdc0bb0de99d55dfc43477b802b.nq.gz
│   ├── b5a957bcd5ade05a2329a8fcfcdb5e8498516d4b.nq.gz
│   ├── bad19439894f5567517297f5e8957b13eca1d434.nq.gz
│   ├── c0567850bb85f21c5a12186fbe1335969de48b85.nq.gz
│   ├── c9fd222e7d584efd86be24b35748d7d4c4d1d115.nq.gz
│   ├── cba3eafac66f366d12064d669dd4235eb0caf205.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d364d48a7837dfb4ad60bc766bcae8024bbc7af8.nq.gz
│   ├── d8c09e298991a0e777b39641de9f2f29883efd38.nq.gz
│   ├── dfb962e2199fef6ff840c4b307151450dc4ec638.nq.gz
│   ├── e1029abd90924b88d6198de373b818b273e32a8c.nq.gz
│   ├── f1615782f5c773e321454066344b38f51a1a409a.nq.gz
│   ├── f2328fb7e50218574b0cc94e3c6967a81fa3dfa3.nq.gz
│   ├── fefa40d5f6188617cfc008b6ba9f0e8ea46c725d.nq.gz
│   ├── ff33b8f7ca0b1c05bb0bdc546aa760c8e78757be.nq.gz
│   └── ffe59abfce6e641e3e6c12f3b9d47deb4087d9da.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8aa836bc3e9fbdde3ddececdc0cfde0200e81054.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[pytest-dev/pytest-xprocess](https://github.com/pytest-dev/pytest-xprocess)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
