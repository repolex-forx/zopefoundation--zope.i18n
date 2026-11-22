# Repolex Knowledge Graph of zopefoundation/zope.i18n

RDF knowledge graph data for [zopefoundation/zope.i18n](https://github.com/zopefoundation/zope.i18n), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.i18n
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 565b0ef9e74a89a39e85b9171db1b29d3b0a88bf
│   │   │   └── chunk-001.nq.gz
│   │   └── a95fa6bf498706665c0a430ce4973ded8473a40c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 565b0ef9e74a89a39e85b9171db1b29d3b0a88bf.nq.gz
│   └── repolex
│       ├── 565b0ef9e74a89a39e85b9171db1b29d3b0a88bf
│       │   └── chunk-001.nq.gz
│       └── a95fa6bf498706665c0a430ce4973ded8473a40c
│           └── chunk-001.nq.gz
└── blob
    ├── 005e186262f8a7fcdbb3dcb3da709d3a069746c3.nq.gz
    ├── 00b0b19b0f14352347a09e5d7693a0354f5f5079.nq.gz
    ├── 00fdce040d94a1606386fe637cdf16307d8108bb.nq.gz
    ├── 015ee1ca1cb00e8c01f1d1ca4ab78dec9cd404f8.nq.gz
    ├── 0263af91f1819fa0378b14e3b323ef3d26e89124.nq.gz
    ├── 02e802ff90445f645ed207e07e4372d10df3f347.nq.gz
    ├── 02eb9caa59fe6445002be048f54b331d1753c381.nq.gz
    ├── 032bf2d79883d27245a06f542e8e809e153c0ff5.nq.gz
    ├── 033b2310e8846bb30710ce3e07cd5d645eb7df04.nq.gz
    ├── 036af8f65a3b2a27b841235c8c927242f3ff3acd.nq.gz
    ├── 038af45eb1afd160d87d011d31a5e9d40a49d889.nq.gz
    ├── 03b2e99dc9baa4040c591f06db9a223084b69185.nq.gz
    ├── 03e7a85b866117b63a7bbfb6f22f06d7bd355303.nq.gz
    ├── 040022cfb4f23ecca0a7e69b2727c0dfab3eb875.nq.gz
    ├── 0410aa0dcc6f80323ea42a4335ca2c86145cd4f0.nq.gz
    ├── 0455f83675a9c7d2e9ee364d5fa93b7ce3504f56.nq.gz
    ├── 04c848272b900b1fc432d344c79bee434eaf4724.nq.gz
    ├── 05124328cb365330857cf4b6468630263f5b2cb3.nq.gz
    ├── 05392e8a56c928d8aa4bf7a8dcd3b808fe6ed04b.nq.gz
    ├── 05fab2a969e026b8156405cf90b51afdd54d231b.nq.gz
    ├── 062ac535631e21ef582534ab8f630a45edba758d.nq.gz
    ├── 0646895743a78960fabe5a32fa83b4646eebe33f.nq.gz
    ├── 0680179604c8247cacd53ab9a1f7e44af1b756ee.nq.gz
    ├── 071652d479bc279303815f38ae07b0f6bb94e3b4.nq.gz
    ├── 074a9e9649ec4322baf0a65a3d4d65fa196b43f9.nq.gz
    ├── 07e7cbadbae7b372ec3288fdc41d0aa45138a11b.nq.gz
    ├── 080eb059cf2c8a0106f1f0ef0c9911f285ce1213.nq.gz
    ├── 084911167d9919bab023d3c7d3eb1a91b45c7829.nq.gz
    ├── 08524e1e4b1d09bceadec1baf721bdd4c04f01df.nq.gz
    ├── 08ecf5db345a361b14ad46143615bc9ec46ce81e.nq.gz
    ├── 08f35abd1c7f3bb47b1fa991b58abeeab06790cf.nq.gz
    ├── 0928fbdbfeb0a02e0e5322e6710dc9dd2b8548de.nq.gz
    ├── 0953ed9b18ef686e77571d5bc0dcfecfed0e0445.nq.gz
    ├── 09ab9d2a0d810e7cc4ddee4eea66e40508e86959.nq.gz
    ├── 0a20cf982bfea8d1033f3b7ee4f5637fa82efcf3.nq.gz
    ├── 0a2897aed1a2a18ac468d80ed77aabc8e260ae0b.nq.gz
    ├── 0af99a04ba9d392b66ed34bf25029fedf6d1003a.nq.gz
    ├── 0b23f04d88273687638456c36c878e0b19dc3559.nq.gz
    ├── 0b521b04dbf392cf1f34b077740c301c143cdc7d.nq.gz
    ├── 0ba2de54ebc2b554a5be8d4a4c9fad7e7c546238.nq.gz
    ├── 0bae4734344981c6e3719c7681b8e18d6013222c.nq.gz
    ├── 0bb77111d487a1a0494960d1c0ad42a1ca46fdfc.nq.gz
    ├── 0c01630c78e6753eee8a640954003b4cb68ea4d0.nq.gz
    ├── 0c4c61939c03b78ccbf5af4967e8db23e46ce910.nq.gz
    ├── 0c79057ebea5782e8f7da883ed89309dbecce27e.nq.gz
    ├── 0c837368a4799b9d47a03a5c340c70c1ae3ffe65.nq.gz
    ├── 0cadfdb88db5bdc5b2d78b540844e035e4ac28fe.nq.gz
    ├── 0d5635a1ff8c1eac68f733c5ae0731a502e9737d.nq.gz
    ├── 0e871830d23efc0f041acf3273dcb10f84f82d2a.nq.gz
    ├── 0ef660189c5ebb1c4750916280364942a96b351d.nq.gz
    ├── 0fba101a658ba7196615095491c5d0fab3718a1c.nq.gz
    ├── 0fd6779b2bb0a83da22f9dcd0f583319f9a153c0.nq.gz
    ├── 10d4dc11aedece8432976f4ba8464a9919eb66bd.nq.gz
    ├── 110a255752047277096d24c34401cb3c7b868157.nq.gz
    ├── 110df48cae1e2c2ee004079491c4f816ec0d8f76.nq.gz
    ├── 1123435f5c1785f25f5f42d4307543b48a10ce0b.nq.gz
    ├── 11ca44c8c773c4358feb82f2c5636755a29942de.nq.gz
    ├── 11f38fabfa1a4cb4c10795dfe27ba19e3aa7330f.nq.gz
    ├── 1208e55ae7082900febc01ca5943c35582f448d8.nq.gz
    ├── 121fed506ad03eee9c9beb094e300e2e2724d640.nq.gz
    ├── 12a3baa6bda28004d2e1e309b0f579ceb5b432ba.nq.gz
    ├── 12c7ce482ec643676096b18c60317fbf1cc221f2.nq.gz
    ├── 12d9c7252bd135fad12dca951e6bc897a8304f03.nq.gz
    ├── 1300156465ec1600b254234e6cc7580cd0618781.nq.gz
    ├── 1316a05159ca678549cced079a541f01f52ad2b7.nq.gz
    ├── 1324033cbcedd8698e099d3131e0e6084bc0dd28.nq.gz
    ├── 168447f257d71967ce914b8216320d76d7a9637c.nq.gz
    ├── 16b60e98308d60a8d92998dca57edcb3dd769361.nq.gz
    ├── 16cfe849451832dfc60195168898ad37372a9ee8.nq.gz
    ├── 16e1668acdc72955bbc06bf36f72279f5b158211.nq.gz
    ├── 177dea4b62a97954095a48eecee9bb174a1a611d.nq.gz
    ├── 17815a1879ec45a8a3cf524382f1af311ba721f3.nq.gz
    ├── 17993f5ecbfd8c1484a16f5f5d77da8d274f9573.nq.gz
    ├── 17b471274a3f598c9deff784a9270aa8fa0e16a9.nq.gz
    ├── 185a7b9dad6664589e9e37e370ae25c220d324f3.nq.gz
    ├── 195a15ebc8000789af77951e03a5d50f16acd5b6.nq.gz
    ├── 1979d260d7c16acadbef073c3a8febc5949786b5.nq.gz
    ├── 19a8fe49e33585f1192904ad6461ec1a355e2632.nq.gz
    ├── 1a06d22bf7a982f4994b8b623670d8415ba2056e.nq.gz
    ├── 1a905a89327ecc4c44804d371ade4c7cf8951038.nq.gz
    ├── 1b493945a34a825eeb92b84bc51f5aca24d89186.nq.gz
    ├── 1b6fc929368d5c30b89e502bb53400f40b6be0d4.nq.gz
    ├── 1b8ee21f6e5443f796ee05e5a946a9e9901839f9.nq.gz
    ├── 1c44ba6d6cc462a8ffbef2de916bc9723ec96608.nq.gz
    ├── 1d1dae3a9d358041bcc15e85abb1c6acaf56513c.nq.gz
    ├── 1d278ab6b1bbfd27f8fa8473bb9b96fd5aab9ae6.nq.gz
    ├── 1d3b5fd49d3f5a312ffe290d6505c49fbd0fbceb.nq.gz
    ├── 1d9268efa4f1931cf36c660287ef99941a610226.nq.gz
    ├── 1de7d390a277f1958928bf803d0ec7051dce2310.nq.gz
    ├── 1e348f5301d8c7ab636888475b66431e518a9c3f.nq.gz
    ├── 1e4c732567fb6381aca4916c6ab6f32d44ff63a1.nq.gz
    ├── 1e70d2eab5f98871785b095c169d56c2eccc5999.nq.gz
    ├── 1e92e0c2f79a3e7ea46f58d56f40a31200badd82.nq.gz
    ├── 1f0b28442d5f18f825b888f2b4c625af61269494.nq.gz
    ├── 1f21970d8e9059242209db469e69a4949c04794d.nq.gz
    ├── 1f73bd81acadd68cdc5e20fff1e78c30be6a9a16.nq.gz
    ├── 202b5584295479187ccdb4ca16bc6f740dbc5dd7.nq.gz
    ├── 202c073c90d2c4641a1ce49063e9413c2be84a18.nq.gz
    ├── 207f526c9edd69c531ad4ab5d8651cc6667c7a4a.nq.gz
    ├── 21a6d467ded2603435323cba573744cca0d8fb3a.nq.gz
    ├── 21c0e49f6e5921768ff93ba8bba561e4a41cd485.nq.gz
    ├── 21def37d1f771795f8bad4c5ad8176b20f8932b7.nq.gz
    ├── 225e47323fa543083110655c255cabf8e3cb37df.nq.gz
    ├── 235801df019e6564be9630bb248c93d65f2fe825.nq.gz
    ├── 24324983157e5b2d7d22bf8c8af26c30ff7965d1.nq.gz
    ├── 24b29a01dbeee7c3cffb7aa093c2954e9ab5a4f5.nq.gz
    ├── 24ce6b106a389a27f727c4f4a47b88ddc441de65.nq.gz
    ├── 2599f9432fd946dba308cd8a785d2d4249f5e556.nq.gz
    ├── 259d495530ff53e94f05174572673d8c7218aac3.nq.gz
    ├── 25d1cd8321eeb3c116526c8eb42cc72ce2636f22.nq.gz
    ├── 26b86b656c39320789cebd4b756cba5d2502eb04.nq.gz
    ├── 27eb993ce3430417a6fb4e25e12a28dae3264697.nq.gz
    ├── 27f0656125a332d4ce67a2631d8c274ac18dd7d8.nq.gz
    ├── 288ce50f05074579584428dea7d1c3c9b2b929dc.nq.gz
    ├── 2980413ad5004f46ba962a2ffba03b2c37e7f4e3.nq.gz
    ├── 29aabecfb8aeb0a513a60806577abe808b7b0f9d.nq.gz
    ├── 2a6a901962d906222e1afde1de06424eafd00318.nq.gz
    ├── 2ab7d8935276127e066f0b775aa8f6f7490955ca.nq.gz
    ├── 2af1e6cb097dc5e53f29987230e0d4f7be83ad38.nq.gz
    ├── 2b0b0a4b1f90aaadb7209bc484f4c6d642b2c2ac.nq.gz
    ├── 2b960f965fa2b3b8c80120317d0433bbffd4daf5.nq.gz
    ├── 2c3804edc1ab19dfbb826b5a72aa86e711d11851.nq.gz
    ├── 2d36ca194e3a189bbcd99166eae610e5fc2960b7.nq.gz
    ├── 2db95365463fb7154bb76e594712114f8128654f.nq.gz
    ├── 2dd82470a681192878e03d73b2d97f7eac5657b5.nq.gz
    ├── 2e10d48d7f8dd0585ba12113a4d0e744e97411de.nq.gz
    ├── 2efaaf1961a1ca07fd0dd03fc6bcaac95449d8f3.nq.gz
    ├── 2f2607693d025804eebb653bd07059093b183e09.nq.gz
    ├── 2f4a61ff922e6057541263b6b4d6cab218b74362.nq.gz
    ├── 2f8516c7101b431bfc90a1c26a3ea3fd715f13df.nq.gz
    ├── 2fea8a5ad07536c13bfbb47d9537d619b76be7f0.nq.gz
    ├── 3016ffe771a1ebcd53c64887516e3b91ab5f5fc2.nq.gz
    ├── 307387335198a4ca764e1738fedcf7ddc811a5a7.nq.gz
    ├── 321e9ee84f72e8dec959dead2c3ed3347c5186de.nq.gz
    ├── 331db85fbd2479a31917c22d51a7e3edca893f5a.nq.gz
    ├── 335f1470b7bba58c02f4917d5bb943e7033fefdf.nq.gz
    ├── 3374e47b4f3a56c13b45bdf63e6d39488a24de1b.nq.gz
    ├── 340dc9f5e10c33c1b7d34b5c883de2397b9de806.nq.gz
    ├── 3526637f2fa2ba3282feec4629164095347eafa6.nq.gz
    ├── 3530982de597b33583643a6b3b2972a110d6e9a0.nq.gz
    ├── 3579ab6e7c7ba39a8ed49445032393f94bf56a65.nq.gz
    ├── 35d8aef9fe3a2af91a0b69be596fcc51568cf809.nq.gz
    ├── 3643216fa99b810e9931f36163f275fe16509955.nq.gz
    ├── 3656cbb8c5288f4b584c006e5a422a9d5580862a.nq.gz
    ├── 365b645c7080cdbafae742217be8890fb45e503a.nq.gz
    ├── 36b6953f71e938a3315bc870c0e775c6392b1b10.nq.gz
    ├── 372317c7dadd4524170628ed242688826202fc8f.nq.gz
    ├── 37931142b6c0133b33ab85dbda088c0630712e34.nq.gz
    ├── 37ddbfcf586ad0869980992a38c9c28115a0f0dd.nq.gz
    ├── 38119aaa444670dfb459894e09187542300c3762.nq.gz
    ├── 38a1b0a90957d415cc3802ed00d3004b88beae10.nq.gz
    ├── 38f239af030fa0128a0c78a2dcd776db10ff2a6f.nq.gz
    ├── 392a0ff88550ff4122f4c125dd036d0be419958f.nq.gz
    ├── 3951a9cd81d90ed4ae8b536db6a3ce0ccfed9069.nq.gz
    ├── 396a0cc320012b883dd1b62d7fdf16b29b050cdd.nq.gz
    ├── 39a60666dda197dbd4f2bab19fe3f8d2d09913d9.nq.gz
    ├── 3a8ffd676e8f09ba2349a409f609c6072e9e3e6e.nq.gz
    ├── 3af8b07c17354f0c5d63a08a4d197ef3586ce7fd.nq.gz
    ├── 3b4d679e5f325e95abedd908236225f16c2b069a.nq.gz
    ├── 3b70b300a015eb9947b3f987a8c41d7cbefd22da.nq.gz
    ├── 3be1fc06cf63bbe15c10fc544789319fb1e8e2a3.nq.gz
    ├── 3bea75b889186aecb31a59c882c048f184fe4c2b.nq.gz
    ├── 3c51f87ae9af297f620d5457be284780871d4465.nq.gz
    ├── 3caa46f4980b30aa6df6d868c2915ca75da8c4bd.nq.gz
    ├── 3ccf15e94b9d9296c9f33c23076b123407b6738f.nq.gz
    ├── 3ce2c54d435973ba9cbf094196b1667ea9f77317.nq.gz
    ├── 3d2576c052c0945caf66b502acb5d17266437992.nq.gz
    ├── 3e61f58fa137b7486c56963dcc1fc280dcf41646.nq.gz
    ├── 3f2b26e4ce6762443724a4a40d009f47e671a5e1.nq.gz
    ├── 3fa8b1db3999cc75c464e3c9d46d0a983c7ab7e5.nq.gz
    ├── 400713fbba8dad5e59ad2b7ff381a1085c324e23.nq.gz
    ├── 4008b224381031cf4ae68c9f8d6d578b3b9df7eb.nq.gz
    ├── 406ad54c0c005302c4ead3a87f53f7ab345d66cb.nq.gz
    ├── 40a7701b4571819e983246a7ab911c840549db78.nq.gz
    ├── 41640290f5ddd7f85328c75ef8714f99312230c4.nq.gz
    ├── 41821502836cd6f085cad4fc0789009640a2ec46.nq.gz
    ├── 418d0d77c31b36bd61e0eca29fa75e22546f3cd8.nq.gz
    ├── 41c59fe5d5fc2fb171e9c34e7460b4e51ac494ef.nq.gz
    ├── 42968cc9cad32a990aa115392972cac3c34bd1f9.nq.gz
    ├── 42a7b7dc198c1dbcfafbaa8ab03955b9bcd064b4.nq.gz
    ├── 42ee110849dd0dcfea6c776bce0d01ea35a939d1.nq.gz
    ├── 4355cb17ef371f7604179c412aa93e429bea1dde.nq.gz
    ├── 438b0b95c83371821af3cc61def7cfdcf89c928e.nq.gz
    ├── 439de8668d1544a2b1d1dc16060d2ab2a0f27ef4.nq.gz
    ├── 440f42cf271faa85b384bac977a266414a0ed9e6.nq.gz
    ├── 44b9e49eef9df557bf8bdbb76248c9adf8b8b984.nq.gz
    ├── 44c9d60d8a2f8ac1826effbf5154fc2083446f32.nq.gz
    ├── 44d466cbb7153562f03961c99e3b5318e5258995.nq.gz
    ├── 450c4fbf57b567998b030bfc3b2ba040d6cb08ea.nq.gz
    ├── 4546feae594a9c381a81bce28b1e2c6f48468819.nq.gz
    ├── 4560b16661acedb4b2d03ce1c41af4770e61206b.nq.gz
    ├── 45c26719f13ce1ce05b1eb7e048063cc0215258c.nq.gz
    ├── 45e6dde32a17992acb0b754945dc06f53fafcdf4.nq.gz
    ├── 461728b6e23d90a5f13cf4f615195d612121240a.nq.gz
    └── 466ca3d22c834bc4bff1d17184f9b2db311155a8.nq.gz

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

[zopefoundation/zope.i18n](https://github.com/zopefoundation/zope.i18n)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
