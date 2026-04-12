# Repolex Knowledge Graph of ruby/rbs

RDF knowledge graph data for [ruby/rbs](https://github.com/ruby/rbs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download ruby/rbs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fcd48c6b1f61477be88f7ccb15fa4769087ef608
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fcd48c6b1f61477be88f7ccb15fa4769087ef608.nq.gz
│   └── repolex
│       └── fcd48c6b1f61477be88f7ccb15fa4769087ef608
│           └── chunk-001.nq.gz
└── blob
    ├── 00034ef048952f1152dd4e0eb82de3bf0659f823.nq.gz
    ├── 0004da331e6577e02ef8390aa9ef648156bc756e.nq.gz
    ├── 001828d13a9212089c139e596694fc532d782e93.nq.gz
    ├── 0054fa694f325f936687b8de371a8b3237bdb820.nq.gz
    ├── 00826469e4bbd1819c77101238a5c5ef1ebe1887.nq.gz
    ├── 00ad4910d8b96b3fd59d90af06875b0d5b56d14c.nq.gz
    ├── 00e56cc3508a357e37d5afec38753cd179846fbf.nq.gz
    ├── 019e78be7651b190d891819625ff9cd7f3e6780b.nq.gz
    ├── 02095c7febe06490e7d4b8f3e90629b0979e4a4e.nq.gz
    ├── 0221518be7c1f5b4d2ba57e92a83d34b858dfee6.nq.gz
    ├── 024e269e9e0083bebea01933abc20117d6d69c98.nq.gz
    ├── 025b84e920fa813d1068b85accc0e91ccfe10cb9.nq.gz
    ├── 02d0f0a015d327918e8bce388e1bd807e650d552.nq.gz
    ├── 030a1dcfaea840b3be23c053ae62c80e66f5f8eb.nq.gz
    ├── 039b14d73c5ec429ccec247fad70075f7c59c3ed.nq.gz
    ├── 03ca947738c990593543a220486ad4daa321131a.nq.gz
    ├── 03d3f13a63e4479141969b5c39d6397832f1f6db.nq.gz
    ├── 03e0db7da8dfa44fd116cfecfeb4993aa05bda7d.nq.gz
    ├── 0445a6d255f69842a75de0f06e07cce615082334.nq.gz
    ├── 046f71aac0d96a3d7a35d502d2150517e9b50051.nq.gz
    ├── 04b3b89fcad1d9fb6705d25be97f395574dbfa29.nq.gz
    ├── 04cf6b6ec63bfd513b319a175c99b547e598655d.nq.gz
    ├── 04e43cb38c7839f7ec7d134339544abb8b68e737.nq.gz
    ├── 0500d45a257eefa12fdea40e477dedecf4d1c228.nq.gz
    ├── 0503f795e1367d076d2d9cac04e8ae8ee9b4f5a3.nq.gz
    ├── 058f7368260ecb528bc9734246a9acaedc554071.nq.gz
    ├── 05c7c6cb33fd95e466257e16cdc012ec7633a982.nq.gz
    ├── 05da1a9473fcf148f196d7585b3594b21635c2a8.nq.gz
    ├── 05ed568741ceb38f22178b6869f030221c1eca73.nq.gz
    ├── 05f3d3f473a8ffa104d3fa02eb8d28a9b0ae3b6f.nq.gz
    ├── 0604816c3c1d2e74ff8e5bc88b8576a2184ea9df.nq.gz
    ├── 060a751a2fed4fbdf6675320e974fad73ff29613.nq.gz
    ├── 0654474fa98653024608a7285c51549e30b4ef5e.nq.gz
    ├── 066f9f4fc315b5fd13481520a68814c70f09cca8.nq.gz
    ├── 06ce5dbf5a14c79c0922c647700f8568a0f7d6ca.nq.gz
    ├── 06e084d9414a2d49fe235e6d44d91eed62676ec8.nq.gz
    ├── 06fc5773e5c8f12c49e0cd626adbf2fb80398a58.nq.gz
    ├── 07c8753ba37831cf71b3bc8cf0417bfd93c254fe.nq.gz
    ├── 07f67420678991e8a2cf2c519d865f30f9c9c31c.nq.gz
    ├── 080d155837a554a6ca6b8e4fab106466964c821e.nq.gz
    ├── 08245dd24fe603e80acd9d3f1b68df8d38f1fa1f.nq.gz
    ├── 096dbdbf07cd31e2bbe1d7d4edcea60b232cb08b.nq.gz
    ├── 0977b8c4abb9b107cb06242aed216a1251874498.nq.gz
    ├── 09bc5fc792238b613defa140712113e37b4e27f2.nq.gz
    ├── 09d344cd7ec50d66700cc327e4876c2229be48f6.nq.gz
    ├── 09ec37ca3d50a1575823d11bff95082201484b2d.nq.gz
    ├── 0a0b3be096d01fe1c0a52219cb2a150993efe126.nq.gz
    ├── 0a55dd3ac6e1ff1066a70eefe2a40283940468bb.nq.gz
    ├── 0a56bb66f46a937d06e80e9cc9ada36451bfa43e.nq.gz
    ├── 0ab8a93ed43b3afb272e95a56ab15fb79e236f85.nq.gz
    ├── 0bb1cf013da0bb229f5aea5e3240cb3d95c5fc4c.nq.gz
    ├── 0bbb3cda9a67394cff069197b1ac1541e4e6cf1f.nq.gz
    ├── 0cdc83de27323103985cbf8dcab58cec4421ab11.nq.gz
    ├── 0d460c16ad5f0a9eec5108170cbd2942c03eebf9.nq.gz
    ├── 0def4587f40f122a783631758f40a72058d385a7.nq.gz
    ├── 0e464bf43d215836dc31d8ac2730ebfa624f18f8.nq.gz
    ├── 0e57eaaf5a01bd14d1e80eb809fe2eeb0a9903d3.nq.gz
    ├── 0e5aca82f65e496ac333eff7f1d7ac871fcc2d07.nq.gz
    ├── 0e7bf384c713f828992c694e4c125ebb9b400be0.nq.gz
    ├── 0ecb5b2ee50e18cdb4c4dbe21f49a5f7f87461ae.nq.gz
    ├── 0f18b74a8e80b90ee5840db281406a6720db4221.nq.gz
    ├── 0f9e73782f910c27ce490836257843bc475239dc.nq.gz
    ├── 0fae56b2144253adc841eb45d82cf8ac5e740e5f.nq.gz
    ├── 1047879d33d5163f2310c5e08f2051d3b69f5302.nq.gz
    ├── 1077b915d27c213ea99de2a5d0f09c9c283210a4.nq.gz
    ├── 109becfd144b259a1027678ce6abaa050e0c083d.nq.gz
    ├── 10c7ed979f65be2d870548506d4e8237f6b998a2.nq.gz
    ├── 10f37d8a4ebcff3cedadad62546649252d04501e.nq.gz
    ├── 11d1a531f580e98f7e7f2e6ea44d4b756c28d945.nq.gz
    ├── 120fed9af8ee72252c238a503a2a2c6887ec357c.nq.gz
    ├── 121310cf677bc02aac8f70237ba550cddb783f15.nq.gz
    ├── 121f43f478c9d61be56f0cb7053e4b68029149d8.nq.gz
    ├── 122f5f5230f2ea0c7017d1550d504240b85d6cf3.nq.gz
    ├── 1406eff6f534826a52bea9e000815660833c20f1.nq.gz
    ├── 14394214bc0885bf6e07aae6c6a63c6362ddbba0.nq.gz
    ├── 147e874c38a9f7072f31a1d2566186e01db4ad38.nq.gz
    ├── 1490d0306aef940b0deb0183cbcc0773dc857483.nq.gz
    ├── 1495cdd2511ec03b3545e0e38f80d9fec7a45762.nq.gz
    ├── 14de08716e345daf6a94f1c6fffe09e991340b21.nq.gz
    ├── 150a87e04b60e140a8f3c23b7f4fd3ec6101a4d7.nq.gz
    ├── 16651626230a1b87cd2e63f26d17b84341ffccef.nq.gz
    ├── 16c003e100aeaabc3bbb8670c1c0c3a5127127c5.nq.gz
    ├── 173cb6b3431ff065f993b6e98e1c08534b08ec36.nq.gz
    ├── 175651993439e9974e48e8df7d43346e6b49acab.nq.gz
    ├── 17db601a07c624c19d7c07fe00862ba85350ca95.nq.gz
    ├── 182b3bf0059e3120feb6d3e70452dc2dbb4d93c4.nq.gz
    ├── 186e2dc72b8eac37b48359f3442b823e7e50e61e.nq.gz
    ├── 18b213342586549dfeb1acdf13ec592a8df718de.nq.gz
    ├── 18be9a05ef29cca16536225421dd57142ff985fd.nq.gz
    ├── 18e9e28bc6e2f30bcd897d483c1b157441f97a5e.nq.gz
    ├── 190d48fb5ea6d26ced0d5d5aa5cbb9ff27acedb2.nq.gz
    ├── 1922d6f77adef525a578d1fab04191d314f2dbb4.nq.gz
    ├── 1947484e7fec0fe28b4dd151379d0c6d16e2b326.nq.gz
    ├── 19571863a1a5c0db5c7955ee13a917c57049a492.nq.gz
    ├── 19d8b35d6c59b854c979b3d593e27f0010ee6932.nq.gz
    ├── 1a39f099e542fe0f409c99c2b5cc6d88fb4c8eb6.nq.gz
    ├── 1a3e2afa81147ae06bde8f670ed92c07c32ddc5b.nq.gz
    ├── 1a6b315d00461afff8516b662255d1db79c4936a.nq.gz
    ├── 1a8041c93c7c220610ca93bbc7af28e323495551.nq.gz
    ├── 1a9019f1a3dbfef53c063542da29404fa48a7cf5.nq.gz
    ├── 1ac8f5a005270925e9d518c3d869fed53001fb16.nq.gz
    ├── 1acca6f62b9bacbf6ad1451581f2d039866d7cba.nq.gz
    ├── 1afde557d7a6ff8568449141d93f7f237ad35de4.nq.gz
    ├── 1b9cfbc46078f4a030e9bdcb7609e2dc5a987b95.nq.gz
    ├── 1bfda5c5fc5346eaf054fb63a613fcba0fc9a19d.nq.gz
    ├── 1c4db51937db0f91f64e796dc51f96180e17a22a.nq.gz
    ├── 1c6fa7c660a9d907463ace67e9132b768e370cd0.nq.gz
    ├── 1ccdf8efd97fc5e954c8d06a1eaad9f7ba055020.nq.gz
    ├── 1d033aa8106a6967e8fb3437820d237746c334d4.nq.gz
    ├── 1d2bc4e3e0d3b21e35432e08f70b775077b8e9bd.nq.gz
    ├── 1d7bfbde46eb5646ea5f0333ce58fb8e000d495e.nq.gz
    ├── 1da97a631bf12eddc665eea82ad6d344e49cee5a.nq.gz
    ├── 1dee2fefed98ac2a9e721ce05e3452879c2398c3.nq.gz
    ├── 1e7a30d77d74282f679ff2e152ef5b1b8b67642e.nq.gz
    ├── 1e94cd4b740144b8100efe330da20e0e81657e19.nq.gz
    ├── 1fb31f07945a9e6f91638efb1c6ccf13645977c0.nq.gz
    ├── 1fd2a0fc9c9f8427c2fb1911858482c1bfb72343.nq.gz
    ├── 1ff8090d9fd270cf7ddf6c70d0caf840859fa956.nq.gz
    ├── 200a4768c2d3fe9ecd7ffef6188d0f91614bb7e6.nq.gz
    ├── 204cbdecc9e62bf2f26869e23e9b23b8237239d7.nq.gz
    ├── 20b11461193e4e151c4299f8b5aa91f5425906c9.nq.gz
    ├── 20c40dd76b0486c0c36684056bad0adbe6fdcea3.nq.gz
    ├── 20e33ca25d3bf4ce4bc7dbb775a4ad68e8285257.nq.gz
    ├── 21100ecf92cb7cf03f986416d0b1c6f774ccf7ec.nq.gz
    ├── 215eecd34cbd91475b843677f11cfd40b5901fb5.nq.gz
    ├── 21a9d85ddcc0b7a3fba8d1ea89ca6c895caa2680.nq.gz
    ├── 22c78c3dbe077a4b1a17be1e6828951e7594170b.nq.gz
    ├── 22f95d4336758c0d7a796176fd7a8d9f6c273bb6.nq.gz
    ├── 22fc2daa87aa5e9b7a585e29b1962d3a3ebeed97.nq.gz
    ├── 232d20190030e9daccaa2c9f692b7ceb2899a188.nq.gz
    ├── 2359e9529ec34ef9791b914916e9608845daca6e.nq.gz
    ├── 240439d20f795c2852a502f1514e8e1645229add.nq.gz
    ├── 24694911ef4d72d0252208ccbf313b6bc02dc92c.nq.gz
    ├── 2471aada27a21e57db16aa813e176760ed9eea89.nq.gz
    ├── 24edc27f0218b105507250a4125e0f787c370b85.nq.gz
    ├── 257f5de7bd309196632a1961fc918d0e180b3dcf.nq.gz
    ├── 259ae1dffb811c8311fc913009529401daf66209.nq.gz
    ├── 264f41041f14bb6bb217603d776f12baae724563.nq.gz
    ├── 2670fb64a0f67aa8aa42f627bd47a106ca5edf07.nq.gz
    ├── 2685f918b18b2ae6364ce29afc2336dbf365e382.nq.gz
    ├── 26ab1e545665404132f9ea05a3ba4d1b0578011c.nq.gz
    ├── 26ba3824e28a66979dfef9613acb3a297f9c6036.nq.gz
    ├── 2722347eceba50632d8ab09a781f7455d1107a27.nq.gz
    ├── 272578a772b613558ab953eb4ead3e1d3317ff76.nq.gz
    ├── 277de4ccf12165ae9ea6be4621557e4661f069ca.nq.gz
    ├── 2842aa0684b98175784889126fea38f45360f273.nq.gz
    ├── 284bd1350e6c5fdb7fd580bb2ce07378e7a3bff2.nq.gz
    ├── 2866e68b7af446b2b7cafb610777e923e3ffe2eb.nq.gz
    ├── 2943f8ab0e66af23b8e5c8fe9e22a74d9d990525.nq.gz
    ├── 294f4c40bbe2d4ffe43210a45eb4d640ae0bb4b9.nq.gz
    ├── 2951d3ba2a942284db61cf145e6ab69a775932ab.nq.gz
    ├── 29caedb78be4a67fd4de38607270cc813e14ea0a.nq.gz
    ├── 2a09825b581c54f990482685652b5458fa74d527.nq.gz
    ├── 2aabdeec4eac8812c02f1b08c6cf4dcc6eda1dd8.nq.gz
    ├── 2b0568386c1cb27df47032bc4d6b2acfe14b4bb0.nq.gz
    ├── 2b0b6a422af1d9731623c151629f5d5e63569253.nq.gz
    ├── 2b544de827af3e86fefd0de6261009dbacbf36b0.nq.gz
    ├── 2c5f07e0bac7338c79ed34a5098a12ca1230b2c6.nq.gz
    ├── 2c806de7aa15efc5dbca0ea081cd4eb0e86424f6.nq.gz
    ├── 2cb3db53db4c913e74f075b38b7b2a3f807328e4.nq.gz
    ├── 2cbb22a35d84db5aa20de254041b4ad50c866cfc.nq.gz
    ├── 2cc89ae877d4f55764e2e3bba553d4172a87a68f.nq.gz
    ├── 2d60024d5779887a932d176fc1b1cf707859f043.nq.gz
    ├── 2d732c1ebe83470e1f8062f1539c4448837771a1.nq.gz
    ├── 2e9c21d233e107ad781712f902790b50e847153b.nq.gz
    ├── 2f26b63cda99109854d828b358d2bd4e7f83164c.nq.gz
    ├── 2f464f4296ca18d63e97fa2e9cf18d3b9f7db3d4.nq.gz
    ├── 2f52b504813917ed76a66667532a9ab321912d8b.nq.gz
    ├── 2f781f53c8aa58f175ff690c751e903105df6505.nq.gz
    ├── 2fa1db293ca7c22b6fa8ea29c013aceaf0062c83.nq.gz
    ├── 2ff64c43d6d102c2d725a39f552da61778f88dde.nq.gz
    ├── 30378075e0d4fca400746dec887f6d34ea5c51a1.nq.gz
    ├── 3068883396a1bc4cc03ecb5564218f431b8b66a4.nq.gz
    ├── 31230c39a57610f88bdf236739137ec11aaa9c4a.nq.gz
    ├── 313cd428b233b084f27d2130afc978d85308e133.nq.gz
    ├── 31be847f49ff91b3ef6b135b69d8e1f8994c6ede.nq.gz
    ├── 31f7b4fcc9793a01a3bdd3d150185d620c9308de.nq.gz
    ├── 32009ad9460812843cfa2a0c4cf62ba24e9a7c05.nq.gz
    ├── 3259731fb497c2641704938b14ba149f24aa8025.nq.gz
    ├── 325db6f4b92baace6fac26bc4579dae9a08364e6.nq.gz
    ├── 330536538c7008132f3a96f3198c72f418fc9e91.nq.gz
    ├── 335cafe677938a5385382fd523247ce2eda10d7c.nq.gz
    ├── 3366f324fcd69e7070c357668fd6e205e591e956.nq.gz
    ├── 337c6d1a0d5f136c7d93894429bfa2c7794934a8.nq.gz
    ├── 339c83950ca1e2d55493787b5d0a026e0effb2cc.nq.gz
    ├── 33decce4c72afa0d54c206a82aaf0f27ac92bc70.nq.gz
    ├── 33f3ad7acc23570913107bde9a0183fd829d6cd2.nq.gz
    ├── 342fcada404cf1ff4270b40d57c2e110d9630e7f.nq.gz
    ├── 34f009cadd0b24c13897b6f30c8c07ecd401e582.nq.gz
    ├── 3525fddafd04d9156fe3940fb57f598138eeadf2.nq.gz
    ├── 358eac354e97b77272f5befdcfd4271615614031.nq.gz
    ├── 36006878e692e3e1acda021ae6ff100bd240d087.nq.gz
    ├── 369faf8e2db63b3619bdc4e614e7e0f5ee8549c5.nq.gz
    ├── 373fa5b5b5c43c8a156b2f9f6661a3a70cd13df1.nq.gz
    ├── 37862126f22861dddef82136042fc32664d0e179.nq.gz
    ├── 37b56279c1ce40e63e379c2e89ce1203895a039c.nq.gz
    └── 38dd67ede5a7ad2a31a587b381da67faf502de29.nq.gz

8 directories, 200 files
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

## Source repository

[ruby/rbs](https://github.com/ruby/rbs)

---
*Parsed on 2026-04-12 by [repolex](https://repolex.ai)*
