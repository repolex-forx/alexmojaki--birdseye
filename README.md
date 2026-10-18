# Repolex Knowledge Graph of alexmojaki/birdseye

RDF knowledge graph data for [alexmojaki/birdseye](https://github.com/alexmojaki/birdseye), parsed by [repolex](https://repolex.ai).

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
rlex download alexmojaki/birdseye
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 753f6648db380c808534089ead648409dd94abc2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 753f6648db380c808534089ead648409dd94abc2
│           └── chunk-001.nq.gz
├── blob
│   ├── 04573c4c0c9fdad6c1446aabb455efc33ec0b4c8.nq.gz
│   ├── 0812038a16880b74b37ebcacac513772e463b80d.nq.gz
│   ├── 08d33a1980919c1fdee700cc13c1436808ae4528.nq.gz
│   ├── 0945a6afbd48830c280ddf2ca8829c84c57194a4.nq.gz
│   ├── 0acc96a325a694b788f56970fa79d8a30cd752b3.nq.gz
│   ├── 0dc68033d603ea45632ca18d5231e38b2aed994c.nq.gz
│   ├── 0f13cd58bd060ee4d7987ac332387a00c316793e.nq.gz
│   ├── 0f297dbe3e6d1d0c7d2574121da85795ac1886bc.nq.gz
│   ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
│   ├── 17c116a417ead801be8f8bc10b1ffbb53983d5c4.nq.gz
│   ├── 1afe86226712a8119a4061dde676fe003c4ad67d.nq.gz
│   ├── 1b5b2fde42f8ea14e6981339196a9d62b681d79e.nq.gz
│   ├── 1d7a0ba4315c305f4136f3ac5ec466d52464d16c.nq.gz
│   ├── 21ac81e58016f1386fc3d8f8520df3c951f72683.nq.gz
│   ├── 2539b4c808be1afff95b615cc18ca8182c835225.nq.gz
│   ├── 27e7691618100212f7b23daa3d5d7054fb0d4cc0.nq.gz
│   ├── 29d73372deca5a2cc344fddf01e4c6745bacc377.nq.gz
│   ├── 2dcdfa721902456f610795a05c4aa3f0897a27b1.nq.gz
│   ├── 31d040423d48d13f2e2e58551978c50f31ec98bb.nq.gz
│   ├── 32e5592706d8b8bd952fb8d750dac042ac79ff1e.nq.gz
│   ├── 332e8d05f2abd5a7a20649167cd3136a527ec283.nq.gz
│   ├── 35ca59ec5e6bb87b3418d610c174b69dc26b4629.nq.gz
│   ├── 37575a96fb6ab98c5c417afd160480ee4b5cca8e.nq.gz
│   ├── 38124cf96da4ac1300548c60e4f3917470be03ac.nq.gz
│   ├── 3d5c53fa1050bfcaec410ca849290a8e0bf2c52a.nq.gz
│   ├── 3ee3e5d148ce87ce72fbca8d61ef330709ce55d0.nq.gz
│   ├── 42eb4101e514e6e82ecd5111fe09e81a786de694.nq.gz
│   ├── 4406012960274d701e38f8c268718feac1eef110.nq.gz
│   ├── 448b43092dfdc8dd3a5268e0533fd6e0adb31e66.nq.gz
│   ├── 4758678053b7b65a466269603263f2611a26be6e.nq.gz
│   ├── 4792f3be24f99eaadd31415b4c6982edef1a45ba.nq.gz
│   ├── 4bac12b121b55f3161bdc39b494fd876a76986e2.nq.gz
│   ├── 4d9beaeb8f2829c1c8dc9e6fd4b7ed9c7c5b22eb.nq.gz
│   ├── 4fc1f7765cda76982c474125d41a6c8d895eadfc.nq.gz
│   ├── 527c16c7fb0aab69a8c37ce793f7ab751dee47a4.nq.gz
│   ├── 55821540828f5b14e708ecce0d58c6369cede626.nq.gz
│   ├── 55fc22fccbde57f43c80022e8a7995eb49f8306f.nq.gz
│   ├── 5ab5c79631bf0efeb9612761f5b2c20fb2071ace.nq.gz
│   ├── 5c9e81aa14f7bbc580e71c44c048f23357542dea.nq.gz
│   ├── 62b0737d3122fa52b4a64217321e51f2e3bf509f.nq.gz
│   ├── 64539b54c3751a6d9adb44c8e3a45ba5a73b77f0.nq.gz
│   ├── 6d4624b9584efda566e2098547f1f70b8331f356.nq.gz
│   ├── 73c66af26fe2633af943530ff00d0ceb37133b86.nq.gz
│   ├── 740b35cf97e452342f1b8dd84b9f7a5f2fd0e9ca.nq.gz
│   ├── 757a3a2bd442a81d0ff0d6c8279606cc4287dbb4.nq.gz
│   ├── 7725080434a907829caf0c257d8c0cecba53f05a.nq.gz
│   ├── 782f199cda86e9119a037d52e555e63e831d71b9.nq.gz
│   ├── 7a20e188dc8410aea76330481ea608b0481a0393.nq.gz
│   ├── 7f1a1763ca9cebc7bc16576d353d3284ee5d3c7d.nq.gz
│   ├── 85c12adc8f82d2bc71d0968c8d5388f04ec222a4.nq.gz
│   ├── 88192e57f633c982bb37e4afc29c5b30930ab657.nq.gz
│   ├── 8a2e99a535d47e5798b167d1074ae2c77cab21e7.nq.gz
│   ├── 8c1e966370496b6faeaf403acf4603df51a0382c.nq.gz
│   ├── 926110b135ec4ec208ba2220c6989f065a27cdf6.nq.gz
│   ├── 94c70cc15cd102c74fb8111b853f66ce20494af7.nq.gz
│   ├── 94fb5490a2ed10b2c69a4a567a4fd2e4f706d841.nq.gz
│   ├── 96e5203393ac9ea98b29f8e563b8b173cf8c0c52.nq.gz
│   ├── 975352dbf3b6ec12ad7ced4340c7c03347370bd7.nq.gz
│   ├── 9936efa8b63565e5451cbdd8cf306eb41c29c8de.nq.gz
│   ├── 9b2a322c08f0e0b666afcc9bed61cb0b685d79ba.nq.gz
│   ├── 9b9f0c45292925a94da25ad7a012133005efec9a.nq.gz
│   ├── 9e612858f802245ddcbf59788a0db942224bab35.nq.gz
│   ├── a63f44869381d3e0e024a081125b036101337b70.nq.gz
│   ├── a65611f5d5fa3eccfeea1bb706ee122e49848332.nq.gz
│   ├── a7a9aa2f25c2fe6af4fea752fe34a9c19382a784.nq.gz
│   ├── ad8a0ad12861e197e1880d9e8461d54318a3e129.nq.gz
│   ├── adb7ca7e76a3b4f3bfb1c19bec904b04e31b29b9.nq.gz
│   ├── ae0c48e1ba877dc092b9c58a7121a09e149ec6e3.nq.gz
│   ├── ae4bc0174307cf6c08ab3791437233ebac243a7c.nq.gz
│   ├── af6ce295b01303be4a870922d653d3cd2c2d821f.nq.gz
│   ├── b29332f945b859cea0075bb69e8bd5c1c113f05c.nq.gz
│   ├── b53f99ca1e40135757a384db5521c12669216bdd.nq.gz
│   ├── b770743f7a288d2443128c2ea20f39482d3d2481.nq.gz
│   ├── b93a4953fff68df523aa7656497ee339d6026d64.nq.gz
│   ├── b9b8f492f9a53e6e6f215bd412df65d81d29bc84.nq.gz
│   ├── ba287f20e3a0e1f55621c49425765a4595ed34c5.nq.gz
│   ├── bbbc09e5ee99fd01313f68acb63e673e4706ae69.nq.gz
│   ├── bc725172489c56dc679d7f49756cdb116542081a.nq.gz
│   ├── bcdc7a650d9e2c699e08ddf542f0762753433bc5.nq.gz
│   ├── c155f5f142f332f1302e68c2e6afd280814c541c.nq.gz
│   ├── c2dfb839f0e5a338610c9158041ce0f055f8b994.nq.gz
│   ├── c8e298b4672b99ac65185329912a63f2a52b97b3.nq.gz
│   ├── cad925e7bf0ed05b96b1c5909b515b91f3924552.nq.gz
│   ├── cba881502ed17bde5f07a0c68382546991dc25ba.nq.gz
│   ├── ce508397c4ac9103cd74954f2a87c9c2a007ca3e.nq.gz
│   ├── d2d8ca4790e52b0537f3cbb7dcd766099b789583.nq.gz
│   ├── d5b573ed461d0815adec4894a442795f3210a352.nq.gz
│   ├── d5f19d89b308d36ee9e27b912015b0f75ec2f03f.nq.gz
│   ├── d76cd40d11db927bee9165eccfe7aab40a1b9adb.nq.gz
│   ├── db25abe44607685853dfbbe0ebed93b7b7809794.nq.gz
│   ├── e0b6ec3303a8925cd381f8caa40b041c42903afc.nq.gz
│   ├── e4950a070fdf83c33dfe517801ea8a423647a33b.nq.gz
│   ├── e63084632e00fda3fff2afab9fa539bbb0d720d7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b9784fb8e296ef9f797a22990801b0055e7cc3.nq.gz
│   ├── e8f768a83e0eb90edb279295719ce70cff518b50.nq.gz
│   ├── ea4ca8038ddbc766263ee5983f71442b930d50b3.nq.gz
│   ├── eb1db46fb25a553a9628e9be1bc8cb86470c369a.nq.gz
│   ├── eb86901d4527185a293b41abe9f02ad9e82d8066.nq.gz
│   ├── ec01fc363d5ad20cb912f09a438a1abf9e02d361.nq.gz
│   ├── ec7cb31801c239309e68cc1388798fa432c459e0.nq.gz
│   ├── ee6130da8822158233973227ba95b8bef1992178.nq.gz
│   ├── f35f3ad657bffba4356e2f1cbc1742b40c1b938c.nq.gz
│   ├── f387078f59bc4b73b0eb13100967967989ea7cad.nq.gz
│   ├── f3adc9f1bc1a7791a752bc2654137ab78391a172.nq.gz
│   ├── f48bbc021ff73e36e608dbb04d721cb77303bbbe.nq.gz
│   ├── f4a88a82c609e51baac8f3fbbf7915e86466c733.nq.gz
│   ├── f6417b73ea6a8835b5b4352e295b78203240641d.nq.gz
│   ├── f7576c3a5eed03e0c24969f0d7f48a1b5e42fc7f.nq.gz
│   ├── f88cc80b71e4dfe3fb0f1d104e9435990356ccba.nq.gz
│   └── fa95f5ef798f6611188bf25ee514da27b83cad03.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 753f6648db380c808534089ead648409dd94abc2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 119 files
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

[alexmojaki/birdseye](https://github.com/alexmojaki/birdseye)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
