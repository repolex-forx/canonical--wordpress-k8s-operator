# Repolex Knowledge Graph of canonical/wordpress-k8s-operator

RDF knowledge graph data for [canonical/wordpress-k8s-operator](https://github.com/canonical/wordpress-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/wordpress-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b93fa19e0de3166b1c183afd2e0de95723259cb8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b93fa19e0de3166b1c183afd2e0de95723259cb8
│           └── chunk-001.nq.gz
├── blob
│   ├── 02361050a74f8c7508cc12ed3d26ae641a0352af.nq.gz
│   ├── 027c7c721cd8b2065f6d95b949b4590b3d0cf246.nq.gz
│   ├── 034ce2e480cdccffc8d0c7775e6fa30f1e039ff0.nq.gz
│   ├── 056c316370b0d4c0d7d830d8db4e2d7d5f0dfedc.nq.gz
│   ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
│   ├── 0a2c04cbc9e05e705229a35350c8c76e4156cabd.nq.gz
│   ├── 0a548e2a512c06522f9bebf649f9ae50d3dc6391.nq.gz
│   ├── 0c2958d2cd1a885f2590ac56995bb792eb0d753d.nq.gz
│   ├── 0c34ad4a1da9d5f33fb47b3226ca48449d6527e0.nq.gz
│   ├── 0dd95b16b6251f98de8dc9a17e916f42bffd12f0.nq.gz
│   ├── 164099ca2ed0f18531d4ec334f71dd33c490c8aa.nq.gz
│   ├── 17b5e6c699f1498a743bc9ed7c7970fb22cce6ed.nq.gz
│   ├── 17ca0f16a546e6b03826a7dad2e5e4a3e74b4895.nq.gz
│   ├── 1a2aa96722696eed44c76cced6a38c9bde23fa4e.nq.gz
│   ├── 1cc39a6643c3d4bc4eae244e8106fbf633488c44.nq.gz
│   ├── 1d7b9e20986f9f79f572af6e19602d0c7e59122c.nq.gz
│   ├── 1e00afc0a50eb02cfcad6e6bd6f54aa292fd4706.nq.gz
│   ├── 1e579b7a6dd83726ef55b861d65c6571e6c03f4f.nq.gz
│   ├── 20c662dcbc07888afd08c48da971b62e306eb716.nq.gz
│   ├── 21ac729f8fa458952c070a3cf1ab27a96178c588.nq.gz
│   ├── 245e7e5db0f5ecdef7eb50a2eb9579a7c63e314c.nq.gz
│   ├── 25fbdc7166e749e1c716aaf808f83c32283cf20b.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 27fe6c118a85c69a225679690768a44ec1ccdcd3.nq.gz
│   ├── 289a52458f05b4f3fff035e0525fd0f55ad6dee1.nq.gz
│   ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
│   ├── 29ede242ff455a64fa253000d80487a0bb723248.nq.gz
│   ├── 2ab05315f7081ad25b98a8a232803311cad17a95.nq.gz
│   ├── 2ba1c229d81b8885f67a041f9012a9fd8855f7a3.nq.gz
│   ├── 2da96c2ab5d32dede7961fdde481ae4a6164ed63.nq.gz
│   ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
│   ├── 2f69dcfaeaf523b27591891bdf859ecd55e160af.nq.gz
│   ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
│   ├── 307b5f2ec4afd37039c61500decced8f538bc94d.nq.gz
│   ├── 30b1565d422e9a0621e35437d4d08983716aa492.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 35e0b944167ca011872081d2a0f182b5dd81838f.nq.gz
│   ├── 365062213e224a64f9b2f5683e13a199652ae5d1.nq.gz
│   ├── 39759b2cf8e54d854d32c36adac311f64dd9f445.nq.gz
│   ├── 3edd092d9c2cfd6bae939f5568f8d1b4d3cf5618.nq.gz
│   ├── 41e12c644e392108fb89b54bfd8b48ae9aec7dd2.nq.gz
│   ├── 466959f368ba3d862ecd34a1670664b822426f87.nq.gz
│   ├── 46e5742588b0d14c9f425c96849ca80b65d26e4b.nq.gz
│   ├── 48b6e5573b112678e55318e409957bafb195200b.nq.gz
│   ├── 4a4b019744c64680c49cf6b77ae6f8325831f867.nq.gz
│   ├── 4e0f2d0bf0a11dfb1e98baa3454fb750f41e3eec.nq.gz
│   ├── 4f13f0380d610d4f0d7d0f6868fefe56d5f1841a.nq.gz
│   ├── 53da00e6d6a399a02e62d3236f8930b036f771d5.nq.gz
│   ├── 5500f7b0719285d235a87b2f8ff6b1b8cf60a252.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 56a6051ca2b02b04ef92d5150c9ef600403cb1de.nq.gz
│   ├── 572718d72ed437c971dc76244094b261265f229e.nq.gz
│   ├── 57a558871fbf5bc3cd26fbfcf79a645c3f9b948e.nq.gz
│   ├── 58635ef27438e7e20942d71a1575ee10d8318243.nq.gz
│   ├── 589e7f85eacf8090fb542b971227b9f01ab5b2cb.nq.gz
│   ├── 594219187478c3e85838d9695b753d4884cd1d4f.nq.gz
│   ├── 5e71dcf31acaafb3cf87fd190713c0833bfe8e8d.nq.gz
│   ├── 613b9a3c3fb2a70513b9c55ffc583b05dcf1aff3.nq.gz
│   ├── 6193124bd4e0b3c37b622868dbca380b20f72e0b.nq.gz
│   ├── 66a1ec97048795efaa420125475e9555721a75a1.nq.gz
│   ├── 6873579f069a531c09d46741dcf4666dbaa37bfe.nq.gz
│   ├── 695ca89d24ee8df92808e240d3dbb5e4151ac45a.nq.gz
│   ├── 69dfaa762fce02378c5564869a3790f1905bc401.nq.gz
│   ├── 6a8cd1b34d50530fa03bb91bbed65ad0b377486c.nq.gz
│   ├── 6b93d6e72aca3992a70b944921ead6ebf0ae2fae.nq.gz
│   ├── 6d24ffe09c47839331dfd25ff8a086437a505be8.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 71ab28569639b1de2c2f4585580a77206f762779.nq.gz
│   ├── 71ea0873179ea5a38452c9e24b00e2613f5bf4b9.nq.gz
│   ├── 71eca3fd2222d3c7b43c12ec3fc6a1f3c20348a8.nq.gz
│   ├── 738011e88726a3a81b5acf2c09039d5fa678553c.nq.gz
│   ├── 74d7dac769c1157af67eeecb7d408e8a0d844248.nq.gz
│   ├── 75bc79981d90ce3109f3e6af32397f190d84ea6a.nq.gz
│   ├── 76e072066c25dc8b8c0c0011f8e19031d22958a8.nq.gz
│   ├── 777878af16fb132db4a8621fa871ac69002aac50.nq.gz
│   ├── 785a19e711cbf29907d2744aceb2d0a9251bbf2e.nq.gz
│   ├── 79a734cf55e18661f3b6d38fdb333eae6b18a2b5.nq.gz
│   ├── 79f3c499d44849aff119ba76c68a9b7efc7648d5.nq.gz
│   ├── 7e9d50461abcf8053278e38c1eb264abc49fac0d.nq.gz
│   ├── 7f40f2345bb064efb497732cf5667f92948f6e09.nq.gz
│   ├── 7f9987b1745bd7f5a53ed7ac96317facad45090e.nq.gz
│   ├── 82ea0d2b212d4e47db75bed4f3cf1f82e9f0db22.nq.gz
│   ├── 835f5ec520611812dbe8cab235f766d88242731b.nq.gz
│   ├── 87b01cd333717462738c41d8247bbc26344ade78.nq.gz
│   ├── 8987eedfdaeafbbe8f1b8f42a08db2d56bb8b456.nq.gz
│   ├── 8ee0ddf304e57e7fac257ffedbf3257e13e3caa9.nq.gz
│   ├── 8ef26f799f562ace11cdfb3ba25c6db6b01248bf.nq.gz
│   ├── 8f854010aecc2eccf914b7dffefc3695e491c75d.nq.gz
│   ├── 95598bebc4a7413975a88385a141e978aed6220d.nq.gz
│   ├── 970bc54b2bced7ee0b88d90f63c6ff62ba551297.nq.gz
│   ├── 98a9805be2ea9036836696a792ae711103e01d2b.nq.gz
│   ├── 98c7e34748bbfb8fdd3eccd9654e472c8b7e7bfa.nq.gz
│   ├── 9c0ad390e5438a749fb62d57d47e53880c5ee735.nq.gz
│   ├── a13bbd87fe59bcfd1e5b98c7d64809a0d493edfc.nq.gz
│   ├── a2ec38ec4d1f71c31a803e808131bcb1c49095f8.nq.gz
│   ├── a587d8edc0c6419a2de7aa1cf038be8f48e35864.nq.gz
│   ├── a59351ac5646b03e6d3baa9e15f00d05f65ed15d.nq.gz
│   ├── a5b6b2310aba047cf5c53afd2ccf1c7000436ee9.nq.gz
│   ├── a680c956e2de688d56dbf446360714f6e105cb3c.nq.gz
│   ├── a8573bc83fa3e298dcfeb0c60695613d9dca7806.nq.gz
│   ├── a93cd50ad0a57abc048581807d63fbb0d9e84bce.nq.gz
│   ├── ab31b258ddb18365befa7cade83679f262904d79.nq.gz
│   ├── ac4ec0ba8db5c81f0c79f90f8a2d83e046c38143.nq.gz
│   ├── acbb6d3e95bfd5aa6069edfc066cb690becd9e20.nq.gz
│   ├── b075f8ccf29047705eba9a9747586eda24d9cdb5.nq.gz
│   ├── b09404ae6f93e66ea326ea68268b6c34c7a62fa8.nq.gz
│   ├── b10f897e6665bbf1c9e707056f9cf8ff0b24931b.nq.gz
│   ├── b266dffad05f518e55d986d6eafaa1d15e346ff2.nq.gz
│   ├── b74f44b6373e3da3d9820771daf0551a79a45538.nq.gz
│   ├── b87896e7ea513ca11753f260c5dcfc39a30199a9.nq.gz
│   ├── b8fda6c7a611ff00889e44a930a81d9b0a27d12f.nq.gz
│   ├── bbf9af1d88b02ad98188606e19067d2848ea1a3f.nq.gz
│   ├── bcf14e045e0004b20ad10981faca2dfe88765965.nq.gz
│   ├── c1c5afb9b8d5ea51f57bdbd1e1e835206602707e.nq.gz
│   ├── c51f8731433ae312f489f87b230c5aa38ef668fa.nq.gz
│   ├── caaa4a2cc1371c390813032745069c2ae2292c8b.nq.gz
│   ├── cb1719b3eeca4409de6c577fde5f420124dd048c.nq.gz
│   ├── cc2172f06ba14694c9cc2c6a880a221cf637bd9e.nq.gz
│   ├── cd5ac039d67e0bdadb17976e4ac39f0ffe6bb6e4.nq.gz
│   ├── cd9e108a8d6f7c890dc88a268a7f2fde0f891413.nq.gz
│   ├── cdb8291013305111d5130a423200ad3e07a9b517.nq.gz
│   ├── d3ed02fcdbaecbe70c51d1ab02b077542455944e.nq.gz
│   ├── d4eadb6480387a9c9b7e7cf30919d1220902169e.nq.gz
│   ├── d531959f31e2688a5d229868db28d69fd688421e.nq.gz
│   ├── d57d5d6d47ebd8c33c4015153c60f6c30195b00b.nq.gz
│   ├── da81d4e4cc0612e7c75fbf3807d8e1888a6c1fab.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e3979c0f638ada75e933f2f081677f84281d9dae.nq.gz
│   ├── e5a8387d8f0e20481e333ede48d3023bd88cc930.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b483f5a95e530068753fe3301df407025b4acf.nq.gz
│   ├── e6b6dda1fa9ed333dcaebccf2e0e870c36324bdf.nq.gz
│   ├── e9cacd3cd45a6e2c609eb36ad07cdc48fff1324f.nq.gz
│   ├── ea8e9893e50a9433d0f1bdcf6999853d77cec35a.nq.gz
│   ├── ead4708dea56e7d77b95c10e3e71a9f65626cc85.nq.gz
│   ├── eb5545ffa3cc29ed5f25784c1e4fee97f8803318.nq.gz
│   ├── ebfb77b347949be9dbef1af2aa43642dec677ac1.nq.gz
│   ├── ec235d43798f66bdcf0dc657fcdba6be2473eca0.nq.gz
│   ├── ec26cd6741bbb64e3e4f5fcbb4b5e71903a197f4.nq.gz
│   ├── ee516f0147be3b5e4afce5722de154a980114eb6.nq.gz
│   ├── eee6210edae9929438c941c580fa4929f1b3acb1.nq.gz
│   ├── eef8fff6123b4345cf53258131240c884a137f41.nq.gz
│   ├── f0a036ef9c7046ee5a1bd6995c6520955da2f67c.nq.gz
│   ├── f3aa1aa1fedcf21a9375f5fe1751a8f8156c5824.nq.gz
│   ├── f4a65fdd7c0714cb6e6d8696295f9c0110a5e870.nq.gz
│   ├── f71b17fdbd9f00e4a2f2fcf827b8603c0c52c0e6.nq.gz
│   ├── f99cf7ab7fb73581c23e65936ba3672ee3e84dd0.nq.gz
│   ├── fb99736892f68a3cba7510075d648c46f58b5e01.nq.gz
│   ├── fe3518b0772aaeea4b156d5d8453f58c15b3ab96.nq.gz
│   ├── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
│   └── ff98e5b2548e744a2f4881598b8c45285937df1e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b93fa19e0de3166b1c183afd2e0de95723259cb8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 159 files
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

[canonical/wordpress-k8s-operator](https://github.com/canonical/wordpress-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
