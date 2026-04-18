# Repolex Knowledge Graph of testing-cabal/fixtures

RDF knowledge graph data for [testing-cabal/fixtures](https://github.com/testing-cabal/fixtures), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download testing-cabal/fixtures
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3adbfea126622307d381ee26357cbc5d00ef8c34
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3adbfea126622307d381ee26357cbc5d00ef8c34.nq.gz
│   └── repolex
│       └── 3adbfea126622307d381ee26357cbc5d00ef8c34
│           └── chunk-001.nq.gz
├── blob
│   ├── 03058ec9b38ba50402f9cf9299077c751061cb66.nq.gz
│   ├── 06c52e1eb7ae02129418e906aceae8500e241d0e.nq.gz
│   ├── 10d750dbae41151f8090137cd48689e713278092.nq.gz
│   ├── 1b1d1902b066a6e6c6172092618b017388a29cf5.nq.gz
│   ├── 1ef2e0a2d5066aad36fedc456c70e204b303f5e3.nq.gz
│   ├── 233e4a8815083a60fd2691e2a315007460b2cfe0.nq.gz
│   ├── 239d655ac29af793276539be3d92c2a415770e91.nq.gz
│   ├── 2515d1e4155539da55513854db44b0dd98232ac9.nq.gz
│   ├── 2667b77d9875b86dd53897207da4e91df068107e.nq.gz
│   ├── 28c70d81abaeaa3d8ddebaf4fdf37b85d99381c9.nq.gz
│   ├── 2df7f3a9b7adbd753cceca80bd89d9dffe1442cc.nq.gz
│   ├── 2e5ea57ef2a8e6393c5b1d67b105c861cc75ae29.nq.gz
│   ├── 35d89a7ec593ae9397a29c955bbc57a8381c4b97.nq.gz
│   ├── 3715032e2dded30acfac0acea42f5d349da7cdcc.nq.gz
│   ├── 392676f29b6eb77114048411bc381c4293f54530.nq.gz
│   ├── 3bddae943371da0f6ef4501575a4e544c7fa5b33.nq.gz
│   ├── 4ad78a347d67675a4b1129340f12dd67d6640d0a.nq.gz
│   ├── 4af02ddbcd60f333ebe752a80477e9f2d1cc440d.nq.gz
│   ├── 5634517fb0ed047b64f11b908d42633060c8d10b.nq.gz
│   ├── 5dd115925868e38ca7db39dbd714ca6c366ca196.nq.gz
│   ├── 5fcd02450abf25aa865aabbcec03666085211fc2.nq.gz
│   ├── 614b8e629647d3a6feb8f731487eae8b3a580797.nq.gz
│   ├── 62954fff5a0762d093d9e2d0972357ebd88c8bfe.nq.gz
│   ├── 6ef1c8dcca75ecc25fee09263549dad77548359b.nq.gz
│   ├── 70f3c19789b2e16764da069978554bc7e7b4a1c2.nq.gz
│   ├── 716caa4608c7dcaf830cffe25398393e43b06476.nq.gz
│   ├── 723b28789b1e345d7c995e95d139d464dfc73651.nq.gz
│   ├── 7261efa0c7f15b2738c6d02f46e527915df49ace.nq.gz
│   ├── 72d895d89dbed7ad540ad33977f35d584c4b2804.nq.gz
│   ├── 784cd8e13e6faad0aeb5cc8d5c74c773773abcef.nq.gz
│   ├── 7b450fcc64afe017d944349b65668383c3bb4340.nq.gz
│   ├── 7c09a9d5e31a156739599ead2ba289ff91fab712.nq.gz
│   ├── 8044915ab979d85c88168a2aff223fa39d9ccdb0.nq.gz
│   ├── 8a9828fe7b4297d10f8cef70a5de5bef9d1ba1c8.nq.gz
│   ├── 8b4d1fbe4db393895a18d86b9823130737384229.nq.gz
│   ├── 8c103600296cf6b42efd5c8843750c3759ff5555.nq.gz
│   ├── 8f0be65bab23d3ada4699955b69c57f401dbc269.nq.gz
│   ├── 9182f822afcdf38d1103f54daeffa56240a7b502.nq.gz
│   ├── 97c4cb63d9ca6209e9fc03af733ad2296a3407fa.nq.gz
│   ├── 984afbbd4fe2e343d1a403232a351af619480b62.nq.gz
│   ├── a31591aa5b567d4422075dfb08deab7706f7bdde.nq.gz
│   ├── acfe51952f71731907a76ac51e08ca4dd3862093.nq.gz
│   ├── ad7030f889aaf57073ec1608ad7fb109e86f7009.nq.gz
│   ├── c109e3b91dcd76c4103f89c8181bad6e711e3634.nq.gz
│   ├── c120aa33be654981dea572dc7b4c44e476b3f0c2.nq.gz
│   ├── c186f4b21ae9f98bc5ac4cc1560a083eb2add30f.nq.gz
│   ├── c24e9560a7be4b784a0b1898556807c98b12a909.nq.gz
│   ├── c9d1ca1899946bd2a32ee3fe1f87f5d2c402c222.nq.gz
│   ├── cfbf56951e00b5e7a7743cbd37fc1863a7e78c57.nq.gz
│   ├── d01735fdbfa268c0b35590117693f06cae77868f.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── e0fc708a9992205f462123a9cf6865d6c511ae67.nq.gz
│   ├── e128adc0fb1282852ccbb53639eff55d9a0c1026.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── f5e14b3bf1530aab4a9c876eb3e11cbd33386ad2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 3adbfea126622307d381ee26357cbc5d00ef8c34.nq.gz
├── filetree
│   └── 3adbfea126622307d381ee26357cbc5d00ef8c34.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 65 files
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

## Source repository

[testing-cabal/fixtures](https://github.com/testing-cabal/fixtures)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
