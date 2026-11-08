# Repolex Knowledge Graph of google-deepmind/tapnet

RDF knowledge graph data for [google-deepmind/tapnet](https://github.com/google-deepmind/tapnet), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/tapnet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ceedd60bb9f6c9f7c74796e4445aff6c6ddf7c9b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ceedd60bb9f6c9f7c74796e4445aff6c6ddf7c9b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ff65a6a23c6f2e5b7abf3c30a76f1050a13a8b.nq.gz
│   ├── 01401eb6117517f00bb568def8eda76c7ac11069.nq.gz
│   ├── 018b067ce429d887153123331592b39ec81140dc.nq.gz
│   ├── 02aec52ef7604d70d6d5f39fbaf459732eebc6c5.nq.gz
│   ├── 02b94e2c990d6f78d1bd8ed8e6698d7c7d7c3ec1.nq.gz
│   ├── 08c23e03b00887db561a6ad3ff0452b46564b9bd.nq.gz
│   ├── 0cbae4bd698574ec0acb579e05ebbb3f6f5cfee5.nq.gz
│   ├── 0daa59a1a78819cba624f968101380b3b9174c44.nq.gz
│   ├── 0f082f9ff2e99a31d56a88c2e035ac4c4b332423.nq.gz
│   ├── 115c825dea159b3b7da713ff0b97decd78c7027d.nq.gz
│   ├── 14f7aa3c716b773cd96e89eb847dba26c8a644fb.nq.gz
│   ├── 19a163e1d1180d0a2fabbaa922a86ab7607ea2e3.nq.gz
│   ├── 1b1d93363f32dd221ddde8cc988914545c1bff3d.nq.gz
│   ├── 1e52dc3b63e2562758ec4582a359abc6a9345b29.nq.gz
│   ├── 2399dbb0c650ceb4b0f84bcb94116246ab8b1413.nq.gz
│   ├── 247c0af2b130a1787880440f4f0a0e48cbace131.nq.gz
│   ├── 2525710769ce40e315a959defc66fd867c67784c.nq.gz
│   ├── 28b3622495c0e638fb631df09cd28027c979516e.nq.gz
│   ├── 293ec8b9ddae3ee8ff9bed1625bf4ed8b5832551.nq.gz
│   ├── 2a646b6eff22ee4fb076178671ff8a32764e54d4.nq.gz
│   ├── 2b55e84d5c9f4ce6ccd73c566a35ac5d92dbd75b.nq.gz
│   ├── 3136eb2708325647721f8eb56b7c1b73505b3ac0.nq.gz
│   ├── 374e9c0d804c47e1b18d67cf54832abab0dd19b5.nq.gz
│   ├── 37dfdba5b1e8804f6a0f9861ff42443d4d6e0710.nq.gz
│   ├── 38b3a1a1c4c0ec621dfadea2d3145d313884ece3.nq.gz
│   ├── 3935204ee4dfdd648fb19e6c701344143ddf64e6.nq.gz
│   ├── 3f58e126f8d9ee2fb38a54e40d50ea3551ab0894.nq.gz
│   ├── 40679597b10f17c695cb716f8238b8c5028a336e.nq.gz
│   ├── 409920c2433dac7946ee89f1b288b2c1e40a4d52.nq.gz
│   ├── 430d20b7b4bda8ad75c3dbc20d8807e136bf5e91.nq.gz
│   ├── 459f710e69d6e464b894b945dfa60eab08f40572.nq.gz
│   ├── 45c24b9e076c2da78cd8ee0bb980716f8c6ed3fc.nq.gz
│   ├── 4bf01dfc7fa6e68b1e112a3198952626aadd7014.nq.gz
│   ├── 4f45a30da6b1d1746d75fb2f84fab947728121b1.nq.gz
│   ├── 512191cb991e580404b7941b52f34350051c6904.nq.gz
│   ├── 51bb9217fae0669b3ed3989e656dcee015f94137.nq.gz
│   ├── 54599379acef45d998eea5d1e7444ba465111aa3.nq.gz
│   ├── 55fab1b83a05c14e9f91ea3bd51eeee19a0f2bd3.nq.gz
│   ├── 56a767133d7fbec206b6a4c5828e92f887f33473.nq.gz
│   ├── 57b68ccce75fcdf780ed61e2e3b1bd55a1f56175.nq.gz
│   ├── 5fa13da5e44ef5426fea83856f75be6b4f3f3c98.nq.gz
│   ├── 63d6b792dc8425e41d6f8a8b869f381bf4c6927f.nq.gz
│   ├── 66ce33a7524b4d304a5c965a249a034d5986be2e.nq.gz
│   ├── 7153f234a9ed7c670b0c63a569a23c489f8db3e6.nq.gz
│   ├── 721e455383903230d6af95f328c54861a4d03d72.nq.gz
│   ├── 7430a3a3f6b5b21958d79aa9449bf9d890da5cb7.nq.gz
│   ├── 743efdacf4834cc5490246eb26e101ac81212afd.nq.gz
│   ├── 759744476024c466e8fdf89552a59c8a1ac2f141.nq.gz
│   ├── 7ae31f1d76f9c3e5135d8e06227b8608a492d482.nq.gz
│   ├── 802f188b3693ee6d96e78531a5632c03d969dc6f.nq.gz
│   ├── 848408e397d8efa5ada3813d78ee25db59072051.nq.gz
│   ├── 857ad37d58889939df6bf263e7fa41e8a3a7154f.nq.gz
│   ├── 86a70f1eb644ec53a0bd3611030043d4ffb2de4b.nq.gz
│   ├── 89978a85e676cd1a56c20bfa60c5b6c0c210f74b.nq.gz
│   ├── 8a62734bf6a1ca827155a913af5b2291669a88af.nq.gz
│   ├── 8c370366ab1caf863b05d9b65da6cd1801482661.nq.gz
│   ├── 8f2c1dbca93ce0c7843e36f8b577788251b4e4a3.nq.gz
│   ├── 90df3d2a556eaf50a69e7d628ca982119f1970e0.nq.gz
│   ├── 9212aef00e5742d0f6685edc0ac8f4a8c35d5774.nq.gz
│   ├── 97aa3419413e2bbd8de7a38ed9f9806849654953.nq.gz
│   ├── 98afde390ab5d98a1d14945019cc79941982ed29.nq.gz
│   ├── 99b7ee3f61ef0aca8c9be4a02a90b9707cea77bd.nq.gz
│   ├── 9a96f7ab3fb915db87826a194fdf98d2aec65884.nq.gz
│   ├── 9de7d3598fdbcebd2ddf08e409932db2d94c8943.nq.gz
│   ├── 9ff0dd6ab13fb0d996989dd5b94ff3ce9ecc14a7.nq.gz
│   ├── a0306670ef18340a0e0d5fa47e58468926e29870.nq.gz
│   ├── a0a039156048415a76d00766ab57faaad483d3cb.nq.gz
│   ├── a13b5a4ff12d5300634662f405e0259fce1321e3.nq.gz
│   ├── a1569b42078fba64d4a05fea26f05fdea6479d40.nq.gz
│   ├── a62f36544112e53a371753b2573b5ab36dff1011.nq.gz
│   ├── a713e04f02e4df7715fa67513feac2035fb6ce3b.nq.gz
│   ├── a944a5eaf0b47f981185cb9e991085aff52de2c5.nq.gz
│   ├── a9c1e8ba013cd9d3d7fe32fe35c106d5df262447.nq.gz
│   ├── ae52790af066dc2ecf6167f1190866c433590fd0.nq.gz
│   ├── b1813485d91f70c5fe75d9f1e1c42f29a3cb4e9f.nq.gz
│   ├── b627453ff1b6108186cb7ecb6f5567388c3f16b5.nq.gz
│   ├── b75f96a6a023ecd4dbf1f6ce5d74614ef526e235.nq.gz
│   ├── b81988156c1c5ac2d7f2c699bdf80f67f8ea9028.nq.gz
│   ├── bbcc4a2181ac24441a30f3d8f400cc97a84f0a3d.nq.gz
│   ├── bfd0d6d092fb81fbe0a1bbbdc883c8f94cafb71d.nq.gz
│   ├── c411f181902e1c564d5dcc5c0bee934e98e798c4.nq.gz
│   ├── c77701b7d279736d67cf5a0199cd0afc104c6e8d.nq.gz
│   ├── ca17886b935b4b8da11eea36dc92edbd17d55af4.nq.gz
│   ├── cebaf0c392d8220cc91b87b07180a84642a28379.nq.gz
│   ├── d1ff35395cb68b045ab3987fb8e1519f5d8c6823.nq.gz
│   ├── d27f80818d707c2c102b5cac97cacf65fe067590.nq.gz
│   ├── d40d399e8ee759cd01886d60c85a83faa67bec34.nq.gz
│   ├── d4543c00abaa8561bfd448cecaf58f702b7cf90c.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dc7a2bee762ab4ef5d6a278297276abc13e0f8a9.nq.gz
│   ├── dd24d43411cedcbbce29f8553e2b10de9efb3321.nq.gz
│   ├── e1aaa9a25a0b1a68ac23498199eae4eb7cd405bd.nq.gz
│   ├── e3bf09782f981280c06b627c4aba27f7b4f9e296.nq.gz
│   ├── e457382a90198c4cb2a9f1bf8c73526d33952488.nq.gz
│   ├── e495ea50919453370945420b681d4635b6f019e4.nq.gz
│   ├── e569ef92f4e0d1a03510084785960913c3c7d7f0.nq.gz
│   ├── e79a96f3dbf130e8a2de1623cb45ee436117b997.nq.gz
│   ├── e85d9451a8b06aef26eecd751141c6737e1ae2f9.nq.gz
│   ├── e887cfa169aeb15fa7599cd7aeda27aeaaf6aea2.nq.gz
│   ├── e954cf82a093bdd27d3024811d7f5be7d4e307fb.nq.gz
│   ├── eaa1f1e26891a72f2e7cf9e6e0d936121368a830.nq.gz
│   ├── ef73762df2a92b5963c61d6068f085a06e1e0546.nq.gz
│   ├── f10e7f6d6b58ea17fd2308e2ca56d78e48c84475.nq.gz
│   ├── f11a85ae151e47ea146322e9f02850bd927364c2.nq.gz
│   ├── f15985ccd64e584c94a4e3e536d204fa552bb485.nq.gz
│   ├── f30bbc18aa49bb287586f8f0beebcda632cb5ceb.nq.gz
│   ├── f4a15ac6f8073922e477122d10dc0b9e25d936bd.nq.gz
│   ├── f5720762bb5833b38e3087862879cedc7503e6d5.nq.gz
│   ├── f5d313e07d93fced9a3eb1b5a387a577f1d09b23.nq.gz
│   ├── f86450e173b21c5fce3df38145e8a903c8ebdc1a.nq.gz
│   └── fcbcea17f08ad521e3d878af439dd68d1e9bb690.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ceedd60bb9f6c9f7c74796e4445aff6c6ddf7c9b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 119 files
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

[google-deepmind/tapnet](https://github.com/google-deepmind/tapnet)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
