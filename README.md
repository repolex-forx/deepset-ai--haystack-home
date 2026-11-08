# Repolex Knowledge Graph of deepset-ai/haystack-home

RDF knowledge graph data for [deepset-ai/haystack-home](https://github.com/deepset-ai/haystack-home), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/haystack-home
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7981485e6b34e44243c45e744aeb91e6451b1ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7981485e6b34e44243c45e744aeb91e6451b1ae
│           └── chunk-001.nq.gz
└── blob
    ├── 00389b67c4e855049d7db177867d77203f8f43e4.nq.gz
    ├── 00992dcd723da1726b1ba532ad2850faa176c3c9.nq.gz
    ├── 00e163864929bae0907dbee5dfcab6594c717e2b.nq.gz
    ├── 0193a02928bd2d98b9d6a1570f1573a1bc8df0cb.nq.gz
    ├── 01d30b96519e73c4d601640908668f327f1821d6.nq.gz
    ├── 027a2d58d0ac5d0b01babbcba2c8da6de6c695a5.nq.gz
    ├── 0323c8290ecf1bb9b7f67aa6f0fe588384fb92f6.nq.gz
    ├── 04266235adf7fe8d2f3b209d7b6a147ac15d022b.nq.gz
    ├── 043ef6fc7a248245d8a1634f24e1d0b274af07be.nq.gz
    ├── 04e0c0475456573909b5b30503637e10d2160fcd.nq.gz
    ├── 05be036aa2d89922d5e95be69e123e8549b20c4e.nq.gz
    ├── 0693dbe6727de27ade68717a4b26492c11518bbc.nq.gz
    ├── 06b1ca9f9f6890f30f781e177dea19d688821ee2.nq.gz
    ├── 078a5c12d79310d60e10d6edc384b56a57545f23.nq.gz
    ├── 0825b72caf02b1911f6ef09f69cb94e0fa295c8f.nq.gz
    ├── 08cd7ed366d99cd3afcf5c032f1ad77652b1a268.nq.gz
    ├── 08d8dab7abb962a2af66bc16dbbe2eda845164a9.nq.gz
    ├── 08dc5c633b107e4d18978d29e31027546d3ba4b2.nq.gz
    ├── 08e857a64a32a33f947383b4adc2d9bb272aaaed.nq.gz
    ├── 0a4f890657ba129961284034e6bd327eb31e9b02.nq.gz
    ├── 0b4cfd65759db517086385e2cc548758852c6023.nq.gz
    ├── 0bac0bf73da76ef492d64deada6824da2a59e86d.nq.gz
    ├── 0c49d428bda8c36c008bd2260de347648777b3ca.nq.gz
    ├── 0c640d22e1ee5957bd606ff760dbfde586b1d4fd.nq.gz
    ├── 0cbffe19b3bc78eb723bac1ec0364ef0b9f23de3.nq.gz
    ├── 0cddb1743c7a7d7a7cb8a82cd56ca40ce1a50bbd.nq.gz
    ├── 0d0c5b76691e8a5d4db56f5938965a928b395735.nq.gz
    ├── 0d7e1ecf4ac63ecc3e3f9baeab85154cfa99253f.nq.gz
    ├── 0e39b5104972be0552ee35601a4453ad88105b6d.nq.gz
    ├── 0ee79fd39829d3e5b67ae7b38fb4306f8a03657e.nq.gz
    ├── 0f50c9ea5af37565e2a7141d862fcc792b0d9697.nq.gz
    ├── 0f8baebfc9cb1fb6eb0c5fc81182e60a1e770774.nq.gz
    ├── 0ffafd59e5f0bcd0d0953832d76ffacb10af5b0c.nq.gz
    ├── 103bc8e973853e750ec63c2b4ae89816238d49f8.nq.gz
    ├── 11aeb19255b7ab6568b3439b60bd9d87e4400786.nq.gz
    ├── 11cbeb6149f62d6b15321cba9325c7b6a49b8113.nq.gz
    ├── 12001a96558a366b775a795540c31d88227e8322.nq.gz
    ├── 123237e387fb75fd1705be419dc78794483a8249.nq.gz
    ├── 12438f994265c4892f74819ec1bdb9c06db9f884.nq.gz
    ├── 132798df769f25a54f178bb2f66a8c353b4be691.nq.gz
    ├── 132b1061aecd6de2c20787a2d29d78ae3ef0a4d3.nq.gz
    ├── 139ee6156aa5f9ee22a7954b2b0e5ce217a81ebf.nq.gz
    ├── 13e65214f259db5193806a08a7348a7ff7eaf6aa.nq.gz
    ├── 14de8fc6df9a4ca4132e73157af58d767f549e84.nq.gz
    ├── 157d1e3b9df3f12e64767f90efad63286f23cf5d.nq.gz
    ├── 165c62149ee803ba155093afaa157d21b23f94a0.nq.gz
    ├── 16c1a8f8a9d0610bdd658ed602f9f8b2e1f54b2d.nq.gz
    ├── 1770070f956cfeee610ac1fd50aff92e2062159d.nq.gz
    ├── 178e2e91a0b6b5c3abb5ace6d329728d5b0626f7.nq.gz
    ├── 17cae7e5a35dacce0f4951742a6df7475b18b066.nq.gz
    ├── 180b1ac7614d04513e31fc95e8a80445f13a6f81.nq.gz
    ├── 183151974f7177339815800ee04901e485a52d9d.nq.gz
    ├── 1891b99904976d20dff9a40ab29fdbae9cedb647.nq.gz
    ├── 1903740770779507d92060365a43d929b444553b.nq.gz
    ├── 1949da7ce834fa53c77582c547f54cba532fe1d0.nq.gz
    ├── 1ad6834feb1dc37f67aa56fe00e9c6d0bbe3faec.nq.gz
    ├── 1aff89da0a4eba858c57b0d104f49cf93b8a89d3.nq.gz
    ├── 1b0c2b583d8ea5c02250d77f610e6aa956862ee8.nq.gz
    ├── 1bc01019d251063d7e5d58e01620359abff47093.nq.gz
    ├── 1bcc15c1a30cec6e593cf259091b012a5e582a77.nq.gz
    ├── 1c70dd78a1dd98f71941c48c393bde7faf9d05f4.nq.gz
    ├── 1c775c7b1e2b5892c9b478581d0ebfec430c9e56.nq.gz
    ├── 1cfa71dd614ecf7171733f2011300fb0ad78b5db.nq.gz
    ├── 1d9b7ac9e569b588216d72a7fd1108f5f24702de.nq.gz
    ├── 1ebacfd2fc412cef3f31328d980c5bdf666a6bbf.nq.gz
    ├── 1ee915b2da7d9020499e59029e86553dd02c1e1c.nq.gz
    ├── 1fd7f4c3e92ca40fee8981468cc41f4f8ba70c0d.nq.gz
    ├── 210867a87c0242f3faaa7a94317911daf371f0a2.nq.gz
    ├── 2115c62893ef121d7b5c727bb86e09f4ea61e271.nq.gz
    ├── 22127db4d106f9f4e509246a67d59c2be3cde4f9.nq.gz
    ├── 22495175fba2e86f94634a8d232bbd3862b73ba7.nq.gz
    ├── 236468cbc8dd849606a3235cc80d9264ba868924.nq.gz
    ├── 241eb88fb721b5dfb91a5c7490d8082526210b76.nq.gz
    ├── 244b75db2caaac309d1450239255a50618009ba7.nq.gz
    ├── 2465c97e91213ede14ab0a13b691204cad74697c.nq.gz
    ├── 24b50f73baac9052ad3c0c5959b06f9e22da597b.nq.gz
    ├── 253696a244c06d7378e648507aa6ae9ace1d2c95.nq.gz
    ├── 25ddfe6d5eb4d90894a55e7cfeaa028e11a16154.nq.gz
    ├── 2601919ba6704f559943a509adabdf38c9ad0742.nq.gz
    ├── 2601d4d745afa9e7c83ca71a86182df7faca4d2b.nq.gz
    ├── 265e8e097f9ae07cc2c9ed7a70645dfb69359de1.nq.gz
    ├── 26786f12c5f7a177249a9bde0430a51eff5b7e04.nq.gz
    ├── 26bf819ce02e551d2344145eacb3c44bce685f86.nq.gz
    ├── 2705a092d55b4ce2ad13950402ca15ba56775c9c.nq.gz
    ├── 27773fb6dc5b66b990a94e481f2c07ec3cd1b893.nq.gz
    ├── 2849597b605d9828d9be1d925b1dcd9a44487c86.nq.gz
    ├── 2888f95cacfefb8c6ca658a33409d209f0d2e572.nq.gz
    ├── 290aec9858e7e03d44642f91d39fadce32d328dc.nq.gz
    ├── 2a129378aa9eacca26b40ae6454c94e42e393d54.nq.gz
    ├── 2a4d4300d0f39cd288d6c0d6afef604946d1b37f.nq.gz
    ├── 2b3059c6f39af0b7f8b97364d63fa9c68817ad23.nq.gz
    ├── 2bbd08f86efedd69bcc74c40bd8d4402a2d69611.nq.gz
    ├── 2d1cfb12fc051b9cc791e3c0e7de6240caf3cdec.nq.gz
    ├── 2d3a35c7664c9e51a3a9b2ec87ee34d3012447df.nq.gz
    ├── 2e4975fc42a860cd0e803557ddf80f1a0462d09b.nq.gz
    ├── 2f0ab313bebcc8ea422af01448b4659b5d052ccf.nq.gz
    ├── 2f47eb26b744d4ed655d876524b6935a19ebf8ce.nq.gz
    ├── 2faa6bbdbb7bb7287c3d1781b49aa6238d779510.nq.gz
    ├── 2fafc5b13ea92d5cba6f07809a95f148d7a2c12e.nq.gz
    ├── 2fe934df1dc2061ca0fb2d8db2d3b1fce0d617a0.nq.gz
    ├── 2feaf7a9e51db99b5bdcbc7bfed68326d33d27fd.nq.gz
    ├── 301e4e4f31d06663f7497b68b19d94fb884a09b6.nq.gz
    ├── 30b8d9e7e61efa28aad0b8d404b0cef3df1dbbf5.nq.gz
    ├── 311f3cab2401ce93051368e7ab85f20dcc5674c6.nq.gz
    ├── 31dcd7ddfcbf9890aad90cf297e04af46257369a.nq.gz
    ├── 31fc0cc6b2d8eadcfba5a86ec91570159f5959aa.nq.gz
    ├── 323414befc0ce2a23473910b19c906db1c974005.nq.gz
    ├── 3243acb7bc7fd69b6ea8e7f3d8a3344c6a032461.nq.gz
    ├── 326a73dc0b4a486b7edbc67c908d197e84736ce5.nq.gz
    ├── 32afed8a49ad2c6b5b24ba8d83cc62c6ced1a472.nq.gz
    ├── 32e37f43abd1279c7a1c461613f14c108fbfbbf7.nq.gz
    ├── 34da40c52df463086eaa48f8db4273c3d4202420.nq.gz
    ├── 34ea7029216e608f71898712d99764209c331627.nq.gz
    ├── 35445ef38adf0890a6e52449df91020df47e6a47.nq.gz
    ├── 35b2bf7617d850a2ff3220625efed693de1225ac.nq.gz
    ├── 35e35840377c96878204c118112cba5cda7a53d1.nq.gz
    ├── 3745af29790abe409cea10ae8a0a5207df773db9.nq.gz
    ├── 37acc3b09f217a2fe63bf13d79601d5c57b97805.nq.gz
    ├── 38db86fd8455afbf45abc5fac07f81c6f9380ced.nq.gz
    ├── 3a4357f4c325ff6bf2a627abcfcea0fad1175de2.nq.gz
    ├── 3acd33e7d90d0acc97bf8b6b10758df1269bff2f.nq.gz
    ├── 3b9a806564658146d963f0ec74a3d245528b879f.nq.gz
    ├── 3bc1abe9ccbbc1579ec3a40458715aa2bd919abe.nq.gz
    ├── 3c3933a91b52099eed075036ecf030b17f64086d.nq.gz
    ├── 3da54268ccd2b95fb83b9da726b3006004418566.nq.gz
    ├── 3e7d8130d95f43c76df45b0841c4652f9ddc81ef.nq.gz
    ├── 3e9f9b97a0d2fa4239c498b3c258a09093743772.nq.gz
    ├── 3ec76d77bae254569c554624dbbf6187a34253b7.nq.gz
    ├── 3f2b32bc473fb506c2e7251cd9493efb462ae00c.nq.gz
    ├── 3ff1cf0757d799abba93996a6fe7677a99a2fab0.nq.gz
    ├── 40883d3255be38a8eb1b54cc926c73dd3a454b2c.nq.gz
    ├── 40f20a6dd17f04940074ba407a15bac44686cdd8.nq.gz
    ├── 41db8afd37d2c60fad9b6a94e1c989c71d4fb7b6.nq.gz
    ├── 429e7facbe06f16f86668c901287a593879eddd4.nq.gz
    ├── 4339c8a9a82f2e18296b77a1d0cd8b7d50c3f535.nq.gz
    ├── 43ccbef5d1a6cd4fdaf10b6058325dc8ae4127fe.nq.gz
    ├── 44339c20484e24f736e8df7277d940a6aa61e096.nq.gz
    ├── 447cb76a01b43b177d56fd9a7701d3413a707feb.nq.gz
    ├── 44ad8e24bedcf178f728807c62d502e04ae850c3.nq.gz
    ├── 44afca8b5ac2f95bd3513cff6be2ed2fb3133ca9.nq.gz
    ├── 4513afe3d2fe07a478b92b8495ac238b61d06d3e.nq.gz
    ├── 4601d633a0e0d1e02b00f86bb74d125412f284ce.nq.gz
    ├── 474bf78d8ee053a35bb82ce6618c4c0139b50260.nq.gz
    ├── 476b464be7de16606040d9005268c238362f6cc5.nq.gz
    ├── 47b27a937a1d0748b3516227002474108857c11b.nq.gz
    ├── 47f9820bf6d9ef7a35914e96183f4fb1a53cd082.nq.gz
    ├── 489d7de3712ff2dc489e44617cca58681e39854b.nq.gz
    ├── 48fca100ca7fbf73511b78b6f0983e3c565bad41.nq.gz
    ├── 4b74e00098454b1baba98ffa3e491db1b6bb14f4.nq.gz
    ├── 4bf81629520efe83f31a418870fe867b6dc6dd13.nq.gz
    ├── 4bfaea568074668157c3f3bc99e4c2efe3a4798c.nq.gz
    ├── 4cfe564ce5a5483759d616f9ae7abab74305044f.nq.gz
    ├── 4dbfaaaf53ec673f0baf55681aeac4704889983e.nq.gz
    ├── 4e0cc62e5f9eb04435a05d79e2fc41103d735ddc.nq.gz
    ├── 4e1fdad9ea93d832a756a5863579a536955a5569.nq.gz
    ├── 4e9ab76aa425e3e7b31aeba8e7d10a96fcd914b8.nq.gz
    ├── 4eda24f4e86800d6b72ef6860bcc8d95d940bcc5.nq.gz
    ├── 4f4e4b20c69ec982a3ae9bc352ff015bf033be66.nq.gz
    ├── 502ceca91e42bfccba7e91cb5757c227962674cf.nq.gz
    ├── 50885dcfb9ebb97d97372f742fe04617ab11f300.nq.gz
    ├── 50910826b24e51db5c5b4e6c54913fd2aaa397ec.nq.gz
    ├── 513bcd36d121ba059676a90d4577cfb4be64561a.nq.gz
    ├── 514df342404a99821ec790a91991598f2f9f435c.nq.gz
    ├── 5154615bc79311cb7c3ac6e765e7c91d6d48e1a6.nq.gz
    ├── 527f84512a5df84cddecccced8dd0f8de0e4bf8c.nq.gz
    ├── 52a8cf00f3e46a48b3a610ff148c4f5e417ca20a.nq.gz
    ├── 535496a41c19202f7432bd6493a306b6311a84eb.nq.gz
    ├── 5499953f3a7f31bd41406bd8891072b296bdfb6b.nq.gz
    ├── 54d8cea7832a007a0e7b50bd591725569f9a6a8a.nq.gz
    ├── 5549e39d29bbb95211291893695e7ba19142b7a7.nq.gz
    ├── 55630eaaac4ac1dc4bfc82db95d7ed5bf7f93c13.nq.gz
    ├── 5675cd62199597f952b7cfe93056b7d1f2e5dfdc.nq.gz
    ├── 56967246092cef8eaa8bb377c7d59df6d9f973b6.nq.gz
    ├── 5767a24cff47aefe87e883f26b86a8e922f4aafb.nq.gz
    ├── 57caafc1860e466fb21f9fb0d964e2a3708d2c5d.nq.gz
    ├── 57ebb9d65b366fc160cfeef9eaa84bad55305e7d.nq.gz
    ├── 584274f2180eef7d823f6573842ef449885b8964.nq.gz
    ├── 5851cb8eadd70e7a73588942afa64adb30624c20.nq.gz
    ├── 586c8ab969d47c98441c9dbc5d79adeae359510d.nq.gz
    ├── 592c4cf0bbb3ff530ef27e46eefbd6014f67c500.nq.gz
    ├── 596400d7a37a43e27949f3828b7bf3972f05da97.nq.gz
    ├── 59d60edd66d5f6788e0b1bcb17d85043bdb5da40.nq.gz
    ├── 5b0b6407736a28529b17b589edd699cede825d82.nq.gz
    ├── 5b205809fb6c42aa7c119479f8c29c276dd3feaf.nq.gz
    ├── 5b5bcd6ac1b248720cf8b745b63f067ce65ef2eb.nq.gz
    ├── 5c7f09e2d5d0d1a7222954d2ef348aec7113ea55.nq.gz
    ├── 5d4c0ab81de5ee7e245e2ed1b8dce0d530abab6a.nq.gz
    ├── 5d91dcb203183b44daee131315b0e14d35af3bf9.nq.gz
    ├── 5dca22b26b972e8f313b5990c3dcc2366fabedf2.nq.gz
    ├── 60b10e4cee6170073112b00e409a9e8b045c8e75.nq.gz
    ├── 60dacf2665d8280238f7b9eade79379d67c75453.nq.gz
    ├── 612e33aeeb49dfd014c805897ff4c066d707ceda.nq.gz
    ├── 613c6c623c1b3f625e454b01c9791a39f33c2c1d.nq.gz
    ├── 6198fb85aac7bfc0b2c97302115fcb75585139a5.nq.gz
    ├── 61a258de75a2555ca34008dd25e905fd8fbb55dd.nq.gz
    ├── 629c1755386760568652b855ac2f2671a3daf91e.nq.gz
    ├── 63d79cbcceb89c413fb43ba6024f0bda95dd1128.nq.gz
    └── 6484ee5cae32d8f137e1dad3f4d08727d46d14ad.nq.gz

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

[deepset-ai/haystack-home](https://github.com/deepset-ai/haystack-home)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
