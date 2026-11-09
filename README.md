# Repolex Knowledge Graph of twitter-archive/gizzard

RDF knowledge graph data for [twitter-archive/gizzard](https://github.com/twitter-archive/gizzard), parsed by [repolex](https://repolex.ai).

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
rlex download twitter-archive/gizzard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b84325490185f1fa29cb4c9116b39eea374f345
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b84325490185f1fa29cb4c9116b39eea374f345
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bad9f0bd49b3731d158386fbc390cac173c89a.nq.gz
│   ├── 00c59c4033e63f8adf5cd048e966d97d57b439be.nq.gz
│   ├── 04f2a2abd513183dfd49d1c4d2337b3126fc739b.nq.gz
│   ├── 07d995bb21bff85a75c3f52313eecaa74e5c7db0.nq.gz
│   ├── 0891d4197295a2f2419cc93352adc7ed330bf567.nq.gz
│   ├── 0db5d6beb31f25f04af554348c94872568b8be53.nq.gz
│   ├── 10b72eaf3e8d900313df1f6314ec6d1d68f77518.nq.gz
│   ├── 138afe90bb3e7ae405f3df19d7823b11cdeb3505.nq.gz
│   ├── 13ff6d9be9d20a15636e3bafe3ca44561ca045fa.nq.gz
│   ├── 1602d54675a5dfb3ac9ee2ff428f92034b347f64.nq.gz
│   ├── 1b8f6c086254fb49e6db1118d6e321ff9343adfe.nq.gz
│   ├── 1da85f3ac337ced0a0d93e97f5b383848717fc5b.nq.gz
│   ├── 1dc7dd0a6076a54aff27df312e2e7703cdbdbfc7.nq.gz
│   ├── 21b2f183dd28db0fe915da2516e25f1aff8fcd81.nq.gz
│   ├── 2786a66a9255d0dc7336a25c17fa77a501fb38b2.nq.gz
│   ├── 280c595d0bfe172706e3853be1803a7950032185.nq.gz
│   ├── 29834bfe0ef427ee609954050f23e2907535c864.nq.gz
│   ├── 2d63d69f0bb83fd5c45a7940c7befffe7397b291.nq.gz
│   ├── 3167acdbb141c357a6157a50aa703b8497aa224b.nq.gz
│   ├── 329cbbf4c13ae2e8c3b92a2435b47274a4118234.nq.gz
│   ├── 3495c3bc5ebaa7eee27306bbac54779ae1fcda83.nq.gz
│   ├── 34e04af0f7b454ed75edee08d097a29e4f6a93d1.nq.gz
│   ├── 3600a6f54ac3013758aa683ca4f445a7820e6716.nq.gz
│   ├── 382aebd56364fb3b9f1123cf3fcdd89268464099.nq.gz
│   ├── 38829b508afd00f7385bbf5b5bddda836c010ba5.nq.gz
│   ├── 3b06febdca82b77ab40f1d813f0083d02c5c5fcd.nq.gz
│   ├── 3c356bb9ce7d75978b273f80f2b23180d4088ba3.nq.gz
│   ├── 3e74810c1a556da11b8c8f18b3596b75c2045f45.nq.gz
│   ├── 3f4dbb11eac77028eead4359d5e31b3297512d25.nq.gz
│   ├── 411a9e7a0a3e1aa5c19ecd62b1b148b1c66a1372.nq.gz
│   ├── 4378d9293948bcc3041a1a5c0fb732a3cce87f80.nq.gz
│   ├── 4473bc5d526421c10cc887012befecd5e54a463e.nq.gz
│   ├── 451b8830c837343829bca55b7f01632fe6d4bc48.nq.gz
│   ├── 452dfbfe6f9a0058fc8e5de48266f79292713234.nq.gz
│   ├── 45ca6ec903cb98e86666e7e4a252f366f2a09b44.nq.gz
│   ├── 46e3897766cc88949f72220ee64253521d86bb3f.nq.gz
│   ├── 47178d638479da240ddc0d24c0eef0ca2fc17fd4.nq.gz
│   ├── 48093c383cb9ead30790868dbe4e20057282f8bb.nq.gz
│   ├── 493b4f76d8794579ad10e6d2de083aaf0ad3840a.nq.gz
│   ├── 4b615d31699aa2ce850139ad0019c9833227f21b.nq.gz
│   ├── 4d7512d433b62b9286c8a1ccd1bf3af8dd32c89b.nq.gz
│   ├── 4ec6f5df1d3dca0a4d57489f6bc9fd122e631c32.nq.gz
│   ├── 538d82219d638a16192d6ca8c223952b54a2383c.nq.gz
│   ├── 548d56988b05330f70ea70c7f2175956a0229e78.nq.gz
│   ├── 5ab69529464314e0157d1b68607a85bb802b9255.nq.gz
│   ├── 5b758839d8d67842df004b4d6d1ee21650f250db.nq.gz
│   ├── 5c17416bfa6e358b98bf2191965cf2a46b0c2433.nq.gz
│   ├── 5dc9ec4329a06604765f993aa20d23fc8e51d4c4.nq.gz
│   ├── 5e21bbef7fa11840a144afa77f0d2ad92c656eb1.nq.gz
│   ├── 5ebe5d4f56714e8c0d573665fc1ccdfff9f6100d.nq.gz
│   ├── 5f63a6f296f607fff70736b3f9f161b7cee94ecc.nq.gz
│   ├── 6129bfbf1de6f2c13c218d39b3571fffe4ba7202.nq.gz
│   ├── 61a8c0fd783014949da8a4f6c31cc25d03a3753e.nq.gz
│   ├── 64194b9e09308955f9546844ab14679020ba77b5.nq.gz
│   ├── 64ba917a7b1388abcf301e5b0dff2889446ccd9b.nq.gz
│   ├── 6bfa7126fc881e0501ec1d2b3f9230a6b8dc845a.nq.gz
│   ├── 6c2efd437748138157fb6b40bb97e885ea06738b.nq.gz
│   ├── 6cfac0c22f8dea6e9d38349761eebe880ce589db.nq.gz
│   ├── 6df0db8a91dd7bc455b8438622ab7d8b76941f15.nq.gz
│   ├── 6f2daf6b7239d0b28e04b9d954009d5b44552a02.nq.gz
│   ├── 70ed3c18c0fcd7bc852881d5aea298f7b991ac51.nq.gz
│   ├── 776b310cf1cf475a114e8bff44323c7df01ef77a.nq.gz
│   ├── 79fd72cb4f9d68cf7d6a11883021ee2f51d48cc3.nq.gz
│   ├── 7ac05f2be571b681f66b12c14e42fd714b3acdd5.nq.gz
│   ├── 7b70c3744f8deb33a389167e7972adab8b37f613.nq.gz
│   ├── 7d1a1eafe8388fe3eee7f4998b1710bd3420183c.nq.gz
│   ├── 7dd346b472d0a353ce284cc59df6727717bfbfce.nq.gz
│   ├── 805068e2b473f266f646e0d32b46fc8ce8466df0.nq.gz
│   ├── 8165c7fc952b2b506c4dcbf88608e1090e5c77ab.nq.gz
│   ├── 818c3c50116c11e08e224f8cb668fa6898d459ae.nq.gz
│   ├── 81d77bd692e3a70079b1db90f511a600db6ee891.nq.gz
│   ├── 82ccbc51a56a1553326c53dcc992d534dd5448a6.nq.gz
│   ├── 83465e498370b071b3fa02f5d23c01dd871b734e.nq.gz
│   ├── 8452460070ce19057d6db62b661eb29a9ae03d24.nq.gz
│   ├── 87037f505a9594f6b0d0d30b3e40876b445a48cb.nq.gz
│   ├── 89c3e7e9a39feffc5b2d658c02c3135a4cdf3728.nq.gz
│   ├── 8bd5db7a4adec5a431a9020069e1b6e3e70cf049.nq.gz
│   ├── 8eeda3fe8b70f0d7b57b0fdfe979012ed3387808.nq.gz
│   ├── 933b2f6098bab086eeff08413db595a107fdbd38.nq.gz
│   ├── 93a7e1de766aacbf29f7b47b672ed040ddeec3a2.nq.gz
│   ├── 959fdf87d9de3e6e0de8a06151da77a14ac4013f.nq.gz
│   ├── 95d59ef3c4d7939ac360e59031e43ecf64d0808b.nq.gz
│   ├── 972f1d4fd3470150192d22944901ee1c682bb0fb.nq.gz
│   ├── 998f61d5cd6bb53b623588984de87312e0cac17b.nq.gz
│   ├── 9a590df03c62d7a02efe951a7f8daa059a7f1676.nq.gz
│   ├── 9e72550f1d4154a63635b6993cffb33b64d6fe7c.nq.gz
│   ├── a027ac967139dcde724b330ece81e5e0218fcafc.nq.gz
│   ├── a3db72c53a646876af5387bffcd13197a7fe6ccb.nq.gz
│   ├── a4f9c35329486ade671eade136616313ccbf71ab.nq.gz
│   ├── a9b28083c366a52e74de70df1a8b737d9763ccd5.nq.gz
│   ├── ae29b3e4e3dffcdaffa6fac9c56027d9b55f9830.nq.gz
│   ├── b15b22caa94e1177253be2c981b698487471b9e5.nq.gz
│   ├── b278990f19be9b8fa196ad301da4df62e62d5401.nq.gz
│   ├── b38351ef0aafd610c92818ebedef23ad3ce861a8.nq.gz
│   ├── b6f303ba3609998075b526594f761e6f619a0b2c.nq.gz
│   ├── bb4477e7c9c806b91bcd1da3e638042d29ea5f5b.nq.gz
│   ├── bce0833b0480f30cc623699eb728479e905f46a4.nq.gz
│   ├── bceb76bca0f57a46ab8abd47b63a03535b90d2b7.nq.gz
│   ├── bd1f59bcd0666bcbb437dfb9ab75b73c9578ad29.nq.gz
│   ├── be0d65bf9212808aa539b8e6924ac87ba2aa0066.nq.gz
│   ├── beb2357afc9e100aeaa9bcc48d1a1ad9dc4be9de.nq.gz
│   ├── bede1d0751da9ca864694fd20803b6ff5cf8445e.nq.gz
│   ├── c196f12974c3db1e2f6b2edb7dc0455f1f37c18c.nq.gz
│   ├── c4a1c4ff634a549d3c5e4c32605178314932fa26.nq.gz
│   ├── c508b1cba40c2dc058a7059aaa89df9c93f41113.nq.gz
│   ├── c6368598f97965424db8e7f2aecef317535e4bd4.nq.gz
│   ├── c846d1198f5fa8ce2bb22c9947b98492924009fc.nq.gz
│   ├── cd86f32aa91dabf20b3cb0c46243676a44eaa6b2.nq.gz
│   ├── ceeb0ff2add21050f7d2d6ad163cb8557d1d918a.nq.gz
│   ├── d3b9e20ce8a479a529658785d85f306a155987ae.nq.gz
│   ├── d4187f569846397565bd4384a8c8b6e3319b9971.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7e8495f8b0255a9eef2e36c6e1c9c8f9ed93162.nq.gz
│   ├── d851208408e88628b66fa5239fc7bbf23869c779.nq.gz
│   ├── dc5213887f6545fbb7fa9a850d58997fa83892c5.nq.gz
│   ├── dc914053b9f862a09640cdb2ca53a3435f3ded72.nq.gz
│   ├── e04ca248fd6037a8440b5c1e2b6a9a8af35efb60.nq.gz
│   ├── e3bbf6edfec793a742f68c313d4c97d2639e7fd4.nq.gz
│   ├── e4c555dfccef71b1b0647d602a0ee6fe4323e794.nq.gz
│   ├── e4f89875106fd5c26adba4229d66e35fcdff10cf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e2d525143c5100e3aeb4deaeee05a1ef8e5d9b.nq.gz
│   ├── e8382c266fafd2e20a75a9cd9273f8c1c3896801.nq.gz
│   ├── eb82f157f0f8b74fa9243606ef342e6d963b4ab7.nq.gz
│   ├── ec17c06a598b58d2733248d208c05231ca0e3183.nq.gz
│   ├── ecd66d5a70ae75efb6221f0f2c9b500eab3deeb6.nq.gz
│   ├── ed1b0eb11f8462e4fc5a0c3e754ddf987d8dc6b2.nq.gz
│   ├── ed613aa837eab954f362dcacf7d6f11f7bf9ec65.nq.gz
│   ├── eec679e681c6072b8e1501794a1c7c14b25e2be0.nq.gz
│   ├── f056e195c792f70c7a769962ca8d20ba965739f5.nq.gz
│   ├── f1bfd19c27fdc64d795d0b2821e3547f3a3b38d1.nq.gz
│   ├── f2429dd3ac658e8fa055978d25320b446fb08c8d.nq.gz
│   ├── f315d16abf3a38ebfda7ce557ec05296bf7243ec.nq.gz
│   ├── f917adb0a577b5cfc18efa2a8acca626bb055f02.nq.gz
│   ├── faacb284b9129e6bd5d592c635d39bdc636d4ffe.nq.gz
│   ├── fadc906119dd410e205db23e2744989c1b2b3f90.nq.gz
│   ├── fd75d571b03c5d9c38635ee92175cb92383b54a5.nq.gz
│   ├── feb96b91b668d6f49ced2e090b6a20c4e96006bf.nq.gz
│   ├── ff14b1b0ac9c8ae612c61a0d2c4c9226a966a5be.nq.gz
│   └── ff3d35006ef09bd8d5a0f4bdad444849a57cc7bc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9b84325490185f1fa29cb4c9116b39eea374f345.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 147 files
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

[twitter-archive/gizzard](https://github.com/twitter-archive/gizzard)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
