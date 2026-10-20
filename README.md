# Repolex Knowledge Graph of klen/muffin-admin

RDF knowledge graph data for [klen/muffin-admin](https://github.com/klen/muffin-admin), parsed by [repolex](https://repolex.ai).

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
rlex download klen/muffin-admin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2b1f600d0874e4589319779c54f8b4754e396ad3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2b1f600d0874e4589319779c54f8b4754e396ad3
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f16c8ec8b9850f6c5b3d33c45d18289a84fa87.nq.gz
│   ├── 056436c784370f6b47c4f5c12a18297481ad27e6.nq.gz
│   ├── 064cf150752b73bfc3a01e7687fe9fe9cab03b30.nq.gz
│   ├── 08485577a1df8ebac7ee2776c4413c0b5f13d178.nq.gz
│   ├── 0a6ee958310ca78a98bf4803c291d5898c7fd5b4.nq.gz
│   ├── 0bcd51badc6a1a4651bab6b4d997fd401aa58270.nq.gz
│   ├── 0e7d3f0fcaf867ecb4363753c13be7e5f14bfccc.nq.gz
│   ├── 0ea54d384d1fb065826cf08ae68541260a851996.nq.gz
│   ├── 0fb8d82d47ce924331cd7d62abff6f705e59cdd8.nq.gz
│   ├── 10513460803189e62991029d0de9e0fb26569a54.nq.gz
│   ├── 10591cf96ada627cf08c18f8fe575ef6dc4f6d55.nq.gz
│   ├── 1101ec5d993407baef945354e77b5f5a2a4be629.nq.gz
│   ├── 1e65bade39adc19e4ac751190ad812ca01b20677.nq.gz
│   ├── 1f84b002b2aa83530eff53aa5a32414331a87bdb.nq.gz
│   ├── 20ddebd451337749e32429c19e8119bf877aa3fd.nq.gz
│   ├── 21489b19b93150b9fdd6246e9ab09e4ee9daa148.nq.gz
│   ├── 224887cfad1b2793a12c38b2338c7436386bad80.nq.gz
│   ├── 23c5c150f58bdd129447223d88288e859f8cccb1.nq.gz
│   ├── 2ca56e53f9fb1489befbbe5843193fcd85b4fcd4.nq.gz
│   ├── 31aa9a5760c889c682dbb5148305290f88589978.nq.gz
│   ├── 32af91f541af95f83a010582e154bfa22c12a6dc.nq.gz
│   ├── 3445692b16bc16508361e232e1e5425eb09c7eba.nq.gz
│   ├── 34722054a51013064712b0260c8ad80baee8cbeb.nq.gz
│   ├── 37cedc0861b6661ba68652cedd17637776f5c0f4.nq.gz
│   ├── 37f7b1609ea9f2c970b84b7b377e04565d4d58f5.nq.gz
│   ├── 3a0ca9e010d0af18a971738bc1b9c3735920c8bd.nq.gz
│   ├── 3e51acd03f62e91cde06e79444faa7376c514cab.nq.gz
│   ├── 4184791b2049c08139a188cc85d0a2828716e806.nq.gz
│   ├── 467beecfe91baf306049610b436afae4bde7e7a9.nq.gz
│   ├── 46ace36cff7a8a28aa16fb7e96a11776834f94fa.nq.gz
│   ├── 4ed4dab49a947e7eaf44fbf1a2d251c157da01be.nq.gz
│   ├── 50f254be4800fd5965a5eecbd795dd7c66981224.nq.gz
│   ├── 53654c98464063f1b03f482a7f00a4b970844988.nq.gz
│   ├── 5a371001ddb5205da43ed2177380cb832707442f.nq.gz
│   ├── 5e81d894e407bd833c68ecd36e059b440a655953.nq.gz
│   ├── 5f1d5686f3dc12105665875988bbe0b90d32c2bc.nq.gz
│   ├── 609dc27bf303ceb264af4f4750de37a58667cea1.nq.gz
│   ├── 628643d280064f502ef7343509121f1ff8154a46.nq.gz
│   ├── 65e1398e88a705cd3dcd6e6a66d41dfcb9dd7db5.nq.gz
│   ├── 6639412f1bcfcd687bdc6eb42b1875c16c2c229c.nq.gz
│   ├── 666ce2a519fd8f0c3599a11f968422b82612ca92.nq.gz
│   ├── 6a73ce5ebf966b291d648e8d552682ff957706ec.nq.gz
│   ├── 6d76399a9fed618341a3781288e707a855c65d3a.nq.gz
│   ├── 6fb2d2541355e631d6ea97380b68a63674e6746e.nq.gz
│   ├── 72255c54dd7605eba75a9a649b92a7c109b0a6ca.nq.gz
│   ├── 7408563540315ef04eaa4c69369e10313dd6d3e8.nq.gz
│   ├── 76663dfcf647ecf1776624535f983ac7a0625374.nq.gz
│   ├── 76ef7de4ef28f5d963931248eee59239809fef22.nq.gz
│   ├── 78df056a6afd6b2f7c5a8695635380a19f30acd9.nq.gz
│   ├── 799f63feec38d330429d9467f517a042cbcf9173.nq.gz
│   ├── 7a124b0e5194bbf7cf7240b6dd5b9151e622554e.nq.gz
│   ├── 7a3f07ab83552f47a8705fa5d22729a324a2f71a.nq.gz
│   ├── 7d43909babd0136bc3cc2c91652da53d6f978080.nq.gz
│   ├── 7dc82305f938323db9dd4e9182d80a743ec70003.nq.gz
│   ├── 7e7311ae1ad29ecfc4602a542bb2c90437587c60.nq.gz
│   ├── 7e7f5c14d0d4d38ac46d0baa2d4e56f212e29100.nq.gz
│   ├── 844b7e00cd5920bd3f77513f66da2ac9079971b0.nq.gz
│   ├── 886ad3b198614e1a64d1a3bae80f53c9cbda9f5e.nq.gz
│   ├── 8cd06f9e65268edfc98b35793d324e612253b565.nq.gz
│   ├── 8efb1a85f01b37a0d9492b39d00e9891476fb0f7.nq.gz
│   ├── 8fcca2a2082d0b18d7ec88b496849d7221695500.nq.gz
│   ├── 90b529eaf2f48e34f578406352f17fbae4edc29c.nq.gz
│   ├── 90d0668e9838fe1f9c07ebc810886c825ac7632f.nq.gz
│   ├── 9332f4a5870096e23f84f0850c51d179221c333a.nq.gz
│   ├── 934f1e0a88cdb9257c98055b4c00d4d541d10233.nq.gz
│   ├── 93cefab75b026ce5136b1ddecdcbf932c9ff7628.nq.gz
│   ├── a00da0f6af0d49088363ed226cd51352d9d2e582.nq.gz
│   ├── a08358295ed7d66c676c2b53040e2677bc067575.nq.gz
│   ├── a140450694f6f2a097e5c673d674bad044eaa151.nq.gz
│   ├── a68827cf23ae44006d530b488ad85ae283232ddf.nq.gz
│   ├── aa220556e22d7ef6fc2e86de2ebaa1f4ca8b7b1e.nq.gz
│   ├── aa7e0a7e29c1f2b30ab3144b60e0484fccd1cc5e.nq.gz
│   ├── ac13fba5ba1b796004cf37a5aae9c58dfa1dc357.nq.gz
│   ├── ac5e37fa085bae49c9a5e30eff113300fc6bd1d8.nq.gz
│   ├── ad0867fda4eedd69ef8c16e41a414ac530f6a9c4.nq.gz
│   ├── b5a78cb62498673332ebfcd2e65597ce8d3941ad.nq.gz
│   ├── b5bc8eac82ad42eab1bacd5d67a9271c32731f3b.nq.gz
│   ├── b7add10c2dacf8914a5c83e3622453bf9bb14c54.nq.gz
│   ├── bba8a533038615f2aee0272dea9571cf0fad2a24.nq.gz
│   ├── bcd4682cf8caa0310bf6944f3bf77830d80fffef.nq.gz
│   ├── c502c8a8ebc60f908741e289e226c5cbacd96abe.nq.gz
│   ├── c61edd1844b5bc21254d2ee9b185e657aa44c4e7.nq.gz
│   ├── c65d6f999fb9da0c96dffd90aed5c5d20a81cc6c.nq.gz
│   ├── c66026503d901d5c3515d012a5d241e85b475a38.nq.gz
│   ├── c6b287174ac018ce9b3d4dafe31864ebe8faee90.nq.gz
│   ├── c74c67bf8d84469c8a67019670e65272aedff8d7.nq.gz
│   ├── ca6df8593732db444eaa56972da388d5b50675ae.nq.gz
│   ├── cae16b088076fd925ab27357930c3ba129069c9c.nq.gz
│   ├── cd3ca4088139878533c2a76ff127cdd1acb64a6d.nq.gz
│   ├── cd45db43cacc41a71d6cf0b45123f234ef976272.nq.gz
│   ├── cd606e9d9a69847de5e7f403b389d3a573d207fd.nq.gz
│   ├── ce48f87110f5a00c4f3320f9ed0c8e630cb23daf.nq.gz
│   ├── ceb3bb2f0bb7a09d438efa73a06534d235cdb97a.nq.gz
│   ├── d2551b1c1e69917832b7a9de9c549cbe14e350bd.nq.gz
│   ├── d6376bfa4d916a81e9266bd1e306d719b4ceca93.nq.gz
│   ├── d741944300caf2f2e3f74562c1c59b3b5a20b1ee.nq.gz
│   ├── d775f739714d25f5460c9037749947e6ab84c899.nq.gz
│   ├── d7e961ee2253097f7099832ef2f7055ba4d8cecb.nq.gz
│   ├── dc500d4641729c6d456f38902aab6086df7c52fd.nq.gz
│   ├── e43846fc653c60e115da3344b6f3151cc57b81d7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e75959a493bc534b110af24a3fa321c67526a2.nq.gz
│   ├── e728d03676c20ba87a39556e60b642f5df17ebde.nq.gz
│   ├── e784eed8e2c0955d078faff37752a2fe7eddb308.nq.gz
│   ├── e849bd5b82a85ce0064add407ad1fac77efc8ac4.nq.gz
│   ├── ea391c640b429b8e5d24ff62d893952938ff002f.nq.gz
│   ├── ed63a73bb562f984dca73ed599c71bf856d0884f.nq.gz
│   ├── f53d8a9631e4231ee64e252d894f645d0e5f8b20.nq.gz
│   ├── f8db2c9b7ef997dd88dfd3f5568082efb4923965.nq.gz
│   └── fe6cbc873ec7aa1acbc27d6564c1477643874929.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2b1f600d0874e4589319779c54f8b4754e396ad3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 118 files
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

[klen/muffin-admin](https://github.com/klen/muffin-admin)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
