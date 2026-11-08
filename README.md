# Repolex Knowledge Graph of canonical/hindsight-operator

RDF knowledge graph data for [canonical/hindsight-operator](https://github.com/canonical/hindsight-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/hindsight-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2dd8dfeb8332600eca7b84e2a1dcd4c072b8715
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e2dd8dfeb8332600eca7b84e2a1dcd4c072b8715
│           └── chunk-001.nq.gz
├── blob
│   ├── 15b929a6e8e2856c61a23a487084a9f882a68581.nq.gz
│   ├── 1715752e7e847adadc46a2ba2d13d1ff370f1f5b.nq.gz
│   ├── 198d9c2993ec27dc848b3d0da48db948dc12cab8.nq.gz
│   ├── 20b1e9d245d599b8f79bfda88ad45df9dac2bd97.nq.gz
│   ├── 21a5190c500f30dd71d170ccf563891860117f67.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 319e298fe1545781df877970f498aee5599e8c64.nq.gz
│   ├── 36a94f25f87cb2ea740bb154a31d836ad61ad893.nq.gz
│   ├── 46ca5177387ad5e3700f9b551e37134f260946b4.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 50b2ce08ded1dd6cd589653f8a86abfbaa304895.nq.gz
│   ├── 51eeb008309ad8f9b3c74d68f6a2d1e1be835f32.nq.gz
│   ├── 56cdf25c63794ad9e66f1997aabb0047b7257b3a.nq.gz
│   ├── 5706ac096003b425c2474cd6dbe93be46217dc38.nq.gz
│   ├── 5b04943149b8830f5c1f0bcf9f1955909ecc5288.nq.gz
│   ├── 5d946d95f2af5dedb9b3f55492e588e4c32d72e5.nq.gz
│   ├── 61c82417a832a6e5b0c694d608be23bd4749c426.nq.gz
│   ├── 73a168f1b628c666c813717210586e1412eecf2f.nq.gz
│   ├── 73a7bc5b44d3b1d19109727ccf5c0f288b396a10.nq.gz
│   ├── 7408c61189f0d454bc4bfb7f8c86d59bf0e47dd7.nq.gz
│   ├── 747783f52d115c52020559bee56c1668a69a61fc.nq.gz
│   ├── 78146a478bdfffd291006484c46976f4bdc287b3.nq.gz
│   ├── 7b81367103ce1865b3daaa89c12ca6a0a3a02362.nq.gz
│   ├── 83cd91be441c5df1ad71358283cddb2f0163258e.nq.gz
│   ├── 880f3bb1a544083dd6602cf5e0c2bddc5c6fa860.nq.gz
│   ├── 890523870bce0696b019e2cf9e0f9ebc8d7bddf7.nq.gz
│   ├── 8d2435111f57bf9b39603be895c241845c6eb869.nq.gz
│   ├── 90c08f0a63be9347dd7e53d9535ffd47c861203c.nq.gz
│   ├── 90fcef8f2ff7b8c3957ddf8325ea8dc0e6a873b3.nq.gz
│   ├── 9157b28bb0e83f5abfef8bfe99c1071bb5887087.nq.gz
│   ├── 927ef4aa81e2a75a582177ed1b1c6f119ae9299c.nq.gz
│   ├── 939da050a64f482c0aa55f2eed9b1095cfa23fa3.nq.gz
│   ├── 9700bff88efa002825e24003df6cb9eb13a0c1c2.nq.gz
│   ├── 992a6c415af6349ecf861d2bd3ad1ae01afd5ec2.nq.gz
│   ├── a0f3d74771a557937d1f509dd2143385699db869.nq.gz
│   ├── a2835df3a3336e89835d9dc5ae2d66efc1ffa8ef.nq.gz
│   ├── a4670ff46919b276a4c9663b4ca51830108fcfc0.nq.gz
│   ├── a6924456d475a961a0fc4b4c03e1ac0f9e32d9b5.nq.gz
│   ├── aa488b73fb103f718132445c7e2f1159199e89a8.nq.gz
│   ├── ae0d7bdd5b01d06c0a2cce0fdba4eb6bf15e22c7.nq.gz
│   ├── aed8851f114559484d4a2d9522c9923b1e3994e1.nq.gz
│   ├── afecf5b3c317646fecf9d4b637b9e8c9f915d20f.nq.gz
│   ├── b358b2b915ca8e9f579c45f2dfc6a1d637dba173.nq.gz
│   ├── be1aa88056ce93c3417faf9f703760abe78558e5.nq.gz
│   ├── bf7514053740827ea2ce282a0a66294ea003be88.nq.gz
│   ├── c057dab8ecb25a191990ddb36b61baf89b0a3c56.nq.gz
│   ├── c91713a839b5054f811196ecc289b97e025a42aa.nq.gz
│   ├── ce9e1a25ee4c47c7a2174813e66a48b120fb5a0e.nq.gz
│   ├── ceb28776215a098e977650ac090c785dcbf53651.nq.gz
│   ├── ced33c63abfd595242091bfdbf71078f400ebf04.nq.gz
│   ├── d323f2e7973ed4ac6f2cda7917360879075fa87a.nq.gz
│   ├── d46a1f1fb0a027e08fd758be547ac2ab198b445d.nq.gz
│   ├── d8447d38486f33d5caa5c4a16d733f3fd666f27a.nq.gz
│   ├── dbb0ac3a4cb6859764dc6bedcced53de0361a7a4.nq.gz
│   ├── dbc1367aadcc0e77c694cef45e1b760f41d6872a.nq.gz
│   ├── dc60f9ff5d72d2594f0e7c5999d1e1e6a0fee1e5.nq.gz
│   ├── df39a5d3019cb6da1870cf12420b459fa30f4cd7.nq.gz
│   ├── e01dc44bce25c78f756e773d31b7445345c3d7c2.nq.gz
│   ├── e25f9de9995a03109a1356b472fb751fff108631.nq.gz
│   ├── e64065def61748fb687f6981b535f28abef4cd17.nq.gz
│   └── f69efeaf46cff25f57487ab3f311716a069fb826.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e2dd8dfeb8332600eca7b84e2a1dcd4c072b8715.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[canonical/hindsight-operator](https://github.com/canonical/hindsight-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
