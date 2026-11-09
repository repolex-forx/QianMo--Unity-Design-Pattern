# Repolex Knowledge Graph of QianMo/Unity-Design-Pattern

RDF knowledge graph data for [QianMo/Unity-Design-Pattern](https://github.com/QianMo/Unity-Design-Pattern), parsed by [repolex](https://repolex.ai).

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
rlex download QianMo/Unity-Design-Pattern
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a4c0d5df85cf73a04d3a6fe87d3a90f4b6614a37
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a4c0d5df85cf73a04d3a6fe87d3a90f4b6614a37
│           └── chunk-001.nq.gz
└── blob
    ├── 00517f7f028dc5e176a71bac123ee55cabb152a9.nq.gz
    ├── 00768ad1272f495b87b9a6f8843719ad6fcd4544.nq.gz
    ├── 01031faf98de3a9a39a46f18f02c292418679124.nq.gz
    ├── 0168c8bf2a4be3c568b6082ca909cde6008180ae.nq.gz
    ├── 026a87b2a60fdac169ff394fc9a2ef303d17bf52.nq.gz
    ├── 0278c57da818fa9a6cb61eb7c9c29cde5456bc4e.nq.gz
    ├── 02c992ef1fa26fdba04f6390976ac7498b89cd71.nq.gz
    ├── 02e3c4c3f82749d671eed3027dfa9476541ce720.nq.gz
    ├── 036d480c0b6bca4f01fc54b6af5c7d6e5820be01.nq.gz
    ├── 039a807bcd805c3fa4d0cc218d538ce22d4219c1.nq.gz
    ├── 03acbf62c5f7533b16dcc34a8bd4763f7de42b0d.nq.gz
    ├── 03f0f0a6a3e76d590d04f53faf5d89efcf3bc46d.nq.gz
    ├── 04227414cf9f3cdb0631a960574d14a5f4d71831.nq.gz
    ├── 047aefee019e7b7f68ca283abc3c534ba593023d.nq.gz
    ├── 047fa7add7739e70172493e9df6f7392706a3a5c.nq.gz
    ├── 0488e4124e44f0802ce098f4f07863ec7044ec8e.nq.gz
    ├── 0511bdfabefa4bba536eaf274c64e64a6ae819dd.nq.gz
    ├── 05179b206d13436f28c9f14e37d53967df2c7671.nq.gz
    ├── 053e2086f34869a0452b268522b547fe5e918401.nq.gz
    ├── 056e6b396dee0d25c2d3c0a93a8a7438b1bb29b0.nq.gz
    ├── 0596b053598d54a09e66416d35adfbdd3adc5ebc.nq.gz
    ├── 05cb2ace63f307acd47a06c93cfa2f7efa57c5a4.nq.gz
    ├── 06206294057fb2c9d580dd5f61bfe7f5455f0bcb.nq.gz
    ├── 066d18da9bfa0f6badee7250e83cd9fe970f97d1.nq.gz
    ├── 06b7c3347fbf4fe4ef6545e49dce99e78f0d6e10.nq.gz
    ├── 06c1a7ab50b29ccd32bb629add39ba1242e1adbc.nq.gz
    ├── 078cbabb323fefeb9e0c37e97d4e53ab9c2af4f5.nq.gz
    ├── 08e636e83ed9c2b73dcb8ef91332646112324541.nq.gz
    ├── 093302547ea1e8b243127a47fe32992cb2ad3b18.nq.gz
    ├── 0a48d43a0f8c97bb4147989cb4d5bba40f344987.nq.gz
    ├── 0a59d4a49337d0bb4c085ce4347bc51bcc49d2ed.nq.gz
    ├── 0abc5dfc6ffab35a1d4d123dd79e45935b4d32d4.nq.gz
    ├── 0b1a7d2f421f38fbbe1ddf74285ae3dfff582a5b.nq.gz
    ├── 0bad7d6c0c5d0dee139758897c7b73d1ce0288b8.nq.gz
    ├── 0bafc5def67b5911be1658c67cfa211363d0cd73.nq.gz
    ├── 0bc78c85f7b2360f6222a06195d667e638ef2967.nq.gz
    ├── 0c59d497f3388a273272ef3ab97c0afbef68a9c3.nq.gz
    ├── 0c5c641d86e9544c0157bc9724aa3e0d47292381.nq.gz
    ├── 0ce3bf227c8e5883f13b4fb2fc666e9bcb6b17f9.nq.gz
    ├── 0d28e05abd3b0eb37ad9f6f052674b9d6fb56871.nq.gz
    ├── 0d4a260802247afd2e58e35a4e176c3a1ba02243.nq.gz
    ├── 0d731aa612b83f5b9b4327b8e59453ffe9c3c0a9.nq.gz
    ├── 0ef459811af54985a27b232ffb9df6845f13ad2a.nq.gz
    ├── 0f9baf8572beb4b5c1db2c5fe4ee89d8065e6783.nq.gz
    ├── 0fc6de6ff4c01f56e07bcf93f30f8609071241a2.nq.gz
    ├── 1133367e6e3705ae0971dceb525e1c1a14d12ffb.nq.gz
    ├── 11757a8b4be0f89451ea54d227bf78a7f44cf227.nq.gz
    ├── 12588a0a88518c05c6ae8253d49665dd434f5e86.nq.gz
    ├── 125f4e01f395b1f480ef1c1bde1d4d65f6534915.nq.gz
    ├── 12e8c9fd7a32d53e9fbbf7e1016d1e3b3915e7d3.nq.gz
    ├── 13565f781d2584d24250251a9ebc5f05920117bf.nq.gz
    ├── 14c9c418faf9519f0290f4dbcf6164d2714436bc.nq.gz
    ├── 14dedde44d1d36d2f5482b157e9be7e2d6e23922.nq.gz
    ├── 1505735259c2b8b7a9d2d71cad51466bf8be4eee.nq.gz
    ├── 1578c51c3b8030998fc6fcad5d33a48e196befb6.nq.gz
    ├── 168b169f536e99aa0a1a398b8dc21420b0463e51.nq.gz
    ├── 1763081b77f5ee3f3ef89d0a8d4ad24546d3d9a5.nq.gz
    ├── 176aadcde3536e67ca432ffe50b73180bd989a97.nq.gz
    ├── 18371feff8672cd0b7af8eaf0811741646843cb0.nq.gz
    ├── 19b914365db10571162369199209574f912b6788.nq.gz
    ├── 1a3a75c392727dbdf7d00b9447f4c393ee410433.nq.gz
    ├── 1a90abdecc6d316322bd9bc047cc43a51a84ce44.nq.gz
    ├── 1ca9749e9f3d5c60231a729e88a49677fbf3e6f7.nq.gz
    ├── 1cbed8c6241c124ba34e6e3bba1ebcce75c215f3.nq.gz
    ├── 1ce2b23e55a6db6b21bd3e452a51b74da743c87a.nq.gz
    ├── 1ce2d3941236367b9532c36c9ffd7090487f89b4.nq.gz
    ├── 1cfe7a577fdd4ddb758637dbafd201ea7a19f499.nq.gz
    ├── 1d1f010a94342feb7357b1aa7bcde9742166bc3c.nq.gz
    ├── 1d5767d687f8530787ab7d42d270ea5896f16c0d.nq.gz
    ├── 1dbcb26025f8462942cbf703836968a2d18d48bc.nq.gz
    ├── 1eb80b66df42edbfa98a38146ac94cd67ba7203c.nq.gz
    ├── 1f33c9160b6fa82d72bfe5006cf12060284eeadc.nq.gz
    ├── 211ee22a51e3be415de6a02c6407aad31ab25107.nq.gz
    ├── 21ad81b71156ff1a7a18d854395b002f9a72f123.nq.gz
    ├── 21e13d86bf2dd580396edbbebb217bdd175db728.nq.gz
    ├── 22af89d4a2f41c850875cd823ba2bc7fc14f811e.nq.gz
    ├── 22c6aa0a9d625bfed662fb57595fcf0dbf90fe04.nq.gz
    ├── 230f662bee5c40f6a58f7ac29e4319affe98f5f0.nq.gz
    ├── 23839a0c97846cc9e173fdb74b8493ef78bf60d6.nq.gz
    ├── 23a06206ab4508650536550c2a4c1a2294e1a9ee.nq.gz
    ├── 24588979b998a20a19bba5e3836b5d053dd931b6.nq.gz
    ├── 25ef260580a242e629094aea5c425a206b39faf9.nq.gz
    ├── 261536d633175824aed000c1fbe3b89a8423bf81.nq.gz
    ├── 2689a1816387e7732b4a38f1f027255fb89be0ac.nq.gz
    ├── 268f59b11cb3266e5dc35476055bcf9ac415bcf6.nq.gz
    ├── 269e16f56de0b06464c745e63b6f2d4b24396525.nq.gz
    ├── 272eee6e08222f2e165275185c6edef35a30b03a.nq.gz
    ├── 277a6bd5b17570bc6dfca8c570f0d8e2fbc250f6.nq.gz
    ├── 27b8af552d32c5a2225c3cf29078da3e823a138a.nq.gz
    ├── 27fe5fc4f3892c0726a78352101c52e279b19483.nq.gz
    ├── 28435fc52edde140d83df13e872fb19ded31aa42.nq.gz
    ├── 289595b3185a7813aebab2d0b544c2a20a1239e0.nq.gz
    ├── 28f6a498d3259cc1b196867262569bf4b769b86e.nq.gz
    ├── 298ed05f9026bdbb89c9611f19fd097c4e8a8946.nq.gz
    ├── 2a7f2b7db437ff916a28e8f0697e89d967a6d9c9.nq.gz
    ├── 2aa682a8bd911f3b13d0749f9288ac92a9683920.nq.gz
    ├── 2b5f8d025e29839c737eb4ed5b44d778dadccccc.nq.gz
    ├── 2bbeaa682640921cb70128d31be58e164d5712db.nq.gz
    ├── 2c011efcea69a2c403508b241f30fbebcddd8fcf.nq.gz
    ├── 2cdddf0893e267e72e67b41cfb49db7cd963de73.nq.gz
    ├── 2d22b8d0c81e8e3c52bfa6b8fee8a1f2bdd48eb3.nq.gz
    ├── 2e7eefd14827ce7f2d3e1bcd8cf033a31152a74b.nq.gz
    ├── 2f627e2673b379aa1944de6392a4f1e796751849.nq.gz
    ├── 2f8955acd718e1644fb2509cac8373c16b71799d.nq.gz
    ├── 2fcd54f1826fba6a43fcdb4c563fcfce7a8182e6.nq.gz
    ├── 2fd17ef01635f71827c3c3ee34db2ecb0c45df1b.nq.gz
    ├── 30b4cfd328ea0f77de5283bd0e5add63b03352a9.nq.gz
    ├── 31590825297f0f9ddc533651629485d622dc71e1.nq.gz
    ├── 32989d0e135188496f685f98a9ed4ea6eb54c69e.nq.gz
    ├── 32e2f8976afb2cc84526882e749c6f4afff52423.nq.gz
    ├── 32f65c1a08254f9fef2a993c603f6ee889054c3f.nq.gz
    ├── 332bbedbfd01f861497e18aebab5c72dc2c5668a.nq.gz
    ├── 33e3f473e165fc80d0853d99929a0c3c8aec1171.nq.gz
    ├── 34139c435f430fe57eeb0f00d2d36f17e6d1ea9f.nq.gz
    ├── 346adbb5f3f0ddf111d4df90283aada9aa4a2ff5.nq.gz
    ├── 34ccb814f9a43c7175059c13be080ef52daf5fbc.nq.gz
    ├── 36b3709f25b7d5ead6e78c34a28c46b20c14c35f.nq.gz
    ├── 36eb73e1fc4ae21b98b455c71909b523a926df8e.nq.gz
    ├── 375f9a98ccb70a4da4c6bdb7257ef1f091e94d09.nq.gz
    ├── 38c64135680fa22fa2cde61ccb224dd1742ce1a9.nq.gz
    ├── 39ac0e653551be4c5b07e2cda599ab0494a85ccc.nq.gz
    ├── 39c9ee736d2bc634d9cb87810363f76468c39f01.nq.gz
    ├── 39d1d044dbee1a248931fa9479c91e6f42aab154.nq.gz
    ├── 3a267601ef2ad8535dcf8ceaabe60a1132b13021.nq.gz
    ├── 3a4952a8b824d01ce6c9af24205bad5511e66436.nq.gz
    ├── 3a8cc026b3b3f56b06197e66fe0d2831ec240d34.nq.gz
    ├── 3b0e8fc4ff852a8097b4d0e9ad8943bb8676e421.nq.gz
    ├── 3b214f034ec029ef8d5697a75acabca70791609d.nq.gz
    ├── 3b9b1743476d20c74d52bb22e27a5ed5aedabbc3.nq.gz
    ├── 3c2b9d9e314dffc36bec28bd2b699ec8e160da11.nq.gz
    ├── 3c4d2f58deb9ac122014aa1fcda1f38261b1c16c.nq.gz
    ├── 3d730e68a9996bb271f3a65e92398156df6b4187.nq.gz
    ├── 3e39ed94023c3ac34f23bc75b08ddcc94855c50e.nq.gz
    ├── 3e414a3550ba46412ed0630613ec3390cb7846f0.nq.gz
    ├── 3e4e1c8c99eb6bdde7867489ed848a626bae58db.nq.gz
    ├── 3e8a7e8f856f5ebab0e02e579793899b7aef7600.nq.gz
    ├── 3f405c99700f6f5dc2d2fbe48f5fe0bc18788424.nq.gz
    ├── 40c0657cd80b03a3f6587ddea85142c4fb826d30.nq.gz
    ├── 40cbb65c9d1e411a89a738e013aabb59172e6f72.nq.gz
    ├── 40e423fba2616b0068db3de84ef8632d6977d694.nq.gz
    ├── 40f1298e9d45f5a7cfff3afd43ddee2f48a86301.nq.gz
    ├── 419f1edc4e5f9d9a89826f3db634f1145ee0968b.nq.gz
    ├── 41db478662483bba34fb945fed52f8c1e8a0aecc.nq.gz
    ├── 4231c0fb1e93cf00ed289b9898b3703f542f46dd.nq.gz
    ├── 4245eed92a46acfdb074c1338b13b589181b3e99.nq.gz
    ├── 42878d614f6786f3a796546171051efe7503af40.nq.gz
    ├── 42b6853d23c16c75453c8c5538c7a5d6503f6b6e.nq.gz
    ├── 42ee25de810483edd955928f7df95215a85495e0.nq.gz
    ├── 446844e4bf5f96a17275cb117497543692312f8d.nq.gz
    ├── 447748314a63cfce02081b05d1e49f33480cb1a9.nq.gz
    ├── 454907ae9f7fb13aa49fa77602f0bf4c3361b30a.nq.gz
    ├── 46d9c9cfefaaf3abbd03561502dd7d3e815e7713.nq.gz
    ├── 4728702e1aa598a95e6719004503f786bd01a8fc.nq.gz
    ├── 473f52c85c295de18fdecca03e26c2fac3322885.nq.gz
    ├── 478c89fe79a128260d572592a72a8e583bbe5046.nq.gz
    ├── 47927a8c9a39fc888dfe7f163036da4ab3b2677e.nq.gz
    ├── 47e589027918af87dafd967f7f577711ff0757fa.nq.gz
    ├── 49e04fdb66608cdb70e9a25ea8f730c82ce035c2.nq.gz
    ├── 4a4f759d696ab87d8ddde78f8fa9761a7772d019.nq.gz
    ├── 4a983431b72f6682da8f035e2acd057d1202db10.nq.gz
    ├── 4b2e9b9bbebb4f98f42879301fc113d383774a2a.nq.gz
    ├── 4b627482e21480e27fb1f1eb2796e0c38f9b4fbe.nq.gz
    ├── 4b945e4205e4c7b3ede1c083e019061e5597bc58.nq.gz
    ├── 4c3d7d91bd4bf88bbb567c57f7bfec52988cd852.nq.gz
    ├── 4c84a75dbdf82cd14bf0c54e6b2b73845e203035.nq.gz
    ├── 4d45521849b0c6eeb611a496a768d2301f7d0e4a.nq.gz
    ├── 4d7d60519dc090f172bfcd669e80a214616b1013.nq.gz
    ├── 4f18ae11230c767b3a923948d4cbd2c49e015312.nq.gz
    ├── 4f9febc12d53a97584f7e77f34165871f2ddfa59.nq.gz
    ├── 50a41b70e39af05337f51bb2d9d7dd8d7fa90d9a.nq.gz
    ├── 51f59e0857049ca1fcfffca37399b0771c1e39f6.nq.gz
    ├── 51f8bdc9903bbce9b84fe06b6c77df632739817e.nq.gz
    ├── 52d9092a3ea5cfe4f1dcba6ce477eb87a8306e5d.nq.gz
    ├── 52ed3c21f4710c3cf581675271915552f64060dd.nq.gz
    ├── 5313e6f1b2133f9eba160965cbbfe5c92e100f03.nq.gz
    ├── 5353e500a502f80988a71e23b4e01b44adfbd383.nq.gz
    ├── 539bf9327997f681a3a855dc0b38585d8bf4fb90.nq.gz
    ├── 54a8a99596325403aea50710c1069ebd3746079a.nq.gz
    ├── 54d5e77134759beb50f450f8fad6505e30e40260.nq.gz
    ├── 55570e21c89eecbfe94c2c93cf6bc1bba89c62a3.nq.gz
    ├── 570ecd38501876b6dfabdd7a38eb58099de3095c.nq.gz
    ├── 580a4525f7fc0b3d236945f8c25a00e75e725e0f.nq.gz
    ├── 58400fb8fddd29c0a5b7c10e4422c8c564edce99.nq.gz
    ├── 58ebc4fb2bb125fdb0d41c128c8de3f772cca1ac.nq.gz
    ├── 592ce8f77251251a8ba7cc6cbf2d258e4efe87bd.nq.gz
    ├── 594a69aafd979cfefd847b746bd1d938e662e3a5.nq.gz
    ├── 59ef486ddaaea82507925e2fad442924c0f4005e.nq.gz
    ├── 5acf94e469f86a4e02a79e8de9a405ee455b8294.nq.gz
    ├── 5af0510763ad579e5a318c0f5d677a4a26271bb3.nq.gz
    ├── 5e029ab45ec2cea934f5c82961dc7fed90150d59.nq.gz
    ├── 5e9f1317e9f36189e550e3653aecabec4a07c07a.nq.gz
    ├── 5f9fbb0a4e236542b2318b87a851d75807f101e6.nq.gz
    ├── 60490c9824c5bd75fcc3f852ed5ef2295d332142.nq.gz
    ├── 60837dc80c7eec240c209401262ff024097e22e4.nq.gz
    ├── 6132a446548fa39421c1d08a10e30740d35c0b3e.nq.gz
    ├── 6142a8de4deb9ae4f1e9d79f99b7bc829c263a50.nq.gz
    ├── 6272ad0a7a25c1b64e00efea55729370b25f87c2.nq.gz
    └── 62957abc688400dd6c7618142f7027c0aa4fac3c.nq.gz

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

[QianMo/Unity-Design-Pattern](https://github.com/QianMo/Unity-Design-Pattern)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
