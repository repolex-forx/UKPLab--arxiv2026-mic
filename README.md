# Repolex Knowledge Graph of UKPLab/arxiv2026-mic

RDF knowledge graph data for [UKPLab/arxiv2026-mic](https://github.com/UKPLab/arxiv2026-mic), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2026-mic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53ae2d45d86dcd7777f989be276a268167e1b37c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53ae2d45d86dcd7777f989be276a268167e1b37c
│           └── chunk-001.nq.gz
└── blob
    ├── 000cd5307c705f558521e47548d109cbf27029a4.nq.gz
    ├── 00aa7bdb642484b5c3ac65b6cf1e839a427c7bf1.nq.gz
    ├── 013ec9ed887924138c92d3bf12d94dd035ad5301.nq.gz
    ├── 019580d506239ac3b67995d815abac7d6d083ecf.nq.gz
    ├── 01b4c9fd28aed295d50c71a7a3ed2e97a69434d4.nq.gz
    ├── 027cdbaf73706756ac3a068a411c57ff4253a064.nq.gz
    ├── 03bde11376c21be4bd8d83218278dc479700b543.nq.gz
    ├── 03d6c75ce1987924b1c43a7cfb28b83fc02376a2.nq.gz
    ├── 04bd6dbb6e4d95e55aaeb6863c86e5edfe80b50d.nq.gz
    ├── 05b3cb95097b52f6ab848d6740e5784bb2be703b.nq.gz
    ├── 061c2dfec9454d8d73d157f307fb40fe345e0f17.nq.gz
    ├── 0631c90f61605f2ed0d659c8836f01c451e694a6.nq.gz
    ├── 073438d76d137550e9ef09e782600d99b6fcf9bc.nq.gz
    ├── 07529478b3b716d89158defe7aa996958c4621ec.nq.gz
    ├── 08cc48a075d3f3a2abc131e881f186c0f0df8fed.nq.gz
    ├── 09d2f5d733a6bdd3cab709cfbcac1705cd57a6a0.nq.gz
    ├── 0a4bef3dd3db6800a8016ef5cc16014c61e5931c.nq.gz
    ├── 0bf3c31c3e9cd771451546a825cf9a74504c1cb7.nq.gz
    ├── 0c0b5dcbf2bdd60587526d15ed51d7eb83e1c600.nq.gz
    ├── 0d55b167de6a7153ac29978aee3e52b35680b974.nq.gz
    ├── 0d9f3b8aadfffe82e17c04094805baa3751c4e7c.nq.gz
    ├── 0da2c6851fba900832793b7c76080dc2ad81254d.nq.gz
    ├── 0e216aef471a86d81d4c1fa17568cf783f2870f5.nq.gz
    ├── 0e24f62b788135aa8d8bdc718d1aef989f841bda.nq.gz
    ├── 0e3596e1afa9a507c67b6949479d1c254b30aec3.nq.gz
    ├── 0e8d4f0cde063c1b6fa1bae08d408d88d96e7e0c.nq.gz
    ├── 0f0b2371620ba05f932ec3dd7698cc340b490ced.nq.gz
    ├── 0f690cf003dfc9519c7cabd4c4b4829720019c12.nq.gz
    ├── 0f8062ff888c89a522c0401d6f0f5fc9e06b2338.nq.gz
    ├── 0fafc4fdfd09da63b81d9eeacb5f85cf4205e16f.nq.gz
    ├── 1080b3f139a2cfe3bbd535599b1cd6a301fa5ae4.nq.gz
    ├── 109f6760b2859414f36697172b2586e0e30796e1.nq.gz
    ├── 113bca0d3e7ee9b976a854b48d271b3d27a88e81.nq.gz
    ├── 11846941d7c5046ce93ea4470982565a4df573c9.nq.gz
    ├── 11e1e3576433aedf7471124f705e6e4e2fe2d331.nq.gz
    ├── 12275f1610acd89e2df6a765ca449c023aae38f3.nq.gz
    ├── 1253f5c9ab9943df3c187a3c8458b35f78fe6994.nq.gz
    ├── 12e9a615b0608548f5d29fb91ca55b6b4daacc0b.nq.gz
    ├── 144632dead5ddc9f37fca7e3e63b0000088d3176.nq.gz
    ├── 1454bf2947bb49d6f61d0e8fe26f375c093d405c.nq.gz
    ├── 1512347d92bc6ace6b53200899c9c8df87f5edb5.nq.gz
    ├── 17842b407878fbd2c6e2db59c9f50476b7f1e099.nq.gz
    ├── 17887c02de9381e410d21ca6edae273204cbe459.nq.gz
    ├── 17d5609845571c67037159994ceaae9f62f9f69e.nq.gz
    ├── 17dddd60dc6e76ded09253bcad45d123d33dbe49.nq.gz
    ├── 17ff3779e96124b2043c04b94e3e4890d1eadcbf.nq.gz
    ├── 1839beed3e46805293cc7cdf9836571b4525c7fe.nq.gz
    ├── 18e0615b9ecd01bf1cead1155ff8124865e07d24.nq.gz
    ├── 19e5279dcbd387cca14c76058a4acf8f5155a221.nq.gz
    ├── 1a8d9743035e3c5848ba943eb0fc47eb7b1da6be.nq.gz
    ├── 1a981b5cd4cc62a828fdb6e3c840ae8d0a26f03c.nq.gz
    ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
    ├── 1c3286bfe7673deff28f93dc84fbf1bc4889200f.nq.gz
    ├── 1c4232cd8df2c678f866fe19482ad07ac7d1c2ab.nq.gz
    ├── 1cb989b296ccca0c7fbace473f48ed5f3176a529.nq.gz
    ├── 1cd1e8433dffa0b3ba420be3e346f4f5cd062014.nq.gz
    ├── 1ce90c5eb352d85c59105c0dc85b5f1dd576f095.nq.gz
    ├── 1d679821f7247b8dc7cc32507d692ad75036de02.nq.gz
    ├── 1d79d574c61379db55041b147250098952b2a600.nq.gz
    ├── 1db46ab48359087e9979d6efd6ce787913b3e5d4.nq.gz
    ├── 1e670b92c99e3d50362184fdd690cd372fe033d6.nq.gz
    ├── 1f5c2898372d7dc2563472741fe76bba04de5479.nq.gz
    ├── 1ffd94644446660ca001c5b45bf6650ee692ca08.nq.gz
    ├── 205814a234bf4d1162a2fa89f1cd051d6463fb47.nq.gz
    ├── 209c2aae39bf2d7386d7b88085ceffb3deff6433.nq.gz
    ├── 20ef3a37a091805fd0efe77d7363a437125efb01.nq.gz
    ├── 218a1fe5d4a7ab58d18233a7910d361f8cc6b524.nq.gz
    ├── 222ebef4997588257ebdf2e6ad88964ebcba78fc.nq.gz
    ├── 2243fb0787f77e5af817f07c3bf89294df636b4c.nq.gz
    ├── 22a5f63532713dcb895b0a940bf9bc9dfe42cfdf.nq.gz
    ├── 230f6647305d8181bc9a669c336968c34f8806a1.nq.gz
    ├── 232ed6140dbf292a0a81fd0d17a9232784e3d0ed.nq.gz
    ├── 23cf570cda83bfbe96a337d3ef10dd0e4865cb77.nq.gz
    ├── 23dbea72ccce3030beb76691ba1832fc04dcdc76.nq.gz
    ├── 2402e6fb741a15cfd23dda9cae600e26c473869c.nq.gz
    ├── 241b540dd851152b5f7a341f3dd5515ad3d1b714.nq.gz
    ├── 2426a380fec2096b0a3074605524fa4ce3771af0.nq.gz
    ├── 242a5117a5e9f9ef2013416a577e6fbc00e84f52.nq.gz
    ├── 24b46e13c1b46f31d1eb441985c97ccf785e51ff.nq.gz
    ├── 256174b6dd38696b5b180501102af40ff395d0a9.nq.gz
    ├── 25b1d9431e237287bfd720788974894d1c07873e.nq.gz
    ├── 26a4a8616bcbbf746fae29bfbd53c47bd50eab45.nq.gz
    ├── 2725bb5bc3d94deda88fc6b10d63e1ae57606e54.nq.gz
    ├── 27624cbcd8492ff810b22ef3eb6692339d4cfbdc.nq.gz
    ├── 279733900d68d7f3d417f3cdbc29c82cbaf7af6d.nq.gz
    ├── 27f950204289a5fbcbcf13a0a12f06172b03e64b.nq.gz
    ├── 28c21ffa0491234966d22f08a3d6ab0fc4e2b853.nq.gz
    ├── 2968b3daace1a2fa67c4a3939bed1754423d4c55.nq.gz
    ├── 298ed16c668c67facdb6af2119878da576f5bdf5.nq.gz
    ├── 2a51fa90043bb0ecf78149b092fd3447740fdaee.nq.gz
    ├── 2a5eb1bb966c534f68625ce63308d8080964c6ca.nq.gz
    ├── 2a87a053c59f9ad464ced527ec017498917d92d3.nq.gz
    ├── 2a954b2417cd5b8d09e88b9935e52eeb6ef5273a.nq.gz
    ├── 2ab2f70fdcf3982026263a309fa1beb973038991.nq.gz
    ├── 2b3fb6eba7260ff5b6a01e19f9f05fc172a64df4.nq.gz
    ├── 2b9a6642e1267c21ab1a2771575dd1fa5b7fe7f4.nq.gz
    ├── 2c05274c622676b017e12cf2210cd72e445dd247.nq.gz
    ├── 2ccc06f4a9d2dbc818b4faa08160d2fe1b5698bc.nq.gz
    ├── 2d06219fc582d4cb91f161c95ffe9f14fb5d324f.nq.gz
    ├── 2e386379310756f2c2fad273940a005cd3db4051.nq.gz
    ├── 2e76561080288c4b20bbc0c632bc2853e66f8ed5.nq.gz
    ├── 2ecf113c8394c651655e80fb3780837cd85288c3.nq.gz
    ├── 2efd44d183cf0397a325236da8703193e9735eb4.nq.gz
    ├── 310a9dc76865e8742ee855e0cae8dac433deec83.nq.gz
    ├── 3168635c7fe7b5b0e35a8e99b189057acbb8a5cb.nq.gz
    ├── 3187004aa5dcda9f2327370d4af47381a4ff5af2.nq.gz
    ├── 322f5353c06e7fd8463b9236a69b8fe078f9adb9.nq.gz
    ├── 32f08475754bc280bca407d1643ec3aa68eeacf3.nq.gz
    ├── 33320d0d02f8e77eb38244b43739735db100e371.nq.gz
    ├── 338f52365533ce312468f1d3195f4c808cf99ad9.nq.gz
    ├── 34348fdf2e123396a91893318ecf42d21bd202f3.nq.gz
    ├── 34e656f7540e274b365df03c78b7d79abd179466.nq.gz
    ├── 34f17b957558a0ce73811994fb6b14a2476f9aa6.nq.gz
    ├── 35057f451c9445a058ef9318696c9541d99cbfc1.nq.gz
    ├── 357ab7899f9eecbd29344482d109b89af274ea2e.nq.gz
    ├── 35bf5a3ab5bd32544b2eec487e96ef61312766b9.nq.gz
    ├── 36bede8c319040ae713ef335372f2caa40ce44a3.nq.gz
    ├── 373069a66d2179570f6004caf66aaa29fa07cc9c.nq.gz
    ├── 39a99a74046b056eb338b8ffbc16961bbd7b4e70.nq.gz
    ├── 3a0e3d4570b9822b2a2c1d753a6af9be6453bcf9.nq.gz
    ├── 3ab0ecb9cae12eff0e6b722073beab4f66e45a60.nq.gz
    ├── 3abf0cf2c20dbfb7fa9cbbfd6bcc27ac21f46568.nq.gz
    ├── 3aec85c24b7aa96d4fd1f47cb688f0bd37e9f903.nq.gz
    ├── 3bac76e9a142530e86a32c3ad4228e6964afc19a.nq.gz
    ├── 3c48b44132a38619b619d55e9dca1c450e3b88b5.nq.gz
    ├── 3d0424c77479d1a18a39f78240491461d50f3d22.nq.gz
    ├── 3d129d1fe2f96c25debaf534c41e4117a4b2bb63.nq.gz
    ├── 3d6c5c71e54a1d6000025840b1abc783f56b60d5.nq.gz
    ├── 3dd0b8a38d61451dda97edaa229885df4c9f9565.nq.gz
    ├── 3ede5399c3a228ffc29c159faa6a9228bdcb9a4e.nq.gz
    ├── 3fdd7a6776a74bcd71f5852ad935bce6eca474be.nq.gz
    ├── 405a1472b42b8981a8ae52b612acdf07c60c66ad.nq.gz
    ├── 4078ff260efc781de27be1313c22da3021469544.nq.gz
    ├── 40e8d5211150e90a9372ce74dd7fe11c1660b68b.nq.gz
    ├── 415595295e7fde5d4de648284091bc87c53b4a10.nq.gz
    ├── 423bd9a9ccd635b866ea9129d77f4e79f3b115aa.nq.gz
    ├── 42700b7d82e4c4a8a9f66293d262da5ab91a8fb1.nq.gz
    ├── 432fffe2b30755a779a5b3fb41d945d81a89f152.nq.gz
    ├── 43a4bf7898545effb8b2e930d17edecc73890c58.nq.gz
    ├── 43eb56cc1576fd8465265c58e33789e1164f2fa6.nq.gz
    ├── 44948a399531836d8df4256aeb94e2f68fb1c6a9.nq.gz
    ├── 44a7f0c661393ec6ecd55456b646dd2e29902424.nq.gz
    ├── 4589362f933aa95493fdd98ce965eb810180c98a.nq.gz
    ├── 4597672e61de226ba86c538aaec2aa7ce7afc07e.nq.gz
    ├── 474b2b4f9fba001a1fce411960e60bcf80d757ed.nq.gz
    ├── 474f4a42645e20883d979407916bf3b2cb67bd6e.nq.gz
    ├── 479f06933e4e536ee159b738794daa05364119bb.nq.gz
    ├── 480d78e9521348abd621bb1f9c031d2a2c2f2aff.nq.gz
    ├── 490de5e7e4f7b6ba6c0e372eb7c0c3bfce2a77b9.nq.gz
    ├── 4a1ba22e24125d8eb1c1c1a868884951b905a9ef.nq.gz
    ├── 4a855f31aa2b5cc2da591291364597fb97954471.nq.gz
    ├── 4ab48dda2c42b4e3ea291ee539c2e4afe7b51c99.nq.gz
    ├── 4ac686764744b29ba20b0e5798170816f54ed868.nq.gz
    ├── 4ae4aede24a6e02d0ba19f081fc076ff90a65884.nq.gz
    ├── 4af1c7be5fadc8a312d9f248dbf394c2b6adf22e.nq.gz
    ├── 4c06c88d33519b38f8ea6b9cb6e5f38ccb29d420.nq.gz
    ├── 4c3af3ca8a25f68475b30d50435d0f7b68ed94fe.nq.gz
    ├── 4c59f5685622130eb93d3705979016aa35a38aec.nq.gz
    ├── 4d7cdd5e305e96001452db9f6585bb6d14827cbb.nq.gz
    ├── 4dd7d174aa465b966dfa41fff9c5d1fc1de0edff.nq.gz
    ├── 4e8a148df1e322f476cedffe4eadc5ae6ee9b6f1.nq.gz
    ├── 4f304fdd27c815dbb6ade82d59ebb9d3d4107231.nq.gz
    ├── 4f622f73f30017868f55e8503a968593c309b204.nq.gz
    ├── 4fe785cb5cbdd1546d6663880af7d282597a8c84.nq.gz
    ├── 502210dbec824e7ecdc9544d42f3b64b7a4b42b9.nq.gz
    ├── 5070708b214a2d34549aa8a64445a53716573ea0.nq.gz
    ├── 507d666a23fc35f51b931e4f032c6d4b07872a45.nq.gz
    ├── 5097186377948c9302ca73373de4c872ab3f8821.nq.gz
    ├── 50d284511fe12f6b9f5a06e0a39981b29a53eb09.nq.gz
    ├── 516acf56946b8de6fa40e07cc53042e8a2fcdd18.nq.gz
    ├── 52fda9b30cce243cafa1cf2a039c91bf92d73279.nq.gz
    ├── 537f761b424ee90fee08d82873b9fa356cc5c548.nq.gz
    ├── 53c7197f9d2d00ccf256aee57e2de1847a926725.nq.gz
    ├── 54af7cb44879e4e58d321016dab6ab877622b08e.nq.gz
    ├── 5522ee9250986ca0058e86c8438c03d81c3bac90.nq.gz
    ├── 555e884d3066fb1ab517c6737635aed0ae4793e6.nq.gz
    ├── 5612cd25b0474f19f27f9fa46825bed353176ad1.nq.gz
    ├── 56136b206374ceff9c566aa1cd88d5be30f8c73b.nq.gz
    ├── 567683b3b449f0c6a675a58fb168657b2a5e3734.nq.gz
    ├── 56fe293f5cbec4f9efa2a6a77a3374d09e358e56.nq.gz
    ├── 5704813d9eee80a7ca790b204a836e81d58cbf1a.nq.gz
    ├── 57621b248ce8cab819c748df42e0e056b489062f.nq.gz
    ├── 577ffc5ecf4f138ab4183d9ee4bef445d6f8142c.nq.gz
    ├── 57ac6a1f3f6d47f4c9baa1f4c7c33571758527d8.nq.gz
    ├── 57e33ee9e905a64eb92df812d2f0bc6126066042.nq.gz
    ├── 587358e5d777e1217192ae0ec5fe7815d33ef2a4.nq.gz
    ├── 595efcde376ea498ee65bc39310060a046b83d1b.nq.gz
    ├── 598e82b4192a3c2801db1092f3204212d5b64af4.nq.gz
    ├── 599b0f1226cde2e3de6f009c056b8b89c84838b4.nq.gz
    ├── 59b6c2119bed7d839db7324bc5f6090e165f2f68.nq.gz
    ├── 5aa650d7bf99520e306a45d30d639e1db1e68788.nq.gz
    ├── 5ccceec5f9d26e1f8d919cc5f6a0f4075a0f2e69.nq.gz
    ├── 5cf1ece8c068075db21d9f1a097ec4699b603ead.nq.gz
    ├── 5d72271ebc8db3d10bf7e9c6af209e857566bde6.nq.gz
    ├── 5dbeb1449113acf79cd44268ef2d652c154b5f02.nq.gz
    ├── 5e0e8e91a2d8b5e45d6eb338a1f8eee4e12018ff.nq.gz
    ├── 5e208f3336eeba29793f2c81a86762167eaf6f53.nq.gz
    └── 5e22e3ec4d2625201425afd04d42ed5be78ca772.nq.gz

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

[UKPLab/arxiv2026-mic](https://github.com/UKPLab/arxiv2026-mic)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
