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
│   │   └── a95fa6bf498706665c0a430ce4973ded8473a40c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a95fa6bf498706665c0a430ce4973ded8473a40c
│           └── chunk-001.nq.gz
└── blob
    ├── 00b0b19b0f14352347a09e5d7693a0354f5f5079.nq.gz
    ├── 032bf2d79883d27245a06f542e8e809e153c0ff5.nq.gz
    ├── 033b2310e8846bb30710ce3e07cd5d645eb7df04.nq.gz
    ├── 036af8f65a3b2a27b841235c8c927242f3ff3acd.nq.gz
    ├── 038af45eb1afd160d87d011d31a5e9d40a49d889.nq.gz
    ├── 03e7a85b866117b63a7bbfb6f22f06d7bd355303.nq.gz
    ├── 0410aa0dcc6f80323ea42a4335ca2c86145cd4f0.nq.gz
    ├── 05124328cb365330857cf4b6468630263f5b2cb3.nq.gz
    ├── 05392e8a56c928d8aa4bf7a8dcd3b808fe6ed04b.nq.gz
    ├── 062ac535631e21ef582534ab8f630a45edba758d.nq.gz
    ├── 07e7cbadbae7b372ec3288fdc41d0aa45138a11b.nq.gz
    ├── 080eb059cf2c8a0106f1f0ef0c9911f285ce1213.nq.gz
    ├── 08ecf5db345a361b14ad46143615bc9ec46ce81e.nq.gz
    ├── 08f35abd1c7f3bb47b1fa991b58abeeab06790cf.nq.gz
    ├── 0953ed9b18ef686e77571d5bc0dcfecfed0e0445.nq.gz
    ├── 09ab9d2a0d810e7cc4ddee4eea66e40508e86959.nq.gz
    ├── 0a20cf982bfea8d1033f3b7ee4f5637fa82efcf3.nq.gz
    ├── 0af99a04ba9d392b66ed34bf25029fedf6d1003a.nq.gz
    ├── 0b23f04d88273687638456c36c878e0b19dc3559.nq.gz
    ├── 0b521b04dbf392cf1f34b077740c301c143cdc7d.nq.gz
    ├── 0c01630c78e6753eee8a640954003b4cb68ea4d0.nq.gz
    ├── 0c79057ebea5782e8f7da883ed89309dbecce27e.nq.gz
    ├── 0cadfdb88db5bdc5b2d78b540844e035e4ac28fe.nq.gz
    ├── 0d5635a1ff8c1eac68f733c5ae0731a502e9737d.nq.gz
    ├── 0e871830d23efc0f041acf3273dcb10f84f82d2a.nq.gz
    ├── 0ef660189c5ebb1c4750916280364942a96b351d.nq.gz
    ├── 10d4dc11aedece8432976f4ba8464a9919eb66bd.nq.gz
    ├── 1123435f5c1785f25f5f42d4307543b48a10ce0b.nq.gz
    ├── 11f38fabfa1a4cb4c10795dfe27ba19e3aa7330f.nq.gz
    ├── 121fed506ad03eee9c9beb094e300e2e2724d640.nq.gz
    ├── 12d9c7252bd135fad12dca951e6bc897a8304f03.nq.gz
    ├── 1316a05159ca678549cced079a541f01f52ad2b7.nq.gz
    ├── 16b60e98308d60a8d92998dca57edcb3dd769361.nq.gz
    ├── 177dea4b62a97954095a48eecee9bb174a1a611d.nq.gz
    ├── 17815a1879ec45a8a3cf524382f1af311ba721f3.nq.gz
    ├── 1979d260d7c16acadbef073c3a8febc5949786b5.nq.gz
    ├── 19a8fe49e33585f1192904ad6461ec1a355e2632.nq.gz
    ├── 1a905a89327ecc4c44804d371ade4c7cf8951038.nq.gz
    ├── 1b493945a34a825eeb92b84bc51f5aca24d89186.nq.gz
    ├── 1b6fc929368d5c30b89e502bb53400f40b6be0d4.nq.gz
    ├── 1b8ee21f6e5443f796ee05e5a946a9e9901839f9.nq.gz
    ├── 1d278ab6b1bbfd27f8fa8473bb9b96fd5aab9ae6.nq.gz
    ├── 1e4c732567fb6381aca4916c6ab6f32d44ff63a1.nq.gz
    ├── 1f0b28442d5f18f825b888f2b4c625af61269494.nq.gz
    ├── 1f21970d8e9059242209db469e69a4949c04794d.nq.gz
    ├── 202b5584295479187ccdb4ca16bc6f740dbc5dd7.nq.gz
    ├── 202c073c90d2c4641a1ce49063e9413c2be84a18.nq.gz
    ├── 21a6d467ded2603435323cba573744cca0d8fb3a.nq.gz
    ├── 21def37d1f771795f8bad4c5ad8176b20f8932b7.nq.gz
    ├── 225e47323fa543083110655c255cabf8e3cb37df.nq.gz
    ├── 24324983157e5b2d7d22bf8c8af26c30ff7965d1.nq.gz
    ├── 24b29a01dbeee7c3cffb7aa093c2954e9ab5a4f5.nq.gz
    ├── 24ce6b106a389a27f727c4f4a47b88ddc441de65.nq.gz
    ├── 2599f9432fd946dba308cd8a785d2d4249f5e556.nq.gz
    ├── 259d495530ff53e94f05174572673d8c7218aac3.nq.gz
    ├── 25d1cd8321eeb3c116526c8eb42cc72ce2636f22.nq.gz
    ├── 26b86b656c39320789cebd4b756cba5d2502eb04.nq.gz
    ├── 27eb993ce3430417a6fb4e25e12a28dae3264697.nq.gz
    ├── 288ce50f05074579584428dea7d1c3c9b2b929dc.nq.gz
    ├── 2980413ad5004f46ba962a2ffba03b2c37e7f4e3.nq.gz
    ├── 2a6a901962d906222e1afde1de06424eafd00318.nq.gz
    ├── 2b0b0a4b1f90aaadb7209bc484f4c6d642b2c2ac.nq.gz
    ├── 2b960f965fa2b3b8c80120317d0433bbffd4daf5.nq.gz
    ├── 2e10d48d7f8dd0585ba12113a4d0e744e97411de.nq.gz
    ├── 2f8516c7101b431bfc90a1c26a3ea3fd715f13df.nq.gz
    ├── 2fea8a5ad07536c13bfbb47d9537d619b76be7f0.nq.gz
    ├── 3016ffe771a1ebcd53c64887516e3b91ab5f5fc2.nq.gz
    ├── 307387335198a4ca764e1738fedcf7ddc811a5a7.nq.gz
    ├── 321e9ee84f72e8dec959dead2c3ed3347c5186de.nq.gz
    ├── 331db85fbd2479a31917c22d51a7e3edca893f5a.nq.gz
    ├── 335f1470b7bba58c02f4917d5bb943e7033fefdf.nq.gz
    ├── 3526637f2fa2ba3282feec4629164095347eafa6.nq.gz
    ├── 3579ab6e7c7ba39a8ed49445032393f94bf56a65.nq.gz
    ├── 3643216fa99b810e9931f36163f275fe16509955.nq.gz
    ├── 36b6953f71e938a3315bc870c0e775c6392b1b10.nq.gz
    ├── 372317c7dadd4524170628ed242688826202fc8f.nq.gz
    ├── 37ddbfcf586ad0869980992a38c9c28115a0f0dd.nq.gz
    ├── 38a1b0a90957d415cc3802ed00d3004b88beae10.nq.gz
    ├── 38f239af030fa0128a0c78a2dcd776db10ff2a6f.nq.gz
    ├── 3951a9cd81d90ed4ae8b536db6a3ce0ccfed9069.nq.gz
    ├── 396a0cc320012b883dd1b62d7fdf16b29b050cdd.nq.gz
    ├── 39a60666dda197dbd4f2bab19fe3f8d2d09913d9.nq.gz
    ├── 3a8ffd676e8f09ba2349a409f609c6072e9e3e6e.nq.gz
    ├── 3b4d679e5f325e95abedd908236225f16c2b069a.nq.gz
    ├── 3b70b300a015eb9947b3f987a8c41d7cbefd22da.nq.gz
    ├── 3be1fc06cf63bbe15c10fc544789319fb1e8e2a3.nq.gz
    ├── 3c51f87ae9af297f620d5457be284780871d4465.nq.gz
    ├── 3ccf15e94b9d9296c9f33c23076b123407b6738f.nq.gz
    ├── 3d2576c052c0945caf66b502acb5d17266437992.nq.gz
    ├── 3f2b26e4ce6762443724a4a40d009f47e671a5e1.nq.gz
    ├── 3fa8b1db3999cc75c464e3c9d46d0a983c7ab7e5.nq.gz
    ├── 400713fbba8dad5e59ad2b7ff381a1085c324e23.nq.gz
    ├── 4008b224381031cf4ae68c9f8d6d578b3b9df7eb.nq.gz
    ├── 406ad54c0c005302c4ead3a87f53f7ab345d66cb.nq.gz
    ├── 41821502836cd6f085cad4fc0789009640a2ec46.nq.gz
    ├── 418d0d77c31b36bd61e0eca29fa75e22546f3cd8.nq.gz
    ├── 42968cc9cad32a990aa115392972cac3c34bd1f9.nq.gz
    ├── 439de8668d1544a2b1d1dc16060d2ab2a0f27ef4.nq.gz
    ├── 440f42cf271faa85b384bac977a266414a0ed9e6.nq.gz
    ├── 44c9d60d8a2f8ac1826effbf5154fc2083446f32.nq.gz
    ├── 450c4fbf57b567998b030bfc3b2ba040d6cb08ea.nq.gz
    ├── 4546feae594a9c381a81bce28b1e2c6f48468819.nq.gz
    ├── 45c26719f13ce1ce05b1eb7e048063cc0215258c.nq.gz
    ├── 45e6dde32a17992acb0b754945dc06f53fafcdf4.nq.gz
    ├── 46e0020e199b5cc9b2e8dbf25c8cbc343c1cad7c.nq.gz
    ├── 473c06b1f35e024004817f3b4899a7e125052994.nq.gz
    ├── 47ce19caab65c7b87319a37c6da8c5ee0c135983.nq.gz
    ├── 47f671ea0216e576f0f39d0b435bf75ddd1d1c09.nq.gz
    ├── 487967f324653634237deeb988197021cbe160ac.nq.gz
    ├── 4966d73942318db26dcc848999a99e1f1a0634ac.nq.gz
    ├── 4b12d3f8663f44dd8cdc48fd8096a288e6caa57c.nq.gz
    ├── 4b35daf7a91e7802ad36ef0d7c3d371e09666ea7.nq.gz
    ├── 4c88d8e2ba4dda85e12fa1d5afb2d5e993b7752a.nq.gz
    ├── 4d3bcd7f3b2f3fecf33a09a8e7d0e7d6084dffd9.nq.gz
    ├── 4e41a23a052bb14859cbffe30ab480cc660ded33.nq.gz
    ├── 4e9f85e7848bea91d71099fddf46cce9e83a417c.nq.gz
    ├── 4f83b0865fc2501ed8abec968ab9c9a2182fb94e.nq.gz
    ├── 4fdaa83e538ef502bc3541607d0857d6b2d96b09.nq.gz
    ├── 4fdd1cd23398dbe0a1913c6fd80414d12cb36897.nq.gz
    ├── 50cda5266f0b0af0aeac76eb04effba4dd9b2330.nq.gz
    ├── 510f356f8159f5cf720f403cdbccf89ab2757740.nq.gz
    ├── 512f88476dd1253693c79542645552dfcf613c64.nq.gz
    ├── 54bc64b9a0345dff48fdc4bc71e27c5180b83d8c.nq.gz
    ├── 55c9b7748081f9af53060eab9b20d672cdcd461a.nq.gz
    ├── 569fc3bf5a3b1f7a625126d84895b891ffdac34e.nq.gz
    ├── 56ec799b4340a02a1f327fa4f52475be929e206d.nq.gz
    ├── 56fcb78a533f04fceefdca5e5d1a7ea47a805c34.nq.gz
    ├── 5725cde3f22a6f2bfe0cc41bc98ae9d10e20ae89.nq.gz
    ├── 58111ae8452a1b4055d4c746d7610640a5ddf93c.nq.gz
    ├── 593dc3d7cd5a290f4ed66f838fa8c7ac7d1f6288.nq.gz
    ├── 59a39139fca46824b46566ffde505fa553620154.nq.gz
    ├── 59b13ef150a4c98db84fbd311e20b53652ade641.nq.gz
    ├── 59ca34438e4bedaf651a5a56a8bf2d0123b80917.nq.gz
    ├── 59ce22e76c42774748cbfb85e7fa72cda925ab2c.nq.gz
    ├── 5a23c8e1195e52aeefdf0d2c8089ad37b51429b1.nq.gz
    ├── 5a5564f59efea979c82055cb3b2b6507a83cdba4.nq.gz
    ├── 5aa49cd1e187fd797e00ae8ab03a069830b075e0.nq.gz
    ├── 5b2041ce957fb1179dbd91e88dcc74fd7cf36849.nq.gz
    ├── 5ba0888450af1a31b5ece95f8e74fd6add4fd61b.nq.gz
    ├── 5d6815e04ec5a8d2bef8b6a813633ea7b87d5435.nq.gz
    ├── 5e0f36173d611a83b60e793eceaade05aee37e3c.nq.gz
    ├── 5e571c51ab7654ba474f058ec2b745a12e649a6a.nq.gz
    ├── 623efa10efc1d4a135d6f5a01332d966bf9df5a1.nq.gz
    ├── 6396898c5263ff7bd0cca2e5f1f7b8328a65266c.nq.gz
    ├── 63fe8e21015d93afadd37ec5b5ac1bac464c304d.nq.gz
    ├── 643d8413aa44db3395f96c8528cd3f73b183bc5a.nq.gz
    ├── 653d3fcf646527e81e30c74a92f8efff8c5e4f6c.nq.gz
    ├── 65b1c975ce40eaccfe49d15fae80e93c0502c433.nq.gz
    ├── 673cead0b89fb92f4e341a5169e85aea6badc120.nq.gz
    ├── 67895582885ee4358a5599b9c890e87364eb1aac.nq.gz
    ├── 6845b6524b58ff9f8a14dbf3f0745fb547d11684.nq.gz
    ├── 6ac4e7ab2eaa6fe30e7c44f200fc42765d2579a3.nq.gz
    ├── 6b46c0908fd797f7cc57c13b357f645d0e0e7ee5.nq.gz
    ├── 6bdc24e79b44a9072004193e2048b0f021a28b83.nq.gz
    ├── 6c4844100c7a6e28cb70a6563409b99f75edb3c5.nq.gz
    ├── 6c587b3734c0eec5496c545adf94e41e2dd18e21.nq.gz
    ├── 6c90075a8c47a770ac9f22dcb6a500cc09e0a977.nq.gz
    ├── 6d2105b357bb8897cbb1499207735ece7dadb6d7.nq.gz
    ├── 6d379122f065c757e2fcc8a5da06c64cdea7b588.nq.gz
    ├── 6dff75166cc2acf72b49a2f8c9faa05d58abef08.nq.gz
    ├── 6e6e9eec52306c05b362394bdd2dcfd9589038cd.nq.gz
    ├── 703c378103b347e685e76357fd8eb970901b8f06.nq.gz
    ├── 70a65a17ea0e57cd5c43bb380a7d5446dcbe236a.nq.gz
    ├── 716873e5ed30bd580ae38bd31b3b1a51cd82b04c.nq.gz
    ├── 71720555be65ffef401bef7886c8f5a72121ef60.nq.gz
    ├── 736872e6ea083d838e842fe781df919fa9791896.nq.gz
    ├── 739a8bee3798123aea6d51ca01e26f0091adb85a.nq.gz
    ├── 73e05081fa5240f5ed1df124d07ed15b89890c86.nq.gz
    ├── 743419eb1d75ba6666b84d4fad13a03b2f1846e5.nq.gz
    ├── 74a4d24eac844ed0e0e9c915c5663a8e47f826b2.nq.gz
    ├── 75d3af0d5699e58f4b023df0b43aa8f3009f0dcc.nq.gz
    ├── 75f553065e0dfe53a5b9ea466a3c47963f1fccf2.nq.gz
    ├── 76b299a3bfd103d64ad62407d0e6d412b85de8dc.nq.gz
    ├── 7727ac9d39bfa5238fbfb16d73886851047be4da.nq.gz
    ├── 77947f8ae4d924dbce117a0a961b3803401ebbf1.nq.gz
    ├── 78454a978fe8af55abca5111bfdd1b9b26b49527.nq.gz
    ├── 78e52395b82d683ed6feb7689642600a7763bbe9.nq.gz
    ├── 79bed0f89cc58a6071329f4062aad7eeffb2282f.nq.gz
    ├── 7a0d464701dac3df442229b0bc6a0d17cfcbfe6d.nq.gz
    ├── 7b0a476599e08391116f7925ca91cc59926878b8.nq.gz
    ├── 7b5ca60d0d9a0bb268b3c20671bd26597a3dc193.nq.gz
    ├── 7bd32e2dd537ca850e6d67e6f3eb35f656d7094b.nq.gz
    ├── 7d15402860be668c5e559dad70a15b72ee7319d9.nq.gz
    ├── 7d3b2f678235d046ba1d9ea670336abeee1b4493.nq.gz
    ├── 7ffcaf760802a5d079437407fef5af6b6d6d8cd3.nq.gz
    ├── 809b6fe5872fe38d99ffa4a13f1a88b73d29fe1a.nq.gz
    ├── 81848e5aba1fd087c157567bec4572032bcb52a8.nq.gz
    ├── 81bec8ac3d81daa40886e746aaf98ec40beadf41.nq.gz
    ├── 81e62592fe9de4468c54277018dff9c412532017.nq.gz
    ├── 825222997079b7880a5f484d024e41f203b83073.nq.gz
    ├── 8297abe6efda89e1e5365f31620fb2d178fb35d5.nq.gz
    ├── 82d66c0fd1f66a1fc282ad2c8372b03f04f54665.nq.gz
    ├── 834256ce7fe9f4efc9525075bd3fd5bdd6896e16.nq.gz
    ├── 83cca017d4d12692b31b149972e89fffb7bdbe6f.nq.gz
    ├── 83e40a3896a0f108ac648c62ac9cb75349949968.nq.gz
    ├── 8493bdb1dccffef8d964a490b52d4b02479cb4b1.nq.gz
    ├── 84bec07033e1c4e8928770e4abe1df7b03bc7d93.nq.gz
    └── 84e1075109ea3528311189a90b0be728f4d864c1.nq.gz

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

[zopefoundation/zope.i18n](https://github.com/zopefoundation/zope.i18n)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
