# Repolex Knowledge Graph of whylabs/whylogs

RDF knowledge graph data for [whylabs/whylogs](https://github.com/whylabs/whylogs), parsed by [repolex](https://repolex.ai).

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
rlex download whylabs/whylogs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 976bc4c15ca1d4a0199360b8d7708b63e4adaa6d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 976bc4c15ca1d4a0199360b8d7708b63e4adaa6d
│           └── chunk-001.nq.gz
└── blob
    ├── 0009e36078325f506e72e1325d56f411464c7275.nq.gz
    ├── 01a39ce49dd37ab82789b1d5073c16cab4e6d5e5.nq.gz
    ├── 020b80ad4b56792ee63a39b481169ebdcf1ef266.nq.gz
    ├── 0284b76378cc351197020243001fc630b328c6e7.nq.gz
    ├── 02defa287d84d63806f6932dc1e96d5ae5048b3c.nq.gz
    ├── 0398a151cd101feab7a0f638ba7aacbc3fdcb418.nq.gz
    ├── 0412c6a34360d37aaf88e1f9ec01881ba2ab567d.nq.gz
    ├── 04e260e3d25837fa899a7f40b93c80ad984b3f10.nq.gz
    ├── 0558a484ed18ae636a34a270b815a4d532ababc4.nq.gz
    ├── 05ce40c20efb5fa71c879402c6784f03a8a2ba94.nq.gz
    ├── 062eaa363656026276732889fe28468bd7bda119.nq.gz
    ├── 06a71cd7c91eb6550d49ec58335efa0da384f082.nq.gz
    ├── 06b6445fc7b8a1a800de24025ebf16ebb169eb0a.nq.gz
    ├── 071fa8f6868bb78f5a7550f793f8b0831ef35d35.nq.gz
    ├── 07ad3450d44d47924cb36f7bbf22eb1cf7e1d3a8.nq.gz
    ├── 07d1109e31867cd2180f94388a1b05e31d8a9da6.nq.gz
    ├── 07dc8f9fb54e7f16ad60f0d0ea9ad158def55191.nq.gz
    ├── 08ce0cf55aee989d62b3c06c97e3382c1a2ce560.nq.gz
    ├── 08fe895a1629cc3f0d73c0b3273ae82049ba962e.nq.gz
    ├── 0937f6a8a379861afceed8048acc8b2191c533c7.nq.gz
    ├── 0a36d90c58b4e387cdb620d0a29b21cfdf29856c.nq.gz
    ├── 0af5504dd562349b408de03a9e7efa02798b8a33.nq.gz
    ├── 0afb87bdff46b97dd04fbcf1a6fa6beb48d51713.nq.gz
    ├── 0cd323fd90e79239437697c42685b5df888ed19e.nq.gz
    ├── 0cdd3ddab98c8fcd173d4437855fcfd4373b1eeb.nq.gz
    ├── 0e1c57b4f16e8a747b35a74ba005ee9be5ab9c91.nq.gz
    ├── 0f61431d174bea34bb7c005f3517bc30242ed043.nq.gz
    ├── 0fa4a4508e121c7d183f188b2e65ec2a39731828.nq.gz
    ├── 0feb5d4d2a5cda5287db025c948d40623aeb3b66.nq.gz
    ├── 100019b6b44b6255aca1fee66a02f9365da1a4ad.nq.gz
    ├── 1010f3b5c390052743a967dce1afbf7388625ef3.nq.gz
    ├── 10234e44a51bd07f59993757851b950e94623be1.nq.gz
    ├── 107acd32c4e687021ef32db511e8a206129b88ec.nq.gz
    ├── 11ebec8f10f56b73793c4cd528e9452bcf07f39d.nq.gz
    ├── 12e4ec580cbca25419c76e0284b9f0b3c04f6504.nq.gz
    ├── 135f61a8d8c5773fabfb84c94599e22b202947eb.nq.gz
    ├── 13b62ccef8cf5d86edc666959171eabf0a1870a4.nq.gz
    ├── 13e6d63b304550b1594df049947f0ec709f19f72.nq.gz
    ├── 147f6bae55590c4895090de5608267e7d1c3d993.nq.gz
    ├── 1490dce515d78755ed8e845918f7d1d6909d8f00.nq.gz
    ├── 14a2ef3ded7e8f49ca34663e97e4563b6ac0f65a.nq.gz
    ├── 15b98bbbe83b984a55c3e2b46ef35e7541f1f117.nq.gz
    ├── 16943c00a6233f2fffd99ab0bfc414e1463db655.nq.gz
    ├── 17980cc08a437905420eea063b373291c4a0e9f9.nq.gz
    ├── 18040df82747f78e888a2d41b980f318b006f9f1.nq.gz
    ├── 1870639c17ed242f40e482d875f9130fa076aef6.nq.gz
    ├── 1906683a5fd3cb8d0dae0e225ab49ed2a12d6016.nq.gz
    ├── 19e1df4d8e976d016a275694c4e663c1efbb0cd8.nq.gz
    ├── 1a3b26009bc9d0031cad3d8c7ce196e1ae8106a8.nq.gz
    ├── 1a773d6f485bcae0f47fd26720e22bd70b44d751.nq.gz
    ├── 1b6c787337ffb79f0e3cf8b1e9f00f680a959de1.nq.gz
    ├── 1b80efb3905470aca54592a18cba1f7cdf252869.nq.gz
    ├── 1bc2f5d605625472e31e7dd6ef2c7afa36cd080a.nq.gz
    ├── 1bf50856ea29fe000ca6b4a1e3937f30e8491b50.nq.gz
    ├── 1c0a2d3d52b4cfa17b1ca307ab7148e335f617f3.nq.gz
    ├── 1da665d5dc196893aca5d138736f0cb37d2352f5.nq.gz
    ├── 1deb2884990320f4968a5f4637a82b539e551474.nq.gz
    ├── 1eca8d4188dd897cd890dc1ee57193610c58e672.nq.gz
    ├── 1f585ea58351d99e78b06fbb859210bc33977a9e.nq.gz
    ├── 1ffb99628fa0396cb6da33e6becd9d6bd565b504.nq.gz
    ├── 20041cad5c1ea981690903878b9eb1edfd3fbad0.nq.gz
    ├── 20a9b257c1e2c1422f1e9bae7a8a07660388ae91.nq.gz
    ├── 21bae2c34645205dad6d21ddebb37772722371df.nq.gz
    ├── 2228af481659e41f4ffd6507a20d810b23431c3d.nq.gz
    ├── 225bd38a930a9cdd265b47051535743137241e53.nq.gz
    ├── 22a9abd17309d22ca0b932f154c7da06773c827e.nq.gz
    ├── 22c57a7f73da571ceb1cd5d10c0d9e80cbec91f3.nq.gz
    ├── 230eac0344eb66379d3fa22d764c3d8b81119be7.nq.gz
    ├── 232e2c0c99c80cc1a161760a3728b10d0f8a2f99.nq.gz
    ├── 23742ecb2a0dd11f1fca04d6c9540d4e450625c6.nq.gz
    ├── 23c826582f9bd71ee4c613f5ce2af40d88d3bce7.nq.gz
    ├── 240bfa7965b0d2424679e6cd5851ca4fb151b8cc.nq.gz
    ├── 24807350e08c380fbfb62cb58ad4d2ec95ea58f9.nq.gz
    ├── 24a805607e983c1958ebeb97496b8d0c0c7bdb1f.nq.gz
    ├── 254b48ef933db59ed6b100443000530bb8e7171b.nq.gz
    ├── 2579542e493704ba40e770b50d4b276476f0ec09.nq.gz
    ├── 259f01e8a62dce7998396cac9b8caf782b1c7d5f.nq.gz
    ├── 2705161ea344b0c3dc75fdf45f6e5872f5a164d3.nq.gz
    ├── 271fdd8cfdee0e778991fc0fb7e557d03d7f9ea8.nq.gz
    ├── 273b96016dd4d184f2610acba0516665da4ea45a.nq.gz
    ├── 27a8a3024d67947562134f7a16d52be5e941cc68.nq.gz
    ├── 28cdde81ad2944d2b11928082cc130122e875702.nq.gz
    ├── 28fded51cdbe713931008bc3394f7c98041e13e3.nq.gz
    ├── 290c5e1a5069bdd9607ab221aa01255f5907d9c9.nq.gz
    ├── 2947ca18d19756879a4f329591cf9041ad659b72.nq.gz
    ├── 29b454df7b7ac75caa2d837e992f849d10f7aa79.nq.gz
    ├── 2a37f0490d162840e257d35602b04fec186d47a9.nq.gz
    ├── 2ab8c6d17abe8e1d2474c500dcb51ff4b488e162.nq.gz
    ├── 2abd9b6edeef3d00b6e9989555f8d36feeb541ba.nq.gz
    ├── 2c50d0852d5080134dbea695db9afad65549bd3a.nq.gz
    ├── 2c9ff89f1eba8fe6dd9e3238a116615e9652434f.nq.gz
    ├── 2cc3377944180f2cd1ac013b0c48ad19f0cfde96.nq.gz
    ├── 2d103c53d360f81056ca9be434817e72ab6c2967.nq.gz
    ├── 2d61823e9fcb8abe4326991cad29f8f469b7d81f.nq.gz
    ├── 2d73d1b51da47278b91a88f7774bab68ff1616f0.nq.gz
    ├── 2e4daf7242d77861762a21854409daa35c4fc8de.nq.gz
    ├── 2ef12bdec806ac2061a9a3d9b04008bd08c88e97.nq.gz
    ├── 30476976979e4fae5176a5129f4176b099dd7422.nq.gz
    ├── 31790a3103c5ac3c97aa0b3c19f7f4649899fe34.nq.gz
    ├── 32113f4b92c00a2a19bab82c434efac3898646cc.nq.gz
    ├── 32a6418e36395d9c7eda78e3afa160f5713005cb.nq.gz
    ├── 342cc5d2bb16ea34f802e919dd2f4871970d9727.nq.gz
    ├── 344f36466db711c9d514ff4497684fbf61604b85.nq.gz
    ├── 3571093b1281491e0a18b4edd13d6ed102b3b08a.nq.gz
    ├── 35b5ca95319ee818b3de84173140d026a3047487.nq.gz
    ├── 3645cc47b174edfefbcfa8740ed87a99ab864307.nq.gz
    ├── 3653d0914e7387cd8472642035d53c8fa8d63a0e.nq.gz
    ├── 37037c918b08e50bcf54b72d57ce20a678d068d7.nq.gz
    ├── 3751356f8f95ac08a5d08f80e8d26e39fff2283a.nq.gz
    ├── 37774e2cc5afd4c38f58924432408a1385f1799c.nq.gz
    ├── 381686772220a42e6999d5b3560815cd0bf0a4cf.nq.gz
    ├── 38f11ae900604260044e5ea5c29f22c4299b7b68.nq.gz
    ├── 3928a5fcb4c63a2ceefe38250a601e23634e1dd0.nq.gz
    ├── 393f87479d85adb858a36279c3211ef863ee17b5.nq.gz
    ├── 3940a7b27544d18d2271fe21e82f354834245833.nq.gz
    ├── 3a7671a0b0312da2f9e133dbf0d7798efb262e98.nq.gz
    ├── 3b610350eda09c34fcef524c7926ba7b1445ead1.nq.gz
    ├── 3b68ce34a7063386fdc85f27a13219114a8c24b8.nq.gz
    ├── 3b76b02cc119232a1b997fc2232f4728f27cc011.nq.gz
    ├── 3bf076e57442a418e5b57e78e6cf157f81557355.nq.gz
    ├── 3bf403b760f706530151e4a54e3ccabb568185c9.nq.gz
    ├── 3c4c44ea168d3d7ac09f9eee023557a385c10e81.nq.gz
    ├── 3c8706edd3649052b2d046f125563d039110dbdd.nq.gz
    ├── 3ca93f2c9ecb207bcd702b52a971fb9b12a68265.nq.gz
    ├── 3cd2c9831dda2c591ebd76eb64afaee674fa50d1.nq.gz
    ├── 3dd81ef4b9fadebdc7309b95908b34d0708ede90.nq.gz
    ├── 3e0cb0e8afe93d38b91c18a0fd62fca5248a15e8.nq.gz
    ├── 3e27355371232dfc93fb29b3984ddcabcb736296.nq.gz
    ├── 3e72cd920616449dfb1aac7bc1e87698fdc9470e.nq.gz
    ├── 3f54f339b3e7438a61f71999d01f902cea65970c.nq.gz
    ├── 4043ac4c5ad5bfa6c7aeafd049f207face819bf9.nq.gz
    ├── 40dbbc09cbcfae5b2d5d5841282987537ac6e6d4.nq.gz
    ├── 426819a2cb1bfa62f555c78de01fbe5bea5fed08.nq.gz
    ├── 4312ccd6ac8a837a343c93accc1fe952452eab87.nq.gz
    ├── 434b0605f863269058709d882c70240172fb16fa.nq.gz
    ├── 43b69c165cd30e9ee47fac4241c4566879c305f6.nq.gz
    ├── 43f37d87fe4e96500378d4aa27fa5e6eb263bc06.nq.gz
    ├── 4420242930f5193c3b950ad0155c0571400d89e7.nq.gz
    ├── 44263748f352de945139dc7f39d32b110c2e3523.nq.gz
    ├── 443300ffa4b8894af7c43134da4ac2ae66b77b29.nq.gz
    ├── 4483d0d6c4738645e322a275e864b61d138da64f.nq.gz
    ├── 449d3d55b71182cbd72ba8a249150a0d7a08f933.nq.gz
    ├── 44d1569b6feb91c17b81522c1dfcae05001aaff8.nq.gz
    ├── 45287d0c360aa6edeb3dffbc8f743f5de517c3df.nq.gz
    ├── 4556caf68f8b330e53cd39f499e43a7c2e98452f.nq.gz
    ├── 4574ff9ebc088be39471456b6d35e59ebb589516.nq.gz
    ├── 4647b6348393813aa4b2c5da246cc7326b468f4a.nq.gz
    ├── 47a1ab90801b2cd3fa1d2df40b75fda1a12daadd.nq.gz
    ├── 47fb237f85546bb811b2e0ce4b3278444e1cfa4d.nq.gz
    ├── 4818b97314cff4d5afae0a846c517d8c7596822a.nq.gz
    ├── 483bbe6f5bcaab06b65cb602344453b1077adace.nq.gz
    ├── 48fe04044d5b44b857f67163f0aa80e852f77be0.nq.gz
    ├── 49302dccf3912854f2d175a39dcde8ba01135a9c.nq.gz
    ├── 494b4f906eb469d9675a1e6c2578d8f260bcd6e3.nq.gz
    ├── 4a972066d306bb2df9d2e15bdb224042cfb7771d.nq.gz
    ├── 4bc2ded18049a20c132b27ea4db05c5a4cf7dfc5.nq.gz
    ├── 4bda1acfc03a19b0a8461a52b9e2dbb9c3a36087.nq.gz
    ├── 4c13ad331cec93e1a99e7574ee0b86e10f5e4f5f.nq.gz
    ├── 4c88b8b353574b075230ca71edc78551588d55fd.nq.gz
    ├── 4cc612d45a768cc6ae1760698371fd0209db3d85.nq.gz
    ├── 4d73639fcb0736106c9f070d2c50bf52334b5666.nq.gz
    ├── 4e3e51b693e8fd90bf71f9917491f06493ecec07.nq.gz
    ├── 50176969b782b8d103e5673ee66da84f094d94c0.nq.gz
    ├── 50239105335e90317e1a238fc58ee9e6e045a1c1.nq.gz
    ├── 506fce34b939cdc84bfecc0bd72c70ac683c13bc.nq.gz
    ├── 507dad18f62a60985ed0a2f29aaa45affbf1864a.nq.gz
    ├── 511ebd854f77b6bfeaa0a18b7e8bbe7f3dd8878a.nq.gz
    ├── 52605c581de1686f3f87a83492759a83cb1a3286.nq.gz
    ├── 52b3bb4973edc69b425e9e0c61161f412f0db8f3.nq.gz
    ├── 52ffa88e14ac51770234385b3888861e95c1b525.nq.gz
    ├── 536e0541fbc01bdc959cf18589400547781b7cf5.nq.gz
    ├── 5392e1c120fa35deb0bd1514e5d85adb40f282a0.nq.gz
    ├── 53aad7bfb46ec3ac287a70f008633d6acf9b29ba.nq.gz
    ├── 53b7363a0e3e413e669a84d0b18d185c2c578b08.nq.gz
    ├── 5475d934a6e2beb07ef3d0b602d92b55e51ff062.nq.gz
    ├── 54b70f6c41ccbeb7dda946e7f7685ed4ffab07a6.nq.gz
    ├── 54c3dd409b1933251576a4eb7b047b97d4da8bf6.nq.gz
    ├── 55048eeb9e4745222fb1b86e2f12b14e264da776.nq.gz
    ├── 557be2a06d1d5815f175003c4569d24809a885e2.nq.gz
    ├── 55bbb2c045388376c87a8317d53dc38de40e02a8.nq.gz
    ├── 55e1f8c7f225ae6c12b805fd1f68efcb94159c65.nq.gz
    ├── 560e92c202d24716fe8778be24b3f6f9fc6f5372.nq.gz
    ├── 5735148303029839ccb93c5a4480e3f52b88668c.nq.gz
    ├── 57c5c7ad0da4cb229ae4620147029c67f8d330e1.nq.gz
    ├── 57c89ca7cff593d49ac2437a516759cc82ebe73d.nq.gz
    ├── 57f35ccf1addec6e672c5d5b418dd404fcb200b5.nq.gz
    ├── 57fda96f89eb5cfbb36ef37061b494369a9f4fa2.nq.gz
    ├── 586785a3ec1f28b2e659900cd27ccddb58efb9b9.nq.gz
    ├── 5a99b3e3fe7125664c9c7e80f65e6e51f0ae3139.nq.gz
    ├── 5b3c588522f2a4665300c45fe04b10ea335f3c47.nq.gz
    ├── 5c38aee8e95b9a79876756bf501cec3be27180c2.nq.gz
    ├── 5c6f9988fd3e9a8d7ac9b8b9ee7aab37f76b6803.nq.gz
    ├── 5c8d3525370fd79b191fefba3dd2a70fd43cfcef.nq.gz
    ├── 5d60ba081dcb084ce84dd0a030495926230d2fb0.nq.gz
    ├── 5edb85c918b82fbb6b25614572ed88b6120d23f2.nq.gz
    ├── 5f45e5b489a6aa74c6ae9079e40bbbe9729981b8.nq.gz
    ├── 6082f34bab11e5a3d7c6e8ade1d4ac27ec5690ec.nq.gz
    └── 60875fc22f28c2c30b07dab3632fed7881bd5c6d.nq.gz

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

[whylabs/whylogs](https://github.com/whylabs/whylogs)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
