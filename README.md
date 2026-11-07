# Repolex Knowledge Graph of ansible-collections/community.ioscm

RDF knowledge graph data for [ansible-collections/community.ioscm](https://github.com/ansible-collections/community.ioscm), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.ioscm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2f46bc70c79962a1516126d3978157a92fba10be
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2f46bc70c79962a1516126d3978157a92fba10be
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a3082aa0a79adfb8c9f0ca5dcf684d17ef6d9c.nq.gz
│   ├── 083e0d7b02a7ee9725559b7cca871ca351e8307a.nq.gz
│   ├── 1a6d8d2e482a94fb83e18fac10fc4520720fdf51.nq.gz
│   ├── 1beda4fe751520ce739052fae10313c760d04aa5.nq.gz
│   ├── 1f9858c45831f17e4d3ddebab73b2a101688310f.nq.gz
│   ├── 1fc1583a6a04fde0d365202efdfac5d696cd67e4.nq.gz
│   ├── 26f81c117aa467843b531ad8bd88bea36deb87b7.nq.gz
│   ├── 297a0407109df43985a44f4773355302571968bf.nq.gz
│   ├── 2abdaca563660791592998039959e779d582e1e6.nq.gz
│   ├── 2ba83a70e5267fe23eca0c5e101187d5de6995ac.nq.gz
│   ├── 2e910acfe334561c1a424fc72cf9e11357dcda60.nq.gz
│   ├── 322ddcee84bd29cb1205a2b3e7d91d86fe93d3b1.nq.gz
│   ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
│   ├── 407e477403349c09e7893121cccb0b37faaf3197.nq.gz
│   ├── 4f897cc82cfbe694ea453e79200dbd25e3a96c1c.nq.gz
│   ├── 558d02dbfff71369ffe8994f486213e8dbd9180e.nq.gz
│   ├── 5a75a65a46e32b965a8debadaa7073dbb040118b.nq.gz
│   ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
│   ├── 5f69ecf81f03274c6761af4221e5f66a9dc7c0e6.nq.gz
│   ├── 6751f22b38943fa97c9bde862904a4875a436618.nq.gz
│   ├── 691c6822101b1eb0b7360dcf6b8187e8813388c9.nq.gz
│   ├── 78270301dec304d278a2a3125066564321c17151.nq.gz
│   ├── 816cb44098cc8881b333f2ca0a8f8a1d8f57df8f.nq.gz
│   ├── 832f5f41884e95eb0a437d362e4eb9480f78bfb5.nq.gz
│   ├── 89699587f68651607244c61dd4501f45b442bb2f.nq.gz
│   ├── 8c44c98fa4feb60ea2a2836f55419ce47faee67a.nq.gz
│   ├── 8d7dd4ee2f0eddfdb28376790e98738f3f9d4e43.nq.gz
│   ├── 9290d44c35f036e6dd2673afa71c09c4daca0beb.nq.gz
│   ├── 9400d99b2fe6a3b0939e706388750db215de0bb5.nq.gz
│   ├── 9454dc92f2fe57536133739c7583fb6c716a9dd6.nq.gz
│   ├── aaa61e745424f1f6e8ca6e810d1c4554dcf24cff.nq.gz
│   ├── abc40033b9064d057e4bd1483e88ad387ff9acb9.nq.gz
│   ├── b45d870eec22b13581d0771a66c226d6e3b77f89.nq.gz
│   ├── bf66af6e3a784f3d8485c5ac848bf73dd0eb3cdd.nq.gz
│   ├── c3ab52e7b7a5adc20ab20cbb7dbaf23b31ecfe19.nq.gz
│   ├── ca7842f34ede48d47cfba47642bf9e4f021b4798.nq.gz
│   ├── cab23f9fcdcde20d83796722ac0cbb8348573161.nq.gz
│   ├── de3685a5ba19b518364e2820678a4e6fa7d5b68e.nq.gz
│   ├── e10ed39aa9bc8885f14a8e4a8a3fa548562c64a4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ece2e24663da1f1ac96ef34538c73d27e12aa2d2.nq.gz
│   ├── ed03942503258fa97ea1e13da4d5c836ad510b12.nq.gz
│   ├── f1d2926a894ea868efb23396fe4b33e418e969cc.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   └── fa0308a6a8833ec223280b8884848541b86147a3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2f46bc70c79962a1516126d3978157a92fba10be.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[ansible-collections/community.ioscm](https://github.com/ansible-collections/community.ioscm)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
