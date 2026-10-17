# Repolex Knowledge Graph of statsmodels/statsmodels

RDF knowledge graph data for [statsmodels/statsmodels](https://github.com/statsmodels/statsmodels), parsed by [repolex](https://repolex.ai).

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
rlex download statsmodels/statsmodels
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 283253007bde6dd60b48420c47c64d635e96be34
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 283253007bde6dd60b48420c47c64d635e96be34
│           └── chunk-001.nq.gz
└── blob
    ├── 0006dfc515eac5f65192b53e48747bf68cea430a.nq.gz
    ├── 001c24abbdc4233b4b6666593ce498c463565faa.nq.gz
    ├── 00dde102f76f0d8452e16d5862ccc7a6938c8819.nq.gz
    ├── 0122b5abe2e12e47d43b8b88b9061f025c88b4f2.nq.gz
    ├── 01d922a29858081c909c9aad401256d8b19a48e4.nq.gz
    ├── 0204e3e9114d0b2f7be33b8e85e9dbb107006f23.nq.gz
    ├── 02122116aa978b5034973f3dac51b073f9b12a72.nq.gz
    ├── 02477debf4345733fa8b1624f918091cdfa35825.nq.gz
    ├── 027dc9cbced08020d966bc9d40ca6315d99c165a.nq.gz
    ├── 0290922d5ee4a053c69942c655375c5d23311f8f.nq.gz
    ├── 03ae38cdf4ef7ed5ae867930f5f2abb50d7aeefb.nq.gz
    ├── 03b8f9ec710a29e1f8075d1381092d940347b937.nq.gz
    ├── 03bfe3c58249ce53bda8b0ae6f2ad50e2a80b8c3.nq.gz
    ├── 03f21fab89af345dd55c3050a5b8d39555d2d02b.nq.gz
    ├── 04268d38ab21de102cbaa4ff4d5957967899e134.nq.gz
    ├── 045d461f009ff609b9ac6852806b6393c959abf9.nq.gz
    ├── 0625afdd8f9fb94562350677401b010b083f3064.nq.gz
    ├── 067bf896cd8ca75fab7592a59d531df979f86314.nq.gz
    ├── 069b1f829bef4b7c3a84e264089185ec1ae76c3e.nq.gz
    ├── 077bd7d061070400d568c95e944863b7e1ba144c.nq.gz
    ├── 0836f408f82d7ac24c8fcab35684eea85ebbfcd4.nq.gz
    ├── 0897ccd51048f53839ec41221d968b4eb50e11b7.nq.gz
    ├── 091403c170d9ef20ede7dbcec524b3a7e9ed145d.nq.gz
    ├── 0989a17600cd7a4e5e5b0e6529dcceffdcd6379f.nq.gz
    ├── 0a81e38f5d8dd5185ea2c477864d0ea1755fff9d.nq.gz
    ├── 0bfc71336e8f15555c5f34452c0440de60dffe70.nq.gz
    ├── 0c1ea1ee8028cbc4b2bef54d59dc3e907e536962.nq.gz
    ├── 0c8d6bfd316349c79c94adeeec149ba66a70a2f7.nq.gz
    ├── 0c94d5f98a56cb475b25400594c3ab703509212c.nq.gz
    ├── 0c96d7a7dba2051477548b2abd0eaada8262f87d.nq.gz
    ├── 0d1fadc84fdedb57b13b613eda44e0aca85a77fa.nq.gz
    ├── 0da2f84b68ec3801d0f261a1431ae995f066c7e4.nq.gz
    ├── 0da53d52ad87cc210fb7482720ac93f6b64916eb.nq.gz
    ├── 0dc7e07bd9b73fb59a6ed092277659ceae838d83.nq.gz
    ├── 0e358259104a13e2e7463adc4535f7a4281943c1.nq.gz
    ├── 0ed44ae05a5a4308cb76cbdbfc444c9c4fef13a0.nq.gz
    ├── 0edefea483def29eeafc4fb2ff7e57c9ac891e12.nq.gz
    ├── 0f4dc0cf129ab02e594277fe3f41a8062557c92d.nq.gz
    ├── 1122bbf5ec1a609e1d7e380bf174a6a940a006f8.nq.gz
    ├── 11317f26f364220406abb733de2047905c8f8cb9.nq.gz
    ├── 11b3eeea779a00e5870fcb172bbebc10bf741d6e.nq.gz
    ├── 1220918a5b928802810c1e4dbb73f1e569610401.nq.gz
    ├── 12753733a185f78f394b026ea88fc976bc37fe9d.nq.gz
    ├── 127af9f04cd0e5d218a8440c9ce06bf48778111b.nq.gz
    ├── 12d19a7542c950f69fc04f0d3c0d7c934bf19da3.nq.gz
    ├── 149b93dc81bd95673fc1618adaf3e8823c78768f.nq.gz
    ├── 15d016115ea18f17d446bfc0d35f2b796ee4ce3b.nq.gz
    ├── 163458d6c0853511bba1da1c642b8fbd13a771df.nq.gz
    ├── 164b038826376b17c827a8c2e3340ca7dc707be8.nq.gz
    ├── 171cf78f895d7a548dfe6fb815c01228fd834df7.nq.gz
    ├── 17d9257eb36dc4e22b7b361d8c11d9873ed08c96.nq.gz
    ├── 18366969edb649f6af831bea2f355b1b900aad9b.nq.gz
    ├── 186aef0bb980db315b46c1ef60fdfc788660c413.nq.gz
    ├── 19e30830204b69d574cb26f8d48800f8f5f9ebba.nq.gz
    ├── 1a2025ec4723fdfcdccf5c601bc8ed0d4b4a1977.nq.gz
    ├── 1a83bf96791fa2fc7728431d2ef7aeae14958ffc.nq.gz
    ├── 1aaefb1c80ac6e85e39ddc2acdd0a11075bb9f9f.nq.gz
    ├── 1abb4fb3accea1ae7416e149acedbe67950b4cb8.nq.gz
    ├── 1b719c36950e78ff0581271b98c1d8d39d895784.nq.gz
    ├── 1d4d2786dbe37a24de5d3695dab002c97bde61b1.nq.gz
    ├── 1e87dc55767db6379f1c55f843615ddb99737355.nq.gz
    ├── 1ea54c1dd5abb124bc42159443952c14cf041adf.nq.gz
    ├── 1ef116b5e0cf5fa7cfbca6dcd1ad3c1a98ee0e9e.nq.gz
    ├── 1f097a858f5286dc2cecdfe114c35839f47e2ddd.nq.gz
    ├── 1f248626f248b5412111fd0fc5f23268441267c2.nq.gz
    ├── 1f71429319ef292d27012ab16218472f6f07436b.nq.gz
    ├── 1f774cad062f7549b5335c2ac9af540ddcfc37a7.nq.gz
    ├── 1fb3d16ef2cae0c94018822824277821f51e4de8.nq.gz
    ├── 202a45563d18e39cc2be87929cfa1a5f9943efe5.nq.gz
    ├── 2088587c9bd795236ee68b6a063a9494743d629d.nq.gz
    ├── 20e1129201697096d6985e687d190b7daa935ad9.nq.gz
    ├── 20ef445c526d49f86769b5d1e718000ca8744f65.nq.gz
    ├── 214dddd4edc49f704c46ce6699c0dcfd4e41b3a7.nq.gz
    ├── 217f211571a0ff3112c7000c10638d024f0b02a6.nq.gz
    ├── 220cdaf9e2db6979426c0b4c2f4dedb1359c2c93.nq.gz
    ├── 2223b04bbb93f489e933a1d9699504c14285fa1f.nq.gz
    ├── 225ea2b32f423a10e9bd6623843b758234014dc7.nq.gz
    ├── 22ca99b829600c62ef4781eaa0a5a262b7354c22.nq.gz
    ├── 234434d0de7b130f65b56a77d10bdcb51efe6c5f.nq.gz
    ├── 24d06c546b5ad515e33675a593c07460265da6c4.nq.gz
    ├── 25dfac76f40258fa59148b2e29a153078df625bd.nq.gz
    ├── 26b1e01ef49042e19f829af932e5fccd74dc604a.nq.gz
    ├── 27f7af785d56e7730022a61f54ae8524f180e1b2.nq.gz
    ├── 27fda1b0fcd3c42ecbd54c0c25331d5070031029.nq.gz
    ├── 281018479e249eee8b1d9b3a572c689cae56d842.nq.gz
    ├── 28832e27798ee0e8b662fb03899f0a6c6689fd86.nq.gz
    ├── 2892fa0b739b2a7a029704fc6bae3e89e45cc4c0.nq.gz
    ├── 28b6f26ba5d9927880314cb81f5d69be0a584b50.nq.gz
    ├── 2907aab6621cae3b687960d39315cd5947c82dd6.nq.gz
    ├── 290a4f0df2afc9250a857cbb25e5fba79c513970.nq.gz
    ├── 295e7f41144960c6b3b80b2c2c622fa8f8e9d1de.nq.gz
    ├── 29657b6ace98313f0e2691285f6b9a7712e4f218.nq.gz
    ├── 29de308b680603a4a4e15394d017eace499e6598.nq.gz
    ├── 2a95520d1743d51c4bdcf9245f0b3f13d57c7fca.nq.gz
    ├── 2b207c2c5f47c3710f8efd44c43a1525eeafd2e7.nq.gz
    ├── 2c2b80e33bb84676880c126ba5d13e227d863332.nq.gz
    ├── 2d703a373f5054a332e2bd8feae78afaa94416d5.nq.gz
    ├── 2d7cf7de4e93ce8ff4b55483eee460bd4d1a9508.nq.gz
    ├── 2d7e2084219fbddd94eb88d04900dd9f274fb8c7.nq.gz
    ├── 2e5bff6a17693b30bbf59ab922fb7f0466ba6a07.nq.gz
    ├── 2fc862ae837f76045e4de3aa1754dcc67a09f52a.nq.gz
    ├── 31246355309da377332b376a2117bbffe30bcea4.nq.gz
    ├── 31dceacd1062fbfd59eb8d84239eb275f9829bad.nq.gz
    ├── 31f0f1ae789e9ab9fb6688a847869d0219423dea.nq.gz
    ├── 3283bff49bbf17a954534fbba93c9e771f7be1a5.nq.gz
    ├── 3307099211b6bd1e71d9563ef0fa0184c80d2874.nq.gz
    ├── 33d05b0de1a541877e6a0109efa5c6f98c493088.nq.gz
    ├── 34d39d62c389addb0c1b96e9857a7d04a05390af.nq.gz
    ├── 36228f64ee042d02919ebd71d761262fd0ce8d09.nq.gz
    ├── 369bfabe2ac5130803d92c8f7198a556b9af043e.nq.gz
    ├── 369e7683c7eae45f94377b82b650515558f98945.nq.gz
    ├── 36c5126736aa8a4165acfa7ef36ffa97edc3f966.nq.gz
    ├── 3732b5880ecea88ddfe46b827ceac45b45492062.nq.gz
    ├── 37c086150da2555dfb0027a0cf16330ef6091a4e.nq.gz
    ├── 39417e580c823e741bf235eb568b4150757d6b95.nq.gz
    ├── 39d37856c049d2a4059700b4f2d06cc256c9a0c8.nq.gz
    ├── 3a2f7758ba646dc1260f88ec3223cff6ebf3502b.nq.gz
    ├── 3aef78a65226d3568ece5d4ff2acff777a0437f6.nq.gz
    ├── 3b506b912f51f810604561f5eb6aae4a68a98e4c.nq.gz
    ├── 3b7d35934da9d4934e7874f5faf08ee059651786.nq.gz
    ├── 3c3d54df356c8a3c70072b82f49c8b99b3aa1196.nq.gz
    ├── 3cbd3c089974919cd4732a3c9026d0883d361849.nq.gz
    ├── 3cc999245a8817fb00c013d697467cfa7c58a77e.nq.gz
    ├── 3d0e1a03bfaf33181ba448435ef591652246a99b.nq.gz
    ├── 3d51e06bfc0206c230c9922516caed415de85516.nq.gz
    ├── 3fa024cbb99ddfe4b0c984ffd1c7ee979a141764.nq.gz
    ├── 40b6354e7295f3cef0a58deb8e99998ab762dea2.nq.gz
    ├── 4134bd581906e62e27ce76021726384de3186827.nq.gz
    ├── 41596574fe86a5502a72ab992268900ae482234c.nq.gz
    ├── 42e2d29b6479cbde5f2cb08b5bd810365ee3d3b7.nq.gz
    ├── 43abe9aa15414703d55f8cfe34961e6038f43643.nq.gz
    ├── 445c40571e369b365e18517166377445010f2dfa.nq.gz
    ├── 4494f9453c235a3f88809e8a0b0655e9a07782df.nq.gz
    ├── 44db82424c723f6b4639dac40dec19aa489d87f7.nq.gz
    ├── 456cce027dc7f249e1b1edccb3bd48f43fbd1b5a.nq.gz
    ├── 459302c8153605bf800bc338438530ab4d28691c.nq.gz
    ├── 45a3ae54789b2f7f5b2f64ba4ede1a526022e4e2.nq.gz
    ├── 45fe2f844f1db78d1f094756f291821352f17696.nq.gz
    ├── 462f44c93301a92ddc5415041defb0e14220fd7d.nq.gz
    ├── 463590bd5b4d8574b838b8fd15c5303cf7d35280.nq.gz
    ├── 4655b5be75adbc000b4040252b254fb8f833fe96.nq.gz
    ├── 46867a40fb1b3d003b0033b62bf3d32d182b9dbc.nq.gz
    ├── 46b98025059bf197b70e423d8a2b8679a6b1d740.nq.gz
    ├── 46d877725fe2dcae2dac69994a643868136fcd47.nq.gz
    ├── 47914bb52e5f9c32ce86756e36b926b2cd27e3f7.nq.gz
    ├── 47ec04d22be13f51ce7df04ed23c99a2fa431d62.nq.gz
    ├── 4a2df46b205d732db28ffa176f76e0394d75deed.nq.gz
    ├── 4a44704b9577ca8fc31a8f7c345de37437a72459.nq.gz
    ├── 4a9ea7d6ffba9b842bdb360db727134faa5f3068.nq.gz
    ├── 4ad3381ee4db2a65d5e103ff364e687325040026.nq.gz
    ├── 4c5d0852856e39d92b7cc45d2bc3e65683f90129.nq.gz
    ├── 4c668aed6338368081a4e120fe43c7f8b0ee104d.nq.gz
    ├── 4c76ffcf1f597a4e67de03882b07918055401f02.nq.gz
    ├── 4d6180d2ad1fa7698e9a3ce3a74e3481d9e22981.nq.gz
    ├── 4d88edd1a86c10e9e53e826be214440f21f2d5ac.nq.gz
    ├── 4d997faeb672d50ce77fa12cd1a399e42d462aa4.nq.gz
    ├── 4e179bf413d741d083448861113fbe3b34768ec1.nq.gz
    ├── 4ec468552a101babb8dd59fd30f799253dce3cb1.nq.gz
    ├── 4ec5f4424df31c30d23f2a981f9d7667f7e73275.nq.gz
    ├── 4ed1e56ed4218026359a7a664975a70ba005ce33.nq.gz
    ├── 4fc16a4691abf3d3ff1e5b4ca8795e05f6ccc6ea.nq.gz
    ├── 5117c57d0800f6139be46b9a8af50fb8ed9dd251.nq.gz
    ├── 5130a8bc8404d6ae08d1d3ed3d29d2439bb6ec26.nq.gz
    ├── 51f29eeefc7609eba116c551f3b357d4333e2262.nq.gz
    ├── 523a3f854ab259bdcc64d86fadd88e451ec39863.nq.gz
    ├── 52700ded4f333295add385a044efa9525fc59956.nq.gz
    ├── 52dc1b0e28645a7125029ae7144d7a7043aee710.nq.gz
    ├── 537505b4cd7e45ec5d6cc65461a1896d7d126524.nq.gz
    ├── 53b2aa9ba6d8003dd7431f08e92dc6654af10e57.nq.gz
    ├── 53f0bc15c4dd1eff800e370e2de1e9e347c201c1.nq.gz
    ├── 5428dbc1bcf7d68a0370245ba346f6dce6549481.nq.gz
    ├── 54afab9002f4380fcc0dafe1817dd1c345193c15.nq.gz
    ├── 5502eff3ff5c9c3fb7eba3480b22e15d1bd9db93.nq.gz
    ├── 5515e2e44e7497f9dda077f8c4261ac33d1869e9.nq.gz
    ├── 556bf4677205f2b025cb056110871f36f18f9da8.nq.gz
    ├── 557f3bafa1da35f5048d056429befd20709381b9.nq.gz
    ├── 56772bb6b78906e99d8fd3ca9b43cbf6139ff78a.nq.gz
    ├── 569303498e986e25a7b664abd3bb7150356f59fe.nq.gz
    ├── 57215692c10091444030f5770414c6da8de644ab.nq.gz
    ├── 5759c5b1180ca895c935d9be6539868952010ce9.nq.gz
    ├── 577651857c570fbdb4c528863ec35533ece87ef2.nq.gz
    ├── 596890ffe3e3cc8b3be9c28d0dbf0315b87054e0.nq.gz
    ├── 596cdd2c4228010d2c8ffed82a0fd97946bc9b91.nq.gz
    ├── 59bd78e0c388c9c9778315f51e988e731968eb70.nq.gz
    ├── 5ab3d2a2b8517a8df6a178bbc079a8893d8fd00e.nq.gz
    ├── 5b0bce1a3120dce7786627c4048c87850e34369f.nq.gz
    ├── 5ba5f5ede5417753df7abe4645ee2a1ac1e56c9b.nq.gz
    ├── 5c5e3a31e92c96966ffc4af8a84ce43b65b11997.nq.gz
    ├── 5c8d3e4f343026fc6e33b36e9e5b7920c1565916.nq.gz
    ├── 5d2d16907177fa2f425dd043289715cacedb5c0f.nq.gz
    ├── 5e39d598142ddb54c1341a82b8416eea803b3397.nq.gz
    ├── 5e9f2e7e7c6959cee5f1c1f4fa8c89923251bbbe.nq.gz
    ├── 5ef4c7509249c1ebcb408577f96777c4495a6736.nq.gz
    ├── 5f8f16af2b6a0b62d62be1a46292ed7af10ce610.nq.gz
    ├── 5feba7fa49a7fac1f26b530973e22eec0bf74049.nq.gz
    ├── 6060623355d12fef5872f8c94fb835a207ad199b.nq.gz
    ├── 608809aa3d10e170d77b487defb0f4987e858f70.nq.gz
    └── 60b864d4a0f806358111385f655cc5bcc567e7b5.nq.gz

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

[statsmodels/statsmodels](https://github.com/statsmodels/statsmodels)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
