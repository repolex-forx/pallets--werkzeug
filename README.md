# Repolex Knowledge Graph of pallets/werkzeug

RDF knowledge graph data for [pallets/werkzeug](https://github.com/pallets/werkzeug), parsed by [repolex](https://repolex.ai).

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
lexq download pallets/werkzeug
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 039353814b491be2717811f7643f7959271de727.nq.gz
│   ├── 03c90b79603fb7a8ab3ed7b8f9fe1d67d0f4697e.nq.gz
│   ├── 06498913629b7267f403f42be82026a74a8fcf5b.nq.gz
│   ├── 0800643ca4c548b3e7afe74a7daade62f0548412.nq.gz
│   ├── 0913e93af0f42f73f9320bf865e58519d6256707.nq.gz
│   ├── 0f798af8108b53283accc422cd94749264a45b7c.nq.gz
│   ├── 11ed68fa7fedc08d478e7677f17cdb135c802286.nq.gz
│   ├── 1446d245209b85063776231278c4c7ad5fe567ff.nq.gz
│   ├── 1489fbc145c3a99d09c147af1b97cee108ec7cb9.nq.gz
│   ├── 14bebd83b32fd3e2b7bc11de88c33cdbe1c2a539.nq.gz
│   ├── 1568ada2642507399096f4f92fb56125d0dd3620.nq.gz
│   ├── 17995f96c502053ced1aeed7b11cea9530ba99c8.nq.gz
│   ├── 17d584f11bc4eafb8b163faad90663ea0f92c764.nq.gz
│   ├── 18ce7b0afd36a61870c1c8c5b2ada27c6f5118da.nq.gz
│   ├── 199a17f64e31eb291ef9799510bbe1dad281f10f.nq.gz
│   ├── 19dd8210d0a47c1d32d826e7188282c4ca956ab7.nq.gz
│   ├── 22cc1e51886f502dd625fadeda8747141637f563.nq.gz
│   ├── 27fd381d82516af0e0f52d32e8422bb31114edea.nq.gz
│   ├── 2a22389e3b2aaccbb06cc9a8ecfca93d0a56c8bc.nq.gz
│   ├── 2b2ff8f33e9a9af7c5f9ef775e84ed5a85805ce2.nq.gz
│   ├── 2b5c74c0bda0b2e625d063df727688abbdf897b7.nq.gz
│   ├── 2e13b130345c49238816919bc239505fe0067e00.nq.gz
│   ├── 387df5bd11a5d2aad111f6c9ba0348f33a96b8f2.nq.gz
│   ├── 393d270c649e965be5a2f217ee8f68bbdb51b377.nq.gz
│   ├── 39b1788551576e4a9810c337d65bc6966a31e8bc.nq.gz
│   ├── 3e552ad881dc4d825746d7f3ddd6ae8c1c5eebaf.nq.gz
│   ├── 3febf07a966c6cb9f3747dd0c3e75b0b27ee457f.nq.gz
│   ├── 4561f2b068339421843c650742240dd28e0157ca.nq.gz
│   ├── 459479587c5f577d11507636b6779085ea9bfc65.nq.gz
│   ├── 48665eecdbc1fde8adef5bff78f579ed8eb67373.nq.gz
│   ├── 49fcebecf7656cf715ae2448c5636954219b4ee1.nq.gz
│   ├── 4c6d858d71264db3a49901ef1102081442540821.nq.gz
│   ├── 53eac91b9741d7666a16c6af0062801ba71af9e2.nq.gz
│   ├── 57ff68a23a89f8d210e36af71daf3c1154b3db74.nq.gz
│   ├── 5a3faf0e87a90b2b5d3d808d9f791f51ee867547.nq.gz
│   ├── 5b5e746aa3e582817cb7f572e5bd753d908a00e5.nq.gz
│   ├── 5bc243bcfa33ca3b8a1ea8f9616bd77ae36adf38.nq.gz
│   ├── 5ce14684682907b21753eaf71ac8b13d70944d23.nq.gz
│   ├── 5e11caa2438dca65cef667b75f262d1e3f6ee28e.nq.gz
│   ├── 61666ab1f093b0dd9e9446de2a0df8d0b631e583.nq.gz
│   ├── 6184df61f66d72cf51de70a46b819318cfc08613.nq.gz
│   ├── 64cba241d1fdcac4aaae09ae0a274563446b3596.nq.gz
│   ├── 657bdc5db50751d3a316689d9ebf3e894e42758e.nq.gz
│   ├── 65d8e31b0bd9a7e38ca1d6a811329685a144a838.nq.gz
│   ├── 687b8482bc1af7d60d763c947bd75d9bf6dbf62a.nq.gz
│   ├── 6a7dced9dd33f61ef4d0820914fb9379fd332d95.nq.gz
│   ├── 6cdd8e0a1c4f84213ba9024678cab502a6a2a912.nq.gz
│   ├── 71e48da9b288c10387f2459ba57f1a1bd77fb6f7.nq.gz
│   ├── 79a4e02cd5f499628a0aff7d5f33cc62a7e76308.nq.gz
│   ├── 7b8bdb709b978272b60fbfef458d6dd32f8fdef8.nq.gz
│   ├── 7bd2284cde192df0870aa12ae0d69b8978da03f5.nq.gz
│   ├── 7c52de92eec8ffd84a8feb45d5b7da313a7d47ae.nq.gz
│   ├── 811da68a8676c4225a60f09542d58ec547988baa.nq.gz
│   ├── 85c0ed40eb5b456350671cc2344f876f562ac509.nq.gz
│   ├── 86293f3d0c70c749c1e416f3bb85476e34010235.nq.gz
│   ├── 8815af4935662b0e27d9fee2ac5f4fe0bec726fb.nq.gz
│   ├── 8f706621f1028838a13858fdda61a2d2a9ac785d.nq.gz
│   ├── 91952a0f87263a7bca2b962e3e1ee3c24d9ef78b.nq.gz
│   ├── 9199e6fa6cc9744c046b08378b831c2d14ab5d41.nq.gz
│   ├── 9c0eb190ae005986c9abf4b9f40b9163f916000d.nq.gz
│   ├── 9dae38a5368b321eaa43e5e78740be70e92d2d35.nq.gz
│   ├── a22da1d71b4f1ae2227bd9fe3959150bf3414d1d.nq.gz
│   ├── a23b13745d4784abc71cd7b8da6342b8683394d1.nq.gz
│   ├── a3ee48596b69aad48b7a85c14b1a20e0ad3f5a9e.nq.gz
│   ├── a8efdcc31e04903586e4afd8c8a364e910293920.nq.gz
│   ├── ad7d5b130d95bb2c9e44d32e46f0e864b9061405.nq.gz
│   ├── b3f497641c54ad9237d6282057dc831bf8b2d1e9.nq.gz
│   ├── b592b7e88c8a70ad3eb883a64b4af387e5975044.nq.gz
│   ├── b73b78999183cfcdb90e48f6f3bb6bdf356ae8a9.nq.gz
│   ├── ba23d896a68982d87dd94e8d05fa74a939e1cd6e.nq.gz
│   ├── bd6521979bc5eb3bcf1fa81e83b580536b269d47.nq.gz
│   ├── be0324681466f7e66076ef87a6f625f0b0431f9c.nq.gz
│   ├── bf4885685837239ffd98b3d273aaff4845b6f014.nq.gz
│   ├── c1c8928896f3e8d3cb368453cd8def24afc3db8c.nq.gz
│   ├── c3a63226a9edfaad300d74a28578a910c868cb36.nq.gz
│   ├── c97b898957a78b6607d48a7259b2edbcb15c725a.nq.gz
│   ├── ccbd518547886571b1808369f4fbab86945ec4bb.nq.gz
│   ├── d06b7dc56e485ed205d2a47e2256c934810e955f.nq.gz
│   ├── d115a68712ebfaede58ddfa370686fb4184adc88.nq.gz
│   ├── d224d727e6269ab574951479338aabfab975aa00.nq.gz
│   ├── d257e70474a9ec56bfccba374b1c76c87e9ded02.nq.gz
│   ├── d7d2b16dbcf1f759927700f688ff8db757f9aeca.nq.gz
│   ├── dd5629bb3515f256aac6410e0592a4baa4972a11.nq.gz
│   ├── df61499f00d7cddb75c9b1211178ccae7b7848de.nq.gz
│   ├── df80288d366ea2957f344951c9b0dbd564a1040a.nq.gz
│   ├── e1d23f6819b0b6304ba0d46d56c6e4fbd6eb1f97.nq.gz
│   ├── e653a9915171c947ac37589fcf4084e76918ff4b.nq.gz
│   ├── ea29dc34e4da85cf095aeda66390ce1e191101af.nq.gz
│   ├── ea881bb3836e9a477827dd661a75694626b8ecbd.nq.gz
│   ├── ee7596d5ac84c54110c3a39ab7c5a2fd13dd9e21.nq.gz
│   ├── f4c48c50ddef10e6d47481c9ccf4a9989ce1f90e.nq.gz
│   ├── f642a3f32d723338795c25361971d9887ff1bdea.nq.gz
│   └── f954b6b3ce0380493d1e6c18f4da7253b0547fd1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 99 files
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

[pallets/werkzeug](https://github.com/pallets/werkzeug)

---
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
