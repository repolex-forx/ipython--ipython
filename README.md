# Repolex Knowledge Graph of ipython/ipython

RDF knowledge graph data for [ipython/ipython](https://github.com/ipython/ipython), parsed by [repolex](https://repolex.ai).

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
lexq download ipython/ipython
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b5734353b6d697be2bc4bc98333b0d29462533f9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b5734353b6d697be2bc4bc98333b0d29462533f9.nq.gz
│   └── repolex
│       └── b5734353b6d697be2bc4bc98333b0d29462533f9
│           └── chunk-001.nq.gz
└── blob
    ├── 00cd842eff54235d5cc484d142f7220fc715cf86.nq.gz
    ├── 015937b9af83da200d814b21fc50a8552ec3f253.nq.gz
    ├── 024ebaa104b9e36a3f844cac13ca69c9dc8e61bc.nq.gz
    ├── 026682f026eb4defc9ef39200d92f733edcc9fc2.nq.gz
    ├── 0441eab59af7ad23125e9c5756333f75c31b54e1.nq.gz
    ├── 04c4e9eff91974c8ca54834b36a993f676fa7c40.nq.gz
    ├── 0566fa9329f4cb54fb2410cf335e58ccd716df7a.nq.gz
    ├── 05bdbde6f445bc0e1a737f75e8a9e803e73234d6.nq.gz
    ├── 05d139a16eb3145632330cf5695e21894d834060.nq.gz
    ├── 067e45d4d75592d9d1f260ccaa6e58c46a493ab9.nq.gz
    ├── 07cef1df657faee1844c19455e4420e3d5088cd1.nq.gz
    ├── 0a5fcc218008a91bbe024d15879cb623dd5430fe.nq.gz
    ├── 0a7cc0f00e366524152826d3de2e9d56e565ed48.nq.gz
    ├── 0a992a4d170a7d0ee729ec3ea652f030256487dd.nq.gz
    ├── 0c79cb3cf0867a0bf00911a738afe82937b38246.nq.gz
    ├── 0d8ac7f973dfd0aebc8b8c0ce88cd4545b67224c.nq.gz
    ├── 0d9a5fd0d09d9848846e5d5dfe97756813802b14.nq.gz
    ├── 0e41db598f9b1c91748ffb5db8afff310b386146.nq.gz
    ├── 0e463d48adfe4e8e36d17f854bca2d18c23bc1d1.nq.gz
    ├── 0f4a191f3fa4c5678013589be9c9254e3f791c9c.nq.gz
    ├── 0fe0398297355c288a0defe3345f735595973e76.nq.gz
    ├── 1014abea6973f12c1e5afd3e78185cfb795ab2b6.nq.gz
    ├── 1113d9a0e2815bcd82526b350cb71cbe55537526.nq.gz
    ├── 116eaac31119f87d269dabbab4aaae4f8bee92e0.nq.gz
    ├── 123419b2f545ca25532dbbc770a4c606fffb9ee7.nq.gz
    ├── 125a567d19322d2cdd8b7424782a358576fa5981.nq.gz
    ├── 13ecf88c5deecf5cfc6193d4c170385c4fe6d6f6.nq.gz
    ├── 143f3ebb148dbf6805eb0253af1a4bede857b356.nq.gz
    ├── 14903bdc74c138f97cfa78a7ec153027c8508b18.nq.gz
    ├── 14a731a2d0c21c7efb46f1f93c7c1282a67d3b2b.nq.gz
    ├── 14bafe1632a555fe8ec751a2a4fb8b87556b8e71.nq.gz
    ├── 159b8228e2d20c2175fc76319564a3071765e2f2.nq.gz
    ├── 16032d0c53b865decde0571ee5d6d00fc6f1e10d.nq.gz
    ├── 165f503169a9e7d13c02baf0899dc83f03bc8e26.nq.gz
    ├── 1731bf21a923265c7a83d211cee2dd9b42da81ce.nq.gz
    ├── 1751adf8456d574dcadfb266634cee4edea90de9.nq.gz
    ├── 1775d72d02bca21b96ab45371d485325db14f723.nq.gz
    ├── 17cfccd21d1d8f3af55d2538705b504203605a13.nq.gz
    ├── 17ff7d39003bda77375e89c4086c0b0cd47f338d.nq.gz
    ├── 1860c63840d548a131e48c55a1bc17bf91665a3e.nq.gz
    ├── 18e94da34e5aa277d522593a384a90376b6d5961.nq.gz
    ├── 1953bc4809e80510b37d1621f7cd2819fa131069.nq.gz
    ├── 195df96ee50d81923ba25dcc8f925aee456a7447.nq.gz
    ├── 197e82867763bc33695327a7d0f2e30f279288e9.nq.gz
    ├── 1a242894da58eeb39b67ec43b9f335452d20eb54.nq.gz
    ├── 1b29437c8200d0b8e792c4b4a03f0067fef784e3.nq.gz
    ├── 1b390c7f0e931a0a088dbc036a4d0017b97b1cd2.nq.gz
    ├── 1b4d55b1eff1c13fab82962f1557b6f0389a6cad.nq.gz
    ├── 1de0047e6b4e79162a21167ec5a99f465b1e51c2.nq.gz
    ├── 1ee7c98d642fd47551c0c3e148cb8ef30a0f80d6.nq.gz
    ├── 2046211ee52ac1b6073e1f3848adb3798b0bc147.nq.gz
    ├── 20f956a699755cf43b12e7ac8edb54e17cefde7e.nq.gz
    ├── 215f72b65c4ec0b09a89d95b73f72e165d29c611.nq.gz
    ├── 216f5e78e6de6d20f3da3c42601eb267799ed6b8.nq.gz
    ├── 226b4b851875e96da162efc35d563b32e53e5bc8.nq.gz
    ├── 229190d9fd463b7a32aad10ab046e8c9e83edd6b.nq.gz
    ├── 22aef6335f3ddf81a60933b1ce9479ca3860601f.nq.gz
    ├── 22e22fd530070aed45af3a49d1639fff9120bde4.nq.gz
    ├── 2489f7c67b0f5a1fa825c495fdf25c4cc14b7a23.nq.gz
    ├── 2500a07b135915b050562a91971be7924e06860a.nq.gz
    ├── 2514c513bfde957bea8920a91c9cc3137d04f685.nq.gz
    ├── 252fe6756349ac58f56d0acdca88ee000321896e.nq.gz
    ├── 2643b3e6d85cd6f68c8eebccb9171216b9bf8a17.nq.gz
    ├── 2767392b6231d60c3f620c4dc189b60432ab3b85.nq.gz
    ├── 28cd33abd356b8c4bdcdc16353bf6a01e42e2527.nq.gz
    ├── 29039afca6b8778a24a3d5347204c212f40f355b.nq.gz
    ├── 29085bdf4330ebbfed92333791f274df4d6a2b3c.nq.gz
    ├── 291473c99fffc5b4378b7ae9dd8737780f125e9f.nq.gz
    ├── 2a2ff334993531d02c8d7a8e9d3dd3ba428964d9.nq.gz
    ├── 2abd3fa945b7c551ed56aaa0e8f4aad2c651fffa.nq.gz
    ├── 2b4b656f91ae13f6852897a328190d30b27eb2f0.nq.gz
    ├── 2ba3fd5d023934143ab36a1b4b5e49857f679f6c.nq.gz
    ├── 2ba75a499981b46f0d8384f862ffaca3bfbfb29b.nq.gz
    ├── 2bacdd7e4442c142b3e740528b0dbe669206e75c.nq.gz
    ├── 2cbe13311e0b8215f01102df2fdd991e99bd9bec.nq.gz
    ├── 2d4ac507a309315adfe64c7a6e2b14ad7f4a1dd5.nq.gz
    ├── 2d84cfb69be31dc33a8ded89a0189fb1089904d0.nq.gz
    ├── 2db0d3153c632e58465007e3163f210fd6883933.nq.gz
    ├── 30345d791a1ecd1a8efda9244b73064d35bfa6d7.nq.gz
    ├── 30610d5830a739127c1b585008ccd082c07af2d0.nq.gz
    ├── 308a692559b2e07427c08cf29fdb0a42a7d6c1ef.nq.gz
    ├── 3180e25f2d27e88a93e914e7711fd6f95023a66a.nq.gz
    ├── 3441c705f92f87aa3b2f07fb3e8cf7e449f56436.nq.gz
    ├── 34e2f2dae86322c2e4aeb62e91648d1783532f15.nq.gz
    ├── 34e697029db767baed79924877f49bea45fe71de.nq.gz
    ├── 3521e5f5311278b4e4a624d0fcb731f3fc8c6363.nq.gz
    ├── 35677d342e77708ab26a54c0dc4d20756a9910aa.nq.gz
    ├── 35e186e802c445acbe85be236b414196c3e10661.nq.gz
    ├── 36655c465ba5d4447b01c2c8ea718a130c2e2d39.nq.gz
    ├── 3697251e9b351589fe810c6110c71087124f8eae.nq.gz
    ├── 372455d00ed563383be509dbcf600b86e578336e.nq.gz
    ├── 373846a4bea485cb424bcf462323e45ac2c9e5ff.nq.gz
    ├── 373a7169261295aa087057a24e7c79e2eba401d4.nq.gz
    ├── 3768aea4e522540f968ddf7dcf69fadbe994f864.nq.gz
    ├── 37fefe31459930281aa2303654e595a6dd0d0180.nq.gz
    ├── 387a24700cfcf31979930f05244865996372e823.nq.gz
    ├── 38d5ed06b298f3ff0544f979a8050d3908e791bd.nq.gz
    ├── 38e871deb7e27ba896d15304378708f50e5ea0ba.nq.gz
    ├── 39ec35c7d4ad0dabdf32ad92cbdae72a07c5df02.nq.gz
    ├── 3a197386dbbdccd9b6d4600b005d5bc00e7f559a.nq.gz
    ├── 3aac526131527ca86dac671bebc18d65a3343e31.nq.gz
    ├── 3ac59b2c299c8da5abb829a759fa2de31dea1bda.nq.gz
    ├── 3b53e89d6b272c25f82d4f9831ac8d7a7fbca9da.nq.gz
    ├── 3b8c046b2d185da110beff1b86983c8f63d97a37.nq.gz
    ├── 3be2ec2d2e8a66d0f31ed9b1591245998e61eced.nq.gz
    ├── 3c046a498dea81ed03900e8317cd1eff82a75f00.nq.gz
    ├── 3c88e7c2a1cd856ed6b8bdcd670873b4386e8674.nq.gz
    ├── 3d176625fc53435042273e971c42a0daf855aaf3.nq.gz
    ├── 3d2953933a0b1fd741dd1dd9fd8e926d360c8d41.nq.gz
    ├── 3dcb8cb146dde6eb6546f84bcf951287b3b3e3c2.nq.gz
    ├── 3e791e64c59471d7339d865d7f1a3f83834ab2d5.nq.gz
    ├── 3eb9bdadd806849f00eeb9efbd50f5410ed06e8a.nq.gz
    ├── 3ef89a7ee65d0b1f62bfd85608575bc44325b920.nq.gz
    ├── 3f9aef18f90f0b8c758b55cd47e3bfbf1becb339.nq.gz
    ├── 418af98d9134a4b92eddabc9fa5614f941a4acd8.nq.gz
    ├── 42a8bc5e4c204074b50cc621f32d88457a88a76e.nq.gz
    ├── 435670dfaa0e2d5106fabd6b9913c750a532368f.nq.gz
    ├── 43fb66e930008fada0acbc1d527a10299f9aa4fc.nq.gz
    ├── 44c40ded5cacebd453a41656a691752e32607c37.nq.gz
    ├── 45a711c0b41cac8cfd3a52a074597248539ce765.nq.gz
    ├── 45e78aa29104c073c7e02c4788a1e8a895a14392.nq.gz
    ├── 466eaf5fc40b54c926ab746abd0506cb1493a178.nq.gz
    ├── 473d52c8cf230f2668a3782754135d6700c9bc19.nq.gz
    ├── 480ddc2540de6bac259814300c56a94d01625d48.nq.gz
    ├── 49cf8b236a6b82803bdff4677c3d65be2da480b7.nq.gz
    ├── 49ee2cef3778cfd0220ea0b5023783ff54a22b61.nq.gz
    ├── 4a1072f7fe37176cb17a193d926074b950a6eb81.nq.gz
    ├── 4b0bb8ba9cad491b370c63d1aad4167cff17c09a.nq.gz
    ├── 4ba0f54ef32030222d2cc329f3ec46eacbc93365.nq.gz
    ├── 4c793b43c17f70ee7f865db6c6232945a1e62094.nq.gz
    ├── 4c938ed2d2f28e7f16b1ea6b118f2a662fd84e3b.nq.gz
    ├── 4d61ff2433d2eb49b1003bbbb8b0c552b95a26e1.nq.gz
    ├── 4d9d310870b8829663057975269ed58df252c990.nq.gz
    ├── 4db116ab0dffaa95d35cea1437d8837861001c83.nq.gz
    ├── 4e323758171fc7a2fd6eb358f9b0db255530d2e0.nq.gz
    ├── 4fb8fb78b10ac8682815d95b9d74996d84224d8b.nq.gz
    ├── 5037e3d3563445bce43e18afd834c5406d7dde63.nq.gz
    ├── 50c660af321e5dcbfa8cf81fc7808c45aa29dca4.nq.gz
    ├── 50d0857134eb9b85552a82c617afd49f5f568d4a.nq.gz
    ├── 50fc66c354c3f165624868fc1664eda6982bdf87.nq.gz
    ├── 511003298a58391708472ce59085e5e53c30e095.nq.gz
    ├── 5134c6e928ba9bfd9d76630ad6740e7096dd64e2.nq.gz
    ├── 529169b7bb925e7d740d0f877465c81e1051a984.nq.gz
    ├── 531f5cae14c44e47f0af4cdc7248a40bb6feeefa.nq.gz
    ├── 54561824eaa38b1a285975b3bc60a52dedd536c8.nq.gz
    ├── 555eec23b38617d5a38c9cb78604323707ab0f7b.nq.gz
    ├── 56085cffd93becbf16d4000ac189857d84f20a76.nq.gz
    ├── 56783b630811a9e2d6ea50d25b396eb1c5426387.nq.gz
    ├── 57dd2b50997fe158514b9b0de6756b08f3740942.nq.gz
    ├── 595ea5d589c1a282b3b1caa39e1dd5f29a8cefa0.nq.gz
    ├── 59674acdc8da4dd06c76d5c03f2fa47ea2094151.nq.gz
    ├── 59787722a53a667f361e41718cf28f67894f3245.nq.gz
    ├── 5a9a0aee907bf5d0b9a1d101545b30ca9920d3b3.nq.gz
    ├── 5b6d40a5d343b6e34d1039e1735f1e5c3307825e.nq.gz
    ├── 5c081b9c038efb3af0325ca453c37fcabd3616d2.nq.gz
    ├── 5c3db3eb567aa2a31b4de67a86a065ec5f9f0940.nq.gz
    ├── 5c6dbfb1116289e99510ed4aef9b4c1b7a65f613.nq.gz
    ├── 5ccd13f9164fa00bd5b3563e07183b736be785ba.nq.gz
    ├── 5dea32dd8ecc7dbd2e1f506f17f33390b5a5d86f.nq.gz
    ├── 5dff1a33368673801b4fdf337ecba71fc8e71206.nq.gz
    ├── 5e02629bf742261816bb1c4f2a4829aaad08b624.nq.gz
    ├── 5e092be6876725f3602a21174ffec9c9385a2498.nq.gz
    ├── 5e34b6e0e4e85409daeed22b49a7419d34251e92.nq.gz
    ├── 5e3532495134059f07a5a290a00d40a73588cfa4.nq.gz
    ├── 5f0fd4846ca708bac69fa545a9d8a763e9c0ba8b.nq.gz
    ├── 5f61eac8ceb1ddd832f2073d0886aa1ef8fa25db.nq.gz
    ├── 5ffdc86ebda73fa1c3bf23e72c20fafb2ff643a7.nq.gz
    ├── 60d95725791f7aba9415fc5ef027484d947c780f.nq.gz
    ├── 6179209c4070d2cddae70059a9be3f0cb6c7b859.nq.gz
    ├── 619605e834600d8f6cda30872591f790b0669c5c.nq.gz
    ├── 61d470004218ae459ce7bfdc974f7c86e0790486.nq.gz
    ├── 6214edbb0ca07a36be7a995221eb328d04c17d5e.nq.gz
    ├── 62aa890274a369b4f2b7b9f673316cb82a0335e2.nq.gz
    ├── 6435808b528b9281068b7b23f9b3bcdfeffd6501.nq.gz
    ├── 64f111d8f66c0aa32debedfe0389a1fdf606bec6.nq.gz
    ├── 65123ab4019f499d2ab85acef287d13b54ada909.nq.gz
    ├── 65281787666de0049b622e0fdcb21dc551ce2443.nq.gz
    ├── 65f3993258c799287c89e63aa93a72435d7c3886.nq.gz
    ├── 665ff09f2d4d3190e333302b7c23497393a787b7.nq.gz
    ├── 6668776e7e3a3414ae46956881386e0a0aba3cb3.nq.gz
    ├── 67345b7e7d6027f65dfb0a4518e45d0136e0923f.nq.gz
    ├── 674f7e86e766e3d69c39a2ed674b23696c105836.nq.gz
    ├── 6766abba21f5341db02e5fc262638e7cbdf1ec10.nq.gz
    ├── 6818be15372a32f83b4e083686597fcf640dbe94.nq.gz
    ├── 68440d9a8b62c800c967bf3ffc2fa04f15b96fa2.nq.gz
    ├── 684cbc8da6ac01989141ee39804c8b75744641d2.nq.gz
    ├── 69767e215f0e9755dc9004b02715e7e5b36d9544.nq.gz
    ├── 69954956359b0642e2aed2889122bd687c187e2e.nq.gz
    ├── 699d019c815073eac45a8e85b63cf572027bae5e.nq.gz
    ├── 69e51231bc1c07bec1cc56b9dcc669dd81d72307.nq.gz
    ├── 69e56339fee91215e9fba69ae40556337e99fbad.nq.gz
    ├── 6b34f9e5e10816d0f532f06b4a718cbcbbc6df4b.nq.gz
    ├── 6b40827ff8855a3285b45150123449a5d649cc47.nq.gz
    ├── 6beba8a33cf3955d4a70c5ee3193711deda5409d.nq.gz
    ├── 6c8759f3e72ae3f1aea989826f58ca6863337435.nq.gz
    ├── 6f73f732463b5cba0389ffb20580f04a7a6cdcff.nq.gz
    └── 6f999a38fd3add3ede67486ce00ff220946ec6a4.nq.gz

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

[ipython/ipython](https://github.com/ipython/ipython)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
