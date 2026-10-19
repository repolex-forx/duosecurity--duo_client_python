# Repolex Knowledge Graph of duosecurity/duo_client_python

RDF knowledge graph data for [duosecurity/duo_client_python](https://github.com/duosecurity/duo_client_python), parsed by [repolex](https://repolex.ai).

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
rlex download duosecurity/duo_client_python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 685f32163918c1b369da3317b1e64b4532ac5724
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 685f32163918c1b369da3317b1e64b4532ac5724
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d2d5bc98dc3cb4b3e6bba941180c09a18cfb3e.nq.gz
│   ├── 03d94e96a7352c4b2e5aa50e3bc61efba3dcc366.nq.gz
│   ├── 093e70d1ff0994058595fcc0b9e8065393432581.nq.gz
│   ├── 0cc67ef2cb8a1ac98e1ae32d5f9854d1b282c467.nq.gz
│   ├── 0e0934993664a758a417e1f212574df39dc9cbaf.nq.gz
│   ├── 11165f8100b5cde57230ee38aaff7d286a8d5c43.nq.gz
│   ├── 14dce958977d9749d0ec4893bc01a4213e445b39.nq.gz
│   ├── 151e9b16b071819663a63506cb4ba220e2fe4db3.nq.gz
│   ├── 16c9604eb8f3b1b41949a90f08676cb96cfbd0b2.nq.gz
│   ├── 1aebdd6eaf8c874c859eea2043b34608871a0abd.nq.gz
│   ├── 1ca785c0457e3c85377a527f1d9fd315011eb7e1.nq.gz
│   ├── 21c1d8e3d97f964a10d6c9affddda04e73ddd668.nq.gz
│   ├── 251a4517f36f5a459344529f9996ad92e061ab3e.nq.gz
│   ├── 2caf0267b7f33c676bd7cba4feb428428fd210ec.nq.gz
│   ├── 2d9b23a90b7a1118759ae817fc0cab65589fb7cf.nq.gz
│   ├── 2dad9b96d0b9527f1add3dc387abce3aab03ff62.nq.gz
│   ├── 2f969d67ba24d99c96a7b6dc825b78eb480e56f9.nq.gz
│   ├── 33ad8e9aa877eeeb3379c4be218db53d7d614ca2.nq.gz
│   ├── 36cfb70257b2d827626b1f31e608534416773a1e.nq.gz
│   ├── 38881f7195f5102e7639e8705e808fb2ba368f0a.nq.gz
│   ├── 399261f1af9e770378f350a1a64f437f4e334607.nq.gz
│   ├── 3dc4944e6727375c7d7f105d0c3ebc39786ea053.nq.gz
│   ├── 3fb5d01ae0438d15c7c21ec8ce499f07f4544008.nq.gz
│   ├── 43286ef8bc3e90940f24cc3190f38cfd61a594af.nq.gz
│   ├── 46c30628515e7993b6add6508dece73b1c175bba.nq.gz
│   ├── 4825bce39226578c77717369756cb4413b3bd663.nq.gz
│   ├── 497efd3e8f462084b3e4b9fc462ddb07c9394b33.nq.gz
│   ├── 49fe098d9e6bccd89482b34510da60ab28556880.nq.gz
│   ├── 4de2a46943a6013270cd13dc9fe95d632c9b53f2.nq.gz
│   ├── 4f088c2ff8b3b30541e5e79bc496d147ad980e26.nq.gz
│   ├── 4f74867ee56d96b4d4d22d64b2bd037df7b659d8.nq.gz
│   ├── 50c3e61970b6242e005cf09c4f9438a1fd268da4.nq.gz
│   ├── 53de0a3a30b40af4cbe149a9630c72e4fceefc9c.nq.gz
│   ├── 54abd3b9e3ef03f73e6aa215085d2f9e727cdaa4.nq.gz
│   ├── 591c6d226daebcb2fc5b38e1566e35552fd92e9d.nq.gz
│   ├── 5c72e193323fa67591fb7c87862e764ac67070e8.nq.gz
│   ├── 5c921c238a038f6b5408c41a4dc1ceaaf1a83b6e.nq.gz
│   ├── 5dde950a4dcf284d98a027de5c120c8bb108eb2b.nq.gz
│   ├── 5e744002531135ab9e0f37f8f221f160966ed6f4.nq.gz
│   ├── 5fdc9b26e19a9647b5303b432c9874f9c7ed1106.nq.gz
│   ├── 61d4ed59eb59dc18635ec4f2d8e04f9569610371.nq.gz
│   ├── 642f739463303ec4f68c66b5849c54a89bb26ec0.nq.gz
│   ├── 65f14cbec0052e5e601512d6e5e69a197ae0421b.nq.gz
│   ├── 6747dffeb2bddc6e6ffb8d1324a1700850137a11.nq.gz
│   ├── 688222210e127e63618b6d2d5748746c8ef7f0df.nq.gz
│   ├── 7117de04a4facdd5fb982b787ae288b62a1a73b4.nq.gz
│   ├── 71f59e650ae530134a114fd911f8260bb8a13f77.nq.gz
│   ├── 72b02b04b28231902ecb72f4b727318b615aabbc.nq.gz
│   ├── 730060e1bb3bb5b518294b3ea90f49db96574072.nq.gz
│   ├── 74cbc3a8219d1e6ff36b5264d1741ab419229817.nq.gz
│   ├── 75369fed467066d9a0c185078b28f5ed3493c946.nq.gz
│   ├── 7771771c8f8b677e61bb0082fd533d9fae85f973.nq.gz
│   ├── 7f46f36f0e5327461e5ec53c5858db364f985cc2.nq.gz
│   ├── 7f55786b4181bcf71fef9b18e4e9a915e687679e.nq.gz
│   ├── 80ed15eefe9c68a65af06e502c24181c6407bc6c.nq.gz
│   ├── 8303bea94d3960ccd51507b1e6a3949cd15cbdf1.nq.gz
│   ├── 83b1e62dc99abaf14b7821da193ef0dc865602f1.nq.gz
│   ├── 84bea67576ff11ea78c1bc71f44c70a106f70c9d.nq.gz
│   ├── 878612e26e8286117910cfed28207c806c2fe5dc.nq.gz
│   ├── 87b5627e75f36c4ccef04ba460593f9b3f119389.nq.gz
│   ├── 8936fe9b001c5e4a8e202778479c44886e386e78.nq.gz
│   ├── 8a7010e58f275d792e76d70939a75ffc6db592b1.nq.gz
│   ├── 8acf8d9039412267815f0aaae95b194794956cab.nq.gz
│   ├── 8cd99c6785f7f0e2dbdcc6442467fc4582f52ce8.nq.gz
│   ├── 9410ae0fa5903d3d1c84520610a0d632d4bc9c9f.nq.gz
│   ├── 984d4c4a78865b00747d996ebd71099449677184.nq.gz
│   ├── 9a6c9391456da6fa9f1943c17f194fbf085177c3.nq.gz
│   ├── 9fd709ade63478ae74a53924d4c2e901e066b595.nq.gz
│   ├── a1bd29113af075f7cbe076e6ce23a367aaec91a0.nq.gz
│   ├── a279cc914601acab07015c10a8e58688ef354a41.nq.gz
│   ├── a2bdc379e4d4444b5c34d2fa35628a318a9b64fa.nq.gz
│   ├── a6e0a04e89f659ef660a46faa0d120e0a58db087.nq.gz
│   ├── ada15a75d93a5e648a90997b2f35b34a1667311e.nq.gz
│   ├── afe1433c79fef04c67b261aa5f7bf95de3c79a1b.nq.gz
│   ├── b77aba4177a1cd07b0eb8ed336e697863acb45cd.nq.gz
│   ├── bbb22531c470c30863e781b29ebe01491e5ff4c2.nq.gz
│   ├── c0d061a74b56c6a52466b8237d1194270919b2c3.nq.gz
│   ├── c2dc933ea85711054fe530c19f1b53f9f033dfe9.nq.gz
│   ├── c41116ea76ce208d781dbd8e01a2a52581a6624b.nq.gz
│   ├── c64b5d7b5bd88444c2f55a880d8ed80e61b0f78d.nq.gz
│   ├── ce7f300f77539ddcd76f4e024c2f6066a874e2ca.nq.gz
│   ├── cea38bd278584aadf3f38ba614925e4d0f96ffc8.nq.gz
│   ├── d26f2d73fb171e3ab6fe08bb40e04f6fdb6486b2.nq.gz
│   ├── d55916e22dd52fe84985f2c5f5fe145031a19834.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dd12eb96e93b1adc87de0ea56e1633afa0a99e00.nq.gz
│   ├── e0e49dbbb757032a8be1a5d1676d9be409f3cb55.nq.gz
│   ├── e657e7bdf5dfd154c1d91175d46277d5ca8664eb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6efb56154c88ad23a0e663ae0b8577f7b6719d7.nq.gz
│   ├── ecbf5a818db991cbda377655941bd11ce796ff52.nq.gz
│   ├── ef43078e4735461a00814657f849494e21d4fde0.nq.gz
│   ├── ef6ac5b4cf4496d25c76ac290d0d566209a92bc2.nq.gz
│   ├── eff9f4859020929efdc769cf1446588880cdf99e.nq.gz
│   ├── f149bd2304069365d49d233ef73ce2426e5a9d5e.nq.gz
│   ├── fc24e322a6db53cd723356acc3c29457666b2021.nq.gz
│   └── fd3262af5751efb74c8f0ed85efeba42a92ea716.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 685f32163918c1b369da3317b1e64b4532ac5724.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[duosecurity/duo_client_python](https://github.com/duosecurity/duo_client_python)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
