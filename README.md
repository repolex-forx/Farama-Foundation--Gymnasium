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
│   │   ├── 365080941ea3a815ac09e57a7d4ee263a142651d
│   │   │   └── chunk-001.nq.gz
│   │   └── 57c1610e80214db72c1c7410d6b65bb1a989e233
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 365080941ea3a815ac09e57a7d4ee263a142651d.nq.gz
│   └── repolex
│       ├── 365080941ea3a815ac09e57a7d4ee263a142651d
│       │   └── chunk-001.nq.gz
│       └── 57c1610e80214db72c1c7410d6b65bb1a989e233
│           └── chunk-001.nq.gz
└── blob
    ├── 0000c848252b4c1edbc37ff228c1c6d3bc04a2e9.nq.gz
    ├── 006f9841e142156db8f5ccf7f71b91a984ad5708.nq.gz
    ├── 012bc5560cccc4fc4b8804a04106ea76def6ef6c.nq.gz
    ├── 012ff540124d265f9cf8579f8d196545e3a56508.nq.gz
    ├── 014daec15acd6a88967dca9ebab97c0e250ef21a.nq.gz
    ├── 01d6aca4f9b34e9436baff56ab98004a13a00847.nq.gz
    ├── 02724791e28428e415c4437005d0efe594b02a1e.nq.gz
    ├── 028dc2321b36c4e99b622f4902408cc05df54d2a.nq.gz
    ├── 02b908c95876a9331333a4884532886c2002fe13.nq.gz
    ├── 02e47dfa91568b067977f0904a2a9480309600b7.nq.gz
    ├── 037b114d8b2cec34efb70ca1f7a664bcf9687a99.nq.gz
    ├── 0391589d86d9bc453b11f3a9d6d15de41405b5d5.nq.gz
    ├── 03a6354826253a5da8efe076a1780db6d06c41b6.nq.gz
    ├── 03dd56ab1c85837304d61a08031e63ebe2b4ef04.nq.gz
    ├── 041a2a2dd38b1783846f869334c4a1dc6df1922f.nq.gz
    ├── 048d85cb4ac0d3bdc15d19e708a89758e2271792.nq.gz
    ├── 04aac955ee1014e8a4065c8f91cdee6b47c7121a.nq.gz
    ├── 04ec431da076dd52267d801ec8e471f0e02c4463.nq.gz
    ├── 04f8cab50261dda58873564b916dfea1b1ba5c54.nq.gz
    ├── 05364776e731177b5ca585435caacbdc161246c7.nq.gz
    ├── 05398f8cf8cd4bab5cd986bdd8870cb164b0e2c7.nq.gz
    ├── 05519a42935dcbdd2e0fe80fd5eef85fd73ba0bc.nq.gz
    ├── 0601e3eec8803d61860ea3c48c63984da7ef9411.nq.gz
    ├── 06388f6fab80656acf69ab1b5b229e07169949eb.nq.gz
    ├── 065a725c9ad8871d445bd964c01896814aa3ba6c.nq.gz
    ├── 06897b80c728a7d756111426a52daaf04f359654.nq.gz
    ├── 0693da248942ce59cac5191ec434f9192965a3fc.nq.gz
    ├── 069422654adf642b8e81a1e6466eeca3892289e2.nq.gz
    ├── 071a8380cb0ae96c710c20cffcbab673d157d860.nq.gz
    ├── 07447c59dc560e9f9b5a3141623d2672162886c5.nq.gz
    ├── 077094c980add74c0a20bc73cc2cc857b4950d29.nq.gz
    ├── 07c690436899e927fb2e0fceaff0c1d74aa57082.nq.gz
    ├── 082794295c0669d3c3c3fb9ff969c03f0de0920c.nq.gz
    ├── 08428b6e6f61dc15a6f839b2319ec5285340f5f5.nq.gz
    ├── 08bdeb19129ca649c765ed5e80e2e3af5a09d669.nq.gz
    ├── 08f4496d92e0092df32491e7a40b31ffb78cefe6.nq.gz
    ├── 096ce4d3310260ee9f579f6457fa84e2151ece3f.nq.gz
    ├── 09798942ac56fd2b6dca2ad5bc31399ad505dd97.nq.gz
    ├── 09c4eae0df5a344a53ebe52e9d3b609a0399e3d3.nq.gz
    ├── 09e7f6177c1fe312f98ec07228dc3a679d789f42.nq.gz
    ├── 09eaccc3ee0e3ce4208fd787faae21bd7622ed15.nq.gz
    ├── 0a241a966ec56cf31cf446235f606ed9f5eca73d.nq.gz
    ├── 0a4d2ce321900a591ac7a1db7ea0187e00c5a971.nq.gz
    ├── 0a6f53b4afbe54ef90f293cc2f10746f43136379.nq.gz
    ├── 0b3bb56fce15b6f5a36af8bb52795e51327584cd.nq.gz
    ├── 0b4f1f11b3a8c4214534a7ebf446b878f12dce08.nq.gz
    ├── 0b89acd714efb140c520be2c0ebf214e5ac85c21.nq.gz
    ├── 0ba2f57511cf652f033c822319c161197f0e68a8.nq.gz
    ├── 0c7e28c3b35489872d3425dc7cbe511911140cbc.nq.gz
    ├── 0c9aa8d980df0c1c3c27dfb3177aa3d0f95f1e6c.nq.gz
    ├── 0cb791a7728d407a5a6e3bad9bc3913f97a37749.nq.gz
    ├── 0d0a86bca2838f1012f6344e4567c939b20a8006.nq.gz
    ├── 0db0c7d1fbd64ed97c8ddcc3f1d313dc48c3567c.nq.gz
    ├── 0df60733e71d9fdb6116cd19f84428dcda284b7a.nq.gz
    ├── 0ee0174d615f11abedd8b2bcd59a3d3b96bdbe3f.nq.gz
    ├── 0eed7ae6d55b57fa681270931e44443c7d7806e0.nq.gz
    ├── 0f46393d38bd7fcf44b616e5b282a7f8984ee997.nq.gz
    ├── 0f754f9cd0e33ea1d2e3db1465ac09b7b86fb63a.nq.gz
    ├── 0f81ec061bd8cc09013d2dde45d2ece2fb2b52a5.nq.gz
    ├── 0faa41852126e4974e4a491be55a50e8eabf957a.nq.gz
    ├── 0fefe9014686278fddae70fca53fdbf7e12cfe4b.nq.gz
    ├── 10266e24896a363fe25ea1e433a76f8d7587bf1f.nq.gz
    ├── 10d495dfbcadd4d479d2c5df543c0c81b142434a.nq.gz
    ├── 10e9ccfbe936274a18aee604d0cfb656a2bc7f8a.nq.gz
    ├── 11008bd3765740caee7ca814dff03ac2ee65a6c9.nq.gz
    ├── 1160435cf23c62705fcbf56b5b96abe036e6dfa5.nq.gz
    ├── 117d426fecdf4120d9ffa98c25a4a73dc05f5676.nq.gz
    ├── 11d340b971f758e0327e8ec14ad432d90017c3dd.nq.gz
    ├── 12a8b22efedff1ece7105e50627351a30a680ce6.nq.gz
    ├── 12baef14b7957a2930583408c677ddd8bb22520c.nq.gz
    ├── 12c19e8505fab938599abada31241e656c89e1ef.nq.gz
    ├── 132b6e4518c4e59073535d43c38f0c2932342583.nq.gz
    ├── 13387c6a8ed9cc6a75fa83c9e659da3ee5ed4045.nq.gz
    ├── 139cd193d5c1eca968e3955e72379e4a43aa6be3.nq.gz
    ├── 13b673a8848bfc1b24bec131748381741209f977.nq.gz
    ├── 145b7124355fdec1c33a0360cec4ce6dfb345093.nq.gz
    ├── 1473d833e96138dfe4d0669ee9abd53bf3d26715.nq.gz
    ├── 14cb127c95766152fa94cbee4643a8ccc8783d40.nq.gz
    ├── 14dde4a111bb42c87be7e4032cc2df5b67b5319c.nq.gz
    ├── 14e155d10eb4fb47eaf31b88ccdd4a818b6fc94b.nq.gz
    ├── 1528b60d80ac33ab4b36fd1c73fe6fafa9374277.nq.gz
    ├── 15a56740f8171c66bb5ef7fb1bf71d0eac1dc189.nq.gz
    ├── 15c509c99a70f1304a979d95bb798ec25eca629a.nq.gz
    ├── 15fce72d9816fd0e14ad8e697ff85e3dcc2f8d89.nq.gz
    ├── 163f9783034d09554316b3ad884320e3b7f39ebb.nq.gz
    ├── 16d46c9870c7a7943bcad94b39defbe9394b31ea.nq.gz
    ├── 173e1c86bd7ed350b7a6cd6446c478954b48c8b5.nq.gz
    ├── 1793e7737e8921b005721c1e5e0fa97017983da9.nq.gz
    ├── 17bfb91a0a8d0e662e83ee726dcf7389e575f238.nq.gz
    ├── 180bfaec2c541dffdb1b5b0b0703df5298f15e75.nq.gz
    ├── 18c387f7bbbd2c2a480851db1f703b6ee86e90f7.nq.gz
    ├── 18ce4edef81d42417978f556c496f73dda0c5188.nq.gz
    ├── 1900c08a2cfd46c1102042c984d7cb7d330c1adb.nq.gz
    ├── 1906171c7c8266c06d29b91705518ade15181df0.nq.gz
    ├── 1945a7f166be6382f409b5220a2937afb30199d0.nq.gz
    ├── 196d06dd1b7c2e340596f80c77f97da37ae5c1aa.nq.gz
    ├── 197ca1da1422515e6371fe346d08301c9475f47e.nq.gz
    ├── 19bf11c591f3f9cf54b08bf8d867818924068e80.nq.gz
    ├── 19d7c250a3267bfd7388e8eb3e3f031d6ad52b67.nq.gz
    ├── 1a0e3297de72b60b73dca81d2699890dff1a5b0e.nq.gz
    ├── 1a5b1ea1df6519588b53e63fbd1b9bd9d558c0ac.nq.gz
    ├── 1aa128f4b283c96d5a085550386090bc2b0614c5.nq.gz
    ├── 1aa423652b279e6bf31cd1f06bed6a9c421f9323.nq.gz
    ├── 1bbf6d22627ad3f35abe9c982410ed0cea104624.nq.gz
    ├── 1bdc9ccd9017e7a8d397db6ef8bd8ae09dfd931c.nq.gz
    ├── 1bfe5b87ff1eacdc5a5f881ada7068bc521baa40.nq.gz
    ├── 1c190366a05e6e036cafd2e48f69c1698aede9fa.nq.gz
    ├── 1c2b4ea357b66c30ec8b8c1444854fb5ce6af6e2.nq.gz
    ├── 1c48fa647ebc89cf1e4d5c7d608fd79894626028.nq.gz
    ├── 1cad6bf494169112d4531491e21369abf61f2d60.nq.gz
    ├── 1cd277b640ce1576fc9b409ae41e724f7db7d12a.nq.gz
    ├── 1cf664580928eb78dcc3d30ecd6f405b821fcc06.nq.gz
    ├── 1d3829f8f5daab7afdce1d7a20eec09037f60b75.nq.gz
    ├── 1d481c04ce815134d54cd7778e3edafb0fc50e8d.nq.gz
    ├── 1de070afa9aedb6c96ca12acbdbe0f0f570a5031.nq.gz
    ├── 1e02955708c7f7e4d912f7b6d1d9cb5a46615521.nq.gz
    ├── 1e5343caec6bca9b5123d79fe055a2ed65ecd8f3.nq.gz
    ├── 1e581aea997fa6e09d6d2bae5f7151d09309a67f.nq.gz
    ├── 1eb69207db36ccb7adc5d2799f984288f4e7e067.nq.gz
    ├── 1ee5f0b4afb1d01a545c12e3078c0906a4779358.nq.gz
    ├── 1f652b23fd279501df5f94fc480fb8a2b46c5d54.nq.gz
    ├── 1f7b2c626deac30a431a6b623bb4fa79cbac2ee1.nq.gz
    ├── 1fa5a37d7db514adda932ed2810754c796d26444.nq.gz
    ├── 1fbd57304717b34a776d103561be14ee3c9ec7d0.nq.gz
    ├── 1fd6f80dbfbd76294c12c3a0ac61904852f50b4f.nq.gz
    ├── 1fe97cb2f9cb9c2796339a47c150a1ae60dfe5c7.nq.gz
    ├── 209d4b83956215e0a8dd4bca1810cdb51b055c81.nq.gz
    ├── 20d259da46a0a40c878ec4155e5bb090b0b85f48.nq.gz
    ├── 21037ce3f79ab6ac3847ddbbe71a72020b50a696.nq.gz
    ├── 214659a6ebb9fee34cd08c218b07843e03da66aa.nq.gz
    ├── 215d8185c9117364dc3f9d9bdbe0faab5cc72173.nq.gz
    ├── 2189d5b9930ca9dd7eb10c7a71371363487c7a5e.nq.gz
    ├── 21d1e843cd1a5b8f4c84811673931218076f45b7.nq.gz
    ├── 21e314c2d2ce904279f1ecb2e49c42fed6b76252.nq.gz
    ├── 224edac42494ee131fc7a59136019f8852541235.nq.gz
    ├── 226ab57501aa6aeb91872e3a766af64362244c4b.nq.gz
    ├── 229102cc30eaa39bf01c4806bd15948bdb0d1243.nq.gz
    ├── 230ac9b4987962720917c43443ed9fff8ae6fc49.nq.gz
    ├── 230db548f94dbbf0f28a5b250eec9f39d326fd20.nq.gz
    ├── 235ac25cad286646748b5abae0c816a45c9d57a1.nq.gz
    ├── 23b58115875883a8f1a234cee344ac1a4f9f8447.nq.gz
    ├── 241575c6f8a42d6572b115ab87466bd0b9733cca.nq.gz
    ├── 244e9460d087d7eb3ce60896f47097cbffe2137a.nq.gz
    ├── 24534029e0b5aa32d3f92088a861d9ba271e06dd.nq.gz
    ├── 24819ebf5291414c4b0003aa1fcff793698f679d.nq.gz
    ├── 248928ebeefff2a0d5cd2b7245b07cf1f8704930.nq.gz
    ├── 24a1f7815715e9aad64196fabd4588b78e642c0a.nq.gz
    ├── 24bd5594f08ec28c0dcc0095aa8f959d1c9e1821.nq.gz
    ├── 24c6a896b73077a5155388d21da0d9c2123eb697.nq.gz
    ├── 255a41b1d6ff915795a44a23ee9514b163725bb6.nq.gz
    ├── 25d4acedcd9bb603a7cae392c15b301387433508.nq.gz
    ├── 25e2e2e03ea493f6b29880a65b4b6bfbac6f0df2.nq.gz
    ├── 26e6b7138160fdee98de23877b7959b43829b9f2.nq.gz
    ├── 27941c7ee98bb8a04bd91bcd5fcbbcaabeedf2be.nq.gz
    ├── 27a6089bb3695fe4ce1a246ba60cbc2c4ff4259e.nq.gz
    ├── 27c1819614d396f784085ab3d88c6a69f727d7ed.nq.gz
    ├── 2814dc793929be05dffc3695eaea5bc34d3e731b.nq.gz
    ├── 28355139d66f87d211aae7d7ff60a2da1b825933.nq.gz
    ├── 28c0c42ad81c8b8010b2d1660097fd485df2867a.nq.gz
    ├── 28c440af281858c30e95fb6023f19923065d64fe.nq.gz
    ├── 28cf6a3b4a8e63c4ecf43633a08045bd5c458fb6.nq.gz
    ├── 28f8b2ab016abed8b0d21070bc750871ca66e534.nq.gz
    ├── 29173c8b61ace626f2092b37d35d3154ad51429f.nq.gz
    ├── 29d44c74487bf7a0ef7307e0f5e771ef62f8ddd6.nq.gz
    ├── 29fa890149dfe7fd9af8ab91cfa4229b7153fd51.nq.gz
    ├── 2a6ea1c7ae79b1df62683fc80d8bce5bb784da99.nq.gz
    ├── 2a8fa9a08ece0c178c2d48ab96ad62b6b6ca76c4.nq.gz
    ├── 2b4babadfbd0c7b7c58442093d1b025c38a2c359.nq.gz
    ├── 2b5be1aaadaaf8782d056a7094e9e9d21a7f0213.nq.gz
    ├── 2b6e248df6aaf933736b0153efcfa86145bb9bfc.nq.gz
    ├── 2c13a60d78e0610021d15c4d16544149489cc61b.nq.gz
    ├── 2c1aeb66149d5ba785a422980d4b6b9359917f77.nq.gz
    ├── 2c5334a5ac98a681d4fcedde1c5e10e0e056523c.nq.gz
    ├── 2c97ca20a57eebd2f18657b08514246142b528ea.nq.gz
    ├── 2cab22143500b66a471c0949829a0990bcc11007.nq.gz
    ├── 2d08beed2d8c9c5691e021e9b8e280345a8ab2ca.nq.gz
    ├── 2d6e5ab53ac89da5c53fabfe62677fef2b0735c4.nq.gz
    ├── 2db6ca5685a96ce40c5187a00e71119cdca6e1aa.nq.gz
    ├── 2e00893453b0a49f4df19197d5a979ca3a61dc6e.nq.gz
    ├── 2e66e26c79e268098abcbd662e0afa903cae96de.nq.gz
    ├── 2eaba50221429223acf81f5be37fdc385d72df65.nq.gz
    ├── 2eac755c04878af00b3320bc6fbc4b24d9e5964d.nq.gz
    ├── 2f717558a8ad311b132c7fea45acf3f1570778da.nq.gz
    ├── 2f8854de2979123898549d172389af182028e843.nq.gz
    ├── 2fc9ca4338a6ab760a5737c0670dcc15ee3cef32.nq.gz
    ├── 2ff409958145f2b4a56d06cb548849c32257ae6c.nq.gz
    ├── 30255b0b799868d10f38aeded7bc2f2a538fd356.nq.gz
    ├── 302b41476395e1dffddcf2eee5bbad5eaa822ee5.nq.gz
    ├── 30e36f53e6f5884cdfd010178ccd2ae12967aae9.nq.gz
    ├── 313ecda5bf4bdcc13647eccbd085c5c164bf4649.nq.gz
    ├── 31e940fff06ae55091ef4cdd20537f39880a1e25.nq.gz
    ├── 32097c22825cdb242a38d00ebdbae25afc20ce2a.nq.gz
    ├── 321fb6564f61e15b18b0f835e3218051884daa64.nq.gz
    ├── 327a086f601a6326d6ac2c8e7eb77074bd8b7684.nq.gz
    └── 32d4195ec1c5268dec2fa2a01c43242185503e83.nq.gz

10 directories, 200 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
