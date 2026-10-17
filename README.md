# Repolex Knowledge Graph of Farama-Foundation/Gymnasium

RDF knowledge graph data for [Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium), parsed by [repolex](https://repolex.ai).

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
rlex download Farama-Foundation/Gymnasium
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 57c1610e80214db72c1c7410d6b65bb1a989e233
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 57c1610e80214db72c1c7410d6b65bb1a989e233
│           └── chunk-001.nq.gz
└── blob
    ├── 012ff540124d265f9cf8579f8d196545e3a56508.nq.gz
    ├── 014daec15acd6a88967dca9ebab97c0e250ef21a.nq.gz
    ├── 01d6aca4f9b34e9436baff56ab98004a13a00847.nq.gz
    ├── 02b908c95876a9331333a4884532886c2002fe13.nq.gz
    ├── 037b114d8b2cec34efb70ca1f7a664bcf9687a99.nq.gz
    ├── 03a6354826253a5da8efe076a1780db6d06c41b6.nq.gz
    ├── 041a2a2dd38b1783846f869334c4a1dc6df1922f.nq.gz
    ├── 04f8cab50261dda58873564b916dfea1b1ba5c54.nq.gz
    ├── 0601e3eec8803d61860ea3c48c63984da7ef9411.nq.gz
    ├── 065a725c9ad8871d445bd964c01896814aa3ba6c.nq.gz
    ├── 0693da248942ce59cac5191ec434f9192965a3fc.nq.gz
    ├── 07447c59dc560e9f9b5a3141623d2672162886c5.nq.gz
    ├── 082794295c0669d3c3c3fb9ff969c03f0de0920c.nq.gz
    ├── 08bdeb19129ca649c765ed5e80e2e3af5a09d669.nq.gz
    ├── 08f4496d92e0092df32491e7a40b31ffb78cefe6.nq.gz
    ├── 09798942ac56fd2b6dca2ad5bc31399ad505dd97.nq.gz
    ├── 0b3bb56fce15b6f5a36af8bb52795e51327584cd.nq.gz
    ├── 0b4f1f11b3a8c4214534a7ebf446b878f12dce08.nq.gz
    ├── 0b89acd714efb140c520be2c0ebf214e5ac85c21.nq.gz
    ├── 0ba2f57511cf652f033c822319c161197f0e68a8.nq.gz
    ├── 0c9aa8d980df0c1c3c27dfb3177aa3d0f95f1e6c.nq.gz
    ├── 0cb791a7728d407a5a6e3bad9bc3913f97a37749.nq.gz
    ├── 0db0c7d1fbd64ed97c8ddcc3f1d313dc48c3567c.nq.gz
    ├── 0ee0174d615f11abedd8b2bcd59a3d3b96bdbe3f.nq.gz
    ├── 0f46393d38bd7fcf44b616e5b282a7f8984ee997.nq.gz
    ├── 0f754f9cd0e33ea1d2e3db1465ac09b7b86fb63a.nq.gz
    ├── 0f81ec061bd8cc09013d2dde45d2ece2fb2b52a5.nq.gz
    ├── 0fefe9014686278fddae70fca53fdbf7e12cfe4b.nq.gz
    ├── 10266e24896a363fe25ea1e433a76f8d7587bf1f.nq.gz
    ├── 117d426fecdf4120d9ffa98c25a4a73dc05f5676.nq.gz
    ├── 12a8b22efedff1ece7105e50627351a30a680ce6.nq.gz
    ├── 12c19e8505fab938599abada31241e656c89e1ef.nq.gz
    ├── 13387c6a8ed9cc6a75fa83c9e659da3ee5ed4045.nq.gz
    ├── 13b673a8848bfc1b24bec131748381741209f977.nq.gz
    ├── 1473d833e96138dfe4d0669ee9abd53bf3d26715.nq.gz
    ├── 14cb127c95766152fa94cbee4643a8ccc8783d40.nq.gz
    ├── 14e155d10eb4fb47eaf31b88ccdd4a818b6fc94b.nq.gz
    ├── 1528b60d80ac33ab4b36fd1c73fe6fafa9374277.nq.gz
    ├── 15c509c99a70f1304a979d95bb798ec25eca629a.nq.gz
    ├── 15fce72d9816fd0e14ad8e697ff85e3dcc2f8d89.nq.gz
    ├── 163f9783034d09554316b3ad884320e3b7f39ebb.nq.gz
    ├── 173e1c86bd7ed350b7a6cd6446c478954b48c8b5.nq.gz
    ├── 1793e7737e8921b005721c1e5e0fa97017983da9.nq.gz
    ├── 17bfb91a0a8d0e662e83ee726dcf7389e575f238.nq.gz
    ├── 180bfaec2c541dffdb1b5b0b0703df5298f15e75.nq.gz
    ├── 18c387f7bbbd2c2a480851db1f703b6ee86e90f7.nq.gz
    ├── 18ce4edef81d42417978f556c496f73dda0c5188.nq.gz
    ├── 1906171c7c8266c06d29b91705518ade15181df0.nq.gz
    ├── 1945a7f166be6382f409b5220a2937afb30199d0.nq.gz
    ├── 196d06dd1b7c2e340596f80c77f97da37ae5c1aa.nq.gz
    ├── 19d7c250a3267bfd7388e8eb3e3f031d6ad52b67.nq.gz
    ├── 1a0e3297de72b60b73dca81d2699890dff1a5b0e.nq.gz
    ├── 1a5b1ea1df6519588b53e63fbd1b9bd9d558c0ac.nq.gz
    ├── 1aa423652b279e6bf31cd1f06bed6a9c421f9323.nq.gz
    ├── 1c190366a05e6e036cafd2e48f69c1698aede9fa.nq.gz
    ├── 1c2b4ea357b66c30ec8b8c1444854fb5ce6af6e2.nq.gz
    ├── 1c48fa647ebc89cf1e4d5c7d608fd79894626028.nq.gz
    ├── 1cad6bf494169112d4531491e21369abf61f2d60.nq.gz
    ├── 1cd277b640ce1576fc9b409ae41e724f7db7d12a.nq.gz
    ├── 1d3829f8f5daab7afdce1d7a20eec09037f60b75.nq.gz
    ├── 1d481c04ce815134d54cd7778e3edafb0fc50e8d.nq.gz
    ├── 1e02955708c7f7e4d912f7b6d1d9cb5a46615521.nq.gz
    ├── 1e5343caec6bca9b5123d79fe055a2ed65ecd8f3.nq.gz
    ├── 1e581aea997fa6e09d6d2bae5f7151d09309a67f.nq.gz
    ├── 1f7b2c626deac30a431a6b623bb4fa79cbac2ee1.nq.gz
    ├── 1fbd57304717b34a776d103561be14ee3c9ec7d0.nq.gz
    ├── 209d4b83956215e0a8dd4bca1810cdb51b055c81.nq.gz
    ├── 20d259da46a0a40c878ec4155e5bb090b0b85f48.nq.gz
    ├── 214659a6ebb9fee34cd08c218b07843e03da66aa.nq.gz
    ├── 241575c6f8a42d6572b115ab87466bd0b9733cca.nq.gz
    ├── 244e9460d087d7eb3ce60896f47097cbffe2137a.nq.gz
    ├── 24819ebf5291414c4b0003aa1fcff793698f679d.nq.gz
    ├── 248928ebeefff2a0d5cd2b7245b07cf1f8704930.nq.gz
    ├── 24a1f7815715e9aad64196fabd4588b78e642c0a.nq.gz
    ├── 24bd5594f08ec28c0dcc0095aa8f959d1c9e1821.nq.gz
    ├── 24c6a896b73077a5155388d21da0d9c2123eb697.nq.gz
    ├── 255a41b1d6ff915795a44a23ee9514b163725bb6.nq.gz
    ├── 2814dc793929be05dffc3695eaea5bc34d3e731b.nq.gz
    ├── 28355139d66f87d211aae7d7ff60a2da1b825933.nq.gz
    ├── 28c0c42ad81c8b8010b2d1660097fd485df2867a.nq.gz
    ├── 28cf6a3b4a8e63c4ecf43633a08045bd5c458fb6.nq.gz
    ├── 28f8b2ab016abed8b0d21070bc750871ca66e534.nq.gz
    ├── 29d44c74487bf7a0ef7307e0f5e771ef62f8ddd6.nq.gz
    ├── 29fa890149dfe7fd9af8ab91cfa4229b7153fd51.nq.gz
    ├── 2a6ea1c7ae79b1df62683fc80d8bce5bb784da99.nq.gz
    ├── 2a8fa9a08ece0c178c2d48ab96ad62b6b6ca76c4.nq.gz
    ├── 2c13a60d78e0610021d15c4d16544149489cc61b.nq.gz
    ├── 2c5334a5ac98a681d4fcedde1c5e10e0e056523c.nq.gz
    ├── 2cab22143500b66a471c0949829a0990bcc11007.nq.gz
    ├── 2d08beed2d8c9c5691e021e9b8e280345a8ab2ca.nq.gz
    ├── 2d6e5ab53ac89da5c53fabfe62677fef2b0735c4.nq.gz
    ├── 2e00893453b0a49f4df19197d5a979ca3a61dc6e.nq.gz
    ├── 2eaba50221429223acf81f5be37fdc385d72df65.nq.gz
    ├── 2eac755c04878af00b3320bc6fbc4b24d9e5964d.nq.gz
    ├── 2f717558a8ad311b132c7fea45acf3f1570778da.nq.gz
    ├── 2ff409958145f2b4a56d06cb548849c32257ae6c.nq.gz
    ├── 313ecda5bf4bdcc13647eccbd085c5c164bf4649.nq.gz
    ├── 321fb6564f61e15b18b0f835e3218051884daa64.nq.gz
    ├── 338c2e87a705c425ab7c2ff733d5c40c96fcc918.nq.gz
    ├── 33a9ed37923f453e5687ed1b31f7d7ffa8ec5938.nq.gz
    ├── 340b8216371e444cbfbacd4f4a21cae2339956bb.nq.gz
    ├── 34195e87eb86ba9a27963964ee37db56d9c2df58.nq.gz
    ├── 3581b7688a0f9f3376191987e4cd5d3e0b165f6c.nq.gz
    ├── 35c793ad0c7308d4807cfdc96b32d2f3f9371603.nq.gz
    ├── 35e97025c951618fbc450105b012e3d6fac1e0f2.nq.gz
    ├── 397303bb39b8441198ba3f5ba6609391a1d8d1c8.nq.gz
    ├── 3b54afa5c1d51b2c97538e5b92dcb0dfa079f01c.nq.gz
    ├── 3b5d9e183709d07c73613b9c1a9bd6e65db028a9.nq.gz
    ├── 3c1ceea062fdd8b18d56fefddcd03f5b8f593304.nq.gz
    ├── 3e66b8a981bacd15ce52373ed4cc480b99b39180.nq.gz
    ├── 3e95d515dcb04d0d7318856d4e3abb8dfb606aee.nq.gz
    ├── 3ecc962f970e299294eb1c2df33e6601aeb4efa7.nq.gz
    ├── 3ee3d7eb209b2a41e99b04445b31e1510c60ebe8.nq.gz
    ├── 3f1999133525054e4d7a2fb7e9ad2b8c38e0fb65.nq.gz
    ├── 3fca36af0d2cfde6bdec057511f8346fd28995ee.nq.gz
    ├── 3fd75d793f66cf32f1e16fd88748c23b707cee8e.nq.gz
    ├── 402af8baad1307555ae974139d0186b18f039bd8.nq.gz
    ├── 4158e354dad5521353972c9081a586cfba0384bf.nq.gz
    ├── 41cdeedfc40c3624b4f857516820eb05d4f978af.nq.gz
    ├── 420627141e06c6ad92bb43761e017b8a4044415c.nq.gz
    ├── 426550d5f57aa972722b1d43fdef5eb90b935109.nq.gz
    ├── 4270ed4659b244a4291c6a6d43bad9966f10b6bb.nq.gz
    ├── 429f204e807e01f011ba5f54cff28c0dfb5a1d13.nq.gz
    ├── 4343822ed112486b4c7300f798a1b3d9d98c8887.nq.gz
    ├── 456d95f5e8cd91a79a325fcd00ad90a7d571ed4a.nq.gz
    ├── 459df5f4e64aa6e3b666023f453970d0553e24ad.nq.gz
    ├── 45ae45bd2854fe41557d95de2b8bfc03c4ecd42d.nq.gz
    ├── 465be56849afffc26aabe3f2b5e7507d9c436695.nq.gz
    ├── 481de7551b9bae389d0851e8c5d335713268d1b6.nq.gz
    ├── 48a21397c758b6769d6b3267cfd0004eaf1fcfea.nq.gz
    ├── 4972d8087fb58050cd9a073f9a61ff3cb6e61265.nq.gz
    ├── 49b45fcef5b95d9e72c5cd8e82001a0be90bafa8.nq.gz
    ├── 4ad49e56ad7400f795834ea06a77b932b008d86a.nq.gz
    ├── 4b3aba2c7dafa407594576b6ef93a7b4ea6b8d2f.nq.gz
    ├── 4bed3a134abfc6e33c12aa8bfa7144d141801c10.nq.gz
    ├── 4cc1951dafecb57bff51e0a4bfd533ffc5536f27.nq.gz
    ├── 4d23b318bb991135ab05b01ca19930a19d53aba8.nq.gz
    ├── 4de0b6c9f419e979b0c83300a1feeff847584da9.nq.gz
    ├── 4e758e7b18baad069da2965d27b134922f7c90ef.nq.gz
    ├── 4f73493247306253597f6a21635fe699184bdfcc.nq.gz
    ├── 4f7485006fe65184570b344c0a7fb7da8c63b9b1.nq.gz
    ├── 503ad0a6aaa7fb2cf43b3f061e0db80e88798672.nq.gz
    ├── 50704b77de552717902eabfdab9c5554807a98c2.nq.gz
    ├── 50f34d66369ecd62a18d51791b596376bd2e9548.nq.gz
    ├── 51091425a43fdc85c145c9e5cff282836bcb1902.nq.gz
    ├── 51290511d2fb286648cced382cf8eb712c8c7df7.nq.gz
    ├── 51dcbdb8911533e1096173baae86342627d7aa99.nq.gz
    ├── 522b20127faa318f8d88a54c47e5c1f285d0a03e.nq.gz
    ├── 522fa829101eaf275c41397fbf9120e356186ec9.nq.gz
    ├── 523d42edd593487788271d167d81fa41452fbd27.nq.gz
    ├── 5262d30f76d4819c64e8495d9955bf442fb45c2a.nq.gz
    ├── 52897ab07072ae88f0d2781d1931cd8b82f80afc.nq.gz
    ├── 52c5562bb398f05fef63a0b46add1ca5e75e9d01.nq.gz
    ├── 52d4d1336f72372e6cecf3ab5c1cfa1752d3fb01.nq.gz
    ├── 52defe6e789f6727a9c9e5c4d5380b4cf7c5931f.nq.gz
    ├── 5300ecb1c69858c5a03578e9b9d9a809cea6707a.nq.gz
    ├── 5348868ba2434f0bd91d4e4e18d966a0f174ce46.nq.gz
    ├── 5404a0771f261f7679acc7bbe21f8d8a97c55d5a.nq.gz
    ├── 54741e5b7c85e07fcc9f0b2d894d0167f35ed6a6.nq.gz
    ├── 54ad144b2677e092a661df53a9eef9bed5b164d8.nq.gz
    ├── 54e422b7637e047ddf0e353afe43cfa0b3b17f7e.nq.gz
    ├── 55c1c9628d0e2c9c1a6fd6a8fdf7f59bf8ac8875.nq.gz
    ├── 562eb420cea1b2c4dd92756f91ee667c5229de46.nq.gz
    ├── 56a8fa57c3ed3f51411dcd9945fd6d6492c470f1.nq.gz
    ├── 57349cec50f5abe180b89ad6cec96b7ab8635691.nq.gz
    ├── 57ab3dca54ee7391633f5ee994dfd06f7ac9f279.nq.gz
    ├── 57db86ae3c1cae866c0bd76d22312bcdfd6ce233.nq.gz
    ├── 583ea309cd33fadf5fdb88545636222a893e84a4.nq.gz
    ├── 59357d6a29f4ce93ea75874b9adabd6d79df9c2d.nq.gz
    ├── 594abef913ee4f3feadd49cb62505ba613f60ef1.nq.gz
    ├── 59fad5cfe6f2d3c344ac8a03d450135d7c081d02.nq.gz
    ├── 5a13f696df28b1aece6644a8fce0a9fb3bddeffb.nq.gz
    ├── 5a90ceae97e63440cd3a0c92d172195df9b23cf4.nq.gz
    ├── 5adce15d799817fc2d230658a2d94e81b9a0bdf0.nq.gz
    ├── 5b0d3987dd25fe860de0d3573c98fb28a6936bf6.nq.gz
    ├── 5b0eba67b3cbe724bc8f824dc55aa72ca4b6df16.nq.gz
    ├── 5c027355aebd3dbf690aa8748280470f227195ad.nq.gz
    ├── 5c1d988895f3b57c70d27d0f163486d32faf5f7a.nq.gz
    ├── 5c4664aad2758cdbb46dcb32ba935528aedc2bc3.nq.gz
    ├── 5cc1db0da6ceba55036c8dd7bca4a5b6e01ebde5.nq.gz
    ├── 5cc7032f60ec783ad67ee09e117f9a57368f0b54.nq.gz
    ├── 5d85f65274dedf4fa781017a7f166ffff99aaa36.nq.gz
    ├── 5d9bb269cce313e73cbaa01da087d93051017892.nq.gz
    ├── 5dbed7c2f65b27cdf0e8eb302ce215434aa0a458.nq.gz
    ├── 5e1e3acbaa4a4ed3436f4874e92a67d9a3e31120.nq.gz
    ├── 5e8e1a10058fa8f0d5363d6083631167b5b7fd42.nq.gz
    ├── 5fa7ebb6ab7757a7e5cf88cfebb4663a2530c89a.nq.gz
    ├── 5fe346969214c449a288f0c546cc949c3fdfc437.nq.gz
    ├── 600852d3e54d503d4819e26ceb4f52cc9c234ac6.nq.gz
    ├── 609903e625a8140d98dc2bfc15c471fa4ee08739.nq.gz
    ├── 6119fecaaee7fad8a04dce5d8c5fc395764db006.nq.gz
    ├── 6124564ea3bdd58cebad49914c032af2717c28c1.nq.gz
    ├── 613ae084324c4b3a00545c5877e8c46ed06d7d72.nq.gz
    ├── 6179186803d83c5d3b90ef6b435fff6052f4585b.nq.gz
    ├── 61b727ec2034578daa01db4e7c856dccea46c021.nq.gz
    ├── 6225992a48e30a4a96742e9914a66ccda0f36d41.nq.gz
    ├── 631d53203ffcc2b4ba053f5d336f7e0affa48a89.nq.gz
    └── 6498f395ef6aa5c627af145bb68dcdacc2e2acbc.nq.gz

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

[Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
