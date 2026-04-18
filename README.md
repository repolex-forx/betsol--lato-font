# Repolex Knowledge Graph of betsol/lato-font

RDF knowledge graph data for [betsol/lato-font](https://github.com/betsol/lato-font), parsed by [repolex](https://repolex.ai).

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
lexq download betsol/lato-font
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b25aa8693f5ce250f45f665d0b77116722fceddb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b25aa8693f5ce250f45f665d0b77116722fceddb.nq.gz
│   └── repolex
│       └── b25aa8693f5ce250f45f665d0b77116722fceddb
│           └── chunk-001.nq.gz
├── blob
│   ├── 01792cbd13451c1ac83300a7fd30e82dd897e80b.nq.gz
│   ├── 0c897ce40ca1dc8c905f0404466138f69d6ba86d.nq.gz
│   ├── 0e1d574463799655c821e413d7013bf0d2710bc3.nq.gz
│   ├── 1749981817bae8449038c90e03d76451ddd143d7.nq.gz
│   ├── 18eb24f3fbacfc2ec5e95ffc4b0a7a24362ef3e8.nq.gz
│   ├── 1cc79653a631b76013c15b7304cb5ec75204eabc.nq.gz
│   ├── 209d51d30485cd33d1ae71825437677544b0c5c6.nq.gz
│   ├── 2297f4369c2a1eb5556d375764c5199a925baf47.nq.gz
│   ├── 240ad3f9277dcfd43618790270a2a219249990ff.nq.gz
│   ├── 2c4f52f2bb8152680d68ca6c15997bb34c327f71.nq.gz
│   ├── 30f2c71ca39e0ff51f3faf5573fb8a9be1d37c0b.nq.gz
│   ├── 3404f37e2e312757841abe20343588a7740768ca.nq.gz
│   ├── 34ca2fad2618dd2ad331aabf88f1753620e104a5.nq.gz
│   ├── 3864de12ca0c2af2be742d107f3796a5b9965493.nq.gz
│   ├── 39d53fdeacb5f43e1db44c5af0f3211840684fb6.nq.gz
│   ├── 3bf9843328a6359b6bd06e50010319c63da0d717.nq.gz
│   ├── 3dc41cff50c3daf37dc477700a4db947174a1704.nq.gz
│   ├── 3ee7cd441e47372f956e43128696e300208eca9f.nq.gz
│   ├── 43a3c80fbac8d2f6072698bb6ad5110fb9a411c1.nq.gz
│   ├── 4ab1be8a66e9b25a9760351a98a7057f45c9c55e.nq.gz
│   ├── 5916925412420a12f766e921f01a1ba075aab5b2.nq.gz
│   ├── 5c9c0a42b5e1cd583488e6cb05d2a4b48cfbe2ac.nq.gz
│   ├── 5e6ac271926780eb6e643524c597f7a539834789.nq.gz
│   ├── 5edbbafcb6832a66972ff695e6d999c9bd9cf7e0.nq.gz
│   ├── 5f887f119236e1b3ff9506228d69278b2e798630.nq.gz
│   ├── 61134e49288b6607a0a98593543127de727b0ae3.nq.gz
│   ├── 61989ae09a991fc4fcfecb00835ee2b8318a8801.nq.gz
│   ├── 6a59bdbef51d850d3540054d6150d346b09a3d3d.nq.gz
│   ├── 724962beee28dd7b828eddc501809718704f69f0.nq.gz
│   ├── 760b12479c59e5bd7a2096512ab5146012066740.nq.gz
│   ├── 76114bc03362242c3325ecda6ce6d02bb737880f.nq.gz
│   ├── 77b4e148f7f48e9b2df6bdbe6d082c8ab8244eb8.nq.gz
│   ├── 794417f6af35de21abc0bb8748e7ae969e2dfe3a.nq.gz
│   ├── 7ac0a1465694c0d46ae6c65d44cd71f32254ab6b.nq.gz
│   ├── 87908c19b84245cea2df2a86856a4e94966d06aa.nq.gz
│   ├── 88ad05b9ff413055b4d4e89dd3eec1c193fa20c6.nq.gz
│   ├── 8a2436573b7f46c306b1f35536754dbbd33afc66.nq.gz
│   ├── a05daaaa2d083b6208f1ab7ef1f19d610854a333.nq.gz
│   ├── a0ab25e9afc5300e204cfff09f30dfc498bc9dba.nq.gz
│   ├── ae1307ff5f4c48678621c240f8972d5a6e20b22c.nq.gz
│   ├── b5fceba0dd1c05ecbc04243f7a11b796d754c68b.nq.gz
│   ├── b93209e96a4695dd32412216c36c56a92fd572b5.nq.gz
│   ├── bb195043cfc07fa52741c6144d7378b5ba8be4c5.nq.gz
│   ├── c15375c3f75c790c1ef1a2953ff917ff62d13438.nq.gz
│   ├── c4e3d804b57b625b16a36d767bfca6bbf63d414e.nq.gz
│   ├── c6dff51f063cc732fdb5fe786a8966de85f4ebec.nq.gz
│   ├── ce49f82217ea5a4820e828eeabf3e3c714864758.nq.gz
│   ├── d18785fbc2913d6fed73247d026522364824e684.nq.gz
│   ├── d1df7676e867c245731b6edb000e3f0784f803c9.nq.gz
│   ├── d7d21079a28d04ec72950663183386c63d87814b.nq.gz
│   ├── da3dfa30a456ca0a5971e7b6661082697dd55c7a.nq.gz
│   ├── dbac8a9f0c305a0051cac442bf28ea94b7e64932.nq.gz
│   ├── e15214fdf9f885efdb0c308a4879734f28eb4054.nq.gz
│   └── ef8de9a0dacbaa813f46ba0ce6ead24b62042641.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b25aa8693f5ce250f45f665d0b77116722fceddb.nq.gz
├── filetree
│   └── b25aa8693f5ce250f45f665d0b77116722fceddb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 64 files
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

[betsol/lato-font](https://github.com/betsol/lato-font)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
