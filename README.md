# Repolex Knowledge Graph of huggingface/trl

RDF knowledge graph data for [huggingface/trl](https://github.com/huggingface/trl), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/trl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6d6901c5e3963108076131ac4979d344566b13a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6d6901c5e3963108076131ac4979d344566b13a2
│           └── chunk-001.nq.gz
└── blob
    ├── 002faa97d17b608f9fc7d77945132b5031ab9a58.nq.gz
    ├── 0033d4c6cb08b34a5f68cd880bd64bcd8f022195.nq.gz
    ├── 0195a3eeda76067d7b5eb4eddfc4bed54724fc20.nq.gz
    ├── 01bb56ac01f14299e420ceb3ba84f0c18c3ff80a.nq.gz
    ├── 01be9b307daa2d425f7c168c9fb145a286e0afb4.nq.gz
    ├── 02d336c81f6facb8c5e44d93894d7688d33f1e4c.nq.gz
    ├── 02f8bdf79ba0ec629ded1a32a847babc6c35ca97.nq.gz
    ├── 0350bc21612580f6d333860872289e8f1b4b201c.nq.gz
    ├── 041a38542a6fbaba81fbdb3d278e737109c95f83.nq.gz
    ├── 046c12bd5abbeabc8b27dee37835b1e41db5fd8b.nq.gz
    ├── 048721bbdffb09a6b2e7555b26738ccfe7a9c215.nq.gz
    ├── 059c88b13e5922f6a87ace9a991c3d31c58b9450.nq.gz
    ├── 06b8df2cd28fcd814338ec5200ed9cfd838d685c.nq.gz
    ├── 06cf9e76a9e52c632c6e4a9c87a6bd108d818b6e.nq.gz
    ├── 07e50e69a8c445f2c31a089b828e85b2a93942bf.nq.gz
    ├── 084c4eb88e618c6398402d142716cdbfebec99c5.nq.gz
    ├── 08a0e46903ae792d3906384f3915e1253c942f71.nq.gz
    ├── 0981940902f6045920ae51f5c0fdbbead4abebb7.nq.gz
    ├── 098a4500287fe99701772f879e0ee76d4b9a97cb.nq.gz
    ├── 0a0a3e7deb624d067a679071673517d71d369e8f.nq.gz
    ├── 0a3e74f09f7a441d697b747e876f63a8181629c6.nq.gz
    ├── 0a593186c098ae3824ef994374686092f97ccb4a.nq.gz
    ├── 0a7024ed0e206b1610c4c3b5d2773b236396a9ba.nq.gz
    ├── 0bf247a6f322cfdf78ef56f993b2d03ed49425b7.nq.gz
    ├── 0ca03b8e607765cb41a69b608548b2a237b3cb3f.nq.gz
    ├── 0cb0eb30fa4ffca4ddf9de9222b8baab7368ab79.nq.gz
    ├── 0d415db04c8b544f518a2f0c1f20b3bb8b8e03ae.nq.gz
    ├── 0d5b13ded4966ba0e587bc968be5c687d6fd4101.nq.gz
    ├── 0d8e5d4acab3b69ad04e3a5e062233b5d8a04bfe.nq.gz
    ├── 0db3d2321e03bcff6da0ec682b6135efede274c3.nq.gz
    ├── 0dd021978a87e4f553ce75bd35da3d4c57e374a9.nq.gz
    ├── 0df9cc58ef30630588cbbc925995c2e264684360.nq.gz
    ├── 0ef09f214eaa6d9bca297988afc1454b5827b2c7.nq.gz
    ├── 0fb320dfba4b1826a11d86fb278d931febead159.nq.gz
    ├── 102bd3f793cd64ed642ef235914b24aa05faf367.nq.gz
    ├── 104fc5b552f8639e67566d9c064a19ff510c540c.nq.gz
    ├── 1117055ab8e8c90e1b200be00cddb78943616d9e.nq.gz
    ├── 124386803f142761528f710e77ae483f5f8c4fc4.nq.gz
    ├── 12a52d22e4c38c67a6a98b5b396e134ad3de94f8.nq.gz
    ├── 132032646ec65e2e60aa1e015af9082418924d5e.nq.gz
    ├── 135e7d66a4d0d91fbce6aa801b0902815f86c806.nq.gz
    ├── 137a64a1722352220eee524909ef631a37066541.nq.gz
    ├── 15027660a0f90d61f4ad8ac1ffd152106edfeeec.nq.gz
    ├── 15dad9be3ba44f7c934e1ecab98a93cb83cbc79a.nq.gz
    ├── 1602b3af51e0e891c1577d6cdc614583414826ea.nq.gz
    ├── 1632b2c8c6fe3e95c5780abb3285ce08f4bb4af2.nq.gz
    ├── 1783032defb549cb6e1bdf3e9f5ebd37cc2b34a5.nq.gz
    ├── 17a5a33f1e46bd3d53c57dc26c94e374e9aa184e.nq.gz
    ├── 17cb900c6f19443519f81b88ffa807d5fa7e027c.nq.gz
    ├── 180068d68098bec9c8e5b20a77a5e5cd28a0bb0e.nq.gz
    ├── 1804a8a305e776b78982fec14509e7140d168bf1.nq.gz
    ├── 192249d2b0d100dbc7030d733c2136cc16e664ee.nq.gz
    ├── 19622d249da62b5ba42b30ab91cd51f8b3a2810f.nq.gz
    ├── 1a937bc600dbd84ee9edce20dd89338567b1222c.nq.gz
    ├── 1aa7532609571c2422bc0fe4da3a871a2759c15e.nq.gz
    ├── 1bad6a0f648dccdbec523ca79ba90fbcfc806af0.nq.gz
    ├── 1bdac5d52715e2162067887b95a6b191ccfd8b05.nq.gz
    ├── 1c255451d538c64e1ccb01e655cf0e2049655384.nq.gz
    ├── 1c54e43664f4348320676d88e08d11428f9b5b10.nq.gz
    ├── 1dd9c37089906a6e8e44503f3b0089232e8b6fbf.nq.gz
    ├── 1ecb73756530d0fcdd87f668dd8385ebfbce1536.nq.gz
    ├── 1ed3e9a88b4972b33e04e678cc974b3d83f6b5c8.nq.gz
    ├── 1eeba24e97659d1047c0565afc4b67088d5d16f8.nq.gz
    ├── 1f431f87dee617cd8bef9a54dd4b0911601ec607.nq.gz
    ├── 1f77c0e7a0387150b561306b16531fac17a15ab5.nq.gz
    ├── 1fdddebaa08f198c91923b255dec9d1660c81021.nq.gz
    ├── 200fcc18dde040e6c35708d18927ce9bc522079d.nq.gz
    ├── 2065b72b9b9064b41cf08a589d21eea4290a8c33.nq.gz
    ├── 20a48a76d94acef9521a065f9a05b5205e8ecd4e.nq.gz
    ├── 20f7d7f3433f693b171a0fc6b06bd8aaf27d0339.nq.gz
    ├── 2257be8b7e64de4fe69ebf17ae2f513fed0e5fa0.nq.gz
    ├── 22e7cf6d88463c5b6774725e2b66ee1496bddd22.nq.gz
    ├── 23716990d2b4a00fed45ba741149ea90ce17e208.nq.gz
    ├── 23796225b19709f98f4b73b8ef4c21cdb6b2bbeb.nq.gz
    ├── 239b14ac3a9ae8de73122d1154bf0d71903dc15f.nq.gz
    ├── 23bbce4ad52aed902a31a09d99b8b43530681404.nq.gz
    ├── 24885ee5215f5b7f2c2f2a320749f3b11c87f4b7.nq.gz
    ├── 24d9d332883be1b6cebb6ff65437bc14cadd7b41.nq.gz
    ├── 26180651a6b23b012ea42f34a79aba719e4af491.nq.gz
    ├── 262539565de49f0778cd4dc606601d3b77286236.nq.gz
    ├── 274141f25833636ba2781193232d9c13d7d846c1.nq.gz
    ├── 278b813d2b718df1de549bfcfa613c52d9d9bce8.nq.gz
    ├── 278eca47773e67595fc602bab3e152db5b5a64fa.nq.gz
    ├── 281401ece19ba47c850d9851a3eb1a0bd6e6e551.nq.gz
    ├── 28498ba15cb0ca1998b2f4b937c6393b7fbd1536.nq.gz
    ├── 2880c183e22636411d91dfc48babf6bd2e6de658.nq.gz
    ├── 28d06ddc213012a7ff74f51cd71523aca639f147.nq.gz
    ├── 290e63f8ebe2917790b67568cefb231804a08299.nq.gz
    ├── 295bcbb8e025589d2908754dcae6e03a37dfe6bb.nq.gz
    ├── 29e5b5e1984a29d63749e1d1029148087dcae130.nq.gz
    ├── 2a109cabc240f871544e5ccc56ee5616794c0ba9.nq.gz
    ├── 2b562cb728f948a0a88d25d3db10a6e243549e35.nq.gz
    ├── 2b9b8b92f32dd88246c26bfb07c6261aac7e7eb1.nq.gz
    ├── 2c319d28185e89c12668675af82f76a69cf43b62.nq.gz
    ├── 2c8022f1668149e1c0b96e4bea650b1a671ee594.nq.gz
    ├── 2c877bfec52239b3c65fe1b4da0d44d26b56287f.nq.gz
    ├── 2d4a2c4c20624a35baa9565c742f038ce74f0ae6.nq.gz
    ├── 2e48b6c822653d1200f448f86a425d26475c8a39.nq.gz
    ├── 2e53b809eafb8be22fe59e9618dae0112a243b15.nq.gz
    ├── 2f8937a8cbbb5029d114c8a1d93d0deb7c8963a0.nq.gz
    ├── 2f9a91a553837be5d73174a265a9d687644b3fa0.nq.gz
    ├── 300debdc8dd4d74502c3af75f29ad9ebb1b14d1a.nq.gz
    ├── 304a5a92bcff6792bd850854758e43d21fb95fa2.nq.gz
    ├── 305cf1d17fbe8e5afdc95e2e5f97e59326a8b4ed.nq.gz
    ├── 33089ace1be88f22a10fe861ad49718d5d886090.nq.gz
    ├── 339d47bc69390593dbe6ed8f258ceeef613ba316.nq.gz
    ├── 34349080854b310a1db612a38dc8fe8ebbd01488.nq.gz
    ├── 34d73b3b167ad71a844c35d0a84a97ce5cc4596f.nq.gz
    ├── 37230651428136149c64e05b2e1d526554e71b8c.nq.gz
    ├── 3731c44bb96928e4104d56b3544ba5dc02e75197.nq.gz
    ├── 3805a8803ffce580d8082c4974e20d7332b6714e.nq.gz
    ├── 38eec85cfdbc6610bd269ad611330fd86cdf0db3.nq.gz
    ├── 391e1a3d648eefd175bcc1d68a2dcc3ec6753dff.nq.gz
    ├── 393aababb365c8c5f2a229c663b76d62a78741f6.nq.gz
    ├── 395764282b3a04ab22b84ac46959a2d06686df6e.nq.gz
    ├── 39a0957c4e220ff0dab7c9cc0dd4ff546da8a98d.nq.gz
    ├── 39b65c018321026d437a7f71ef207c90fc3d33c2.nq.gz
    ├── 39bd0c9f7fe30aea14eda194fee17703da4a4dbf.nq.gz
    ├── 3bde9becafa8a8abf38f53a0b18ad5aa42967640.nq.gz
    ├── 3c2dbc4bed50e5751e43749237191460df5c090c.nq.gz
    ├── 3ce82f4679651f79e991513fab8daade685546d1.nq.gz
    ├── 3cf680f69320a982d303a7376d679f522734c979.nq.gz
    ├── 3d26f4482fe3969b6de2b51bd1f85fc16dad6a65.nq.gz
    ├── 3dbc9c68c3c3e03b2ff6613d16b71d4a2d612b8b.nq.gz
    ├── 3f765967b82dc46fb5510306af2a788c3afde905.nq.gz
    ├── 3fc30c059a76572f449ca53f59aeff47bd789cf5.nq.gz
    ├── 4013ebfdcb4a754cb7232a4b75410ee19af07692.nq.gz
    ├── 410847b02b8263530c513cb4a86144b8791b953c.nq.gz
    ├── 41478957aca7a04b7321022e7d1f73de5badd995.nq.gz
    ├── 41a15eb54e936f396f3f74ae8d27dbbedec1abeb.nq.gz
    ├── 42c78d315be2a8cfcb4bef507ec9f6c5988488a6.nq.gz
    ├── 4385457f8cb707a5d0fc1bb56d5340cafe4a3d07.nq.gz
    ├── 445e22e976a27556afa03e4330e2698c3c0c3cfa.nq.gz
    ├── 447b4b9c96d4010a1d52feb3e9b1d333780d617f.nq.gz
    ├── 457cc9664640a35f255b7ffe51d8d1c5f317db24.nq.gz
    ├── 45f23792104f145a6d9484ec36f03ad5adac9117.nq.gz
    ├── 45f2e45ff129807f418de923230b513bff39a351.nq.gz
    ├── 468341111c1405703355f40223c1e5621878decf.nq.gz
    ├── 46ce5e4ed9c9195fa1d8ab3930dd37a364ef71ec.nq.gz
    ├── 46d2694b8d0a98ac8764ea16f12c6167af2665da.nq.gz
    ├── 46e34469a34f03fa8c12b7535307cc189997d14b.nq.gz
    ├── 4848d10d183a1fb1e21a35b631f1c68e6f678c34.nq.gz
    ├── 489024ab9380c5f41174958850adbbd9b5b91f8d.nq.gz
    ├── 48b1c3c75a4a624f57d3963dbe5a6ca861528e84.nq.gz
    ├── 4a2dafbb9a2654c92feff9b2690e5f9b34b4eabf.nq.gz
    ├── 4b505ec4daf4ddeee512b38d726bb49480aef662.nq.gz
    ├── 4b9082f0f9e93d532d4be11fe6b26639ee3df479.nq.gz
    ├── 4b93bd1f83c2c33296efa61ed7a95cb6662d0c22.nq.gz
    ├── 4ba1255b61236f91346afdc6772bf7c9e71a19cc.nq.gz
    ├── 4c2edd2ac5f0c86ea289b8c5f4d5862c203ff25c.nq.gz
    ├── 4c98dda9855a37f8efede293e7666bc9044d9136.nq.gz
    ├── 4ca0dda114edc91a7e8ed3e69a08a1a3eafe66a0.nq.gz
    ├── 4ce1e59f1334dc4ce787ab3065c7ec947869553f.nq.gz
    ├── 4e1caa3be3ff5b7ead5c6807e8318783c8435e7a.nq.gz
    ├── 4e93120fe19a8dfe3443e791bff8d60350908b8b.nq.gz
    ├── 4ea10761c45228f10c8acb42ce7cb48eba5eede8.nq.gz
    ├── 4f2043b87c41c2ad5b7ae6439896e4e052f073de.nq.gz
    ├── 50560137fdc0f715d8c113ef56173e97dfe1ec61.nq.gz
    ├── 5187ed8ec07d1ebd08ed555c43932b63933ddea1.nq.gz
    ├── 51bb5a9f61271b88e96b0385738cc818032fa0f9.nq.gz
    ├── 522f737b9ad4eda2d45751159c30393a5ad8d11d.nq.gz
    ├── 536f21bd805b150b6081418c9b6e78dbe14fdfbf.nq.gz
    ├── 53ee8fae46dd2ac38244878b5ae68142de3cc1eb.nq.gz
    ├── 54b8d243e40b5f288090501ca79d71aef23a9e38.nq.gz
    ├── 5556fc54ee4a157f76fb47a2968611bda1d2d7f4.nq.gz
    ├── 561e15bb73d63ced108e80a27dff7bf40a5a7697.nq.gz
    ├── 5764c4775aec451d115d573965bf82a6d8414a58.nq.gz
    ├── 57e151f53f63b9af52f3b7ba9355e1b3e223fc93.nq.gz
    ├── 59c64a74c15503cf19952dcb055a557c601acfc7.nq.gz
    ├── 59cb9347339bee3f1ff2b3ccd202f142b410b7e8.nq.gz
    ├── 59cfde1d7cd3f0472e5ba5449bc4c2e48791a315.nq.gz
    ├── 59e55fbf6b5c29c18719f28302063c305ba605d0.nq.gz
    ├── 5a971e816687c77e32d686217e6a70bbec7ae83c.nq.gz
    ├── 5c7035b839d4e21adc9d463da2d4f42f1856b531.nq.gz
    ├── 5caa8c88713d2088c9c4c728dcea3e62236cf4e4.nq.gz
    ├── 5ec218a49f0d657f9acc2f374d2f42edd0a97d98.nq.gz
    ├── 600a378a333f89789728e665aa0c0c8b98f52456.nq.gz
    ├── 604f74b15e06270b0988d72b0a712f40844ee0c2.nq.gz
    ├── 605d0eac6f871cf0aa98227494939ac96e524e7e.nq.gz
    ├── 607199eb62a82238d1f74175314c933ba4679851.nq.gz
    ├── 60db5f27b9a25f2f8003a87e6936557803439c0c.nq.gz
    ├── 61381ebc11936e9fb0a284d9d51a46b60510346a.nq.gz
    ├── 61510add89a5dcf3a2d294a3e51c8cb5fc4b3b23.nq.gz
    ├── 618816638d112d1003a54fa1b5cc9a310e29cffe.nq.gz
    ├── 61d15d77936bc8ebbf965f4478185e9b4233caad.nq.gz
    ├── 622f6ddf124333c0376d2c5921f341ddc51a9d4e.nq.gz
    ├── 6246844db5738c7cc6807c9b221544f6939692c6.nq.gz
    ├── 62e34a247e98e1565d404d18d4f2164d616b26dd.nq.gz
    ├── 630c5ebbde9b2543189163f33a5ac31539dfa697.nq.gz
    ├── 631f412471e9e1453266173748c46e4cfcf939de.nq.gz
    ├── 633bab4fff5d6303d902ac8365f336f65778f699.nq.gz
    ├── 6456b722ce5d5572682278792dfb5d145d774599.nq.gz
    ├── 645f3183cbb0befac1bb776f6886d257330c5cc0.nq.gz
    ├── 64f52c73b7ec998d42d420d53890184bd5a40428.nq.gz
    ├── 651e5256b414f13b4805fa4e976eb25ca2c7e10a.nq.gz
    ├── 652bef03f344c200c6e110cfececfb33ae941e26.nq.gz
    ├── 656cd8bc7155f196975c4005b022c2decac9a846.nq.gz
    └── 67afe84b9b539021ebd1f1bf3ff6b63e15fd4a69.nq.gz

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

[huggingface/trl](https://github.com/huggingface/trl)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
