# Repolex Knowledge Graph of scrapinghub/spidermon

RDF knowledge graph data for [scrapinghub/spidermon](https://github.com/scrapinghub/spidermon), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/spidermon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5bac6dd768463ece308ca67dc9fd18525364c940
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5bac6dd768463ece308ca67dc9fd18525364c940
│           └── chunk-001.nq.gz
└── blob
    ├── 00c38750e905f0eb48dd3a4f2c45a2b3c5871a55.nq.gz
    ├── 00ffacb3fb633c84c2020d1807bcffea54dcb6d6.nq.gz
    ├── 0454fc83bc5a172adbfca603b6c79450fc35f160.nq.gz
    ├── 0480b497cfbee0522f2e9bebd4f75dc79694f8ed.nq.gz
    ├── 05ae2e5bc3ff4cea54810d28effdaf5254660ed7.nq.gz
    ├── 05e9d262a9fa70a114c145a1b101ace8a2b32b4e.nq.gz
    ├── 0646bb6dc2e7ca7b9cc5495891fc420f42a05f9a.nq.gz
    ├── 06a41b787d379a6fdec4b276a90dd3979879d400.nq.gz
    ├── 085bef776055764a81a5980d0494ef889e01b0c5.nq.gz
    ├── 0954c5fffc9774774c25544c01922d6b90ff4350.nq.gz
    ├── 0c70897a50049e7a0ead48cf3c62e3b4c4f8fd6a.nq.gz
    ├── 0d1201552daa84f23a6fb9fa33a87e922b2a74f8.nq.gz
    ├── 0e44d0b579c4c62d9e31f0288f83e3875d88b81d.nq.gz
    ├── 0e7bce8571714d8e779320c2352a33b86059c683.nq.gz
    ├── 0ee04f445fada2938a60416a4c23a81d30c88384.nq.gz
    ├── 113c32e16982f655de21300913de58052d9b2c0c.nq.gz
    ├── 11dd9b5ff3dbb006a82c92c4385deca8b4b5ce5a.nq.gz
    ├── 124bd0752565803f98b82906a236208ca18b2513.nq.gz
    ├── 1275ef936f4abdf09ed1c611ed03392199c550e3.nq.gz
    ├── 129c830383f99ce26391b7004f0e44961ac0c9a2.nq.gz
    ├── 1356f662da6e3435e79affa041f5e80509a5ffcb.nq.gz
    ├── 14ce89d4ed828d13e633cad24bf9b53c77ca74ec.nq.gz
    ├── 175d667493f03d44c9916bee96740fd8edd03285.nq.gz
    ├── 1cf60b50240cc013d2ccc012a0d8417e55916406.nq.gz
    ├── 1d1096ce2a68165cb3cb72a8ff25c590f5a6044d.nq.gz
    ├── 1d5522b8d1903c3145bce93d95d995e2354f46fa.nq.gz
    ├── 1dffffe5e9e86b8457484607377fd3ca83fe52b1.nq.gz
    ├── 1e1df51d4b8e14a89234c26aef8cc31b420b98a7.nq.gz
    ├── 1f161319a7709510f809a902becdfd7a32737991.nq.gz
    ├── 201288da6405332574e38e5189750b084a2c9e9c.nq.gz
    ├── 214da6a4424bbdc064fdd2fb17a7689f1565bfc1.nq.gz
    ├── 23589a19c3bd9920e2a93f459d82f3bc56e36e21.nq.gz
    ├── 24bcc4cac5a2bece04a3b43c7b2578c9dea5b41b.nq.gz
    ├── 253ead51a808e500447f9ee54a733bdec47daf4c.nq.gz
    ├── 26110176a355bf3be754f79b899e99a8faa860f0.nq.gz
    ├── 26b03ff1d34aff3ad95690c5c0f764b0ee495b02.nq.gz
    ├── 26eca98c33708a582e850a034dbd1c7de4b84b97.nq.gz
    ├── 27a193baca1228ab08c0898cdc6525f528671c8a.nq.gz
    ├── 284aca413709769e7e33776f83cfe20eebb9297c.nq.gz
    ├── 291ccfde6dbc9c945027f3845ff3a30801df1523.nq.gz
    ├── 29f46bb3a1c866f845c321b7b4143b3d83ae5394.nq.gz
    ├── 2c1b9b77d4aa508b8e2fa5d700a484a654e2289d.nq.gz
    ├── 2c363e91b32b81f98884f5089c3a3c4401d78ce3.nq.gz
    ├── 2c3f606cba8f58e210850d8c977d6b84706a153b.nq.gz
    ├── 2c6accbce5bd3d0e900048d419a22ca21b92eff2.nq.gz
    ├── 2c8b1b002cab766be1756b623b1077773ce3cfe2.nq.gz
    ├── 2c8bbb4774ee2414621a40127d18368554a8232c.nq.gz
    ├── 2e692d336dad578b1524c62580e44fa8b568229a.nq.gz
    ├── 2fd7e6ec9694f3c407abb8fe934f203f6e2f9c2a.nq.gz
    ├── 313c479d36838acb0770e85f4317a3a9db83b99d.nq.gz
    ├── 329b4189a16aa188e888bead797459af61d1965e.nq.gz
    ├── 35007f304c724db713dcb56268ac120046304eee.nq.gz
    ├── 35b54bbcbe66db3cb22a7151c183a14497bd5354.nq.gz
    ├── 3816a342f3246ecaccdc1193e0efb5b41153d23d.nq.gz
    ├── 398fc3d061733286e360e7834850adb5467ff950.nq.gz
    ├── 3fdccf016ca2d7173b95ffe2d39f70fea7595865.nq.gz
    ├── 40355c8e9c461d4784de160ae611e7c5ec8e37a2.nq.gz
    ├── 418efcee5371e86831f7f72a2d59ee25658ba315.nq.gz
    ├── 424ac0f7123a64b193b0b497356b20b695190395.nq.gz
    ├── 43baf1bd28852603d9f73facd3e95f57fb0b8444.nq.gz
    ├── 45294c366d0cc535a8d42e52d4fb55517c8e7791.nq.gz
    ├── 458b5d00297729e4f244138189d59c382e248e32.nq.gz
    ├── 465b7f0f3b2546c0a630c805702748d772f7b99d.nq.gz
    ├── 46a5395bd81171382b687095bb4ae9b6096f0eb7.nq.gz
    ├── 47f6bff0b65109520d8609c08f7ab62c546ccf93.nq.gz
    ├── 499c5843e8b9aea528b83f828df3f624685bf88e.nq.gz
    ├── 4a0036101290ac171809d923b6946ea98469068a.nq.gz
    ├── 4a874796985037206c873228323b2c5dade20cb6.nq.gz
    ├── 4be4d1fddf0aeedc3b1af37e929bf8744ffce9ac.nq.gz
    ├── 4d209a86f5cc761f448dadd2a64a8107e2304a65.nq.gz
    ├── 4d6f4f0b4432ce088c989c8e62e340615fc19e89.nq.gz
    ├── 4d71142fbd5e9a09e531daf6a70b1581a4a04442.nq.gz
    ├── 55243ec985c578020f58fe2eea8d05a0d9c8c5e7.nq.gz
    ├── 5705b2f2b79c90b4756e1898bb8d823820c8b3ca.nq.gz
    ├── 574ee5ffa018734cf95f0ca41564f2cbbcec7333.nq.gz
    ├── 5c3cafdcd05b99941096cdcd24d95b00be1ba9f5.nq.gz
    ├── 5db08bf2dc57979f9a3785791285b2724e9d45b7.nq.gz
    ├── 5e7d07a4ca48814fbf9635a5b4870e7d1a3222d5.nq.gz
    ├── 5e7e6a4b9472e740f94408e83f95502c01e9d8a0.nq.gz
    ├── 5eed7ee9af962d53683c374058eb7e1acd0e5b20.nq.gz
    ├── 60a821f0764fe571180935728567d05f505c3e0a.nq.gz
    ├── 6498990879b4671dd262ec3faff68df4f200e11a.nq.gz
    ├── 67e91f2769f8d8529de89a9da8eeaaf0f1204db6.nq.gz
    ├── 68a5f729680355659cc64565ec145910adb86372.nq.gz
    ├── 69d9392257d95a856e3ee30567be9e42c8b69901.nq.gz
    ├── 6a8f5ebc793cacc8f57a56b023b75573b8cd4809.nq.gz
    ├── 6c7f57ea1165c1d879d114331b8fc0a62ef48dbc.nq.gz
    ├── 6cd3d4df10870f1da2a847acd848013f1afd4761.nq.gz
    ├── 6cd912eb607acb77d8fee1448b375ac1f2d62875.nq.gz
    ├── 702434419c69d821e5c037f2dbbabf53286abf0f.nq.gz
    ├── 70397ced544afa6c349d57fc96ebdc865520bafa.nq.gz
    ├── 73b8a278128b91ba280d84e4f1814563335cb7c8.nq.gz
    ├── 76afece8fef6e7788453ed68a205223d1f63e097.nq.gz
    ├── 785b9c29c9f362a584f393d08d280527b12bb185.nq.gz
    ├── 7a055669baf22f6eb01f4d6315155f42ea4d75bb.nq.gz
    ├── 7aa235fe5eb6e84da8744cb4f9668c1ce9b3bdc7.nq.gz
    ├── 7b675f5e5306f8b40af103cd6e74dead8ecb4ca0.nq.gz
    ├── 7cf56dab9b7bc089a48d855c95db077ee73b3757.nq.gz
    ├── 7d1bde721fc1182e06ebc60a8aeee6106660e8bd.nq.gz
    ├── 7d636944592fb079eec6ed80dfb7cf132a64ec49.nq.gz
    ├── 7e41bd01a80c16fa9c5dafc8ca26de772e7a507e.nq.gz
    ├── 8090840ea1bd9eb56b0ba6c121109e2d2213e526.nq.gz
    ├── 80c291721df95fdc5c0bc186d411019f3b3c4182.nq.gz
    ├── 83b12cf7c1eca586e538b1f50a8fb2c1ee557bf7.nq.gz
    ├── 8403545fe8b3666772af4b14aa51eb9d54c90308.nq.gz
    ├── 85cf19cd573953d0e3161b009725d3847e9b6663.nq.gz
    ├── 87548e69317e316145c7dcff7145458bcb22feb1.nq.gz
    ├── 87a5705fb3719fa51a3a02c8245ede3d0f4baaa7.nq.gz
    ├── 87fd2e96e6f3e54df9540bdba4a5efe122e38c56.nq.gz
    ├── 88ae4e79e7a3b04e917778c41e6e4fbca97a1f92.nq.gz
    ├── 8a7c4c56b85b9931beaeb703229400c28c94b757.nq.gz
    ├── 8b8d7492acadfb18faf6c5ac6f8b91129232de81.nq.gz
    ├── 8e6a9ae3b256049d716a18cc3988ff5a0837be82.nq.gz
    ├── 8eb656e121f84177ecceee42f4cc36c5820a2687.nq.gz
    ├── 91123d47b7a59e87e0b4bc872911bed077278014.nq.gz
    ├── 91c3fb8eb68605eeeb22362a5c371e6e1faab44b.nq.gz
    ├── 9260d24b613504bd40189101cd4695c88fbd117c.nq.gz
    ├── 92e6506ed02428117d8838b419e179d2ff8e17de.nq.gz
    ├── 9325dec2c244222f1e0e4f0488ffa4bc620f8388.nq.gz
    ├── 942e3f821a7a1352632e12a96a5cefc09884e7b8.nq.gz
    ├── 9449e1f984d25f4afcbddaceeb31223eed69d922.nq.gz
    ├── 95137df328f2db2355ae9cac928c795ece047ecd.nq.gz
    ├── 95c73f2f4b0f4b5fdcce5ea71d77c74fd6c4358f.nq.gz
    ├── 96b4ff9225f77850d268e9cd6ddf2b7b53f55430.nq.gz
    ├── 9701503ae12d2d5817b7b4645f08b783e389bba8.nq.gz
    ├── 973d65547229f3baaf303655f93cad1da30dc724.nq.gz
    ├── 98e0167c9591099851f842a39b047aa3b16fa79b.nq.gz
    ├── 995e005c4c1c00e2e3d7f63a8d5cb245f1466c74.nq.gz
    ├── 9ad075f8c42729052a7ecd3418f1485413d370f4.nq.gz
    ├── 9b30b9620c830c2a671f9c4982d91590c9915eaa.nq.gz
    ├── 9bb39d833c1ec45f507df94860608804e7a0f57e.nq.gz
    ├── 9bec49ce3d975674af8ad22a5a436c2aeb218f00.nq.gz
    ├── a060ac4feedd05ced7eb1cc3e2df160b19315987.nq.gz
    ├── a1226a8295e9fb655bfd246bdcd794fd7938a8aa.nq.gz
    ├── a1d7f5f3f39fdc0c9c2d450eefb2049b754256e0.nq.gz
    ├── a4a0e4a2bdff49cf0e47235a04fa9375f2316afc.nq.gz
    ├── a519ae12156d94161c1bfc6c20346cad9f79dc7c.nq.gz
    ├── a622d5af9311eee394d42d5e780182ea06a769c2.nq.gz
    ├── a655cfe9efe353f65d9ee2e7e9b2ad95f123e347.nq.gz
    ├── a75edfe8c6ae5872541c518d00cb91cdc6df9db7.nq.gz
    ├── a81804c9bc771e641c2b31d5a9002a2fda178155.nq.gz
    ├── aa277d170dc98e8a2947c7ef2b33c3c902992404.nq.gz
    ├── ab0f603f5d5478af31bf26bb483363ae447a264a.nq.gz
    ├── abb5b3b0f58661d0c90d4239ad6a6877526440cf.nq.gz
    ├── ac8337d44d37ea93329169d0eef62187f41f4e7b.nq.gz
    ├── accf7c04b5a8af04f846df211558c444915f3831.nq.gz
    ├── ace04405bcd0b74d4398b15093f6b5bf3d27c70f.nq.gz
    ├── ae6b5195892087da0f6484516f7d0b636d3844c4.nq.gz
    ├── b016494f17ca40051fb719ff4f854d9a487507bd.nq.gz
    ├── b15f4f460f313e0b2a85551cb676e48d78fb5eea.nq.gz
    ├── b2cb97c8dc85abf0defda6b3c648b694e1a45236.nq.gz
    ├── b3178a5b016848d2e773b0a651c87d81d815c675.nq.gz
    ├── b38ded922482eee00197ac9989aeefc0f188b1a2.nq.gz
    ├── b3c8a4ca33d43e3b1598c3efcdcf439201d6338d.nq.gz
    ├── b6ae847f5fe61f902608c3b74b7bc4119874f223.nq.gz
    ├── b7116e0185b2569673b8e7bdcac25e4f1a8438d6.nq.gz
    ├── b774b0a28c5badfe5528c601bf196c8f6524d34c.nq.gz
    ├── b7cbb3b13a075278a493b997d9dcd364b231e52b.nq.gz
    ├── b91da0121717b3e9c013fc5845836b49f5468d47.nq.gz
    ├── b9a384a4a8e606f25fce5ef05e3d549defdff41d.nq.gz
    ├── baa74d18bed3e74829a0980a53e4fcd4765c7590.nq.gz
    ├── baf2f8e62c9efc1b5b32e4ce66237a2e687a1146.nq.gz
    ├── bd636f598e4d3d28e5b1c3274ec3152abb7ee373.nq.gz
    ├── bd9ecf18e5515950145e6fc7c77ae99860dd1d0f.nq.gz
    ├── bf461c70ce92f75917a4594cc3285ee7f81192f3.nq.gz
    ├── c0bd1b52e5e32bb0a12b41aad916f79d33384512.nq.gz
    ├── c29499a8cf5868863b5ea2b25943d5c4881b5bed.nq.gz
    ├── c323b5d850d9854c26e18ea39b823ac8b41b5f51.nq.gz
    ├── c41cf3e109c347901887fae3d25328579089c09d.nq.gz
    ├── c4d4577cec20106537ac2aac87524f07ec010e36.nq.gz
    ├── c7a57a9a8f7be735c5e308b9bef63927c4d82376.nq.gz
    ├── c97d9864862fc3c5cb84b83fe11d38bc7d694336.nq.gz
    ├── c984ed1c8d9545eff771c4939315678cb4223501.nq.gz
    ├── ca3e3bc4c0564c10cc6bd241a4c92bed1ee8b50c.nq.gz
    ├── cb1a8f24a4823802e795481b5f5d30b149c1098b.nq.gz
    ├── cba832b7dea56a4145d4092b1737012a43746a70.nq.gz
    ├── cc2a12b08b1cb4c7793182e019cbd59fd23ac25b.nq.gz
    ├── cce19c6fe541dc0751f13cfae5e0d8f7bcf1f2e6.nq.gz
    ├── cd51b5ce867ebb0658615b7088ec43e5dbc77647.nq.gz
    ├── cdfad19ee87f908e003cb30d25cb0646039aec69.nq.gz
    ├── ce35f7487900a807a7963edfef7a4708a262503e.nq.gz
    ├── ce738c404bba38d7a32ae5388f505477b29167cc.nq.gz
    ├── d0ef2d3baa1d34381f68f396ecea20598e288872.nq.gz
    ├── d1a3cf0595c27434d677662bd6d8e4c62d71c87b.nq.gz
    ├── d5f4d59bc07ca316e9224a53391a5425d497476e.nq.gz
    ├── d706d1f7be280405d7bc30975e03739e9e1211e7.nq.gz
    ├── d79f6f1c5455761dc2abde220ba3f493199be11a.nq.gz
    ├── d7c75b90cf1fb93adff1023a4bd7b097775a892b.nq.gz
    ├── d7f3767e39ef8b605aba6d37817a8b99b36f58a6.nq.gz
    ├── d8d984ad3f995315a9d01865e07c71148306d733.nq.gz
    ├── d8e2353d69dd21a622add5dc97f0c6a3c9c6a0e6.nq.gz
    ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
    ├── db8979bec43db5253bb4a024a9d62c01bc691278.nq.gz
    ├── df64a74c42346f2d18906f01bcd5fa4c6fabc768.nq.gz
    ├── e0576861aa7de32082150c41e344b666f6f38025.nq.gz
    ├── e180481c77b7fcc5e5dda90b2dd5628f6152be91.nq.gz
    ├── e2693e35b3d0b1b17f3955815cfab47399fd8967.nq.gz
    └── e36967285bcf55105b2d3145aa8930970fac07db.nq.gz

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

[scrapinghub/spidermon](https://github.com/scrapinghub/spidermon)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
