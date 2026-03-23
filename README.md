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
│   │   └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
│   ├── lsp
│   │   └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
│   └── repolex
│       └── f930a7821eff188a663252c390fa5ad2319d31c1.nq.gz
└── blob
    ├── 00cc0c357bc43f1370c5812880312b8850012fa4.nq.gz
    ├── 0193276f0e90a5b50ab473e4d0c12592f4d6e003.nq.gz
    ├── 0294b3f8972ec96e8b33c128875c12d05392e387.nq.gz
    ├── 039353814b491be2717811f7643f7959271de727.nq.gz
    ├── 03991fa398e498638ded8b883dad2b7c3df37db3.nq.gz
    ├── 03c90b79603fb7a8ab3ed7b8f9fe1d67d0f4697e.nq.gz
    ├── 0495a6c9dc1e0d44883dbeda2e6467d3cc97d042.nq.gz
    ├── 05c4e86455f1d6d766b7de623ccb3a280f9b94ce.nq.gz
    ├── 06498913629b7267f403f42be82026a74a8fcf5b.nq.gz
    ├── 06ebea91b41bf35619ebaadc1157b298c5d40cbf.nq.gz
    ├── 0800643ca4c548b3e7afe74a7daade62f0548412.nq.gz
    ├── 08749dfb54400a70a98a87d5468bc10b07840854.nq.gz
    ├── 08cbb7fc6dbd7ccca8c9c137abaf3f49e18f3cb3.nq.gz
    ├── 08e52c10828a102acb7d73b1c038c8f93d0de880.nq.gz
    ├── 0913e93af0f42f73f9320bf865e58519d6256707.nq.gz
    ├── 097e8deff8ec7cb26ee46c793f196204326a3aad.nq.gz
    ├── 0b1d8269dd2976bf2bc743abd5a15273d670d004.nq.gz
    ├── 0c3a78530748193b2f20727e9c231cda77671a68.nq.gz
    ├── 0ed0dae80480d9aba3612141951b870a15fedcc4.nq.gz
    ├── 0f05ed4dbcff31c699712f9e08e16b1700365143.nq.gz
    ├── 0f5dfcdde2b628ffcefd907d7515b31a50578c46.nq.gz
    ├── 0f798af8108b53283accc422cd94749264a45b7c.nq.gz
    ├── 0fdb8c042b5973bb73c05c2e3babd7d6924face2.nq.gz
    ├── 1081dc1439fb984dfa7ef627afe3c7dc476fdbce.nq.gz
    ├── 10e3715e228450a5523da540b701a763d645c1fc.nq.gz
    ├── 11425f54fe111535933580574d038d0da63f1dc5.nq.gz
    ├── 11ed68fa7fedc08d478e7677f17cdb135c802286.nq.gz
    ├── 13f32c9e425371071991fca633bc73fea97dddb2.nq.gz
    ├── 14326468943bf6fbf00d73b4acb0ae11d041ae05.nq.gz
    ├── 1446d245209b85063776231278c4c7ad5fe567ff.nq.gz
    ├── 1489fbc145c3a99d09c147af1b97cee108ec7cb9.nq.gz
    ├── 14bebd83b32fd3e2b7bc11de88c33cdbe1c2a539.nq.gz
    ├── 1568ada2642507399096f4f92fb56125d0dd3620.nq.gz
    ├── 159ffea1aa95932c5053b50ba729896bc6cfe2f0.nq.gz
    ├── 1618bb99b25ccbf289f3999b7bb1e789cffe7c5a.nq.gz
    ├── 17995f96c502053ced1aeed7b11cea9530ba99c8.nq.gz
    ├── 17d584f11bc4eafb8b163faad90663ea0f92c764.nq.gz
    ├── 186e20deca8375d9eeb64e02f83e4d598770c976.nq.gz
    ├── 187039ebece275c1504481084ba41c027de7949d.nq.gz
    ├── 18ce7b0afd36a61870c1c8c5b2ada27c6f5118da.nq.gz
    ├── 199a17f64e31eb291ef9799510bbe1dad281f10f.nq.gz
    ├── 19dd8210d0a47c1d32d826e7188282c4ca956ab7.nq.gz
    ├── 1bfc3a9772a9eca96b940378f6a946e41cc8b8eb.nq.gz
    ├── 1c2e0b7dc6db835268a10f6e7e34733786b6e986.nq.gz
    ├── 1d95cafb9b6356aa742a124e12736367bbeb0fd7.nq.gz
    ├── 1e28af863ccf7221dea6b32d15dae787da7d0965.nq.gz
    ├── 1f24a19e4ccfd08f639f35aa26a757bb77963f44.nq.gz
    ├── 2078c2937513c1fd99a141131946638390b0fd19.nq.gz
    ├── 218e762b650318f461da087eda6ad0a961987164.nq.gz
    ├── 22cc1e51886f502dd625fadeda8747141637f563.nq.gz
    ├── 23905ddc55466dd3e41acdaf083b0fbf45a78768.nq.gz
    ├── 249a3b3a5fdd672f35f899647aef857cc87e3b46.nq.gz
    ├── 26cc9724baefb1205fd635468dfa612322330574.nq.gz
    ├── 2765f931d84ef20619871fca7f1aa0a8245d23a8.nq.gz
    ├── 27fd381d82516af0e0f52d32e8422bb31114edea.nq.gz
    ├── 28bdb4147b9f7f7ed3298a22e8c325e32183583d.nq.gz
    ├── 292208a56560c7e07e110828b942ef6d330546a5.nq.gz
    ├── 2960b0f3f74fa0ec83053224da3686c9040f10cb.nq.gz
    ├── 2a22389e3b2aaccbb06cc9a8ecfca93d0a56c8bc.nq.gz
    ├── 2a7da6e2a8e3b8daf8e2a51968cfc8083b0a6628.nq.gz
    ├── 2b2ff8f33e9a9af7c5f9ef775e84ed5a85805ce2.nq.gz
    ├── 2b5c74c0bda0b2e625d063df727688abbdf897b7.nq.gz
    ├── 2b87e572a3d20e5be5372885b2b2100dd91a8bf1.nq.gz
    ├── 2d8e61e5c66588dd1aea635d060ce5f13c29c174.nq.gz
    ├── 2e13b130345c49238816919bc239505fe0067e00.nq.gz
    ├── 30d4e3adc827796f447f3069adef1aa36a432723.nq.gz
    ├── 30ec04082d9cb5ff9c64447689b71beea9ee22be.nq.gz
    ├── 31b68b1216dcb308e8aa3793ce3a21e30d19866c.nq.gz
    ├── 3368da2ea931348a1fd8ac0dbec71bd8de564509.nq.gz
    ├── 34b0a2f6b0cf01671aff67c630fd44023d6fe9b6.nq.gz
    ├── 387df5bd11a5d2aad111f6c9ba0348f33a96b8f2.nq.gz
    ├── 393d270c649e965be5a2f217ee8f68bbdb51b377.nq.gz
    ├── 395d8cb052d7e446e5610a50b82b34c661cb7c54.nq.gz
    ├── 398ed7e4c5608849139d4f71e96c9def42d4a37c.nq.gz
    ├── 39b1788551576e4a9810c337d65bc6966a31e8bc.nq.gz
    ├── 39c8ea29639f997179fe411407ce290a39f900bd.nq.gz
    ├── 3be2346898cddc53f9021b82842c7edee29b7f30.nq.gz
    ├── 3bf804d5434cea45f56b60816f05a58e16bbffa5.nq.gz
    ├── 3cc833b89a5866f4126f9c05613a7bef0dfc8594.nq.gz
    ├── 3e552ad881dc4d825746d7f3ddd6ae8c1c5eebaf.nq.gz
    ├── 3e572ebed1496514a3662933c80387e02237e7f6.nq.gz
    ├── 3febf07a966c6cb9f3747dd0c3e75b0b27ee457f.nq.gz
    ├── 415dbd122636262862f2bc4df57904bf98d1d346.nq.gz
    ├── 4391c89a6ad1043f2d5f36ec3c1383b10daf08ce.nq.gz
    ├── 4406923a66862f292e1b1177b8efff9c0c65c64b.nq.gz
    ├── 4561f2b068339421843c650742240dd28e0157ca.nq.gz
    ├── 459479587c5f577d11507636b6779085ea9bfc65.nq.gz
    ├── 472adba196449d6a54a0224fe8012ffc9de8080d.nq.gz
    ├── 473352d70fae172c7a303580602ea8be2ccfd564.nq.gz
    ├── 477b056f122c457f2d5b799823edb17f88d2a2c3.nq.gz
    ├── 48665eecdbc1fde8adef5bff78f579ed8eb67373.nq.gz
    ├── 489290b6730d72648b7a748c5c2984aa7af3c2a5.nq.gz
    ├── 48c0da56306a1b88b57f66ee208d0ebe61ec1261.nq.gz
    ├── 49fcebecf7656cf715ae2448c5636954219b4ee1.nq.gz
    ├── 4ab4c3a75a2178df4ace7464c9ee7d84c295aa3c.nq.gz
    ├── 4abf830eaeed7664e03c8c027a6a65baf90bd852.nq.gz
    ├── 4b582dbcf5baa17c22baa4d9a1496c43bd27e05f.nq.gz
    ├── 4c6d858d71264db3a49901ef1102081442540821.nq.gz
    ├── 4d71696372d6d3dd6fb580b02e90bcc262e93fa4.nq.gz
    ├── 4f1e31c124dfcbbdc18ed37090178013ad95f2bd.nq.gz
    ├── 4fa66f849e0ee6e736907e49eb1b81dcad54f2a8.nq.gz
    ├── 4ff403be06eb24706c20ed460e897b2a61dcc90c.nq.gz
    ├── 501793e01298604a646610da75c377d5ad2aad7a.nq.gz
    ├── 524d528342e35fcf725ba5aaf78ee85d951b8dd6.nq.gz
    ├── 526cf188a555b498c114c073bb1da644ac167f47.nq.gz
    ├── 52d78d9efe62717d529631ab25b56494389c520a.nq.gz
    ├── 53a107eac3298d0be5b06745c661f835ae291226.nq.gz
    ├── 53eac91b9741d7666a16c6af0062801ba71af9e2.nq.gz
    ├── 55ac707b8b81d8d975b24b48fa588d98eb26f2d8.nq.gz
    ├── 57f74a2385d10e69142754da1e97a0662ad0f5f3.nq.gz
    ├── 57ff68a23a89f8d210e36af71daf3c1154b3db74.nq.gz
    ├── 59fdeae2b2c234b95c94948583011b71a96f73b7.nq.gz
    ├── 5a0190a19a3e4d1ed3bdd92f056676cb68ed770e.nq.gz
    ├── 5a3faf0e87a90b2b5d3d808d9f791f51ee867547.nq.gz
    ├── 5b5e746aa3e582817cb7f572e5bd753d908a00e5.nq.gz
    ├── 5bc243bcfa33ca3b8a1ea8f9616bd77ae36adf38.nq.gz
    ├── 5c79d5afcfd23aedb42489b084e5885cadd8b821.nq.gz
    ├── 5ce14684682907b21753eaf71ac8b13d70944d23.nq.gz
    ├── 5e11caa2438dca65cef667b75f262d1e3f6ee28e.nq.gz
    ├── 5efefd62b43e4f11dd300be4355a4b413c7a70d2.nq.gz
    ├── 5f5e53984bf1e13f2a9a77e07885aad5905afc64.nq.gz
    ├── 611c8a886bfe4cca817a66f39f3e2b1aa69f6bb4.nq.gz
    ├── 61666ab1f093b0dd9e9446de2a0df8d0b631e583.nq.gz
    ├── 6184df61f66d72cf51de70a46b819318cfc08613.nq.gz
    ├── 62e208e356eeff740a57572e3e8d21e41e8b2d09.nq.gz
    ├── 6332fefea4be19eeadf211b0b202b272e8564898.nq.gz
    ├── 64cba241d1fdcac4aaae09ae0a274563446b3596.nq.gz
    ├── 657bdc5db50751d3a316689d9ebf3e894e42758e.nq.gz
    ├── 658c7117bb8c5f7f6127b82725880898c3d7fbb1.nq.gz
    ├── 65d8e31b0bd9a7e38ca1d6a811329685a144a838.nq.gz
    ├── 662b5c24b07703ffde3c6aef409fadc2fb8ba460.nq.gz
    ├── 6644e0b437ceed4d045ed9e0bfbda4250f6e83e8.nq.gz
    ├── 668f98c232abf0ec4caf0b8ab38801d034949290.nq.gz
    ├── 66f1957e52bd7379ca3ec61cfc24c2c093171fdb.nq.gz
    ├── 675294cfe3182595b58438744ef41d1f9fab276f.nq.gz
    ├── 687b8482bc1af7d60d763c947bd75d9bf6dbf62a.nq.gz
    ├── 69a87811b44e24c4be4c52fda41b62180344c44c.nq.gz
    ├── 6a7dced9dd33f61ef4d0820914fb9379fd332d95.nq.gz
    ├── 6a9ca4abf30eaf8dbea5235fb7bef94e4eb99efd.nq.gz
    ├── 6ab549a330687cda0d201cbe8cfaee873dd1a865.nq.gz
    ├── 6b33d1b78ba878d832bcb161267484c6ebc234cf.nq.gz
    ├── 6bb91397cc92f3e2aaaa99e320c17d415f18d315.nq.gz
    ├── 6cdd8e0a1c4f84213ba9024678cab502a6a2a912.nq.gz
    ├── 6f993b5e3da27708d913115f46f9e2f9d80b2f39.nq.gz
    ├── 71e48da9b288c10387f2459ba57f1a1bd77fb6f7.nq.gz
    ├── 71ea3b27f4c24d9177a0bb000d9bed7f88af9418.nq.gz
    ├── 71f25acc0d7ef63ff954b5bb74a9994a9ed29cc0.nq.gz
    ├── 721e04e34c7072738a2cff660206e0a3da0cff1f.nq.gz
    ├── 73305bf06243d724f9c4153a3eb05d8f551b3c78.nq.gz
    ├── 7542db1d1a57f9f3ccc6d5d4dc82ddada796e67f.nq.gz
    ├── 7615eaeaa882d528d9d0d8c13244132f526a0e09.nq.gz
    ├── 783f39facd52ffb9ac77d464f535f9c205bee375.nq.gz
    ├── 787632f084eb857c37042d92e2a04f10a036008c.nq.gz
    ├── 78b5f1df300e4c6e4162f0ad74dbbbae24e09368.nq.gz
    ├── 7966c957580aadccb98232963351ddb5a4431757.nq.gz
    ├── 79a4e02cd5f499628a0aff7d5f33cc62a7e76308.nq.gz
    ├── 7b8bdb709b978272b60fbfef458d6dd32f8fdef8.nq.gz
    ├── 7bd2284cde192df0870aa12ae0d69b8978da03f5.nq.gz
    ├── 7c2ac210d95ecd0ffb968bb5a3b6a7bd8fadee33.nq.gz
    ├── 7c465b7a7caba50deac64cc62b4d693fbb0d27c6.nq.gz
    ├── 7c52de92eec8ffd84a8feb45d5b7da313a7d47ae.nq.gz
    ├── 7c8395f06ae3e3997f991314d56a800dbc01a75b.nq.gz
    ├── 7e4a7fdea5bd231db428564bda2044969c7037de.nq.gz
    ├── 804fa226fe3ed9e6cc2bd044a848f33a2d7b4e4f.nq.gz
    ├── 8079f938c9fa5aede9a151439f136e267958ccd1.nq.gz
    ├── 811da68a8676c4225a60f09542d58ec547988baa.nq.gz
    ├── 82002eae732f8a87225b248ed9785c2ff91a5976.nq.gz
    ├── 83716f16e694c904468a49da7a90a4516cb99ce9.nq.gz
    ├── 83c8e04d21d73b242c0491d4df6c5477e113c76b.nq.gz
    ├── 8438c303da599dc3eaae47b590fb4a857b61d484.nq.gz
    ├── 84a4cd7314fd540acf9ca3dc8f58cf78c3bd29b4.nq.gz
    ├── 84d09877f1ebbb83310cc8b7cfefac3b3265b91e.nq.gz
    ├── 85c0ed40eb5b456350671cc2344f876f562ac509.nq.gz
    ├── 85eb965b967c3228feaffa37130bb1c9383986bc.nq.gz
    ├── 86293f3d0c70c749c1e416f3bb85476e34010235.nq.gz
    ├── 86925b1bb7ac87a42bd6bbbf5d30ad76900980d5.nq.gz
    ├── 87153716cd02b753d53523e231ebbd0ca808faed.nq.gz
    ├── 87b0c66a954286bd5c972a006bdae4a76bc5ee57.nq.gz
    ├── 8815af4935662b0e27d9fee2ac5f4fe0bec726fb.nq.gz
    ├── 89841c092babd0a0008a649fe2dcf7ae8479224d.nq.gz
    ├── 89b6ef9d159a2c9e043fd8cb42124e7c76ac2689.nq.gz
    ├── 89b8c5a2e05fcdb9614bf584d99be92a2f11e435.nq.gz
    ├── 89c8129a490b329f3165f32fa0781701aab417ea.nq.gz
    ├── 8b48d5e0f7978d38af401823725f09381b137b4d.nq.gz
    ├── 8d2ea9a8453c615b1a04a1f08b0c18071d453910.nq.gz
    ├── 8d83962eb3d5360af02b5ee94be2aa5a5fe9e2ab.nq.gz
    ├── 8d89ffab48b0ef21bfd0d1cad39fa4b3d9e08d78.nq.gz
    ├── 8f325914165f6bf5160b0d3e7e5a082141fc019c.nq.gz
    ├── 8f3ca2e2daf435edb66e57a0b8681aeda957c865.nq.gz
    ├── 8f682e09748052f38d8a8d6db5b8b0568e74e88e.nq.gz
    ├── 8f706621f1028838a13858fdda61a2d2a9ac785d.nq.gz
    ├── 8f797f4d91f0b5727118f24c61f7e86c7d322a7b.nq.gz
    ├── 8f81f3929efb824edcb3e6a5134c68be70038efb.nq.gz
    ├── 9065fa53b9b7ddae495f584e24b3a79d9949417b.nq.gz
    ├── 91952a0f87263a7bca2b962e3e1ee3c24d9ef78b.nq.gz
    ├── 9199e6fa6cc9744c046b08378b831c2d14ab5d41.nq.gz
    └── 928957aa3c01701a9b842138a93ee8474afb779d.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
