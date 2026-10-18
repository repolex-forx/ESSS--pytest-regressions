# Repolex Knowledge Graph of ESSS/pytest-regressions

RDF knowledge graph data for [ESSS/pytest-regressions](https://github.com/ESSS/pytest-regressions), parsed by [repolex](https://repolex.ai).

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
rlex download ESSS/pytest-regressions
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── baf5a54685f92b5f399dca7be0e445d4d586db8f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── baf5a54685f92b5f399dca7be0e445d4d586db8f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0daa7dde9c106cf8089fb65e01226959e4672ebe.nq.gz
│   ├── 13073c877bf954490eafc6ca82fa7716bcd5b360.nq.gz
│   ├── 1350b266118ccdf26597309dd744e7b7afc727a5.nq.gz
│   ├── 19d13def9ce98e30993135a0c51d51e8d5cef1d9.nq.gz
│   ├── 19f03375ce7e9595359f7e0c1a6d6372a2339eda.nq.gz
│   ├── 2251dad4fb0dd17fa01f84e98f51bc255447f3ef.nq.gz
│   ├── 24f457c8982d3980212c2b2b40aac956d0f56d1d.nq.gz
│   ├── 2a376c3b0dfcee74bdd0531ef1b2e7641c99ffa1.nq.gz
│   ├── 2bca5eecdab1694efa46f63f16151babcffd8fa3.nq.gz
│   ├── 2cf53540bb17a9db98816075e277243f7bb01b88.nq.gz
│   ├── 34b13bbba0c6bc4f59391be79119a71d816c8eeb.nq.gz
│   ├── 379d2612c93662e5f9cddd6f75d4568e8ce91a82.nq.gz
│   ├── 3c44c649a5edefb6cbdb4cdbdc7f3d8db77167f4.nq.gz
│   ├── 424f8fc3f6c92a8d6e18850cee12aa462b375c59.nq.gz
│   ├── 44090922dc8201460dd3cd52412a0455be9ea333.nq.gz
│   ├── 4419c8bf8c46c4321e8f737a99336982b4b6aafb.nq.gz
│   ├── 46158e2ccfdb82488d4cf0663ecd31f1a7802c53.nq.gz
│   ├── 487457fc03f4b93013a9affb955ede03df118184.nq.gz
│   ├── 4a62d4b799fbea991fefe1a040fa8f13ba0b1802.nq.gz
│   ├── 4ca9bb22aaa51acae408f018285974d6ab2e06ee.nq.gz
│   ├── 4d697ec30cfe8ff7b8e2c196aac4b922f25f3651.nq.gz
│   ├── 4ea4fc5dce2a9dbcd6c91299dc268d62037f7655.nq.gz
│   ├── 518fb61f79f600e77c89e8b1c0c3dc8bd4840d0a.nq.gz
│   ├── 54cc58579704c99acb704066677cbcb6436d3f55.nq.gz
│   ├── 5bf7a677f7ce82ba3e0f3c4a5f6295b56d3a8449.nq.gz
│   ├── 5c2e3d2e9f349e3d718925c8b04e6c55ba0f0f7a.nq.gz
│   ├── 5d6b905d836bf908601ff06ad3bffd308e93e2bc.nq.gz
│   ├── 61d99b0f753134f15c1165335b874d8418643b32.nq.gz
│   ├── 666d4c2bc8cc05b67b5226ff46c521dc870302fa.nq.gz
│   ├── 68658db701ed148de31139d5d683c453b123fd63.nq.gz
│   ├── 694d7d58d440c236ea8ddcfece9eb605427f7be9.nq.gz
│   ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
│   ├── 73842167807f6ac874c3f79dfc9533426b6e42de.nq.gz
│   ├── 76ed1dec8529a83b8c9919b026ea3d8acc960841.nq.gz
│   ├── 7c018508529b843567ab0eb11bf7fd08a2fc39eb.nq.gz
│   ├── 7ce1aae9863a658bc41162720ab666daf7a1442b.nq.gz
│   ├── 7e6291f3b9bea34542bd0bf4af2fe238d981952a.nq.gz
│   ├── 7eac8004a5e053a9485d2e992d607deb6eb67b2a.nq.gz
│   ├── 7eb5aef64ca602f03f2f6e04b02a38c6730d8814.nq.gz
│   ├── 8252cef178bcd6f04acf097b1026a05b3860b374.nq.gz
│   ├── 87d95f47e6430700e4a6a8a99fd74357efb0e402.nq.gz
│   ├── 94df3ae95401a6321bdfb69f01efeef3d2d0af2a.nq.gz
│   ├── 96bfda2494d8f9ef1284f456668afc34696ae973.nq.gz
│   ├── 97d5717685fa4d240e62ed866fdb653e1065d81d.nq.gz
│   ├── 9eb7a1fa64815d8f2fff6786372797f1bbbee191.nq.gz
│   ├── a23e568468a468a55a0ac223c730337dc37c4445.nq.gz
│   ├── a6ee3421bcc4c305d1ab1de82c0b78176dbfc90c.nq.gz
│   ├── abeb4fa0a6dd2f0449add1018629b4690a0259ba.nq.gz
│   ├── ad0ad3cb73cdc645a8572f04704e0670a273b0fb.nq.gz
│   ├── c2c1f5a1eafc6833a49d5442a1052d25cc9d4700.nq.gz
│   ├── c2fbb224e9dc8c14b6189cf3c69e0c57b734b9fb.nq.gz
│   ├── cbf1e3658e6aa8a22988927b510080a973450f52.nq.gz
│   ├── d24a8290e54e830c3a589f1828f7009200ab6806.nq.gz
│   ├── d84ca0b7d2887134f0c5b9d715b3952dd9f49887.nq.gz
│   ├── d95f85aa30cba0706526ebb694dc1f7529c41216.nq.gz
│   ├── ddbd379d6d42d9067e2e5d8e727d8a4777c5c2ae.nq.gz
│   ├── e3697dfde27ba2eae2f87154445261282c70dad8.nq.gz
│   ├── e5cd5d7484273e37cb225d1986f352a701832b44.nq.gz
│   ├── e609076cfa53c3acccf2483028363710be9f3fe5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea7acbfd6cb9cc74eaa798a9d37e1539ccb3ff97.nq.gz
│   ├── f1b9ff44a53089735b764a5c61ea252e66d375ea.nq.gz
│   ├── f3c3aa3c5add3a318c3ae21ef0af7253bed01fa9.nq.gz
│   ├── f60544763a11750565a407aaa186be0f83ce338f.nq.gz
│   ├── f784c5d70e45598556efb88f1dfc93131d7fdb32.nq.gz
│   ├── f90a671507fd3c715504ced491ad1f1f3143776b.nq.gz
│   ├── fa2e616e3715c9cd1f6dcb28ffddad3e158e5d96.nq.gz
│   └── fd90994486260a72ba91bf40d59b0a5ab0ef8dcf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── baf5a54685f92b5f399dca7be0e445d4d586db8f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[ESSS/pytest-regressions](https://github.com/ESSS/pytest-regressions)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
