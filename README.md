# Repolex Knowledge Graph of apple/python-apple-fm-sdk

RDF knowledge graph data for [apple/python-apple-fm-sdk](https://github.com/apple/python-apple-fm-sdk), parsed by [repolex](https://repolex.ai).

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
lexq download apple/python-apple-fm-sdk
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d56a2d9432a0ea71c939e7357a5c4524730bbd3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8d56a2d9432a0ea71c939e7357a5c4524730bbd3.nq.gz
│   └── repolex
│       └── 8d56a2d9432a0ea71c939e7357a5c4524730bbd3
│           └── chunk-001.nq.gz
├── blob
│   ├── 008327f32fb813676c6b41464d100d134e77440d.nq.gz
│   ├── 0a7a532333c383f10ad7a923ab463a8b7e8f6339.nq.gz
│   ├── 0bf11c38d1baadd56735b831399d8377ea3eab9d.nq.gz
│   ├── 0ca8beaf67c39e6580cae12aae8df58323422628.nq.gz
│   ├── 0cd0ccec9d7651d856508e29efe9291f1ad0c5e4.nq.gz
│   ├── 0d5643ed86d6a5392bd11378e2eb108cdd5765f9.nq.gz
│   ├── 0df35c52a5722de9edb5e1ff37535d10b1db4466.nq.gz
│   ├── 1262e0a596e138a8de4a15d0299c5ca3ec47a9c3.nq.gz
│   ├── 134346b9d9857eee1a02c20e5543c5c283672731.nq.gz
│   ├── 1352e2e37e72f95a9bf76cfa43603d0187e63f7d.nq.gz
│   ├── 142aeaf1c2b374efb922e85401af697c7eb27f53.nq.gz
│   ├── 1bd4060c6284998f094c373bcc35d500c00f3e10.nq.gz
│   ├── 1ce37b1daa46122b729c2df5e7d56bdbaac796d0.nq.gz
│   ├── 1d5630aed44ffa80db466b52336e24b81d708d1f.nq.gz
│   ├── 1f1634df2d18c3d55aa90921546cc0ada75be0c6.nq.gz
│   ├── 20d919f549cdf7f75e0b25d87dc09e1b663d0855.nq.gz
│   ├── 2bbed7d7662c1a7faaa2441cfadaacef95c8e589.nq.gz
│   ├── 2c7ed6c2b3f06b1cff29678294c7831838ac50bd.nq.gz
│   ├── 2f7c6f65d1d8b944d711de9f3eaa01df50076ecb.nq.gz
│   ├── 355613b3bc3eb0965ba359e7bea108f8c3ef80ce.nq.gz
│   ├── 35665dce33e643549ca89eaa7a34d446f9b3fa08.nq.gz
│   ├── 37e5a119d6ef0cc12d9e946f9fad165740bae584.nq.gz
│   ├── 3848a05b255f99ffed56fdc7a8c4dab528344017.nq.gz
│   ├── 40a867915e59d4e41adc2521f5b490f2b0736ff0.nq.gz
│   ├── 43425ef33f2ba3d6df3d29e43fec1314c6e595a8.nq.gz
│   ├── 43a82f9a6ec47f12a9f41a4688b3944acd5de62f.nq.gz
│   ├── 46f74503ce653e0573802b11577fa39395df846d.nq.gz
│   ├── 4b1d7d92fe5d2f8d5a421998b8b83b017fda542b.nq.gz
│   ├── 4b43156d8f7bc872d5503b6a4911b3e1e22abe89.nq.gz
│   ├── 4ca4db4a1dd34bf26a33119c01763e6e4cbe4cce.nq.gz
│   ├── 4d693485662c2f543865acff96b8449bcf4678ba.nq.gz
│   ├── 4e7ead9c3af757cdff4e306d34aecfa402746201.nq.gz
│   ├── 4f42478ccda4506823e407d671690167b49b32cd.nq.gz
│   ├── 4fb507c9db9e8cabc1adc7eb1f6670297cd38cc8.nq.gz
│   ├── 5692a0690e7ccd5cf05ed7f475f2d059b64961e4.nq.gz
│   ├── 59a3ed5b885c392a5c378c87d84d88aa8ae4a7bc.nq.gz
│   ├── 5bef49fa9c06513440f5cf8fe9875a34590c50d6.nq.gz
│   ├── 5d05329b2162d62b4f430a0eccfd574786fdbf58.nq.gz
│   ├── 5d9d59b0768e2e167518bc4195a7809683edcbd7.nq.gz
│   ├── 5f06d2ee905bdf939c123d645bb005cf1307894f.nq.gz
│   ├── 5f3ff4c7859c9b8af19e2f72d69ad2ad478d116e.nq.gz
│   ├── 60b58ca131b758ecf392bcc5563e37d2277ff237.nq.gz
│   ├── 690c6179a94de5b294682eecc3f07c33f48c52d2.nq.gz
│   ├── 6a55e9ba182800567a1127c68657a5bb5019ab6e.nq.gz
│   ├── 6be47aac23dd05b3513722aa46e45e0ff5350a44.nq.gz
│   ├── 6e74ce7f4868460f9762c7795947938f3e0f1a81.nq.gz
│   ├── 701a78588272f5007b06bc8594b9111bee9f0c75.nq.gz
│   ├── 720e1b266d58ef630ed72f2f49c8adb29101082e.nq.gz
│   ├── 765dad9ade93d71bd921fda73e795b04c76275d8.nq.gz
│   ├── 777dc81c94b168e4a7119dd2d9293433c4f3b497.nq.gz
│   ├── 77dcc2235190b08c49bf4e27f654eda58c3c1b5f.nq.gz
│   ├── 78e333ec5ae84a9293c7bbe0a1f06ad8ed4c5cfc.nq.gz
│   ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
│   ├── 7b0e6a3a8062ecfbab3c58fc1cf25c0f80e06d44.nq.gz
│   ├── 7da51b0e2c8ee6ce7a37ca4029122a7175579393.nq.gz
│   ├── 86d74bfaeb44c09a924c0de2b1df87ecb2cf22bc.nq.gz
│   ├── 88903075ba4e126408b8ed0ae0cc83564ee2fb65.nq.gz
│   ├── 8a5c2e2eccb70061b92198232fb17d1c6d7507b4.nq.gz
│   ├── 9220a8b0a126fbd92883ec6857f1722b6aea96b2.nq.gz
│   ├── 93d7be827a8c8ea58016c82fb256e1c056743e4c.nq.gz
│   ├── 952162b2ced30ab893de52d144953149d7c6be78.nq.gz
│   ├── 98cdbf0a960ce00f0cc4fbf3debce04f414de918.nq.gz
│   ├── 9a518eec04ff7a01d0ae59c129ccb9e18c730e75.nq.gz
│   ├── 9d27a81d4e55d4fff129ac9a74057c12e98f461d.nq.gz
│   ├── a86567f824f385dc1292296ef8f73bcf7bde0758.nq.gz
│   ├── aa306db5bb884b760dca3ea7a8ea5d990eaaef4f.nq.gz
│   ├── aa99c43a8f8f1e5811c2ec03a81d8d77481f9816.nq.gz
│   ├── ac51e8cde4c33a074a3b64ac4d3890b47b24679b.nq.gz
│   ├── af1439d4b409dff3aca57b37e0c73112cf5c6944.nq.gz
│   ├── af60b0a89957b6e37e6ba3978e1dadc4561e6e55.nq.gz
│   ├── b0eb380b45455b8db26beca66725e3698b7d97a9.nq.gz
│   ├── b60c9db14624d1beb2758f0cfd7e946d3c2ff77a.nq.gz
│   ├── bae92707c5f53fa3e943f053dbb07906390a1710.nq.gz
│   ├── bb3425d864bb55f49360026c2c6ae0a8f391e772.nq.gz
│   ├── bf268999bf13fffb6e2fbe15311fd70fe6eab630.nq.gz
│   ├── c1f0b600754128f9c42127f2600c1132ddb91cfa.nq.gz
│   ├── c8bc797d7ac815f12073d1b5de0f822dda8f0622.nq.gz
│   ├── c991377a60951acbcd7f586ebcf0184840e30e55.nq.gz
│   ├── d0536dc63dbf338db41a8743639ca7c1882eb69c.nq.gz
│   ├── d056a25ff0a796db74b365839a06ebcb35b86afd.nq.gz
│   ├── d0a5c49234cc37ffa9c00bb4b89372e5c7d76348.nq.gz
│   ├── d5eba0db848d396825b104a47735a7ca74b58da9.nq.gz
│   ├── db5ef40b9b2cbed69933734b530fba6dbcb5533f.nq.gz
│   ├── db8213cd2b79b8ec492a4beaa0945952249faeda.nq.gz
│   ├── df054ca25c683b09e0940a60c81ec670d4ab1f08.nq.gz
│   ├── dfdfb438a7294cabcae401a0e3271cda9097e6ee.nq.gz
│   ├── eb8d232437648dd95197792960399200758bd724.nq.gz
│   ├── ec326f54fa5c036d22375bb676b794dc2ff71f40.nq.gz
│   ├── ed2f85579a63f01d8bba3820f60dbae6dde6450d.nq.gz
│   ├── f4065b70d0fe44e02504a06caf6cc730a8946dcb.nq.gz
│   ├── f50f6115ca1f2c87f7bd6bb5503008de8b8cf204.nq.gz
│   ├── f60152e0aac038c780eb38a1db8d1b4cc706e6a1.nq.gz
│   ├── f6d1a167b4a8ce375a8d4ae1adda1b252db1f943.nq.gz
│   ├── f9e9b0d10da6f5110bf182d436a98c9691c4e5d9.nq.gz
│   ├── fd10b071d17663e6f7b851eba5bc653c34f94a87.nq.gz
│   ├── fe482b84ad6114126eb33fda1338e127e2982064.nq.gz
│   ├── ff3c3a66abe13a00c4ea16a190c04420680f65cc.nq.gz
│   └── ffc7b1cc5b2c2330c6aa71f212c921fc97674ae5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8d56a2d9432a0ea71c939e7357a5c4524730bbd3.nq.gz
├── filetree
│   └── 8d56a2d9432a0ea71c939e7357a5c4524730bbd3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 108 files
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

[apple/python-apple-fm-sdk](https://github.com/apple/python-apple-fm-sdk)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
