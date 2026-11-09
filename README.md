# Repolex Knowledge Graph of qos-ch/cal10n

RDF knowledge graph data for [qos-ch/cal10n](https://github.com/qos-ch/cal10n), parsed by [repolex](https://repolex.ai).

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
rlex download qos-ch/cal10n
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── db338cf47ad069d22cc9a0331ae433dfe2024e2a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── db338cf47ad069d22cc9a0331ae433dfe2024e2a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0566cd6852a79e09e75f54ce84c73999df82257e.nq.gz
│   ├── 056a099fb47592acdba6b38adbdeebd6e13f9362.nq.gz
│   ├── 068be4d981ad367414df1ce484fc38e8c536656e.nq.gz
│   ├── 068f43af51e9fbb609161d85daa231bc9b76d916.nq.gz
│   ├── 09c3d740f897cfc1bf280abe5884341b59f19099.nq.gz
│   ├── 09ee1a2d49862da1f97094baefdbb975ebbf6fd0.nq.gz
│   ├── 0c45931535d7c1473428e5e60c5a1032150325af.nq.gz
│   ├── 0c633d0cb39f4434b67eb4e23c7d1f7dea5ef8e9.nq.gz
│   ├── 1093e793019545bdb7a2df0ec2c70c83d23fb3e3.nq.gz
│   ├── 1275baf2ce5d252180dfc65ca950e37934e3fadc.nq.gz
│   ├── 136cfe128f30d73c8cfc4221fb802bc56b2e0d8d.nq.gz
│   ├── 16ad06c5acaad09ee4d6e9d7c428506db028aeeb.nq.gz
│   ├── 18718bf1096b5506e474cdb3964e0073cedf832a.nq.gz
│   ├── 1b3d790ac35d0d8207e65d0d406e87f7c3c02c75.nq.gz
│   ├── 1ba87d5c7b4c1465743279998d7ca5f258563626.nq.gz
│   ├── 262f52cd0fc01200f237a3266e6dd42823e86e76.nq.gz
│   ├── 2baf43f3b4a48ff3b7535c514e42cda679bef2b1.nq.gz
│   ├── 2cd97acb2b82fd1b17d879dbeb20aed17d0980f5.nq.gz
│   ├── 2e053371955b46655c6addaa5eccc9a38022bd54.nq.gz
│   ├── 2fb0edf0aacab5c72338c5953d7e8782a44b2c5b.nq.gz
│   ├── 3293733b295e9108b805de37ee432fa417a0f5c6.nq.gz
│   ├── 3612ea9ff7379b737c7d54dc275ec848a07f0bcb.nq.gz
│   ├── 362712eb58f9d8eb4a3ffb64c155e5af0b17feb9.nq.gz
│   ├── 36cd603457ab62407f0ce5e3a377a2999b75dd78.nq.gz
│   ├── 373d1449ee19912dfd30799a8bf6763aa25f6352.nq.gz
│   ├── 39e29d4240fff93a446515468446c3862df88721.nq.gz
│   ├── 3a33e2b10cb4ad4aa603e6ac35ca9a3b416c0b29.nq.gz
│   ├── 3fe724b6edcefe0ed5a9b979bc3cd5778c65eb23.nq.gz
│   ├── 401665bf1266a7e2a1a64d5cb30b4edeaaf5b73e.nq.gz
│   ├── 432c470f2d4745966d238e6184092620d1999228.nq.gz
│   ├── 4964d5f1d542d47c532b4b7cafc4efadd9a34c0a.nq.gz
│   ├── 4afae3da7fb8d0e4ff26587151f346f80c89f19b.nq.gz
│   ├── 4c715a3f4fba48a6df775d227dc68b231b4f32ab.nq.gz
│   ├── 4ce0bbc3a986eb877fe0933570c2a5079c95c0ae.nq.gz
│   ├── 4ce5903e256af4e3037bcf59d102c5a2f34d0b83.nq.gz
│   ├── 4e632afd01b10608d61270b96832b22967907b2b.nq.gz
│   ├── 5231397118c6be2c39c5aa569de49e47d9b8c36a.nq.gz
│   ├── 5435d8be13c1faa38c1e518ee2838396ea0f1b14.nq.gz
│   ├── 553d9824ce24c4890aaac33bd906bf0fa4c4c4ba.nq.gz
│   ├── 5587b31309cb3252b7aee2627e5d977a8970358e.nq.gz
│   ├── 5990d12bb246960a0997a16e5e499aaaf7fc6ca0.nq.gz
│   ├── 5ad9648fe42bb43d7b3be7e0448d54f45a87dd24.nq.gz
│   ├── 5e921308f5becde24d5f26df4e09ac1aadcf07d5.nq.gz
│   ├── 5fe3c3ccf1418012e8b7d0763f6e2498002068a3.nq.gz
│   ├── 609b59b24221e2f76c1df9613d940739fce25153.nq.gz
│   ├── 62a87524f87fde16a0f5e201b9db899a663f8b46.nq.gz
│   ├── 641a9dbe35236d6afc5822b66241fce9c2c570f8.nq.gz
│   ├── 65c26c1e3a21c4ba3076d473cdc184d473d46faa.nq.gz
│   ├── 66bd7adbcb2e4c39387bb8a2dc9b3c12e9b24749.nq.gz
│   ├── 68ade795a5d179e287465aa3615ea41e643de593.nq.gz
│   ├── 68ce297baa13c9b155ef23a8457685f6865a2c55.nq.gz
│   ├── 6988910c5ba6f327fb16c9e17ad82e5a45054ac2.nq.gz
│   ├── 6c07953c37669cf8474c504455fb9ec37f16339d.nq.gz
│   ├── 6ca3d4f24bcbc9e772a0b4da6de864ca92617ad1.nq.gz
│   ├── 710abbdf381d1f95a423fcad642873091798fe19.nq.gz
│   ├── 7119b639cd574dbfb5e19746f21c64beff13b239.nq.gz
│   ├── 7bab3a18a700d248ce37cdf81a999f2c1e160ed0.nq.gz
│   ├── 8048480d5423fd241749df94435d1f2108ba5d29.nq.gz
│   ├── 8109f8d44e2f688eb0c5528d8c923504a1ed8aee.nq.gz
│   ├── 82d55e7d15985b48f6777a79801f8a8cab464fcd.nq.gz
│   ├── 84b45b04ca56dec1aa8c319b09d3c62b29bda3d8.nq.gz
│   ├── 86a954d7f406817e133f56429c21d2ad72e6d736.nq.gz
│   ├── 8a5791831449724bc5db800adfe702b66287a323.nq.gz
│   ├── 8ac2ba272fa288ce19041797cb2e4b8d25949b16.nq.gz
│   ├── 8ae4715b770acd64331d993a36977f1920bdc57b.nq.gz
│   ├── 8fc4c93393569ac23186a30d005db6cb0b19924e.nq.gz
│   ├── 91df36d1c734fd88530b0cbbf4620fa7e3bd08b5.nq.gz
│   ├── 93447c3de7b2d915e1bf0c781c4667cc5052f85a.nq.gz
│   ├── 94457139f672a509e7a5ecc9231636cbe7debb55.nq.gz
│   ├── 95d9564a027a8e561d9904a65be21cb7c4d52a1f.nq.gz
│   ├── 95f47ecd3517968be3567cb5c2ed05600ebd7cf9.nq.gz
│   ├── 961b1ab248f60d666cd74f703f5b2793d906bf79.nq.gz
│   ├── 96c65334a23ae456c0bfbfcf98820eb5fdae1a0a.nq.gz
│   ├── 98a19c8888020002b9f9adeffdc5c12a77a13377.nq.gz
│   ├── 98f09950214c504ccfbf8f1de7ac9138025db577.nq.gz
│   ├── 9925f2198fda397c17509eb356bbcf004e6034e8.nq.gz
│   ├── 9d6eac27be46ed8f0ba7051bc83fb6615551b581.nq.gz
│   ├── 9dac90f04ba131be28025c89b65fe3170583f331.nq.gz
│   ├── 9f804d415c087af43fd3dcb2fa1f3b6e571d93fe.nq.gz
│   ├── 9f88cf17da6f855011553199a65540a06e58a9b1.nq.gz
│   ├── a0372620eafb503011b46f60ff442a4d6e0d5c29.nq.gz
│   ├── a65186d960a038494319295b10e71def8c9492b8.nq.gz
│   ├── a6d6b5b33ab5cd97d4cf5ad5e4c2dfb6ade0ad37.nq.gz
│   ├── a705e87e20a852691ba6352a2f5f9cc84fa99ac9.nq.gz
│   ├── a89f78e6b1045b1775288805f49591db0b049bed.nq.gz
│   ├── a8e26507d73f7b4335d988c29bc234ff5f9b6e93.nq.gz
│   ├── a960d6acc8cc63e58cf47592361d1be7b42e272e.nq.gz
│   ├── a9c319694cd4fa40f5dfaed74480aac564e3b8bf.nq.gz
│   ├── aa03643675dffe0c1627343faad6d2353c230ab7.nq.gz
│   ├── abecfac9ccf622f51ccc55a9f839cfbd1758b6ea.nq.gz
│   ├── ac6c515bdfa08d4b32635313fe765e1734620044.nq.gz
│   ├── ad1a8c6950f2bb0b4eaa5cffe31343127ab5017e.nq.gz
│   ├── b1c3b70d18d223f5a0034b44581c2ca5aaef52c3.nq.gz
│   ├── b2789cd8bbb2f50b16b0b44a219736681df7ee1c.nq.gz
│   ├── b3ddfa56a9d5388ea5308dbcfecb70605262d286.nq.gz
│   ├── b6647129c14689a78f06059c8dc5351f414de4eb.nq.gz
│   ├── b69706693527b65ffe2c7d81fc3a62ad4b9db4be.nq.gz
│   ├── b83716213d9bfa5c261b40384f7d0eaf7fc7e2d9.nq.gz
│   ├── ba2607113c0748a16275032738689ca725961fb2.nq.gz
│   ├── ba91089885cbf206a1109f406346a19190b8ef12.nq.gz
│   ├── be5410c385596621c5c838472d6d02cba5d97ccc.nq.gz
│   ├── beb4ed60460fbbcb0a127364298ad610f15eb0d6.nq.gz
│   ├── bf3cb7ffcc7b9c86dc2612e1170325dea37fbc16.nq.gz
│   ├── bf50e2e09c3ad3d31bb0b5ea57b87980302f0f25.nq.gz
│   ├── bfc2235f0ea210fa289f562db3afad1023eafbb1.nq.gz
│   ├── c0676f49d5a7efe0cce9eac5bdefa8193b7b388e.nq.gz
│   ├── c209ce0abd31af30f2bca7e4c11108c8b462d318.nq.gz
│   ├── c5bb5ab44ee3363868eff960d681755ce6d25a5e.nq.gz
│   ├── c6b56026a5637676c7de64c531465878e7e44dff.nq.gz
│   ├── c7e86ebb44d08ac95a304d0602bb5927c8c20728.nq.gz
│   ├── c85d08d3dfdc34dd1d202af3d33fba8c7a24f917.nq.gz
│   ├── caa0e78443b81b9b7e62322f3d1cab5d059b8b46.nq.gz
│   ├── d1a3251830189e9876b37736d8582d2a79dcb29f.nq.gz
│   ├── d967af3e05123630fb49432985788c33ec02afba.nq.gz
│   ├── da0bbaae5cfdac574d8d8f77e8c6165f5cbe23a6.nq.gz
│   ├── dd2ff4c836675e1932cb0c4382a08bedd37b0473.nq.gz
│   ├── dd90af54a0f823cab06188eb8a28076547f75115.nq.gz
│   ├── df63bdc000e61b3882dddee2e0e6c8c172b19813.nq.gz
│   ├── e4433453acec1289a7fdc6aa308dc6eed1d62a88.nq.gz
│   ├── e4f3a7118c9759273b12008fc3aea8cf2fd3426f.nq.gz
│   ├── ea3ab6aea05c7935f3fde8562627eeb2a2ce94ee.nq.gz
│   ├── eb1c4acab183cf806e0e30fe7d10c12f30519320.nq.gz
│   ├── ec1ee307bfb46e74b78e4cdc828cc47c2a5bf973.nq.gz
│   ├── ef063708a9b03b21f5e8c9b847b58992ff38fa0a.nq.gz
│   ├── f43100735787162d614471bafff824d0e1c36c5a.nq.gz
│   ├── f4797c8cf89d1d12ff6a14b9b2e0234b983383c8.nq.gz
│   ├── f5819b779944bb34b0fa865e228efca7c68614ad.nq.gz
│   └── f8ca5a8237169c890cfc0fface9fddefaaac887a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── db338cf47ad069d22cc9a0331ae433dfe2024e2a.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 135 files
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

[qos-ch/cal10n](https://github.com/qos-ch/cal10n)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
