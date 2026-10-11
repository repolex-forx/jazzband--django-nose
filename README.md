# Repolex Knowledge Graph of jazzband/django-nose

RDF knowledge graph data for [jazzband/django-nose](https://github.com/jazzband/django-nose), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-nose
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b90f7c96da10048eb5196612bb5cf88a82dfd4c6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b90f7c96da10048eb5196612bb5cf88a82dfd4c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a381599532da770acbdf84a2bf665db25105670.nq.gz
│   ├── 16ee71f52ae9f6ea527de63d28f0b5d012a9ba22.nq.gz
│   ├── 1aedaf3c11a607a3ba0488e19dcf5d003d9507a6.nq.gz
│   ├── 1f2805084e906262c6a39d9c2660aebb36c2d4b8.nq.gz
│   ├── 2cbd96636b081bdecd0e53d8bdae3ebfdd6926cd.nq.gz
│   ├── 2d0bf614ba8328ec68f82ab885a52681bc7ddd1d.nq.gz
│   ├── 2d51cf9ad183392bc3a5325131b78879f5573b68.nq.gz
│   ├── 2f3a0be5df045914eec3f3feedcd1ae35d0b569e.nq.gz
│   ├── 3116c0158fedc3eefded0c6cd95450b9abf0ca4a.nq.gz
│   ├── 38edfd5d9fcaf406352e155ac286a9bb4da1bb8b.nq.gz
│   ├── 3bdd7dc21ab8a25854b5fd89f2eeae8a3af657d6.nq.gz
│   ├── 4151a22270cf2a1b75c75cc597c6878f99b07a1e.nq.gz
│   ├── 42f836aee257b086b3aa642d40306932d311df3b.nq.gz
│   ├── 488fadb2430c4def6f69310ddce090a1aac0b4f1.nq.gz
│   ├── 55311206ed273d6d9ef0bdbe07dad21d6fd57551.nq.gz
│   ├── 553a5f23627b3f0285286174e9b0f8964d8b8210.nq.gz
│   ├── 5ec4f95d7325e44323b843e833b49f633cf1cc23.nq.gz
│   ├── 61edcac64fec088a9063060f319b2a5b98175cd3.nq.gz
│   ├── 63b4b38932a3773e721404ebe5be4892d6b9a51e.nq.gz
│   ├── 649e5403bf7a4fa9de065a52b3021061788e1dbc.nq.gz
│   ├── 67be1fe7301d7ebce373dc8a350ed5efbd5abf9a.nq.gz
│   ├── 6d457661ae62a32e8aae9e48fb550834eda5cf2e.nq.gz
│   ├── 7093beb92395c5dfd63ef8db862ff0b710c96a83.nq.gz
│   ├── 7369c0595b43c0291074fccac11d85964952c4c6.nq.gz
│   ├── 768d09b28540c26ce5e6ba9c11a6effd2e24d6f0.nq.gz
│   ├── 7cb0d5a81daebc273cb9a10727a53cf5843a2303.nq.gz
│   ├── 7ed6fd68b47aa45eac99e813c7417b7d9cfc3281.nq.gz
│   ├── 83dcc8e635240c560992451154c8dc1c1724f6ad.nq.gz
│   ├── 895c0fe7fcf71dcb3edb9f983e84ee4d69723dde.nq.gz
│   ├── 895dfa6b95cf573a26eada638c726852afa5b5de.nq.gz
│   ├── 90b2ad06d166a8fed96e6fa4d255de1e43fef2b5.nq.gz
│   ├── 9667ad7a8896c6a616dfa59c2a2375d8c30f8178.nq.gz
│   ├── 97c798f8aeedd89207e1216519e8903090c68b68.nq.gz
│   ├── 9fca92a77d88fa615f06b622568a0690f9b59e26.nq.gz
│   ├── a2b686ce5dc6ba9c6b5b8b83eec0cbfb58e21c19.nq.gz
│   ├── a36cdede2c3deb58c2bb83c244b9ffcced638d83.nq.gz
│   ├── ad0b4194e5b160c0929b716f247876526d8ab87d.nq.gz
│   ├── ad3dbc737dba48a070178c6b379aa9b97a8b9d15.nq.gz
│   ├── ae8ba4214aa6fcdb99bf747e1a3bd800a5299c17.nq.gz
│   ├── b2af0781f92568ad8b47ca9aedfec9c62d7887b0.nq.gz
│   ├── b2c81311d2bfa155361989ed44dbecb0e0fe8d0b.nq.gz
│   ├── bb1e861d9b2f6b933d6f41ee4c96c710383b3e4a.nq.gz
│   ├── c640f65c40b08f6a23694debaddc873a1c7ca88c.nq.gz
│   ├── cc42e5b18826caf141ee52423828b92d05c64ae6.nq.gz
│   ├── d732e41056d3582e3300bfe95a167f31925a863f.nq.gz
│   ├── d89e6712d356beb3362bf5021b430e43655564ef.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73b91c582b84d65dbc4bcc030f4771bcdfec865.nq.gz
│   ├── ea8cb6c91ffb3f93a9aa87923fb2123046e6f8ac.nq.gz
│   ├── ea9da7b10a51ee0d3edcc803e49249d871625183.nq.gz
│   ├── ee1d4c2db311a1d74bd7fc5b78374655ab22268c.nq.gz
│   └── ff75e2c0f9e319bbbd7042d26020f52ecbc94b62.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b90f7c96da10048eb5196612bb5cf88a82dfd4c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[jazzband/django-nose](https://github.com/jazzband/django-nose)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
