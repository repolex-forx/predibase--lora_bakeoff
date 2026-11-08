# Repolex Knowledge Graph of predibase/lora_bakeoff

RDF knowledge graph data for [predibase/lora_bakeoff](https://github.com/predibase/lora_bakeoff), parsed by [repolex](https://repolex.ai).

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
rlex download predibase/lora_bakeoff
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ac88b9586058c16d83709b3021e5516f532ce51
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ac88b9586058c16d83709b3021e5516f532ce51
│           └── chunk-001.nq.gz
├── blob
│   ├── 035fc54596fdb5c95c12aed581d18ecbd0114f5c.nq.gz
│   ├── 0ff84461e60b5c125d763ef19ae29647feda9ee2.nq.gz
│   ├── 1303701fa326ab199a463baee19a38260cbcf276.nq.gz
│   ├── 15a3e88cd03b71458c6a4a89804d3a36c3e1bb0a.nq.gz
│   ├── 1add3517f1a9681d2c2470d25e4ffee6a3768d79.nq.gz
│   ├── 204e3d402ae7ea2c492ae7057676c58d1941fac3.nq.gz
│   ├── 224cf23a735a8a78df9b46fec4cb9820595299e3.nq.gz
│   ├── 245470e90e2abe22b30148ca97595c9af34f5b7e.nq.gz
│   ├── 2550a94667077163e43ac539ed6a2ec34dfed00f.nq.gz
│   ├── 263aee59cb6b70d954e0ee955956556fbb11c84b.nq.gz
│   ├── 2820f611e13f26af34be26cdbdedaa0fbc35386e.nq.gz
│   ├── 306cac44cba796c4d880c0f7cb4df1b2048f05f5.nq.gz
│   ├── 30ac3e9e6a5408568c4495518678081793a9cd3e.nq.gz
│   ├── 32b21356d8801d5e83a1c27e1bf6184e9fa1ef62.nq.gz
│   ├── 3e7f2faf78647e734d1d20fe2807fcbbc9dac456.nq.gz
│   ├── 3f90569b7eef6d8657a9c6e7149fe87950e58801.nq.gz
│   ├── 409f26947c500bc621807e3176505e47d625d670.nq.gz
│   ├── 45a3f936ae4516868ea7339b1b9daa50bfe77ff4.nq.gz
│   ├── 46fb71ea1da5a912c2b5975fe4cf5f5ab83f14f1.nq.gz
│   ├── 581e626f3f544f1bda245eabd2ea68c500fb3d0c.nq.gz
│   ├── 588c346154a14e2d375d069b2b35da2b51edbfdc.nq.gz
│   ├── 58eabd55be2367427c14c86a4b798ef56f474021.nq.gz
│   ├── 590d36bdddbd3bcffee793ee533585d02c9843f2.nq.gz
│   ├── 5a371810be3fa8499cae89866e06c3abc6b122bd.nq.gz
│   ├── 5a391235da8b287c2c86c12cb5c303b0a5e8d444.nq.gz
│   ├── 62671c47daffa862fd90517ffc7c771900bd7b1d.nq.gz
│   ├── 62858f669e005237781ac987c96e38944d8e3ecf.nq.gz
│   ├── 6295317479c89666b8f005c6ce807defd3caf845.nq.gz
│   ├── 64e63bab0aea10dd14c69952d6871a4db230fd00.nq.gz
│   ├── 66b865a6e0d93fee3a901cbfece46ca23f2c05e6.nq.gz
│   ├── 69583b5b635b0025632c72c19fc25ff501597cc7.nq.gz
│   ├── 6c888cdcc013aab520826abe84c4d0b275dc8d43.nq.gz
│   ├── 6eb3da351f64228ac57e2c6fa6c470de7969c051.nq.gz
│   ├── 74bc208b626e9f9bd50f2fb1a0fead7e77da637f.nq.gz
│   ├── 78ed0cc8e775be2395591c3911bab3408418a379.nq.gz
│   ├── 800449c364b93ee89945e7e031c47b4658cc828c.nq.gz
│   ├── 80e90206ec126cb929427678f28d4e02abb65b29.nq.gz
│   ├── 82375b6e565addea307a0b61945db789940ce692.nq.gz
│   ├── 8906b6fcdfcb6fc827527548d1198974b6281302.nq.gz
│   ├── 8a2a30111e1f04b6d5288902bca4ce84c39b86ad.nq.gz
│   ├── 8dcae8f317bb4005df70b3470d47589740a78200.nq.gz
│   ├── 903a1848450b81920a6e2640e59b2d33e8d6ca6c.nq.gz
│   ├── 907fe3731f6087f2b16d00df8ffcede3af761546.nq.gz
│   ├── 930ca57831fa7809065cc0031a9473c35e2ff30e.nq.gz
│   ├── 98a2aa2d073dceca451b0561d9c44e9f6666b672.nq.gz
│   ├── 98b3c6d78a479586abcd05bf3325123b06cf4ddf.nq.gz
│   ├── 9903e934e3daad06a4a9e843f8ff3e13a8e359d5.nq.gz
│   ├── a255aec4a0cb1ae5667f4fc2d84cac93d0a5f353.nq.gz
│   ├── a3ee0580563755d452f00fdf98ccc7c323962722.nq.gz
│   ├── ab3ce505c69504119f3055f2747684ca29a5c7b9.nq.gz
│   ├── abc7e40ee4b91244e5b933756efe3a4ae3c77e25.nq.gz
│   ├── b282a5477a3caa2bc0d63a0f208963d8a0291cb5.nq.gz
│   ├── b2ef5be1a535b034c4db12a4617f2058b7c87428.nq.gz
│   ├── b79b22543018e56efd29c90923b93037049c5bbd.nq.gz
│   ├── c061f277da00935f245576b11d5b0284b0549dd5.nq.gz
│   ├── c8a3ba03c2aae0d8d69bb907b296d17b64bb006d.nq.gz
│   ├── ca3bd64ec14f255fc075abc94919d30c752d96a7.nq.gz
│   ├── cdb815b02fae6eb734299cc633448a06849a22d2.nq.gz
│   ├── d0286fef8bd401f1a147ecae7cdde9f6b4598941.nq.gz
│   ├── d1844de70a4400d7cf8e8d3eebbbbc355321f0e3.nq.gz
│   ├── d7490fe7e26a934c7a5c095fca20dc27fcec50c3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea449a45a638762e4b3eb7c597272bfa27d3dd61.nq.gz
│   ├── eb724c1e01740e122768a6360ec1c5742bf0f802.nq.gz
│   ├── ef314a5b6e32b326308456a1120d6e3004ec66cc.nq.gz
│   ├── f125ac5737bc70318bae6e4459b1f80c2ede183a.nq.gz
│   ├── f3bd3e16c3427e2807455e010d747869321aca7f.nq.gz
│   ├── f50cd382ebdef13a0b3da29e1ef4a9f1aadd4a18.nq.gz
│   ├── f53ae2ac82d0bbacef60e2583d0b14338316998c.nq.gz
│   ├── fbcb367141cf51972b88240519479e7476d0da18.nq.gz
│   └── fd44244c35ee7a005c4a4ef5e979b2329cbec4ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2ac88b9586058c16d83709b3021e5516f532ce51.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[predibase/lora_bakeoff](https://github.com/predibase/lora_bakeoff)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
