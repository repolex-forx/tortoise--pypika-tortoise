# Repolex Knowledge Graph of tortoise/pypika-tortoise

RDF knowledge graph data for [tortoise/pypika-tortoise](https://github.com/tortoise/pypika-tortoise), parsed by [repolex](https://repolex.ai).

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
rlex download tortoise/pypika-tortoise
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e175c9c1a685d060477e325e126cf0b500d88b48
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e175c9c1a685d060477e325e126cf0b500d88b48
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f4e64ad54dc9bdff6359cbaf9b26a537cebe45.nq.gz
│   ├── 102409f591df5faa9c6752e3655672ffec161b4e.nq.gz
│   ├── 12a8f69fb2fcce9f8561c60f5a3f31f49c4af9e8.nq.gz
│   ├── 15cde343930bb134bb9c9392bba4e5bc22c4a10a.nq.gz
│   ├── 18313c28172889b62cdee5473e39aad5ec1a6d7a.nq.gz
│   ├── 2268c09c5ec13fe0efb2cd3b3fab0a55315c8aca.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27a1e6a6f66dbb7438466763e57d3173089ff83e.nq.gz
│   ├── 2f7daddc706a830bb7e223059ad9db23a9fc0a44.nq.gz
│   ├── 34b885dbdbc3a3dc36b15deb87dfe9ea3efdda7f.nq.gz
│   ├── 39f4c3683c221d2f843d08dbf01d1447aa37886a.nq.gz
│   ├── 4110bf614370769ae494339fd886996f6925786c.nq.gz
│   ├── 411607251c23d34352c3c986b36761a2433f0f7c.nq.gz
│   ├── 41faefff3f00abc5cd1bca4735a2dbc880983529.nq.gz
│   ├── 453631e150ea37127aa04db7444e14690d60bd70.nq.gz
│   ├── 49e4c74fdd0941243f5eb1a91721a3191cc63c09.nq.gz
│   ├── 4b90ffec3fab90d5263957ff4d78a9761854b134.nq.gz
│   ├── 54132786936b1b7adbe304a2449678f703d7e51b.nq.gz
│   ├── 5b313203dfdd6669031e22e9c63d416dfcb48142.nq.gz
│   ├── 5d959c10bf07f09147b97a6bde729897a390bb60.nq.gz
│   ├── 6318953874592a9e2fdcaae7f508806b0d255df3.nq.gz
│   ├── 63f5e2d052ec5b69daccecff527470067e1deb68.nq.gz
│   ├── 6aeb47c0e5045d3a2bc477a71a79f170e36caa11.nq.gz
│   ├── 7adc84f2e82cd5bf034d9fc034f2660e60f781a2.nq.gz
│   ├── 834fbf79d64bc66df3759616170c3a68e4c77de1.nq.gz
│   ├── 869f043e26644ed352ddf7521f98e3ec37079ae6.nq.gz
│   ├── 86d8a68101915c27b95484243dd81d55f7dba356.nq.gz
│   ├── 88674d7a2d368193a634b1ce1c168239c9b1735e.nq.gz
│   ├── 8d2508992ef5cf8bfcf3ab4899d7d09f62e6a9ef.nq.gz
│   ├── 8f52c675392b58c047e2c38ae54a5181b56bdff2.nq.gz
│   ├── 905ead7dca70f22184fa1ce7e7c0f9ebf3c3b396.nq.gz
│   ├── 9bb470f2181d89da09fdf2d924fd75201a8b1ae6.nq.gz
│   ├── 9f27f2b3c765909c3dbe84edd72fe2ab4461912f.nq.gz
│   ├── a130e6051837567914850afe378068dee3f32628.nq.gz
│   ├── a2b798ff4e313b9e5202b807a145fba7865d4c13.nq.gz
│   ├── a900a63a93dc906f04b8f5c639d6a6fd40eb3e72.nq.gz
│   ├── ac6fc41c82ce2224ed6cae296c13ad11f0f3d958.nq.gz
│   ├── b0755f55de2054f5ec786aec25d843e2dcbbc66a.nq.gz
│   ├── b7d3d3d0b93e1e4c7a3f667774472690e94724ee.nq.gz
│   ├── babfa36ebfd5670fbfa587ddb00eeea9a0490b41.nq.gz
│   ├── bb73f43a29e31844521f96b317af0b7e4e9bbcd7.nq.gz
│   ├── bee1d6831365489c9b493f7bc60a2ddd8f3f0472.nq.gz
│   ├── bfcecb2ffd6bbd4427a30d3ffd7bf18a52d45bc2.nq.gz
│   ├── c0c81ad57acb19526dfe36b21ca2ea61f6fb04dd.nq.gz
│   ├── c1dffd30110fd2c2d8420a321f2b7e3c31b8a8f6.nq.gz
│   ├── c35fb9f387593975dec917dd006a9a381eaf7bc6.nq.gz
│   ├── c3fb49bfa0b6bebb2d9675fb12e4d069cc1c8f8f.nq.gz
│   ├── cc6ff983e3fd8c610660c7a53629fa5eefe13d90.nq.gz
│   ├── d4e3ca2a347ecae7e871f5267ac18141597189cc.nq.gz
│   ├── d7786868bef848eaa7e3ba40c69baa2397326bdc.nq.gz
│   ├── dd8047a7683cdbde5993b40bf4581188d4e7b70f.nq.gz
│   ├── e17e6b76c78902d7f37bf56cc2ccc53e486241f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75dd68eeb9e13cc75f0840b686260d63ae5f30f.nq.gz
│   ├── f09ee3f9ff24b068cb3ef5d73ca86b880aabd8ff.nq.gz
│   ├── f25adb8cf375f15a130791b5f0ae7f990c004535.nq.gz
│   ├── f2af4d4e99adcee0fbb7ea443a4eab0e3c7d1304.nq.gz
│   ├── f437af10741b0630039f79fdb6280ba044d34b94.nq.gz
│   └── f93fb354bf0e90682f8ae4d416483ed9267e5949.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e175c9c1a685d060477e325e126cf0b500d88b48.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[tortoise/pypika-tortoise](https://github.com/tortoise/pypika-tortoise)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
