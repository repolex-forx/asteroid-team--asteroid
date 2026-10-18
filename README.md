# Repolex Knowledge Graph of asteroid-team/asteroid

RDF knowledge graph data for [asteroid-team/asteroid](https://github.com/asteroid-team/asteroid), parsed by [repolex](https://repolex.ai).

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
rlex download asteroid-team/asteroid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c15708a04d3d28e9a1cd50553c456299dbc6d236
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c15708a04d3d28e9a1cd50553c456299dbc6d236
│           └── chunk-001.nq.gz
└── blob
    ├── 00073c601234495534ab9a0c34a4825478ab5c1b.nq.gz
    ├── 00336bd6c9d9b2e27ff9c54fef38aebb9b4e9ebc.nq.gz
    ├── 00cd3a3b93f9339db75aef6cbf370e160c9d7191.nq.gz
    ├── 02071b61b520ca295b4fceb86ca3f322284968f7.nq.gz
    ├── 025d106f887afa1a6a70f38b3c0d46c9ac68e735.nq.gz
    ├── 038dfbc14640dce4cad62a88ec183304a53abd90.nq.gz
    ├── 03d885b5ba8df5cd70cd1bd2e3ebe4f0eb356e10.nq.gz
    ├── 04e4c6cc350718c08e3693bdc00ee175d6452eae.nq.gz
    ├── 05b2a17dc593508cc5e6ee839fda1663376c37a2.nq.gz
    ├── 05d311ddef58aac38d7fddcce6a3fa71f91f5dfa.nq.gz
    ├── 05e2728e8dfbafaaf607e07a03d9b40e1db64e40.nq.gz
    ├── 0617548bb18e73c45e37f73e4374282d31faba38.nq.gz
    ├── 0652cf34902b743273cec4413762bccb6a2f184a.nq.gz
    ├── 0655fc1043d5082d77c6d1fd7afb465beda56ba8.nq.gz
    ├── 0698cc106246fa49235033d07620b549afd4bfee.nq.gz
    ├── 06a2c0a6714bdf04fbbeb0c4ac7eefb147d1ff96.nq.gz
    ├── 0708f118d816bb6536f0a6c434070ea2ba36cd62.nq.gz
    ├── 0859d631904da4126b7c7d14a7ae9232c3493a4e.nq.gz
    ├── 08b997095c1076b86644df62e369fe8d7aa13ff0.nq.gz
    ├── 08bf96bfb631a78ee39113dc89a7c34b64c8780c.nq.gz
    ├── 0920945df394f0175a471e527279f88336809e8e.nq.gz
    ├── 0994fb6955cdb9c5c0251c3a35907bca380c97af.nq.gz
    ├── 0c29b25dd8f4fe5aaba72de29e4eaabbef9e9f02.nq.gz
    ├── 0e5c233f431f3ca595f5056c80afba21e76fae7f.nq.gz
    ├── 0ec082d1eb09084281e09c1c4b42e27f1184b444.nq.gz
    ├── 0f76d106bf499a25f17785decdac7f3582676e7f.nq.gz
    ├── 10f7a58a9235f855d3f79805d72e775cfb419956.nq.gz
    ├── 1190d9bf00fca6ae280ddb0cf058a0048abb30b9.nq.gz
    ├── 11ddba63ac79374283ade6efd7d9c7451aaa4dac.nq.gz
    ├── 1378ac10561d1aa1afc9501933aea959900113a7.nq.gz
    ├── 13aa10c7e27ac101737ef15168ebe97b35572a7b.nq.gz
    ├── 1495593d1af75d862626bf767eaaaac029dc6a98.nq.gz
    ├── 15297a247fe9a382cfdd584f4609bb018e6c120c.nq.gz
    ├── 155e57ce4bd46378468f7328ddde10d429b1e90b.nq.gz
    ├── 157dc2a6397bcc3df05b769649ee8634036ced2b.nq.gz
    ├── 16858b2c1fafc5718abaa478f34ee8433a299e43.nq.gz
    ├── 180bc0aa34e224baae8d4a79e802a4d8139cee39.nq.gz
    ├── 1920e9c04874217011fada37b97df86ad109c31b.nq.gz
    ├── 19bafc3191235e006a6fa900fe8701b903e34929.nq.gz
    ├── 19d9879a2f91db33d0e585aaf09abf7eb484b60c.nq.gz
    ├── 1b621598273d195cbf33f7c5e6710979cf0a4b2d.nq.gz
    ├── 1bd5dd5e87eacf70fd1c45eb66ea291f8f25f2d4.nq.gz
    ├── 1cc831404bebf149ba2fffb0b27e68dff0ee490f.nq.gz
    ├── 1e661e37356b00bff09086f5b36462c98c872eac.nq.gz
    ├── 1f3dd52b2c3f02f3178b64afd5b0d5ff59516551.nq.gz
    ├── 1fffa15f820830d03aed36680787c9fa00994976.nq.gz
    ├── 207c5b6b394c96de6afe0779f9c4bf4f27c91d92.nq.gz
    ├── 20a81e368ab0419e493170d6b0eccff66158d88f.nq.gz
    ├── 21c1f853009eb5521d1b0a891dc7aef7d11c33d8.nq.gz
    ├── 22186336e4bdbc674e52f0f5bef85b238e7a70b2.nq.gz
    ├── 223d66bfb81c55f06c57e23c0a3341f73797c3af.nq.gz
    ├── 22c2953a545d289ff753c46b0e9f602f48947d79.nq.gz
    ├── 2329ca587b9996e650d73973287da2817cd38c85.nq.gz
    ├── 23481aaffa70171d4b8b4b61cfbaa8a469a0902a.nq.gz
    ├── 23fe7e2386843c0c797ad50d6adadc4981820e4f.nq.gz
    ├── 243d9771aefa6e331e9c0d25a4aabb212031142c.nq.gz
    ├── 24aa30e718b2886e1ae46d92d25aea6758512685.nq.gz
    ├── 24dfd3a4887c867bffbfd35e7041f01184f46f9c.nq.gz
    ├── 25c0c2114410e8fbc0109136aa23d1b266485e02.nq.gz
    ├── 26680b93183a590495240648a98f6f87810fb916.nq.gz
    ├── 26a4693d99af8f45c6513b9227bf87a429a1bae1.nq.gz
    ├── 26a8bf0961f995601b666ac336014fe7ddb60b92.nq.gz
    ├── 27e545daa54b0d55aeef6f553b6e7fac867b6cc2.nq.gz
    ├── 2845989143fe07a5b68c2ab1350ddb1f90ac6b71.nq.gz
    ├── 28651e9989644ac391d398a20df0c86dc6809998.nq.gz
    ├── 28a3bb7c562cc750c7cc7815f653ee6501724a23.nq.gz
    ├── 290ad802da0cb7714ecef921c5081111e1152d9a.nq.gz
    ├── 2938993dcfbcb4f34974980c1d8cff84e43547ee.nq.gz
    ├── 29986e24ff58e2b4585fe8251f2eb655fc24b294.nq.gz
    ├── 2a0a8ceffea95db487c7c192f4fa31ac749b391a.nq.gz
    ├── 2a418d6ff16920dec12054f841e743e8cc4a7980.nq.gz
    ├── 2bb811b6b3a93b88ea8a96f3bc6663b0886ffef4.nq.gz
    ├── 2ce45cb4d2ba31861a7d3b830c048dfdd1b19760.nq.gz
    ├── 2daa9fcef17777802f799a5b06940146618ccd1a.nq.gz
    ├── 2dd9b4fccf561bdf5d01ad1d43909439d4145679.nq.gz
    ├── 2debdf87eb07e69c0a7f31f1d3403dd98649bab5.nq.gz
    ├── 2e170f0317b74d2fbfda0c266a9e697435cb1eea.nq.gz
    ├── 2e960303f93d322d43a506c5f72d3dc92f9628a5.nq.gz
    ├── 2ec99773c4f7192bacd21853404fd92e219221a0.nq.gz
    ├── 321d09c12455bc84841464b1aac932596faeb5f7.nq.gz
    ├── 321ff67d7816f3ba1ab680af2c91b54f07fd752a.nq.gz
    ├── 32ea2358c6a27853fdbab94a0d6d5f57e7ace28e.nq.gz
    ├── 3426c9b29768841c159eab3a637a92866acb9a44.nq.gz
    ├── 3461a9c40794943456d50653ef8ed5fd461008ec.nq.gz
    ├── 346d0bb3d19a7a2d202906b9d90295c21cc45747.nq.gz
    ├── 3472be8c1252d376b2f5ce95fed875edbd759db6.nq.gz
    ├── 3484c2b247b0e965f06ab8fba7cc8b20d4194f17.nq.gz
    ├── 34a53dece0abf97a2164d5f2a5938c58fe4331e4.nq.gz
    ├── 34d810fd557e5ad63064966424c5d5190d84a8d9.nq.gz
    ├── 35a4b35d60861364dabb7b1d575686116fb7b3e2.nq.gz
    ├── 35cb1c6cf9c89d238eed7fe21f05c29e3c79a1ad.nq.gz
    ├── 362b7464da7325a1647e57f3f5ce3913300c97f9.nq.gz
    ├── 364c77672cfa568167568c34bea41324c6c44cb9.nq.gz
    ├── 370e20f3104748a26512ed80636f9a3a2529fc62.nq.gz
    ├── 3802008afdd9b2df56182b2781f70845d93ef46d.nq.gz
    ├── 38865efa07949c240418d9def115097300379dbd.nq.gz
    ├── 39b4c3854ee6d2ab63d4a4ea0517c2e34052f00a.nq.gz
    ├── 3a6119579a6a5e330199b98f09a3ec292e68db3c.nq.gz
    ├── 3bb4a066db1ec1dd3b3beb3f9827c5868866a922.nq.gz
    ├── 3bf7a89ed9b237a0ee59942a6707f98a504d9b5f.nq.gz
    ├── 3c66b75441cd886c5b10826afe095bc6e62ecdb0.nq.gz
    ├── 3d1a09924a04236e0995a5cf846679f82bb019d2.nq.gz
    ├── 3d51becd1a66ea68d18d5f98e8c153535dd9dd3c.nq.gz
    ├── 3d83344159410ee71902e5ae61d6295d0d908de0.nq.gz
    ├── 3dc223334bd904194a1e402a00fc5847751f182d.nq.gz
    ├── 3fa07ad02eb1b61bd7f42d37f2a65e4153eebed4.nq.gz
    ├── 4041b1d301dfc3395d8ed3196782a79fe359fd72.nq.gz
    ├── 411b96c5cdbe0b76f8077d68b726bbd612cd1917.nq.gz
    ├── 41200cbda2c250bdcb36bc9f38ed1739d932ab56.nq.gz
    ├── 412b3da2a0447ce344fcca132faaf7b544503e88.nq.gz
    ├── 41dadeb6716f78be2a30fa09e203f280b42b6edb.nq.gz
    ├── 41eae2fc72f329bf0c0d8c4f401b6cfde4c7b7cb.nq.gz
    ├── 4213bccc5103bacb876f8f8024890487fd677343.nq.gz
    ├── 425caef599b2d8305689151055207d857a8c3290.nq.gz
    ├── 429168e80c63894ad10e6ccdddec82e6538b2c33.nq.gz
    ├── 43ca06f90b5014c2216e3f0bcc937e76dd7f6d25.nq.gz
    ├── 442700cfd3c7bdc5219b1e36959ef564cd3d27f9.nq.gz
    ├── 4526b485bd293c884de98faa42ee5ea142e3c609.nq.gz
    ├── 455510b0cd5370abee7bba27d4dba751d85a6464.nq.gz
    ├── 45b6d39f180176d5eefca93884f0339833c505fa.nq.gz
    ├── 4635fd12e298bdd290291acf56fef9406fb69ecc.nq.gz
    ├── 463ed6ea4f57f65d02bb503f775557158797a11c.nq.gz
    ├── 46ced4dac81991e1c4fa0d35aea0a4cb6b8758fe.nq.gz
    ├── 47250dc44d3ba6a73192777071972dbd0553fa05.nq.gz
    ├── 47550f0c07174e7f519b6c9b3b51e2e26e8f8cdc.nq.gz
    ├── 47615aa4b838b0aa1060d7da83813c59da7e7291.nq.gz
    ├── 47f69e802584dd75ee36dfa913c15decc43df1c9.nq.gz
    ├── 489d02b8f6cbb5c02521e064582671bb2dbfb6d1.nq.gz
    ├── 496f571e9b179430319a765308e7ed07d0e913cd.nq.gz
    ├── 4a2ab69c9ccb6a2dff138e7d8820af05405487e2.nq.gz
    ├── 4a46f889ebfdf6e6bab0ee0f99c93cf9c4155fe7.nq.gz
    ├── 4aa63456bde08b30b11aa97bade4fccf2668498e.nq.gz
    ├── 4b7e0c48c99dc31e98b47d7daf306e2c0e28e8c5.nq.gz
    ├── 4bba4b19e6cf0f83ebdb0526093b0fc262f1a33f.nq.gz
    ├── 4c533b8b1f25943a43daac8bb3a8cd24d0149ee3.nq.gz
    ├── 4c5dba5cc35fd2671b4adff4e24dd7f6159e62fe.nq.gz
    ├── 4cdc3f09859a86842e6995031acff0a3d665dc97.nq.gz
    ├── 4d09a4623e55bc2b91736d745434074eec5d6af3.nq.gz
    ├── 4e14500d427bc1bae22ad2555459ee5dfac1638d.nq.gz
    ├── 4e2821de811ad119fd28ba2ff64e170ffed92f86.nq.gz
    ├── 4e2ff7ce08d97ee61410698976e8f2d9e9b73adb.nq.gz
    ├── 4e3cc66e9fdc74d52810f557858908dd3c251403.nq.gz
    ├── 4eecf16e1ce7ac9154d8620e5b23ed43d8360bd4.nq.gz
    ├── 5062f84de9fb39d3308771a83261fc2242b2b470.nq.gz
    ├── 51bcf82d64ca5fa598702d94c52b3234e739daf9.nq.gz
    ├── 51da4a0c0f089bab3f619fc4929de7189f26b7c0.nq.gz
    ├── 52f9456119c4b0b74908699d2d17f100899852d1.nq.gz
    ├── 535b11f2bbed835a4332c831c6b0fd4fa6a3a5e3.nq.gz
    ├── 536232fccd6cde5036c961f6cf1addd5d93175dc.nq.gz
    ├── 53a382d597f0fcd72728305439b09ee95e57af2d.nq.gz
    ├── 53ccddc2b7fa254ccd1adb7344e3aecc12ffe995.nq.gz
    ├── 545097c73f28796a130804f38443a0544afc84e1.nq.gz
    ├── 5472371fd7dae1f8e5dc1daca214bd0dded22b74.nq.gz
    ├── 547b0b547662fa38eb463cdd543dbe437db4dfd5.nq.gz
    ├── 548a1dfcbb5e3fe22730c93fda22dfd63e4da85f.nq.gz
    ├── 5535c077b2f776794ba219e0afbe6cdc55dc15f2.nq.gz
    ├── 5768a7442fc9cdf6cc66216b82c4f8c55a3ba163.nq.gz
    ├── 590a1999e27ff3e072d0cd418e1c4262428f2ea9.nq.gz
    ├── 591691c8f24d955a9587db0b2ad585ef18c625c6.nq.gz
    ├── 5971625a3ccc1afe4fd42da9a59b309b5458e246.nq.gz
    ├── 59e717daad3b5bae7a653c9a49bf4990f6f99912.nq.gz
    ├── 5a397162f5cb5574e1173a522c8d084a99dc581c.nq.gz
    ├── 5a45d2db00cdca5027b19ad6d4ddf239474f9bd2.nq.gz
    ├── 5a7ea29e18fd6a61b0f2236a4dc7532e22fe08b3.nq.gz
    ├── 5a992aae869ba1c87cbf3839f0f6dc3f070b78b5.nq.gz
    ├── 5b79232cd11cfa0f09d41529e151aea39461e7aa.nq.gz
    ├── 5c5f9251bf1e12ab551060f353c1de86b8b29648.nq.gz
    ├── 5d7d7306b0e775e149bccb25b53f81f567777893.nq.gz
    ├── 5ead0c9be1e63a98e4554ac36a332376a4b1e029.nq.gz
    ├── 5ec45b82712760bd1df06fab34f5b9bb0c8365c0.nq.gz
    ├── 5ff2bf0a64161cef836c71c2e97626538b6df776.nq.gz
    ├── 6056688f79a2e959b78565b168804702909eea40.nq.gz
    ├── 6191f4f6eabf29967c06161fff8e0820187eb266.nq.gz
    ├── 61e6873c96805577d7e45c3bc78f9c825dceaeac.nq.gz
    ├── 626963d1b0dd8dbc53075b46f4bd5d42acead437.nq.gz
    ├── 62a5494c048379761a1c7766e69dbdaf5a7caf42.nq.gz
    ├── 632328726408db51b489edeec8b44e2515129fcd.nq.gz
    ├── 63906c06df187529a65d686741385bc2c100d7a8.nq.gz
    ├── 641c9aa97799eda784b04b2ba1bf479bcfd94749.nq.gz
    ├── 65bef3de6d252cef61c51682c853bd5c0eaeab02.nq.gz
    ├── 668fd1c514d91c904b26962a2334f026c8dbba0c.nq.gz
    ├── 66c07eb3fe047c6672163e924945d65fbef5e285.nq.gz
    ├── 66ea92fa10ea1d9c2e494403d07650e7c4fd67bb.nq.gz
    ├── 67614f341f821d23466d96ea49cd25005d8454d7.nq.gz
    ├── 67617d46adf8bbbf0bd6e182d8bfb1af3e7bbd9f.nq.gz
    ├── 678d92f8883f2f387ab59aa062e2ae9ec2372308.nq.gz
    ├── 680a34d1ab0559bd2a2d3df3c0fb9f16a77ed562.nq.gz
    ├── 68794dbe2698b3acae0c4f23e79898b65697bb7a.nq.gz
    ├── 68b11d71e041e0c487a7ddb65f4d69ec962e2bf5.nq.gz
    ├── 69ef973a1d4ec4deb1514dd7160623be6e7e3860.nq.gz
    ├── 6ae75d95dfa4fc62db698156951f314d6eb09783.nq.gz
    ├── 6b6270e53f3643b93db1d5b42b3502fd0002a39a.nq.gz
    ├── 6bb9abc5fd509f16fad0a9477a8a0c6438ef8609.nq.gz
    ├── 6c0f249b929ccf9a5a3096b2d3c69661b715d5a4.nq.gz
    ├── 6d180fad105c6c918038dbabe23687d2018587a6.nq.gz
    ├── 6d65c2ec80762ae5c7aa172cc6a9795b17b81fcf.nq.gz
    ├── 6e065bd6a2c8b0c50867b8e8721a02a2a6b1f129.nq.gz
    └── 6e37217d7f581631b395457c2970796f428d624c.nq.gz

7 directories, 200 files
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

[asteroid-team/asteroid](https://github.com/asteroid-team/asteroid)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
