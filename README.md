# Repolex Knowledge Graph of NousResearch/Liger-Kernel

RDF knowledge graph data for [NousResearch/Liger-Kernel](https://github.com/NousResearch/Liger-Kernel), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Liger-Kernel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 99a90f7cc42a0606c1680cca3999cb498ab75723
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 99a90f7cc42a0606c1680cca3999cb498ab75723
│           └── chunk-001.nq.gz
└── blob
    ├── 01ea82684b4e6d6d4db9d087be1c44ad126d4442.nq.gz
    ├── 029baf3f973f41dd580cd5ea926bfc0de119e88f.nq.gz
    ├── 02c883d9215de7dbe38174c46deb1edd2bb01d4f.nq.gz
    ├── 0328c5ff05074b77adab24051b423e722ac9941c.nq.gz
    ├── 0506d69d899c89d94993be1bcb7ba3bd03cb347a.nq.gz
    ├── 09948c38b48e0d4b9c549ea374064af833dab0da.nq.gz
    ├── 0a4827cbd2f60a8ffce3913753776126f620b8c4.nq.gz
    ├── 0addf78ed8fae60d04869e67f317dac04f3df047.nq.gz
    ├── 0e112ca72dcdf00380f2870e8cd07d89b756fc3d.nq.gz
    ├── 0e98eec279066aeb836c8a59a8ec2457ee5f6427.nq.gz
    ├── 0f3852f090ae2ef4dd2c9734669cb404a2f788da.nq.gz
    ├── 10e994c8c12ab90b0accfcbee81eee9961d84ab2.nq.gz
    ├── 1171ea42d94f55fbdbd954ba44b3a4447639d800.nq.gz
    ├── 1177f05856b7ea012740f483cad2b7167c1275cf.nq.gz
    ├── 12c4a7dfeaed768bb85e55fb88fd9105508133c7.nq.gz
    ├── 130a0386368ea827f67948d48eb321ce0789bc1f.nq.gz
    ├── 133d65b4dd4829703b265719929f25cd55d1ec68.nq.gz
    ├── 135d5fde78bea728e37055915c3a9bd22e4cf3b9.nq.gz
    ├── 148b8e3e4db0d68cc524f443e3076d7f1afd596c.nq.gz
    ├── 149d2d32102f72fd3bcb2adb6c9cfc8abc790d16.nq.gz
    ├── 14b89bcdc1e278a335c7f43179c4c5fb97222c1a.nq.gz
    ├── 150f83f5f628f1e5ba77cd748a76210371275f00.nq.gz
    ├── 159b9a66d64158332c37e763ca9763ac9ede1932.nq.gz
    ├── 15db6cdda36e442007d8c380ef13c3c72293abb1.nq.gz
    ├── 171c986521df2afde5eb5a8c170774d8d9ea8bc9.nq.gz
    ├── 17736429bcfbc11fa9d9bdf9ca549f5ea5a2c8a4.nq.gz
    ├── 17ed94df87afe634d1f2d94d03773ff86963954c.nq.gz
    ├── 1a7994e536d07d8f2c292e27ca1e0ebfd6a165ff.nq.gz
    ├── 1d321343055cf8256b77e7de3c0646a3da24cbf5.nq.gz
    ├── 1d7d1a97d66505021e970a1f3603dfdb27b991b0.nq.gz
    ├── 1d8f48692ce6c44eacf156ed5027a1d330741ba4.nq.gz
    ├── 1dbee9abf21ddd0b66d12b0ebd976d3245f74604.nq.gz
    ├── 1dd7037f2dec6cf6189c224111f6825c0d265e2d.nq.gz
    ├── 1f0a154974ee689a34db3df367c4e54c20f67916.nq.gz
    ├── 1fcee87da2d79abccdb8b7608be6a8f57438c372.nq.gz
    ├── 20030186e9b0c5c171ee18557513bb2c2cd1d410.nq.gz
    ├── 2039b58f02fb71ac1928eafe2ed4e85dc72e949a.nq.gz
    ├── 228a228d55753042b0d1bf9471085076e1eefe3b.nq.gz
    ├── 22a48a84318d001eb2ff5b149ccd6eab45ec1b6c.nq.gz
    ├── 243e554a7108bcd8568c9a5c3d6ea9ae5d9901cd.nq.gz
    ├── 2595387fd68202192af50ee97afbc464e5721bc9.nq.gz
    ├── 25bb65fc78f4fc8268bc81af43e8d5cee08146d0.nq.gz
    ├── 26a942512a67c4519654dac34871228106e19b7a.nq.gz
    ├── 2774e7e665929fd05a4036c92c31d54bd30c733f.nq.gz
    ├── 2bd0c60be9735017eb1ab219eddb8b49773d360d.nq.gz
    ├── 2bdeaecc60c331c3c81268e4b679f3118cf0f5b2.nq.gz
    ├── 2c1e18433524b441728886d3e30f2cf6c9eeb7aa.nq.gz
    ├── 2c91271b74ad28a166233e0ad5d09232655ea54b.nq.gz
    ├── 2ed641fe5a0e9e66f20f1a400b25d264f399c702.nq.gz
    ├── 30b308c42605e08758165f4fb5e719f098995a5b.nq.gz
    ├── 3115a254913b694745a940e73bdd6296c90ff5cd.nq.gz
    ├── 315dd92350fd618a0dff4e9aba59cc8972ff4334.nq.gz
    ├── 324238194cc963373ffeb0d5bd212596de499696.nq.gz
    ├── 326d536326698174b944b4915b4443a670980ca1.nq.gz
    ├── 3426c0fdcc891d57e010b5f96d8a05f226c4510b.nq.gz
    ├── 348a9138021fa05a1faac66c7c778b463d80d420.nq.gz
    ├── 34c8968bf6903c7b345a7f3d8b2164b48a802d0f.nq.gz
    ├── 34f044faf2fe47d1cf972bb09e9472f0dae877d7.nq.gz
    ├── 36ab7fe12b1bf508e8c86fa49b619a346b13ad32.nq.gz
    ├── 37dd35a3ee417ee213089c308c271748695a808a.nq.gz
    ├── 39b090dc9c24b7c02b08c865ebe2120eb85dcbe0.nq.gz
    ├── 3a6b99582f40c251c20330df860910c889708f13.nq.gz
    ├── 3ae5d9d36f2e50967022e69aabcfff54b1a7f8f8.nq.gz
    ├── 3b6af54777479a2ad7078b338cf1da138754be0d.nq.gz
    ├── 3b860a887ae3a075c905ae04b444d97af199a9df.nq.gz
    ├── 3d409e745c1318911861fccbc5248564a45fec5b.nq.gz
    ├── 41a1fb92fab04c9b4698fbdfa030f4619144f83a.nq.gz
    ├── 41de0dcb737ae912d3935e10d23f23f9ebe212e5.nq.gz
    ├── 4245375413ec8f751c34d13b034e3819e758c6a2.nq.gz
    ├── 4342cdcd616cdfe55f0d982fb0a7e220b1bb3038.nq.gz
    ├── 43c0078a32a50f40934e0b48f3eb02ab3a7a7ae3.nq.gz
    ├── 448db55ee806716869a701d6c0aa42f49cf2ec13.nq.gz
    ├── 44e33c7be995e28710e2f62d521313cacace362b.nq.gz
    ├── 45894b0b50bf5f843837ebe2f07d199f5e8a8df0.nq.gz
    ├── 45a88af6e76962c9943583fd460f015603d0113b.nq.gz
    ├── 497d8692c7ab5688637dcfe9c8c9ec955d8cb5e7.nq.gz
    ├── 49c4656eec0a0a83de6e73fe558edf7dc9f16e7f.nq.gz
    ├── 4a6f019598a9dcfd0d78d060d2e3a8196aaa0a9e.nq.gz
    ├── 4c5aafdb63e2e5a371adf03283304eee869a288b.nq.gz
    ├── 4d02986a50bc370d7efe947b031f51e00561cefb.nq.gz
    ├── 4d36a66a6394ec7f9104d0300dd599acf332c29b.nq.gz
    ├── 4e2fef65f45e2947acf1f2ab6c050d942973c32f.nq.gz
    ├── 4ef695b4ffe9ce341f076eb88d3e3cb772d574df.nq.gz
    ├── 503af93a03abe5a941d80eb384824bb454f756a0.nq.gz
    ├── 515d65cad090d098db93624d99e206a73d602330.nq.gz
    ├── 526a4f2ff16c36429635ea94243b8f96b79aad82.nq.gz
    ├── 53e5e7d25e9487689904dcf12a22297d9b4e85a9.nq.gz
    ├── 5433e03d38f05d3078361f950a7fd4fbc8bf0598.nq.gz
    ├── 54a157fbc265a36e75965f65e3686937d9eb1485.nq.gz
    ├── 557358fc9a1cb2916aaeb6a61c6da47ba4a9f3fc.nq.gz
    ├── 57347ca890cc8aec97fdac9a2f224540a6f6dafb.nq.gz
    ├── 593159aa60d7b93f1093c9f94beca49496886fc8.nq.gz
    ├── 5a3f2cdd1b349cbc2be3e6ff89504897bd01c3c1.nq.gz
    ├── 5a8bf37f4af06260409085501c6a0329ae5bfdc4.nq.gz
    ├── 5a98bb1f13e784defaa5ce7a816af6de9ec58f2a.nq.gz
    ├── 5c5c2adf67d113a9cc6896464cd3b98436b01fee.nq.gz
    ├── 5cf12b495c835d507c5f11c7f8078b2e27414354.nq.gz
    ├── 61431871b68dd7419442a765088a16b76784e519.nq.gz
    ├── 61d66f6b0465c4b4cf83013e69676eb0ed4dd128.nq.gz
    ├── 623ceab543aaa4253f56217ac2a93f0597644b5d.nq.gz
    ├── 624ba96d956a92b4612e07edb00a3891328d7c78.nq.gz
    ├── 635aa9dae21bdf1726f51ab844e5e3ce253b97ee.nq.gz
    ├── 663b288122c1aed8eaf377a297f0e1a10e7d4f2d.nq.gz
    ├── 673243b770a871b42d3a99c22e0165e0a5c3b14e.nq.gz
    ├── 674db60c7a4cf23f3848c33055edd4b1acbbbd9f.nq.gz
    ├── 68076b7d796dcfd8b5b138f30d0880bd0536aa5e.nq.gz
    ├── 686fc456f541935329baa314e1787a877cd32679.nq.gz
    ├── 689a97cf07ffc979f93c1c0901d855d8045b1577.nq.gz
    ├── 68bad642b00ede5690e20426eb3a36ddb5143ae1.nq.gz
    ├── 68d682b6b8600afe2ec618db91bc47340826d438.nq.gz
    ├── 6904f28f6ed53aa1f018982ff84bcbdf17db0c86.nq.gz
    ├── 6ae10b35b99770e89f7fdd1481d210e55b1d71f3.nq.gz
    ├── 6b1ecc1e10bcbfbf16d0c16b35b7df71e2f65972.nq.gz
    ├── 6b36955baae75f9401ba1ed64fbc733b88bbf1b0.nq.gz
    ├── 6bcd56a8378a2f6d21dfecf5157569f3d59af9b8.nq.gz
    ├── 6c0666de105a8bf88f1caa58514710fa0119566d.nq.gz
    ├── 6c7d5eec91a94408618dc343d1f1f10abff0bbe5.nq.gz
    ├── 6d0ba99eb3c6cf39b5e5a85ba48f38854f409780.nq.gz
    ├── 6e472fbbecd0bdf2e4f0acfbdaae1c9fb8c0e1ba.nq.gz
    ├── 6e8f1f77c04f4368ecb319c8aefa3f75bac01a52.nq.gz
    ├── 6e9251af62d2277e894204e474a67c6238d360c7.nq.gz
    ├── 6eeba29c1dcacd4ffe7e292e13d4c412e7f116d9.nq.gz
    ├── 7163543df49e0fe615e6f881f7cb4209125146aa.nq.gz
    ├── 71df3fdd214c59d4dbd707e3f58286f24052b16a.nq.gz
    ├── 72269be663089da7db09b87c0a9fc494adbeb3e3.nq.gz
    ├── 722e60d4fb1c440af5e1c61909c1faadd28a1e9e.nq.gz
    ├── 7255b6a79a9041808b9e4bf4bbc7cf885bea8cc2.nq.gz
    ├── 72c3cc721ea3eee1eb831449264380c1f99b2fba.nq.gz
    ├── 73118e493dd9882d4debd5c4ddce8c6b5e6bacaa.nq.gz
    ├── 736990b891a236561cdb12098f94609daa5c0466.nq.gz
    ├── 77058dc0bb9a17f51914054e528f072f7160eae5.nq.gz
    ├── 77254a040f108e9a43da4e148c1177733c7e56e1.nq.gz
    ├── 793550384d4e4220f7f0931b68163653cf78ac0c.nq.gz
    ├── 7a366583651815469cd239f1a9454f46152e74c5.nq.gz
    ├── 7ba984d0d0a1c15572985a7d4bea11efa237968e.nq.gz
    ├── 7c66e0e088adabc3ff32c187e0c56d44ae10868a.nq.gz
    ├── 7cb0bc3716444b5f77d8ab80cbee445495bd6f59.nq.gz
    ├── 7d0d390db2bf99bec99c875070f662d7961eb0ae.nq.gz
    ├── 7dc9450c0160a70dc595c910529dfcfc265c3943.nq.gz
    ├── 806fa86648b89f3f2cbbb04541b8916b19f0b53e.nq.gz
    ├── 841adc2ccae4391d4b85456b897d24294417008f.nq.gz
    ├── 84386f4e416b00c9742ceb261b0a8b1ca8c8db30.nq.gz
    ├── 843b79ab24fe95d9d02cf604c62b3e27adfae70b.nq.gz
    ├── 851d239435fffbbf9ad886cc60567b29b854cd1d.nq.gz
    ├── 8568070ac08c8656d4dba50bf0932f758b4ba220.nq.gz
    ├── 878578604b6f3b8e6be0b27ec7ff69e172049ef1.nq.gz
    ├── 878dc3c199e5028bd2e037fab161f65af939b522.nq.gz
    ├── 87994ace9cf50b9165a345450f2f5fea371efa00.nq.gz
    ├── 88ed0ef96bbf808b8266baf96e65d1bbf461903e.nq.gz
    ├── 8b10d518880b19644bd7d6c3cc4b9cd64cc8a541.nq.gz
    ├── 8b122385f43abc34c3299cb86218b4d4527b9e2d.nq.gz
    ├── 8f89581e5c0c7f2838aa1a9a8bedb05789fe3e18.nq.gz
    ├── 8fbb221c7fdc95258d63f57d1e33aed4633068f6.nq.gz
    ├── 916d79d5fe28b2d6d19fbd84c19ebb4c22b98769.nq.gz
    ├── 919f4c66defbe1d2388aa17c912fec09058316d4.nq.gz
    ├── 928f795898191643dddce37c8850206104e39634.nq.gz
    ├── 93ec85b22d00e33a62f105cd1b38d4f2fe6aed09.nq.gz
    ├── 940d0918bd2c74aaff45666b5d5b4f4778f3fb56.nq.gz
    ├── 94bc63086ee4830947a78c2141db3c637ac17323.nq.gz
    ├── 952b00b88fbe58db1dbf2eca7d7747a3bd64f261.nq.gz
    ├── 9586ba8bda2ba505d91277dc28648336059bf602.nq.gz
    ├── 963600f0120f0a9da95da417ca87c7cbf4e4f3ff.nq.gz
    ├── 96633d01a472649a521180cbb3c69e768edc3cff.nq.gz
    ├── 98f47d713920e6842c3be9761672296066d9d644.nq.gz
    ├── 99d8f1f022950f0dc55f01b996d219c122ac2db6.nq.gz
    ├── 9a1ba6607eb0e9a37ffdae5f1b4c43efdd1397c0.nq.gz
    ├── 9a4b8c8f38091ae6aabe796d050315002d8f22ff.nq.gz
    ├── 9dfdb4f7b8ba3f96bea71af1e7dc56d121723fab.nq.gz
    ├── 9f4154bbb4bfe815938ebad940c8830c95b69891.nq.gz
    ├── 9f9c2543335857485abfba79eee71b2160e2a902.nq.gz
    ├── a2567800c62c352b5c788ef4ff206b908f1d24eb.nq.gz
    ├── a426abdba34d76846f8778a310add9549f968051.nq.gz
    ├── a434d6a8b67fd959be87a892670f8c6f19b8c55c.nq.gz
    ├── a53673562ca60d3e3a152f73211cb690e5b7c63f.nq.gz
    ├── a54fa47d88ba93a9c092f2a062f06a07eb66d992.nq.gz
    ├── a5c43b1b0b7e0dd33ae77a83fd0b3586e9c81d7c.nq.gz
    ├── a662f76e5e439a460a2b2c249301a1313ec7348a.nq.gz
    ├── a678bfc8674b012678e550758af2dd20bd9fc5dd.nq.gz
    ├── a6a3f63030044efd0dd184a15f4198fab7b085d4.nq.gz
    ├── a732581338f56d21969430f5db63937824378149.nq.gz
    ├── a7623a236b6fe8181837e49f322f17db6c272fd7.nq.gz
    ├── a8923251d3814b7a16d6be80ee52e8bc299f3c91.nq.gz
    ├── a8fd959d1a307e2ad87d4d3941c17c2b259a6247.nq.gz
    ├── a91ebf58a90d5c56b746a384e043cf1031522a85.nq.gz
    ├── ab11648783f5ae7c3867dfa097ac5880549e24cb.nq.gz
    ├── ab2f9176055e353199e0bc0ac73e891c8acfe804.nq.gz
    ├── abed540668667e7c9205f35e81eb49922d64d299.nq.gz
    ├── ac62863b216a94f4fd9f9970145e394bbe20ebd8.nq.gz
    ├── ac792881d41965e1ba4fc2be51cd2545159c646e.nq.gz
    ├── ac7f98e07160692b6d95a286d12ac93463881cdc.nq.gz
    ├── ae9d265ab6edf43b4d95bf9bf9b6f446143a7946.nq.gz
    ├── af867f4b17bb4cd95f7e818764f1f72e0d135830.nq.gz
    ├── b18ccc33500acbd981e22150e63f46e1d04c5923.nq.gz
    ├── b3e6b26811ca16433134ab9c56da88801274a414.nq.gz
    ├── b4a600dca9946a062699e4e233448cece33b4147.nq.gz
    ├── b4fd7eaa11e87ee1c162b3c5c54247e77e4374c4.nq.gz
    ├── b5319af5c70baa9ec547bdac130a98ff4ed4e6e4.nq.gz
    └── b57eaafc97bef4e07e9c8b5fba16cab478b10527.nq.gz

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

[NousResearch/Liger-Kernel](https://github.com/NousResearch/Liger-Kernel)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
