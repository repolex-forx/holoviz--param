# Repolex Knowledge Graph of holoviz/param

RDF knowledge graph data for [holoviz/param](https://github.com/holoviz/param), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/param
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a45813bcda1340945c6a38e18f8c95114a2b4a95
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a45813bcda1340945c6a38e18f8c95114a2b4a95
│           └── chunk-001.nq.gz
├── blob
│   ├── 000426f8ffc43f668fdac2e09e40b992b7a5c1ba.nq.gz
│   ├── 019ab89d3b01803eacabb5fce4bc665bcdf67ab6.nq.gz
│   ├── 05a9425fb730e5e566374aeff7b819ad1924105f.nq.gz
│   ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
│   ├── 0ce52b35c0737ca77365a8fb98964a6650c55396.nq.gz
│   ├── 0ec4c5cabe365e3dc5898955493c36e258aed82b.nq.gz
│   ├── 0eed648751075b5ade3c382221e63a589436e9b7.nq.gz
│   ├── 0f7c26543620c01a88f5f69cb68aef812429cce5.nq.gz
│   ├── 1157cd22de9a5c49ec6c1eddf15ed262d06cbeb1.nq.gz
│   ├── 11c59c70da6e89ef2aca585b61714271f0ee6af8.nq.gz
│   ├── 122c6a0f5d5b030de65f33e829fb00e124460a76.nq.gz
│   ├── 145a88c535f6de17f36321d5a9f82a183b9d3946.nq.gz
│   ├── 15809808c2200b6f6955ffd8291c811b550c9171.nq.gz
│   ├── 15f2905b2b7e033f8e1be2d2c24143213f82912b.nq.gz
│   ├── 1ac9858ed892a0ffe95b686357f5221b7fcacaa1.nq.gz
│   ├── 1c34ddec1400028034206893a539915841c1e76f.nq.gz
│   ├── 1dad4bd5753147732d42f4bcb591c1626ba23166.nq.gz
│   ├── 20eaef62a39926397dd7992d06a142bbdbbc1746.nq.gz
│   ├── 20faf522a6b3f8ba41992744a474b0fbb3e86aea.nq.gz
│   ├── 2b049f20981dd0a95b9dceaeb2ff94027e1e7bde.nq.gz
│   ├── 2b3ede68857ec54c66de5ee44199d1dd480223fb.nq.gz
│   ├── 2cd72f0be695e313a53bcf83a6b9f4e35dd231e3.nq.gz
│   ├── 2e11baed6563813dc8eeefd7e9266179cc9b8d36.nq.gz
│   ├── 2e1b794f34f5a2b6b71ff487122cfbf2f7c1b579.nq.gz
│   ├── 3310a7ede0e5a14c2081470af7867e66ee6c70ac.nq.gz
│   ├── 333b5fbcb9d912e32232eeb16beb0ec2752946f5.nq.gz
│   ├── 35a4e93ef574783cdcff7ff1103604d3e751cb11.nq.gz
│   ├── 36dbe2950e3b07d5cc27cc9e4b31e61885ad239d.nq.gz
│   ├── 37f9ddbab5b818b80b5b0acb21bbfc13d0ba418c.nq.gz
│   ├── 38bb211b065081810c8c65af2d44ca10dc9fb059.nq.gz
│   ├── 38bd6851f38b1f5d726af172f2c314f61fb370f4.nq.gz
│   ├── 3fc1ea5e9c57e4fc8d4fb90fb4a5891af87c81cf.nq.gz
│   ├── 4346d81bc21f713e3adf816a7c1dfc45aa84c5d5.nq.gz
│   ├── 45cfdd80b369548912a9e10665db9ddf4fdccb54.nq.gz
│   ├── 48638737c04a2b0451f5f66ce396c791e29ce62c.nq.gz
│   ├── 48b385e68d40d0396af810288330334f40592f94.nq.gz
│   ├── 4bdc3cbd4ddba08cbb5f54112f4673d205edd7a3.nq.gz
│   ├── 51ef0b804283edf66dd8a82a74abc075d93a9414.nq.gz
│   ├── 548b7b248f3ccb2286ae843e536801b8bf8c98ef.nq.gz
│   ├── 557b42ebd8ad7cc03b8557c3cf6bfb096824a3ba.nq.gz
│   ├── 56bf77e12b8a4bb24a3ab6030be9f50b74166317.nq.gz
│   ├── 56f92ce82bb8be0ec601eaac0a0d82d616f76490.nq.gz
│   ├── 5700358b0209bf6f059eb28497046ad3b2db10ae.nq.gz
│   ├── 5770293804615dd6d6a812ea4d2199f10dd3c341.nq.gz
│   ├── 5834810dd9a2cadec231f18e07d5d039f3437753.nq.gz
│   ├── 5910adc1042f63fe6271dd7af5c12718d7c7041d.nq.gz
│   ├── 5a1af2ba57a48dc31a60513511e91121aa5075cd.nq.gz
│   ├── 5a78e6f21801a27724c1474bcd9f2ff3039cc986.nq.gz
│   ├── 61e3947fa322b0d0e71a9e22c1387512962a11e9.nq.gz
│   ├── 6438e4989b415572fdb3b3c29361cad165646dbe.nq.gz
│   ├── 68672c1869c53b58d02d11e328778e97163dd35c.nq.gz
│   ├── 6944e02c1d957a5b33a0819b82978c3f647b2286.nq.gz
│   ├── 6bb7ec8c016b23ebcac1349a6a5df5f130deaeb0.nq.gz
│   ├── 6c62e89ab7f7f9a65b2938d977ce52283a4a799e.nq.gz
│   ├── 6e7f0c13f45eaa43299d72040698ba863f069745.nq.gz
│   ├── 6f49507e51532b54f7bd46efe1d6482ac797f259.nq.gz
│   ├── 702e65cd0a6834bf493f220b84d86b6448ddb8ba.nq.gz
│   ├── 7083cc45b414ae4ea363747d4b6b1eeb2b13ac90.nq.gz
│   ├── 71f008d28214492a8c83708a223d8b26f0da74b9.nq.gz
│   ├── 72aa762e04558eeaabfa251ffc467e0bdf7a538d.nq.gz
│   ├── 7402f650327eeae28280c0a29d0cf0a0d83aa561.nq.gz
│   ├── 748395f0bc483517955733efc47eb43fc60a0193.nq.gz
│   ├── 7744b84c6b71216ba7aa4361676b30336cab4db7.nq.gz
│   ├── 797ca1ce99f56465ab470d8c6b3a9c629fbd69a2.nq.gz
│   ├── 7adbb7c7dd7aca36ae09087d9553194a805feb03.nq.gz
│   ├── 7c4076d15d6576f2375390659e3f01d2e7e38257.nq.gz
│   ├── 7d973efd5f837f09ce070cc7f4811ca02c7ea480.nq.gz
│   ├── 7e5cff89774d7e843981970bd02371367b304566.nq.gz
│   ├── 8050140ad279bd31948a7de64e38516899ed2c5d.nq.gz
│   ├── 8158af945672b7a2d88611f796169ba22a1cb6e7.nq.gz
│   ├── 81dbd230e86511e6ccb4d15fe155c5620a80a173.nq.gz
│   ├── 83947a7724d61d93da2c0efb4dbe4283ca5ada8a.nq.gz
│   ├── 84e2506d0359379341d90ac978429ab066f50f3b.nq.gz
│   ├── 8786434203cbd33de6a2d5ace819e49ff10a6442.nq.gz
│   ├── 879cd7b2247992c35b04fd16585a3ea77af16aee.nq.gz
│   ├── 88df3bed1a10234489014011ec9ab0e9aade9e64.nq.gz
│   ├── 896dde74048d130272d4ba782da948c49183a557.nq.gz
│   ├── 8ba53af59c3f4906ad1180e0aea8e528c0c66dd5.nq.gz
│   ├── 8c70b4c122e2890d5d312ec95c4b177b9fd66236.nq.gz
│   ├── 8cb73224eae7a9c68aed7923c83fec5ae24aec10.nq.gz
│   ├── 8cd90eca02501535b9d1887f560b32ae3b78e333.nq.gz
│   ├── 8d2c9de2a36976fa825ca55b0e112c278dd33f81.nq.gz
│   ├── 8dc035fc5a8531757fbdc57023aa4384e7bc9dd1.nq.gz
│   ├── 8e1328c23ad7b36244a9f0e95cc829e5f5b71309.nq.gz
│   ├── 8f5917b400559e100f3da7368e15a5b3ca2a9c58.nq.gz
│   ├── 90cbf1f31066380d5163506b940c5636899e4387.nq.gz
│   ├── 95f3a8bba047d456001d6111c0f1275e1d29d232.nq.gz
│   ├── 97a273b2c7e97b459b542820ffe3504f99d44885.nq.gz
│   ├── 99ccc5b25a37187a1829d1514c4d9c06b008031e.nq.gz
│   ├── a0b8dfba284a695d1ea951a1ad7ef0b5f6636fc1.nq.gz
│   ├── a14d8e54fb8a9744b523b744bab4ce643ffb5b67.nq.gz
│   ├── a4c58d38dbf885cfadb9a80c72ee6c46ddbad4fe.nq.gz
│   ├── a5510ba748d62b0bc8fa6a98f0e2f1ba6e075794.nq.gz
│   ├── a9026be456ac7e33f8b3e3480e3f75356d4c2bc5.nq.gz
│   ├── aae9dd9e8e4f293734e92e21de4b887ef7e9fbd8.nq.gz
│   ├── ac4e4ffa2ad13419779a81ed90ccf56a156eb0cd.nq.gz
│   ├── ad1a0717869d7e196b3ecad9442773a013d71342.nq.gz
│   ├── ad353acad5fe5ecaa850c6a8481d8f4b5a73f2ce.nq.gz
│   ├── af275c9147fe50d6b4f99064160f7f75e9b2d113.nq.gz
│   ├── b1b2e3c277081e778b925600cea2d60ba93e3af6.nq.gz
│   ├── b1c8e3e0411b062aca98db4db3011d80e0c7b00c.nq.gz
│   ├── b1cd9b6b1473eeb203a1aff507ea86a6bef882ae.nq.gz
│   ├── b20c2017fd53c7687445d3dd1b8dc4f9968a89f4.nq.gz
│   ├── b80ec4e86ac51a44a5cd3c88393b6da78bc28b7a.nq.gz
│   ├── b9727d55dab0c5ba07412796470c71ac352e1e80.nq.gz
│   ├── baa6aa4c90842646bf13c38ba40e0a44fc939449.nq.gz
│   ├── be94b635bc1a98af7c2c4be7199a95fc955dd374.nq.gz
│   ├── bf01bc12ef42c5335d7bba9047614b11bc158d5f.nq.gz
│   ├── bffd0048d2139887598026636633337836e7cf00.nq.gz
│   ├── c106d79ac7e44ad1f0c20516cb45f6390718b869.nq.gz
│   ├── c1ed5e7d6b68abd12e0d3c5e38ec7444726cce6d.nq.gz
│   ├── c4aae111e3a32269e9dc901649a4d933ee41d093.nq.gz
│   ├── cb9f482618372c4cff8ad5f00760e94c0b32d34e.nq.gz
│   ├── cbbef1f31e5a5b340a0980b0be161a5034cefde3.nq.gz
│   ├── cc6d3c29e277c3aa6fd564bfa8fd946a7a364169.nq.gz
│   ├── ccf168b90e68b5d12e07d59de618b86fe131e41c.nq.gz
│   ├── cfd398b94a8e9e43d5d741a52aa644e815da796d.nq.gz
│   ├── d0cedc8b5118b74537a3da398d32391478bf22a3.nq.gz
│   ├── d4c2fd1ca14a93a83405528d5eedb3323edbb61c.nq.gz
│   ├── d5234ba4aa69eef62b7685fcfa1e72634f9793b6.nq.gz
│   ├── d5c9228977b7a9d2fd64fd794cb8f34ddb230298.nq.gz
│   ├── d60aa2b65b6f6258035c61c45f49d6e95302df1d.nq.gz
│   ├── d89d345ff313e12cc580d78da4de437e1a2e9f5e.nq.gz
│   ├── d989eb0a13430243439e0467fb15deb201432f72.nq.gz
│   ├── db6483fa08123ef2d5157a9d4a02e77d7e8b8a0b.nq.gz
│   ├── e45869632374d03371e0119c553967603c1e512e.nq.gz
│   ├── e45c842c8965d5c3906c95ad366c6e11bd99d380.nq.gz
│   ├── e4972d6edc4734c09cde4681249cbcf19a9b9819.nq.gz
│   ├── e663ce059edf67dcc92e722646e9f8e4efb5e71f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a751fb9f2a2f45c4097ba015a33d8b684e60fa.nq.gz
│   ├── e939d9c89478991f1f5ec9aa1e99dbf8e506b036.nq.gz
│   ├── ea2654cf59ca22a6f7399046dc3772ebd499e319.nq.gz
│   ├── ed61ab3d0460753e32c557d0794fef0e4df01e23.nq.gz
│   ├── ee0844c3d1ff6a0b2864637ef82afafc4fe09631.nq.gz
│   ├── f02641ca453cf138c91e275b5dc64ac2d6fee0fb.nq.gz
│   ├── f0d186e94ab204ec243ac7d23b668b8f2f5903e6.nq.gz
│   ├── f0fd596cf6ff9011d442d6ce35d8116071cf5a2f.nq.gz
│   ├── f377f480a8cc03a6174c3004080c09f77b125ec3.nq.gz
│   ├── f790eb420092681b450b180bbb37543d88f9da2f.nq.gz
│   ├── f8ab71f034f62f432ba504208f48468e00be1b38.nq.gz
│   ├── f917a3a7e49d05501523b30edc83f87b5cd9a2fb.nq.gz
│   ├── f9182cd883b6cdb15dfc7aac6c6d2c48e0be0f82.nq.gz
│   ├── fbefd2245beb8eaabc8b7bef338b26b6520ad1f5.nq.gz
│   ├── fcb4c4ce3b4fcebaff55b295039e66c981ea6c4f.nq.gz
│   ├── ff89c74b259607c92a18d5b337ddb83ab816e8fb.nq.gz
│   └── ffc5590c128048d611c027d923b7a07fd4bc9da0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a45813bcda1340945c6a38e18f8c95114a2b4a95.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 155 files
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

[holoviz/param](https://github.com/holoviz/param)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
