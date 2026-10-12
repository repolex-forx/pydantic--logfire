# Repolex Knowledge Graph of pydantic/logfire

RDF knowledge graph data for [pydantic/logfire](https://github.com/pydantic/logfire), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/logfire
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 199cc4df2dec0944015344fae467dba258fbd3a0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 199cc4df2dec0944015344fae467dba258fbd3a0
│           └── chunk-001.nq.gz
└── blob
    ├── 001857e8e6e3ef8f522628098daba8581e837de3.nq.gz
    ├── 004b16e2da7f6fd7f7dce09daa047c574c4807bc.nq.gz
    ├── 00a2fe31ecaab8223b6a59f524130c1db87b52a8.nq.gz
    ├── 00d024b0af3f739e54441a442d6c58d3e22648a4.nq.gz
    ├── 00f604035d29f5e8ace982a84efd816ee9529e74.nq.gz
    ├── 01922466d0ba99e25e46038bfc8047beb997c3a9.nq.gz
    ├── 020559de487cfa01347ee68d5872ef26f4eefb2e.nq.gz
    ├── 0287e70ccde085b19b2446cd9bdb41cb01c48408.nq.gz
    ├── 030df1a65534f1a2cd4f9261b7a534a9428eb49c.nq.gz
    ├── 03ae4c97f9d43e509a81845411686fb34d3a26e8.nq.gz
    ├── 06391483ca7765fd815e0c2c43b0f041bcfe421b.nq.gz
    ├── 072bfe47fd9e268151e122236f24ba04cc341e96.nq.gz
    ├── 077193e8c99a3dda0f1cfb42f761d6b397ba05f6.nq.gz
    ├── 089ea8da1a44068b04e54d44d1bcf3a0bd5ea06c.nq.gz
    ├── 08b0be5c53204e7ace70687c6cf1f883f3e8677d.nq.gz
    ├── 0a0abf41d81c0f003f1db4fcf38139ddb2478b7a.nq.gz
    ├── 0a1f01d0038006b765ea287ccd9f2cb05af2ccd8.nq.gz
    ├── 0afc69aee2dda50837eab5d2418604ae52b65f58.nq.gz
    ├── 0b447198b70b4a2e6745c59e59cf06533a99241b.nq.gz
    ├── 0c7c1ab0c5f2afb69f2b42b06a33ac59f51ddcb7.nq.gz
    ├── 0cada55d35a9dc9d6e1370569d2d7ca97e5cdeb3.nq.gz
    ├── 0cb69b0c8cf0c0b83f2c87ee2d835f0771257ba0.nq.gz
    ├── 0dc8d90a5e5ce020ca8786b3ea868be5f9688634.nq.gz
    ├── 0e2cd9cb30f2d6072b23487e5b0e15313743b101.nq.gz
    ├── 0e9b5a2dd5be03576e05be85eb2c964fde7f3dd4.nq.gz
    ├── 0f0e98729356fcf61f4bd55debe5192bbc0bc05b.nq.gz
    ├── 1057bf797ee4c2a84c8a8e678c1f558281523f7a.nq.gz
    ├── 107a57d71e1f9cb252c4e276094c3768c02c9496.nq.gz
    ├── 10b7dc8335c367cbca146eed68927df23227f044.nq.gz
    ├── 10bbf51b318a8fbc0bddd0769f9065f8179df2db.nq.gz
    ├── 10ea3c7acaeabd811e55dd70272737d5dfb12e92.nq.gz
    ├── 10f9dd40e635ea313e7083c132a83606f8ae614a.nq.gz
    ├── 11fa1cc61162d505ea22f060c71a48e978ec3bc0.nq.gz
    ├── 125bf81c4ffec0ee4da5f9348a31a37d18ae0bc3.nq.gz
    ├── 12b04cf9accd36e9d631dd7244e93097abefeb12.nq.gz
    ├── 133baf4944de3ced107022d4f9182fe67ccd3358.nq.gz
    ├── 13cda9bd7b357ab553b62bbe5f7d7b2a007146b8.nq.gz
    ├── 14581a90efd3744170835a5cadf2e744ba276264.nq.gz
    ├── 1479e9f479baa2a7bbffe946c0eb0dc32d875ce7.nq.gz
    ├── 1496d336d2a3299adf23ce527799e94d9b46e88d.nq.gz
    ├── 15f8498fd5b4c3c44de5f9045f9df0f452f11f02.nq.gz
    ├── 16b904bcc7b46e98310c97e4a189baf5ec6fdbd8.nq.gz
    ├── 17d5dd0ab72b7698155c2f5f5981a5a11170bf94.nq.gz
    ├── 18b305319bb6e7655f309d66d34b477a8a44680a.nq.gz
    ├── 1a748763072361b6f0a106a6bc13b35388335261.nq.gz
    ├── 1acbd45381c1cc2d6c625b2ed4c4d6c7bc331bd4.nq.gz
    ├── 1b033573efcab66bebc30c6e8f974130179ed0a6.nq.gz
    ├── 1b5caee0399f6acbd569410ad60f4abbd147b6d2.nq.gz
    ├── 1c9908b9f3ae9751575cbda2c061e9758c135f04.nq.gz
    ├── 1d532de8b9f0d7ea1142e2e0afe50304d065a93f.nq.gz
    ├── 1dda11b9ce671673ab3c2991b83161ed17dc9292.nq.gz
    ├── 1e053087a7d7280cee539d56756a9206469e2811.nq.gz
    ├── 1e0c83a2836a81343e57587612f5247997fb8eba.nq.gz
    ├── 1f083ddbdb1e0f0815560e00b98fcf5c4ec8f17e.nq.gz
    ├── 1f39f1a5ff2aaa080ace58d25342bbe2004c27af.nq.gz
    ├── 1f5a618179fc707a5955e538d0669b295ac5af6b.nq.gz
    ├── 20e11bb2a3f08897e9bcc574e35c0ba8ead63cef.nq.gz
    ├── 20ed5ecf23bc91425a69cd8b4b93ebd84233ee48.nq.gz
    ├── 20f40b98f2e6c4c92cfa721dddda7872b63a6520.nq.gz
    ├── 20f49a26ed945d50a0a6c2aedd4a3eb302cb4371.nq.gz
    ├── 21b247f00f23d25a401f445bd30c5e8d6ca8e5b1.nq.gz
    ├── 21ea1d40669af8df5df40faca320e6c15efde22e.nq.gz
    ├── 21edcaff1845feac6d94e1fbdafae6ccf737f5c9.nq.gz
    ├── 2200a3d69e202b50076a739e919023311103116f.nq.gz
    ├── 223910370cfab071eb20b878d09ee7d442ae0e5a.nq.gz
    ├── 22e8263274222b380f5bf08e40e884a5af6d6e46.nq.gz
    ├── 2316430a7771fbc44976401c6fb20dd6fa79750a.nq.gz
    ├── 2393b289be808afdb23fc74da162be5cb17914f4.nq.gz
    ├── 240ec2411a59ce51a25ec7277e2628767686b1d2.nq.gz
    ├── 244d843fe16ecc791ccf94b76dd165347563f183.nq.gz
    ├── 253a6f75675d845ee42f5f286b700a5260f0e39a.nq.gz
    ├── 26452474865cf28083cceaff8fcf790ade7a779c.nq.gz
    ├── 273c2f3f22f41246f6e4b9194e6427edc8e31598.nq.gz
    ├── 28045e30f5f0377241ee2aab501d35d86e4940a6.nq.gz
    ├── 285dcbe932fe7567b2afd573bafc3fdced5f85bd.nq.gz
    ├── 297a11e090227bfd6bab3ff110f3ce39b400d745.nq.gz
    ├── 2a3a8e21d504f8a0d51bba75646e1acf9ceb7367.nq.gz
    ├── 2a44f95f11cdbc33cbdf8001434bed24a4fe6fbf.nq.gz
    ├── 2c649738e74acb2a2b63a5d3e3aa65d8510945ec.nq.gz
    ├── 2c8c20a508c94649985a767cb74fcb3769d555e8.nq.gz
    ├── 2c8c8fe6a60ef7e1bc5293190923b8ae5bde3eae.nq.gz
    ├── 2ca5ef9f9d57eec2030586240e3a509952aca1f0.nq.gz
    ├── 2cac02f323dcda25bfccac4f7f1b2b8b230c4955.nq.gz
    ├── 2e33244261bf0a0831371b23045ecb3c8dfbb862.nq.gz
    ├── 2f09af4c67ba3d3749671ee074cc5d1589ac2023.nq.gz
    ├── 2fac2200cb7fde27bf7597f5a0bc6d244080dc3b.nq.gz
    ├── 2fbcb0ed8267b6eaef6e6ecef600eb434138ce7a.nq.gz
    ├── 313192075a510971cfc72525c36959bf9100f7ca.nq.gz
    ├── 31327937f51f65a2734657eee88494e4624243ad.nq.gz
    ├── 31cfaf00ad046b79b61310f5307e31e7656844f0.nq.gz
    ├── 32b833667fe78eee01c251ee7fe2c855ac8e4139.nq.gz
    ├── 3316aff667093a3c9a7e6cf71a5f78d8410f2535.nq.gz
    ├── 33d16367198cc7bc623088fca580a4f9a8146839.nq.gz
    ├── 34a1ee37da58eb781612c3fc30253df468f31c19.nq.gz
    ├── 356aa8dd47647bc207792839b27debddc58939e5.nq.gz
    ├── 37586e0f60b2399a963f00c07f86204fc99c226a.nq.gz
    ├── 37fd9a3715adfbd0a1c36e0125845121cd03b577.nq.gz
    ├── 3818bb7a9cc5049cc9ae5fb3c373c6ee22890186.nq.gz
    ├── 38456c39abc9025bf43d27a72eb1af18d380b132.nq.gz
    ├── 38a7520b321410e32a7ccf679d1b0003d2096717.nq.gz
    ├── 391b9fc359c18d2f4d27cbc510f3af20b101fe98.nq.gz
    ├── 39a006094080c1f3dd4c18319872667d609ae5a0.nq.gz
    ├── 39d1b180c53c3e171bc410ecc238cf154d842046.nq.gz
    ├── 3b0951d6ef5512af5586bba9fd07475679705431.nq.gz
    ├── 3b30a5f23b00bc13f4d1c9a3171c1476925a0e3e.nq.gz
    ├── 3bca5159e052e5abe4ff6ea4bf2721f4423eb838.nq.gz
    ├── 3c212d71c8cd938d21ad0b7273087f679f456ccf.nq.gz
    ├── 3cba037107b53ea256da9041e03e7b20eeb674e0.nq.gz
    ├── 3cc92cc0075ee53ec4d9bb0f1c4f971a1679664d.nq.gz
    ├── 3d2b2575bc64546715819735d5be987d87be1691.nq.gz
    ├── 3d4fde92ff4d4f74f6e8e75de201792d69e9cf8b.nq.gz
    ├── 3d872ff385739cc7ac5a67d85b32af5f3920f0c0.nq.gz
    ├── 3d87a5d3729b6f477d903bf7839c98728c0a3d60.nq.gz
    ├── 3e1d6834eedf337f729fd527ad300e069a00ea6d.nq.gz
    ├── 3e7735471507c85958a2e96af99322648055c213.nq.gz
    ├── 3eadde5f2947132657f4f97f8b61da51ceb586d4.nq.gz
    ├── 3fa511444adab0ca2771d23942f468546e8ec9e6.nq.gz
    ├── 4002fb32ebb3a891861cc09d105db49acd23cded.nq.gz
    ├── 4049d329588ca17ea3ba270cd27a261d32c2c94f.nq.gz
    ├── 40bf509eadd38c5592d7d00e6abd4da7b70371bf.nq.gz
    ├── 40ccd4dfb3dce80e2cf6e9889cff1ce912cacd27.nq.gz
    ├── 414cb3b1ff5269528e5a4a9f816da1d685880198.nq.gz
    ├── 415fd8e51fc67641327fb46f4b95ad6d0bc40f4b.nq.gz
    ├── 416c447a8683d0dfe24d67c5199cf8795c1890f7.nq.gz
    ├── 41a94ba8d5bde8d05120ae8caf1b5789ab6f303e.nq.gz
    ├── 4347c1e807c62a8d2920e1ee075a54ab50990c98.nq.gz
    ├── 4372863318dbfaada7ff5ecb74c13e9ac30147fe.nq.gz
    ├── 43a74ae0bac3cf3571c6d13ccf85f90311863ad3.nq.gz
    ├── 44cd406d161b25efe3f0bd96d16c5a952be303cf.nq.gz
    ├── 456cdf3a8ecf734c80130c6be9c7f6c2591e8926.nq.gz
    ├── 4580f61d326800ac76ad9295435fc50da4de21b3.nq.gz
    ├── 463f4644b8b8952c181d449c37e1cb9587823ede.nq.gz
    ├── 477b72e1967753b206c85421d33e03e222bc72ab.nq.gz
    ├── 4830a891bfa1544a600834fdacffb0780bf55094.nq.gz
    ├── 48d20239dfd66bb321f1436cd502f4c2cf75afb9.nq.gz
    ├── 496242d24d4e0fe3761489a3ac7f9aee1fc806dd.nq.gz
    ├── 49f19af7ce5ce8edf41cc6f09da7450c676071da.nq.gz
    ├── 4a3ac54fc4cda948d56a410c820ee2ac0f5163a2.nq.gz
    ├── 4a44bacad0d070ef61bde2ad18f0b06df9f72188.nq.gz
    ├── 4aaa1f7d22319adfaa5c718e32f5105ff91b6eec.nq.gz
    ├── 4aeff2e330024631577e84d950b5341e2b999436.nq.gz
    ├── 4c3a62f6cf386f3434830d7d4419ae8beb302555.nq.gz
    ├── 4c668cf68e52bcc0a40524dd029413c25886d37e.nq.gz
    ├── 4d822658678266e6b6d292259eae80f8d7907844.nq.gz
    ├── 4d90066380916b4ccd0f5239c2e2bd7feef18b37.nq.gz
    ├── 4e3c416ba89c851755482359725f5aac7f0371aa.nq.gz
    ├── 4efbbb3af685a9b7b18f9685bceb08335dfb68c1.nq.gz
    ├── 4fb3cdfd5b1f0c091d87c6cb9289be662990f837.nq.gz
    ├── 4fb7986910002d3409970d4c26430b7410b0b4a6.nq.gz
    ├── 50160369d80bdd5c872e3e6a5634500d1a38ed1b.nq.gz
    ├── 50a0da0e7fc57907aa748e58a347d590de059e88.nq.gz
    ├── 50d62613da5b8f2e92aa7527fcc1c5b6a2f9b942.nq.gz
    ├── 51212a2c5c17aec2380f2c1a311e799a46736cb5.nq.gz
    ├── 5210c30aa552dd89cf0809282e543cf395a1f089.nq.gz
    ├── 5270d92b098ee5ef854cf32736955e4bc1ecee2b.nq.gz
    ├── 54dd0d210e7356c258f71634ba0b778d10f9f71e.nq.gz
    ├── 559fa5617e02b916166c684fbf5747b2d94b8148.nq.gz
    ├── 56f8ec0f2b640b672bfc50e19e819f059c7c98b7.nq.gz
    ├── 588c9fe463cacb1c6157b8c9eba60c8e07fa8363.nq.gz
    ├── 58f207099624ff98332e7610802bf4f766688f0e.nq.gz
    ├── 59e1f9785d5e074741a40c5d6a79e596db1842ce.nq.gz
    ├── 5c85b74c9f04541ac683ce8a3a3f6b8c7e190c88.nq.gz
    ├── 5d23e5e91691ce12ca2c635325341b3993c49616.nq.gz
    ├── 5d636529bc7c48797ab7585693810a9c1e267493.nq.gz
    ├── 5dc1fa9646bfecd88becee789b789ce69b53d276.nq.gz
    ├── 5de980f4ee07efc0440f5d76c6bd0e25c09bed55.nq.gz
    ├── 5debcaf81dd7bc0b12cdb8d2adce8af647e853f7.nq.gz
    ├── 5e7ae32cd7265b48ca944507557802a5186c31bc.nq.gz
    ├── 5eb977431f60cdae2884325e46cfc51661a2d670.nq.gz
    ├── 5ecdb2151eaae6171cff24a77318de0d13e0f472.nq.gz
    ├── 5ee62f5f08069e048cea1270404a0b3a8657d646.nq.gz
    ├── 60197dc4adcf912128756b32ead43b8b1da61222.nq.gz
    ├── 60332fa04b93c484954a25949e230614ff604edf.nq.gz
    ├── 604a9f5c016168b795dc49be75566896a5f7b513.nq.gz
    ├── 60a882074905cc08ed3f876ba32d20bc6b23234f.nq.gz
    ├── 60f3d95908e73201f093aae56a02ee64d9982eb2.nq.gz
    ├── 60ff4c32ecfc4f4ad314c59e396321b6956f2662.nq.gz
    ├── 6198de0b844b7f496ebee8fe7d65c54a9fc7e28c.nq.gz
    ├── 6231211a762b831fb666d075f6f46d93a466cb34.nq.gz
    ├── 62c20452ce759b81d024a5e4e872b88cc06c09ac.nq.gz
    ├── 63fd236a5928b54f6bc4684fc6a1e7eef14916d0.nq.gz
    ├── 64d0f845b11cb2ae6b59537fececf9528acf8969.nq.gz
    ├── 6500359b2327e5d57e90d6daa667b61fcd0bca10.nq.gz
    ├── 653da36316886b26f09d735af80f4e5532a57589.nq.gz
    ├── 659d1b99662d28c74fb9f61c5e934378fce7e0a9.nq.gz
    ├── 65b5059a6029e83560e239a5b296f7d7bac4b30f.nq.gz
    ├── 65ce2e353f886b8e937140b17a8b0911a47c5def.nq.gz
    ├── 66cb2c81e9cb792242d01751eddae57b6a4f3b22.nq.gz
    ├── 672b715c5496874f7eef87d0661bc7dd00acbe25.nq.gz
    ├── 676b975ccf322f46d0e86c6db82941cbbfc60654.nq.gz
    ├── 678a6bbdd476856c1010e71a72c048272b22fb3a.nq.gz
    ├── 679a802860b041e31a9a304b2e78cc05d43de28f.nq.gz
    ├── 67ab19f4f5f4e99e7c42cd43d21bee7cc43e5111.nq.gz
    ├── 68e79e341e0aa577bd64b0a887f37e1d2a64b8b7.nq.gz
    ├── 695a07cdc9f51c72bbaa4da3e1d526bd12b0f383.nq.gz
    ├── 6a98546c21dc974cdaed6efb62bc7bafd0650f40.nq.gz
    ├── 6ae64d95904cc23884637f909c8ec1305b8c36c9.nq.gz
    └── 6b2021999398416a78191ac543b7e0e34d86bc2c.nq.gz

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

[pydantic/logfire](https://github.com/pydantic/logfire)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
