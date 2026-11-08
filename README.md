# Repolex Knowledge Graph of cohere-ai/melody

RDF knowledge graph data for [cohere-ai/melody](https://github.com/cohere-ai/melody), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/melody
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 92b4073bd7d16529f532d7f212fa12a8660a65df
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 92b4073bd7d16529f532d7f212fa12a8660a65df
│           └── chunk-001.nq.gz
└── blob
    ├── 00ab27f3c501c60e0393f9a1d971214d5cdb4d0b.nq.gz
    ├── 013cf262d65ad637ca267b41190c46803563de51.nq.gz
    ├── 01586502280f122d9d5b8a77777b3e9fd6a0a806.nq.gz
    ├── 0180875c049127931316692019cc05bf7447cc1d.nq.gz
    ├── 02643bd2bbc7c0e36e3d57f020d862e9d48453e6.nq.gz
    ├── 032355672b55560f629c6519d0ecc4e58c3e6efb.nq.gz
    ├── 03bffec189bc7fdff7ef6a2f0d59b098b8ade142.nq.gz
    ├── 03e2812825dc76c54906bc2abaccc510980d6678.nq.gz
    ├── 03ff59ca024a840d8a6509965b28c62333d347e2.nq.gz
    ├── 04160518836a0bd12e38c41cbf46aa65f2ba1025.nq.gz
    ├── 04e113ff3d6df8a3d49cc3ab811d2ea4e2d7486b.nq.gz
    ├── 04f4483f21cfa015b02fa986a42caa1839b76123.nq.gz
    ├── 0514f419f198cbe25ad062d050d6cdace3124da2.nq.gz
    ├── 053c8ef632f7d8a918e92a79e5344eb5a9c307c1.nq.gz
    ├── 061c2f28e335d41be8414b808054745db452577b.nq.gz
    ├── 08be070350a39de810a1920867b6f10e3df9fc25.nq.gz
    ├── 0a1d867441cebebaeacdd07a91e52a718debe156.nq.gz
    ├── 0a960d47d538b73536c5015104f56a65ae8ec74c.nq.gz
    ├── 0acb92da7b2c341db9487f68188d343691670c0c.nq.gz
    ├── 0b0d2d2932a09deef627ac7ab1ae41232b6c9e51.nq.gz
    ├── 0b1d0790fd60fe2249819f49498b4cf1676ddcee.nq.gz
    ├── 0d0d718fc706795eca077b83a14ab0f7b92365d5.nq.gz
    ├── 0db74b13ce451c8071e84f13591e43f5fc054bf8.nq.gz
    ├── 0e587bbfc301a9873eb74b21b70ba86902fc9581.nq.gz
    ├── 0f8d78be88489a930bafd85332bbf98714043632.nq.gz
    ├── 10366d84b99f4dfd17407b506def0ab0c525201f.nq.gz
    ├── 10eb5d7b2981dbae3fa1d984067c4a33d655c581.nq.gz
    ├── 11017e418ee47232c33b9c53e7eb5b513d3f41ad.nq.gz
    ├── 1206763cbfd42b652686d826b6369dafc0d0f217.nq.gz
    ├── 12aca9fa8a462f9b8729adc8c54d111bafee5c0c.nq.gz
    ├── 12ce2ec18382a11ccc0291019346faa4560e50d3.nq.gz
    ├── 147ca3e75c3f08bf94496c1b296bafcf78fcf8bd.nq.gz
    ├── 14bb52e1123b61ef42d634f07e1e928894af09be.nq.gz
    ├── 14ca81c7a1494b7cb490ead2eae1deee51562fad.nq.gz
    ├── 18f7fb7c377226584934f4208ccd437fea488755.nq.gz
    ├── 19130e116f5ee0b3d1e30c0155d0cd3d66e8ef29.nq.gz
    ├── 193bea08c364902e9e0df7e7c445dee1dd9dfa2e.nq.gz
    ├── 194c70f437aa7d234888bf7818e0cbfbf7d9a0a5.nq.gz
    ├── 1a216b1be635e98f26236e74e87d3f75e9f3eaf9.nq.gz
    ├── 1a5627690c2e714c72b8204548ec22dc73838bdb.nq.gz
    ├── 1ac91c89b2f19ed2e58a9eceac49d0bdbc04725c.nq.gz
    ├── 1c327f9e248eba1a88e9d550959d35f0b289ce53.nq.gz
    ├── 1d3d0f9564f4a6dd6e92dc287a44235151fee7b6.nq.gz
    ├── 1dd791e0ba7c291ea745abe224b0b21618fbd9f8.nq.gz
    ├── 1f15acdeb645d512215bb74d9afab4e2f3dfd11a.nq.gz
    ├── 201e1ca4e3b525ef511d08c9678e0eb931eb20d5.nq.gz
    ├── 2094aef1005c79504de75b64b753f2aa46873010.nq.gz
    ├── 2110082e948208356096fe1624cce5f585e7a583.nq.gz
    ├── 21ac1c87117adf44bd28ad7a49472bc96eb83e4b.nq.gz
    ├── 22892954cebbf8b4a9757588916e86149066a0c9.nq.gz
    ├── 22a3897e5de56d8b56b148a5be90090657b82e8c.nq.gz
    ├── 2305f58ce633515ff742af5945fa8a7bde251ab3.nq.gz
    ├── 235c7d163d555a71ba9aacecd8269ac0fa71087b.nq.gz
    ├── 2402c8bcae7e14391fd61e70ba8d114ad40ff6b2.nq.gz
    ├── 2431d13c70753b7e5fad02538e1bd4ff23c5df24.nq.gz
    ├── 24df5ceaf2bb2b37aa541d06284df5d8862ccea8.nq.gz
    ├── 24ff033187ab3bedc1214f111631360261b2714e.nq.gz
    ├── 252f4c5d8f6293959886019bfb58bcca2bd0b031.nq.gz
    ├── 25928e1e3d98810b8624d683be38d70727e974ee.nq.gz
    ├── 2673f48babfe6f8a10ec879dd535684c95cfa6b5.nq.gz
    ├── 27a6e5402425a8926cc39e75381e12d896cd64aa.nq.gz
    ├── 27bc6b937874a08478726d3b0e8f0a491e4183c2.nq.gz
    ├── 29049220f965581e3fc88240eb2e86703f1d2804.nq.gz
    ├── 2b24139c70802323b088e3b26e4c187db272bb73.nq.gz
    ├── 2c2eacf34ce682d531230aeb746de364555ace4f.nq.gz
    ├── 2d0d8885a28f64217d13c0ac64b55bf3d3f3c1a2.nq.gz
    ├── 2d541ab3d7bf968987429eb52ef691141efdeed2.nq.gz
    ├── 2e3eb570d0c2b8f6b7bac465056fa0dcc1fb0c5f.nq.gz
    ├── 2ee24b688b55521fdff14b52dc488e4fe00eb1fe.nq.gz
    ├── 2f623438e21918573162e7bdd133d467edc36fcd.nq.gz
    ├── 2fc94a41efa29f1c74ee3ec837c58bc02620b10c.nq.gz
    ├── 30129636922ed2ce343f086b0f0c2a1563983275.nq.gz
    ├── 30c31145cc9969f065bae71d098a4c3d708cc8b7.nq.gz
    ├── 30cabf4fdfa7261384e701f61811e8fc3a06f253.nq.gz
    ├── 30fb932005025341c24dbc9fcf394542789c2d1f.nq.gz
    ├── 313aae8b3e0d6bf54261fa47cd9aa429659ccb0c.nq.gz
    ├── 313c7794ebd6823d5f1cd6ff2d23fcb45e2362e0.nq.gz
    ├── 3185c7e0f9d456680a74d8ed1cb6d67820bfd096.nq.gz
    ├── 32260275779dd15ec81f7adca371952b676d673d.nq.gz
    ├── 32b22b94581c9c444b1967eb34e6bdf85748660c.nq.gz
    ├── 32dd2ba6968e58bb7c3b48836f48d3f5b68b18f9.nq.gz
    ├── 331dc4e1f6879b071b6d45df66c3f159abe21d02.nq.gz
    ├── 3391794cfbd72ff77033d20f948f003fdefbbd0e.nq.gz
    ├── 3471f261e66f93f71c2302a010139e6559b613cd.nq.gz
    ├── 34fec7ef656b46c764c139e6e00723ec3b6e7587.nq.gz
    ├── 35c6797413c2267334c9365369966f7108294bf7.nq.gz
    ├── 36209091e872ac1314f7f5a2c09298be5428d8a3.nq.gz
    ├── 37b3c5b3f852ae27bcad02b4f4dbbd8f4ed37bfa.nq.gz
    ├── 3874739698c09226d3e17d89528825699c7768b7.nq.gz
    ├── 38d024fe5f9f42d9c448ceee82999edf669ea67f.nq.gz
    ├── 393779707a0bb4784e9733c2334a22a7d1bb5159.nq.gz
    ├── 3a1046736696ea5552b7f7d3737256abd7e39113.nq.gz
    ├── 3b5994515bc0307801c4f2b1c8b36f19059167b3.nq.gz
    ├── 3db8137fbeee3e4ace3fbf0eb13f3c5e4c26f948.nq.gz
    ├── 3e787a6db25b5ae982d8998eaa21fcb405e72b8b.nq.gz
    ├── 3f5a0823476fcd260ac092c13d2cc50e87a242f0.nq.gz
    ├── 4004abd85ef796b3581e3e3c556f6dd18b6189f8.nq.gz
    ├── 41aa0bbf55cc6f7aced10ee02954e0be2c416f5f.nq.gz
    ├── 42b266878375fbb1052ca5d3843a43df895bb56c.nq.gz
    ├── 43ed4dbf21006b79620dbd459665adf31216b588.nq.gz
    ├── 4419f13e745593e5dbea16aa84ed2a59841e8036.nq.gz
    ├── 45070becabdca543311d7f6ff8b295009c866f69.nq.gz
    ├── 453f25f92fe961c78fb2cd40b6c0cddc322b899b.nq.gz
    ├── 45f14438118b79932c4c13de76e9c7e7052ef443.nq.gz
    ├── 46786710e74e4d5d251b7f68ddb50fa543c8e115.nq.gz
    ├── 46d6d3e921fc33661bcb067772948aa1de917174.nq.gz
    ├── 478df2dc369f77d582f45340b76cc9ddc756cb39.nq.gz
    ├── 49522a4095ba473a35d767c090fe2a5d437d9bd6.nq.gz
    ├── 4a0050c77c25bc2ae2fda966a93fee39adcc2f43.nq.gz
    ├── 4a1e5006d1e836ddb06c88767a216cf68a9f6d0b.nq.gz
    ├── 4a1feb98b0a05098599268d674d320a228f65831.nq.gz
    ├── 4a69e4074743d3c654bc14520522715b1e3c7319.nq.gz
    ├── 4d8ed9df3e15ebd88f6c50fd9078c01d28f14430.nq.gz
    ├── 4d90425f2c8fce5158655e4565344c62a461b139.nq.gz
    ├── 4e0c669248711a3416cdffd4845637b7ede717ce.nq.gz
    ├── 50cd5e193a19169a05afbac2a5053b9515ed30f9.nq.gz
    ├── 50fc0d6f5c1349bd81dee1345ecda30f620da760.nq.gz
    ├── 512a51dae66cfe1ad9a71fc3f835f02953b09734.nq.gz
    ├── 518e62ce3b22837dcc7e3d7a06c9e27f0781d160.nq.gz
    ├── 51e89a22b13b9bdea33dcc2e9f3994fa7bb76855.nq.gz
    ├── 51f8abcebb76741eaeef91d8b2c9bc0f3bbe73ae.nq.gz
    ├── 529fc6f89a89a2932c899ef77597e70d06a4150b.nq.gz
    ├── 533bd713a12d86b2c6022568a6141a654760329a.nq.gz
    ├── 54959a39010aa329bec0533e0e4e73d8e43733d3.nq.gz
    ├── 54f15808308d12f721f3f370bf75d22f77130e8d.nq.gz
    ├── 55433f83846a22b95e5e2fcf0a2d74543a39fb29.nq.gz
    ├── 556a6c27ed35040650ebdfb993c582ff5fb5dd86.nq.gz
    ├── 55c22de4aaa015acee36704f172517b57cfccc66.nq.gz
    ├── 5733dc145bd758401dc3047f188466ae52ec3358.nq.gz
    ├── 579ed1d7e7471353e6b208099e97a6afdd8d7430.nq.gz
    ├── 58616ab916ab60c36c7e1c04a6971e5bd9e756cc.nq.gz
    ├── 58dd1ea1f2b880ba7fe743d85f6141fbeaf5675d.nq.gz
    ├── 58ebb50ea0644f1395eb8498e5368c6ac370418d.nq.gz
    ├── 5a90822cceb8415722b5586eaf78862afd8513b4.nq.gz
    ├── 5acd5ee81528cbbab3285c54d4825df18fea2348.nq.gz
    ├── 5b285648d46cf493713f5e1f254c221094760119.nq.gz
    ├── 5b7a52f3e0124d23d31fb93ca58b1cb462aff03f.nq.gz
    ├── 5ba8e65ef3c64aff3ffa2321ba454b90ce5570dd.nq.gz
    ├── 5bcf43665a48acd9a9b57634207739bdf23b1f9c.nq.gz
    ├── 5c4bdd62b56e894f19c0c9ae4ffe59eecbbd8a93.nq.gz
    ├── 5d2367fdbedd4555772386126e836e999af2a5b1.nq.gz
    ├── 5da059cee88167f060bd86222a5963f5a7b22efb.nq.gz
    ├── 5ea37946524dd6999b92899e592e544fc559a20c.nq.gz
    ├── 5f295f0b403312819612842bda4794d97a7328f0.nq.gz
    ├── 5f91840f17b06e04fde063e545e97f9db02361a6.nq.gz
    ├── 6008bd5bc67d23974beb6eabbc2ae64d9dcda416.nq.gz
    ├── 603ca116a31095f4c11b7a06435b12e31fbdef38.nq.gz
    ├── 609bda241aebb85688758e9bbded1e6858d2b834.nq.gz
    ├── 619057fbebfaee94ac9ca6ed75fefe838a30b63c.nq.gz
    ├── 634955574c7d5f25162f6efe88927bf9a5f1cb07.nq.gz
    ├── 63942805097182957b901201041b4a1b325ec6d0.nq.gz
    ├── 63fba640768e08eb87dce09abd9d254422e1511a.nq.gz
    ├── 65a9fcbc7b369f61f7ef411542e000bb8c02011f.nq.gz
    ├── 65e8c82950c2ff3ce789b159f1e2cec6afbfa403.nq.gz
    ├── 6abed43eed5b44a2bc7da9e998939ee67decd532.nq.gz
    ├── 6b84c7c4e3a4d79b43a21323e032710685dfcf04.nq.gz
    ├── 6d7998b977cc704a4b445340f9e2f643251e8559.nq.gz
    ├── 6dd52ac6a7a03bf5c601107ac1638f6bb7256627.nq.gz
    ├── 70184da1957a633df1daa0d1edca1d47cfde2112.nq.gz
    ├── 70291c28703ad13e7ee222bf68f5268c74048586.nq.gz
    ├── 716e7e160bd451d1b2dd3ba799ca9c2ba82e9adc.nq.gz
    ├── 71fd32ab59c5f3cd5b8ac3bb4b7df3f37efefd52.nq.gz
    ├── 72a74b5c6ad1efab72737ae7922af1c693a90331.nq.gz
    ├── 74bf2256d5f11b2fbcd8d9e4e98b3b8a4781c5f9.nq.gz
    ├── 7510889a504dc9cb2436c0b27f3b22a7ed42f196.nq.gz
    ├── 75d6ad278bc0d8ff763653d73ce022ba0d342d11.nq.gz
    ├── 78336055f681674fb83888d2b74861f221f6f384.nq.gz
    ├── 78e522d895194fe74a2d0cddaf7307ecdb76bd7a.nq.gz
    ├── 79eefe75a654085038d488c8bf374cfb083bd35c.nq.gz
    ├── 7a1806bf00310bcab162d802676564b7fa3ef070.nq.gz
    ├── 7b33d91fd5fed150560da965cdf4b8733d1c2626.nq.gz
    ├── 7c8ee870cc51aa93bcfab5e6a3dbf4c95eb0156a.nq.gz
    ├── 7ce0561955d66cc7686d02df103e1c9289764e7f.nq.gz
    ├── 7d400a54e8bd7e99e474bdf9f247ee84c104f793.nq.gz
    ├── 7d95527cf8df79f9f53226619752210841dfc592.nq.gz
    ├── 7e87ec224f0d65d0cb7c2d43d3dfce250ce344cd.nq.gz
    ├── 80298d4d44c33c1b3484d6ba52466d52a4a2f8e9.nq.gz
    ├── 80767103519522ed7c6c523585b52d7c38808f02.nq.gz
    ├── 80b9447438e549c11d2ed5f8c3bec5c311d45739.nq.gz
    ├── 80cab566f8020e3cf7a823db2e6d54628a9a6e84.nq.gz
    ├── 80d972190931373b06daafa234b28c4eb5fc599e.nq.gz
    ├── 814353bd2faae2ebfe90b09a8b79bbd45d03dbb1.nq.gz
    ├── 8182cdadf47fabbcfd0fcf1be04d736ccb34999d.nq.gz
    ├── 81d6d9a85f82189fc863b6983ed51f7ab31b97f8.nq.gz
    ├── 855a2e42c564c4508edf1268ff42c55ef41d8ff9.nq.gz
    ├── 85c72319a6d689d5c02089a5aa2e42fac43d9586.nq.gz
    ├── 8634544a88f94ca509619d1c5e10d0e0ac4df99e.nq.gz
    ├── 86eb94dbd37151cb2b838ca84b64aa45fe7eac62.nq.gz
    ├── 870ccd1c9374143d4f1cda11b72b475227eb9458.nq.gz
    ├── 87519ad01868e82752f31a622e44b39ef39f398e.nq.gz
    ├── 87f743eb1a53cf5fd04076d6be45179f8fb276a3.nq.gz
    ├── 890a4a6787adc9efe11117e5c80267d54809f9ac.nq.gz
    ├── 899f9a217f2c4274bdd1608cf9b60dcd405e19fd.nq.gz
    ├── 8c18c8a57e60aef1d7e2d182dd5b521fe975ea8d.nq.gz
    ├── 8c7090510b405f510ff24cf352e3ce2031734d10.nq.gz
    ├── 8de5e318e03a2fe925e9c5ccd1d65fc179c44240.nq.gz
    ├── 8e9eed5bf62886fc30d06e05f2bb9953f52bf513.nq.gz
    └── 8edd465562ca830538020f2fb195aaf1c3437e7d.nq.gz

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

[cohere-ai/melody](https://github.com/cohere-ai/melody)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
