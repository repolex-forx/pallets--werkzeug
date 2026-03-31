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
├── aggregate
│   ├── ast
│   │   ├── 05978170acf3df1e54c77b0c9804fdaced82f83b.nq.gz
│   │   ├── 086b2953cfa25ae7ac97a5e46892a06e1540e4d8.nq.gz
│   │   ├── 35cc53e1d5f30036cbe736d950b13e257e7dd647.nq.gz
│   │   ├── 79190a5be3e3267feb5c110ffff26ff0c28e0347.nq.gz
│   │   ├── 938a331ddb0c7009f4286e962f8a9c1ebad62be2.nq.gz
│   │   ├── 96e49709d627a7766077cff4c98ebf3cad868ceb.nq.gz
│   │   ├── a09ccc321e92e757842a10d879a2373fe1b81d44.nq.gz
│   │   ├── a5398b1b95d295198b95780c9cbba5c8b50a5edb.nq.gz
│   │   ├── dc9412a98397fcaefe909448c539c556a18d0180.nq.gz
│   │   └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
│   ├── lsp
│   │   ├── 05978170acf3df1e54c77b0c9804fdaced82f83b.nq.gz
│   │   ├── 086b2953cfa25ae7ac97a5e46892a06e1540e4d8.nq.gz
│   │   ├── 35cc53e1d5f30036cbe736d950b13e257e7dd647.nq.gz
│   │   ├── 79190a5be3e3267feb5c110ffff26ff0c28e0347.nq.gz
│   │   ├── 938a331ddb0c7009f4286e962f8a9c1ebad62be2.nq.gz
│   │   ├── 96e49709d627a7766077cff4c98ebf3cad868ceb.nq.gz
│   │   ├── a09ccc321e92e757842a10d879a2373fe1b81d44.nq.gz
│   │   ├── a5398b1b95d295198b95780c9cbba5c8b50a5edb.nq.gz
│   │   ├── dc9412a98397fcaefe909448c539c556a18d0180.nq.gz
│   │   └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
│   └── repolex
│       ├── 05978170acf3df1e54c77b0c9804fdaced82f83b.nq.gz
│       ├── 086b2953cfa25ae7ac97a5e46892a06e1540e4d8.nq.gz
│       ├── 35cc53e1d5f30036cbe736d950b13e257e7dd647.nq.gz
│       ├── 79190a5be3e3267feb5c110ffff26ff0c28e0347.nq.gz
│       ├── 938a331ddb0c7009f4286e962f8a9c1ebad62be2.nq.gz
│       ├── 96e49709d627a7766077cff4c98ebf3cad868ceb.nq.gz
│       ├── a09ccc321e92e757842a10d879a2373fe1b81d44.nq.gz
│       ├── a5398b1b95d295198b95780c9cbba5c8b50a5edb.nq.gz
│       ├── dc9412a98397fcaefe909448c539c556a18d0180.nq.gz
│       └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
└── blob
    ├── 00cc0c357bc43f1370c5812880312b8850012fa4.nq.gz
    ├── 0193276f0e90a5b50ab473e4d0c12592f4d6e003.nq.gz
    ├── 019398abc1e58e85196fda0276234cd9bb471854.nq.gz
    ├── 0294b3f8972ec96e8b33c128875c12d05392e387.nq.gz
    ├── 02a00298b487e0129c85ed80ac698393e814b7c5.nq.gz
    ├── 039353814b491be2717811f7643f7959271de727.nq.gz
    ├── 03991fa398e498638ded8b883dad2b7c3df37db3.nq.gz
    ├── 03c90b79603fb7a8ab3ed7b8f9fe1d67d0f4697e.nq.gz
    ├── 0495a6c9dc1e0d44883dbeda2e6467d3cc97d042.nq.gz
    ├── 04bb912b29a671ec83997d0c25f693fa025d6fa0.nq.gz
    ├── 04bd63c1682a8b86f75d706b995f75a20ab75ff6.nq.gz
    ├── 05c4e86455f1d6d766b7de623ccb3a280f9b94ce.nq.gz
    ├── 06498913629b7267f403f42be82026a74a8fcf5b.nq.gz
    ├── 06ebea91b41bf35619ebaadc1157b298c5d40cbf.nq.gz
    ├── 06fe761ae1009bddf91a59106552545b2402df6d.nq.gz
    ├── 0800643ca4c548b3e7afe74a7daade62f0548412.nq.gz
    ├── 08749dfb54400a70a98a87d5468bc10b07840854.nq.gz
    ├── 08cbb7fc6dbd7ccca8c9c137abaf3f49e18f3cb3.nq.gz
    ├── 08e52c10828a102acb7d73b1c038c8f93d0de880.nq.gz
    ├── 0913e93af0f42f73f9320bf865e58519d6256707.nq.gz
    ├── 097e8deff8ec7cb26ee46c793f196204326a3aad.nq.gz
    ├── 0ac92838a625c553d5ebfc94610dbfb9cf91f16a.nq.gz
    ├── 0b1d8269dd2976bf2bc743abd5a15273d670d004.nq.gz
    ├── 0c3a78530748193b2f20727e9c231cda77671a68.nq.gz
    ├── 0ccc186d0bf4126bd4a7f6c77721a980750833b8.nq.gz
    ├── 0ce2577be90e1233ff9412c29844e099329fc080.nq.gz
    ├── 0de048639ad454d4dc5aa028a26ba544c4385894.nq.gz
    ├── 0ed0dae80480d9aba3612141951b870a15fedcc4.nq.gz
    ├── 0f05ed4dbcff31c699712f9e08e16b1700365143.nq.gz
    ├── 0f5dfcdde2b628ffcefd907d7515b31a50578c46.nq.gz
    ├── 0f60b7bd0d9c395e1748cc962810d2dee9bb9fc2.nq.gz
    ├── 0f798af8108b53283accc422cd94749264a45b7c.nq.gz
    ├── 0fdb8c042b5973bb73c05c2e3babd7d6924face2.nq.gz
    ├── 0fdd91d8cdf0463426cdd15904dbd8341d437739.nq.gz
    ├── 1081dc1439fb984dfa7ef627afe3c7dc476fdbce.nq.gz
    ├── 10d4fa4630aff2fdc7d3337e7612b990edf87264.nq.gz
    ├── 10e3715e228450a5523da540b701a763d645c1fc.nq.gz
    ├── 11425f54fe111535933580574d038d0da63f1dc5.nq.gz
    ├── 114869132df06a257db27d206a83f0323fe5aae7.nq.gz
    ├── 11ed68fa7fedc08d478e7677f17cdb135c802286.nq.gz
    ├── 133c1a39c73f9cf7b842713ba888f530a302adbf.nq.gz
    ├── 13a7eb5bfacc2f04cfe4841429f59c2ea9ab5302.nq.gz
    ├── 13f32c9e425371071991fca633bc73fea97dddb2.nq.gz
    ├── 14326468943bf6fbf00d73b4acb0ae11d041ae05.nq.gz
    ├── 1446d245209b85063776231278c4c7ad5fe567ff.nq.gz
    ├── 1489fbc145c3a99d09c147af1b97cee108ec7cb9.nq.gz
    ├── 14bebd83b32fd3e2b7bc11de88c33cdbe1c2a539.nq.gz
    ├── 1568ada2642507399096f4f92fb56125d0dd3620.nq.gz
    ├── 159ffea1aa95932c5053b50ba729896bc6cfe2f0.nq.gz
    ├── 1618bb99b25ccbf289f3999b7bb1e789cffe7c5a.nq.gz
    ├── 162464465f9ebf5866a68f1561f6458c6304dfff.nq.gz
    ├── 171ec6493b8a17a78ee27dda77d896398d464ae5.nq.gz
    ├── 1764419d8d796909887bcee184165b64887468ad.nq.gz
    ├── 17995f96c502053ced1aeed7b11cea9530ba99c8.nq.gz
    ├── 17d584f11bc4eafb8b163faad90663ea0f92c764.nq.gz
    ├── 186e20deca8375d9eeb64e02f83e4d598770c976.nq.gz
    ├── 187039ebece275c1504481084ba41c027de7949d.nq.gz
    ├── 18ce7b0afd36a61870c1c8c5b2ada27c6f5118da.nq.gz
    ├── 1946791845a84b36d4a1f694de87f892c510a248.nq.gz
    ├── 199a17f64e31eb291ef9799510bbe1dad281f10f.nq.gz
    ├── 19dd8210d0a47c1d32d826e7188282c4ca956ab7.nq.gz
    ├── 1ae242a6eab5c126b84e09843b1445d95df72228.nq.gz
    ├── 1bfc3a9772a9eca96b940378f6a946e41cc8b8eb.nq.gz
    ├── 1c2e0b7dc6db835268a10f6e7e34733786b6e986.nq.gz
    ├── 1d95cafb9b6356aa742a124e12736367bbeb0fd7.nq.gz
    ├── 1e28af863ccf7221dea6b32d15dae787da7d0965.nq.gz
    ├── 1e627d2f7a6a048cba95e15849f512b481f7a55d.nq.gz
    ├── 1f24a19e4ccfd08f639f35aa26a757bb77963f44.nq.gz
    ├── 2078c2937513c1fd99a141131946638390b0fd19.nq.gz
    ├── 218e762b650318f461da087eda6ad0a961987164.nq.gz
    ├── 22cc1e51886f502dd625fadeda8747141637f563.nq.gz
    ├── 23905ddc55466dd3e41acdaf083b0fbf45a78768.nq.gz
    ├── 241b68ee235e59d6431b00265fc6b01e311991b8.nq.gz
    ├── 249a3b3a5fdd672f35f899647aef857cc87e3b46.nq.gz
    ├── 26cc9724baefb1205fd635468dfa612322330574.nq.gz
    ├── 271bbd37778a752ec7dd8d0494a1639cfcad9001.nq.gz
    ├── 2765f931d84ef20619871fca7f1aa0a8245d23a8.nq.gz
    ├── 27fd381d82516af0e0f52d32e8422bb31114edea.nq.gz
    ├── 2858c5e441983add7f8ab0a444fdceb0016d1136.nq.gz
    ├── 28bdb4147b9f7f7ed3298a22e8c325e32183583d.nq.gz
    ├── 292208a56560c7e07e110828b942ef6d330546a5.nq.gz
    ├── 2960b0f3f74fa0ec83053224da3686c9040f10cb.nq.gz
    ├── 2a22389e3b2aaccbb06cc9a8ecfca93d0a56c8bc.nq.gz
    ├── 2a7da6e2a8e3b8daf8e2a51968cfc8083b0a6628.nq.gz
    ├── 2b2ff8f33e9a9af7c5f9ef775e84ed5a85805ce2.nq.gz
    ├── 2b32b12be9c23c2b6aa5100c4079f449e39b1d0f.nq.gz
    ├── 2b5c74c0bda0b2e625d063df727688abbdf897b7.nq.gz
    ├── 2b87e572a3d20e5be5372885b2b2100dd91a8bf1.nq.gz
    ├── 2c60973e7b708dc511ccb6a88ea147937df5b926.nq.gz
    ├── 2c9305657a40e69ceb23785da8a32fbb2aaa5a9f.nq.gz
    ├── 2d1f0feda22ae87613b2aff95ea7a2fe1794e27c.nq.gz
    ├── 2d59669373b332ccd6dd25beb2159a962f8e0407.nq.gz
    ├── 2d8e61e5c66588dd1aea635d060ce5f13c29c174.nq.gz
    ├── 2db571f7b783c0adb7709bb92565b835e6ba9ef6.nq.gz
    ├── 2e13b130345c49238816919bc239505fe0067e00.nq.gz
    ├── 2e1c58458f14db0285cd229e2007e3f0dd3e6397.nq.gz
    ├── 2e81e03c765dbee1ed8854cb44b14e3e5638cb55.nq.gz
    ├── 2ee4718cb70f05202a426fefb0dc4f9da130e9c3.nq.gz
    ├── 2fad89ec41e5bfa2f2cce14e24532128ce20f98f.nq.gz
    ├── 2febd5ef6e22284330f45ad73ee65942c3deb23e.nq.gz
    ├── 30d4e3adc827796f447f3069adef1aa36a432723.nq.gz
    ├── 30ec04082d9cb5ff9c64447689b71beea9ee22be.nq.gz
    ├── 314044191837bb6945a35406a8cf6ffffdf07892.nq.gz
    ├── 31b68b1216dcb308e8aa3793ce3a21e30d19866c.nq.gz
    ├── 321493720c5ed7f4d0371804555e75198a50a4d4.nq.gz
    ├── 3368da2ea931348a1fd8ac0dbec71bd8de564509.nq.gz
    ├── 34b0a2f6b0cf01671aff67c630fd44023d6fe9b6.nq.gz
    ├── 356442a20fcf435895939f36a5a388d83b451873.nq.gz
    ├── 387df5bd11a5d2aad111f6c9ba0348f33a96b8f2.nq.gz
    ├── 392e675920071bd63b4a414351bbdcb009df0874.nq.gz
    ├── 393d270c649e965be5a2f217ee8f68bbdb51b377.nq.gz
    ├── 395d8cb052d7e446e5610a50b82b34c661cb7c54.nq.gz
    ├── 398ed7e4c5608849139d4f71e96c9def42d4a37c.nq.gz
    ├── 39b1788551576e4a9810c337d65bc6966a31e8bc.nq.gz
    ├── 39c8ea29639f997179fe411407ce290a39f900bd.nq.gz
    ├── 3bd96d1a073169f29fadbac716414f9964a8465f.nq.gz
    ├── 3be2346898cddc53f9021b82842c7edee29b7f30.nq.gz
    ├── 3bf804d5434cea45f56b60816f05a58e16bbffa5.nq.gz
    ├── 3c08e300a6d8509a855bb52757881e7e90383a59.nq.gz
    ├── 3cc833b89a5866f4126f9c05613a7bef0dfc8594.nq.gz
    ├── 3d30c187a6e7bb05b8daf1d6e51e333c94baaa20.nq.gz
    ├── 3dab6dbde1243de8a87fdc253ae250f06795f7bb.nq.gz
    ├── 3e552ad881dc4d825746d7f3ddd6ae8c1c5eebaf.nq.gz
    ├── 3e572ebed1496514a3662933c80387e02237e7f6.nq.gz
    ├── 3f5726577ae427d535e3ec14c277491a602e8c64.nq.gz
    ├── 3febf07a966c6cb9f3747dd0c3e75b0b27ee457f.nq.gz
    ├── 415dbd122636262862f2bc4df57904bf98d1d346.nq.gz
    ├── 41f9a98ae1881d04849824fe8a2a275282989d24.nq.gz
    ├── 42be3ce8440e69942ef007536ccabd41278cec57.nq.gz
    ├── 42f9d928d87c801c076cd215dae74c1b78e91b3e.nq.gz
    ├── 4335d55dca1bdc5f04c810578b1dcfca7d0466ea.nq.gz
    ├── 4391c89a6ad1043f2d5f36ec3c1383b10daf08ce.nq.gz
    ├── 4406923a66862f292e1b1177b8efff9c0c65c64b.nq.gz
    ├── 44540f6d4fe1149b206f997c21f364aabfcbb9d5.nq.gz
    ├── 4561f2b068339421843c650742240dd28e0157ca.nq.gz
    ├── 459479587c5f577d11507636b6779085ea9bfc65.nq.gz
    ├── 472adba196449d6a54a0224fe8012ffc9de8080d.nq.gz
    ├── 473352d70fae172c7a303580602ea8be2ccfd564.nq.gz
    ├── 47672b40ddcbfa5e90cb85adfc90c24cfbd020c9.nq.gz
    ├── 477b056f122c457f2d5b799823edb17f88d2a2c3.nq.gz
    ├── 48665eecdbc1fde8adef5bff78f579ed8eb67373.nq.gz
    ├── 489290b6730d72648b7a748c5c2984aa7af3c2a5.nq.gz
    ├── 48c0da56306a1b88b57f66ee208d0ebe61ec1261.nq.gz
    ├── 49fcebecf7656cf715ae2448c5636954219b4ee1.nq.gz
    ├── 4ab4c3a75a2178df4ace7464c9ee7d84c295aa3c.nq.gz
    ├── 4abf830eaeed7664e03c8c027a6a65baf90bd852.nq.gz
    ├── 4b582dbcf5baa17c22baa4d9a1496c43bd27e05f.nq.gz
    ├── 4bfae23692633b119a0f1ad49dfb0b613a43d8aa.nq.gz
    ├── 4c11c73b4bfb6ded0c55500a02454aec2b3a8f41.nq.gz
    ├── 4c6d858d71264db3a49901ef1102081442540821.nq.gz
    ├── 4c6f4292801ab6ced90abdbfa8a5792387db3501.nq.gz
    ├── 4d71696372d6d3dd6fb580b02e90bcc262e93fa4.nq.gz
    ├── 4f1e31c124dfcbbdc18ed37090178013ad95f2bd.nq.gz
    ├── 4f2e0aef60297865cbed3f83208d524f92f3afdb.nq.gz
    ├── 4f32ab66f70d96b9c6e717babf327418192b9679.nq.gz
    ├── 4f9f4510fd18352fc28aadf9b91477c9cd01d9f8.nq.gz
    ├── 4fa66f849e0ee6e736907e49eb1b81dcad54f2a8.nq.gz
    ├── 4ff403be06eb24706c20ed460e897b2a61dcc90c.nq.gz
    ├── 501793e01298604a646610da75c377d5ad2aad7a.nq.gz
    ├── 51f9159706d95259504afa55b3bff7c8e3b2cc53.nq.gz
    ├── 524d528342e35fcf725ba5aaf78ee85d951b8dd6.nq.gz
    ├── 526cf188a555b498c114c073bb1da644ac167f47.nq.gz
    ├── 52d78d9efe62717d529631ab25b56494389c520a.nq.gz
    ├── 53a107eac3298d0be5b06745c661f835ae291226.nq.gz
    ├── 53e868a2134bc9c4960884a313840c0fec8f860b.nq.gz
    ├── 53eac91b9741d7666a16c6af0062801ba71af9e2.nq.gz
    ├── 5597fe542c89cc5b4c1614978cec84ca4a05b572.nq.gz
    ├── 55ac707b8b81d8d975b24b48fa588d98eb26f2d8.nq.gz
    ├── 55e6c99126ac9fa9cd3f193b9a9bc4ba16745d7f.nq.gz
    └── 57f74a2385d10e69142754da1e97a0662ad0f5f3.nq.gz

6 directories, 200 files
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
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
