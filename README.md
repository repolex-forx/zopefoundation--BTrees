# Repolex Knowledge Graph of zopefoundation/BTrees

RDF knowledge graph data for [zopefoundation/BTrees](https://github.com/zopefoundation/BTrees), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/BTrees
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8b46803be1ef9dfab0a9568847d9d69d1b55a05f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8b46803be1ef9dfab0a9568847d9d69d1b55a05f
│           └── chunk-001.nq.gz
├── blob
│   ├── 069a059d0dc7165484537f3625e332a438b66f1d.nq.gz
│   ├── 095ad620e680f5bed5c27bc19e37822728fc6865.nq.gz
│   ├── 0aef88d6f3a33e9fe975aab13324197fcbc32577.nq.gz
│   ├── 0b19416e337b410b989656e52ab59fc57b684d39.nq.gz
│   ├── 136dce6aa161a696f3a0a762e7e6323ea6b87833.nq.gz
│   ├── 192af57b2132a4809553f4eeb073addf67b93d5e.nq.gz
│   ├── 1bc76357acf79020d6500acbb6328936b1d89476.nq.gz
│   ├── 1c95fa6a7ce4f9531b3332fca884673b8be2f05f.nq.gz
│   ├── 232e3bfa0402bd9afa8f4492dbebf001d396f5a5.nq.gz
│   ├── 240602b370f4ad8a4df3c9344406a7a8957c71f8.nq.gz
│   ├── 25295f1c14b3151d806de7d6e5f157481ab289d4.nq.gz
│   ├── 2c6b5d518fa62bab5605fb95a31485390981eaba.nq.gz
│   ├── 2d276ec87ddb4cf5c6e3fe58237f52e5cf0b11fd.nq.gz
│   ├── 2d820a4ceeb27082e316db05f87a5f0702c7340b.nq.gz
│   ├── 2db0a0c841b0f279fc68af562e3379b4aad6fdb2.nq.gz
│   ├── 2f8b004a8ec4256a5c9a24be27c388ff505a809f.nq.gz
│   ├── 349b1511ef1659825e1560cc6e6a696d3f24d8b2.nq.gz
│   ├── 386f62a5e9974c0f58da7b7bbe8aa843f508cda6.nq.gz
│   ├── 388aefb61e9d2221b05e34991bdcf808b62f8475.nq.gz
│   ├── 39b141248561c2e3bcd6cf7a238feac7ee15c2d5.nq.gz
│   ├── 458c319fbabb6add15afe64dbfddc2ab0f6d328f.nq.gz
│   ├── 48cc85d5ad8f186d8b7d35d3888fbbaef11a23cc.nq.gz
│   ├── 4bedaeb2deb1fe9a03654e58a6bc24387ac1cf0b.nq.gz
│   ├── 4cfae0bf5cf79c32e6f9ec446659b7adec6abd48.nq.gz
│   ├── 50ebe92d60887a03e73b8c14f6d08f48a4424b76.nq.gz
│   ├── 57eda1464f2a3afee1181a192c43db6d7c9af57a.nq.gz
│   ├── 59609e15b84e6a3b16ed33146db774f667e44ce0.nq.gz
│   ├── 604ce9cbfcbc8678ff4b92fc7a296e7cd5a8ee8d.nq.gz
│   ├── 637af2bd781857dc46c3d44f3ab17ef857f0b8db.nq.gz
│   ├── 6c259af1571578c345343bcd8e0abada225c2a10.nq.gz
│   ├── 6c631cd74b7f63c18d1ed05d0bf31ae1abed34a8.nq.gz
│   ├── 7170f7bd69f0aaa857893cf0bafc6d72a265dfa0.nq.gz
│   ├── 73f6366f1056c2b4b87acc01c23dbfd290de6194.nq.gz
│   ├── 74bae8a0ffe2b0a9ed26dcf2136024919821208c.nq.gz
│   ├── 77f3c744e601e8cdd746df3914bf9c9c8ea5365f.nq.gz
│   ├── 78cb02e4309d0f44965c16d3382e818e8931e88e.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 7ac5b6e93ebcc1f6fd2d06e69ae3b44df139e82f.nq.gz
│   ├── 7d32c7f4a0667ce2417d68d41e9e202a7eee2fcd.nq.gz
│   ├── 7e78e5aee81324a18ec3aa2a044100ab62d8a26a.nq.gz
│   ├── 7ec72a43b4daa982807caecf57dd6e215f13630a.nq.gz
│   ├── 7f8c1cd9d61f33970598fd1e09cb0ab073a20373.nq.gz
│   ├── 874f364a0c0b4eea01aa928baa9bba6d51da3415.nq.gz
│   ├── 8aac84e75a18edabb2f7e90b6a4c866ee7ad2c41.nq.gz
│   ├── 8e6213b5bcb1f6c9cfb8e2eb40deda40fe07880b.nq.gz
│   ├── 8f780109790d91417eb7e922e18d0954b337f8a0.nq.gz
│   ├── 905d4144bab3092a715d7e35e1cdb67856380d7c.nq.gz
│   ├── 91b1aa49204ab1af3f28d449461dec5f1a0e8143.nq.gz
│   ├── 939242405691125ea628f50c589ee3c114fcd6e9.nq.gz
│   ├── 9445f2270f4bc6011b3d3c912e19ca75511f5429.nq.gz
│   ├── 996451757215764df8f34c2df80e8414d8271229.nq.gz
│   ├── 9a7f7ba071686362ce0bed12cfe7e53d1131a3c5.nq.gz
│   ├── 9b5df33c6b5e625dc17e62e5e347eb5c9e49fdb6.nq.gz
│   ├── 9da519e310684792830561f002c62672e396ad42.nq.gz
│   ├── 9e467e00c4e16cfb0e89750bef023b9f653925e7.nq.gz
│   ├── a0fefb3e4e91111a41b11714b472e1d5fafbb26b.nq.gz
│   ├── a6252c51db63ebd25afca96ff1811484756d58aa.nq.gz
│   ├── a81575852aa5d731e1163e9a98a8bd50bfa4d40d.nq.gz
│   ├── a9a2584420cd1fee6b179308b5f5612919e9ca86.nq.gz
│   ├── aaf975c2e1aee9a6081d0afa30332e904316c1cb.nq.gz
│   ├── ab98bc8b8db67dd26351adc9fe2955021feb58c3.nq.gz
│   ├── ae26dab46f3f692b17b692427ecda82045a17ba7.nq.gz
│   ├── afb97fb6d82327a6fe0dfbbd8b3ab1805ac78c0c.nq.gz
│   ├── b0ba79f6b5053646c36214041796cebebec42547.nq.gz
│   ├── b36879ce765e393d5bc2279706d1a018683320de.nq.gz
│   ├── b647d4caa089809d0fca5657d31a8a8a22ddac22.nq.gz
│   ├── b8def5131e145789ef0a8f965074fedf259dd147.nq.gz
│   ├── bab7f94be5ef86cce49612e6cdab326a57143d7d.nq.gz
│   ├── bd9f092851fda0d6a339879aa6d4a8c8b71e3794.nq.gz
│   ├── c2e68c3c331a9bb9fd33f871ee448d64ddbc7d69.nq.gz
│   ├── c62cf931485cbd72d1d528e2e1a28898d2e6914f.nq.gz
│   ├── c6b09fa3dfb68b216198c91065bf7c1352a57a6f.nq.gz
│   ├── c9557a8ec5ecb246861af64c258aef6f456687be.nq.gz
│   ├── cf8ccb0bc200800b4100cdb48227020da14ab1f2.nq.gz
│   ├── d009fcfac320983f81c7802e692e99b990ecdfaa.nq.gz
│   ├── d25c6853140bc727e6bc6d2830ab886c9f31ce76.nq.gz
│   ├── d6bacb642433ac2698c29c9c3da0cba88619da31.nq.gz
│   ├── d927a14db2ea70598098058c6e263aa3e07b0e19.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── de7cb633c40eace6e83688533a63305d9567fdae.nq.gz
│   ├── defd98dc88d532196a8aba70065c2139f7bbf6a5.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4e900c33c79ece0d6a7292884d58f3df8c1b08c.nq.gz
│   ├── e62eec2685820226d926dae3ba92518b526a522e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e86bb0827e323a682b909b67cb9f905a58d95799.nq.gz
│   ├── e8c61c67dafe6162e848dc16dc75e0474c572063.nq.gz
│   ├── eb61976fd090d9fcc170fdb4f935c15c09d5819c.nq.gz
│   ├── ebda58b4aa2f9135f9c9f6c12e546258586e1d09.nq.gz
│   ├── eea18edce95c709a50815f6fde14a78f75189393.nq.gz
│   ├── f094bf99c328dfb940cbf7330655b940cde7144c.nq.gz
│   ├── f1672c82795e03123c3a586f69f2a43000cf3352.nq.gz
│   ├── f35874c93eae36ce2eca95922894f85dad3f8801.nq.gz
│   ├── f4c98590ca79078d90eaca7966330c26f3581403.nq.gz
│   ├── f7fb3d733304e088eae2b9f8a7a69d187cc2682a.nq.gz
│   └── fcd278f301bd39879a20d075d4830addd5f49a16.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8b46803be1ef9dfab0a9568847d9d69d1b55a05f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[zopefoundation/BTrees](https://github.com/zopefoundation/BTrees)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
