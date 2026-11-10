# Repolex Knowledge Graph of PowerShell/PSReadLine

RDF knowledge graph data for [PowerShell/PSReadLine](https://github.com/PowerShell/PSReadLine), parsed by [repolex](https://repolex.ai).

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
rlex download PowerShell/PSReadLine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a2d143f78904f8a954f8d4b055e55ceca6939bfc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a2d143f78904f8a954f8d4b055e55ceca6939bfc
│           └── chunk-001.nq.gz
├── blob
│   ├── 02482876d3a253a19ff55ab2aea1de3782f00092.nq.gz
│   ├── 064477a930601d3bac2e49555344e117511f5d32.nq.gz
│   ├── 06447e722319d3332f2727f31c1cb2d27a763214.nq.gz
│   ├── 0754efd398a588b29f9e751a44f5f95bf50d43a6.nq.gz
│   ├── 0999a6cffeecf5dcb35f5178f8ba18db27e10e91.nq.gz
│   ├── 0aabcb43a97bee7b47c2c470f3dc558552988d69.nq.gz
│   ├── 0b99add8218865e9cb4fb5366cd7aef80ee8a22f.nq.gz
│   ├── 15c9884da723cd076786b4638ee3084caa0ceadc.nq.gz
│   ├── 1659f38789c4ee9708569cd133fca345a4845bcf.nq.gz
│   ├── 1a6c43a2f1cf05aa22d9353efcb4361b21d12cab.nq.gz
│   ├── 1e3f9dc0a114086c2273af31110748887b1a16f2.nq.gz
│   ├── 215fd61cba8131d27de86e83869a2871c65f5d7d.nq.gz
│   ├── 253f7fbef78bf574c2de443e77d23c3f6cf107e9.nq.gz
│   ├── 27c16b88342901eff93098868567883d4a002dc8.nq.gz
│   ├── 27dfe795665c92d122cb62ceced0047246d70186.nq.gz
│   ├── 29e4629ad14ee8e4efc33485a5b0b83005cd9268.nq.gz
│   ├── 2aa32039c316f31bf6e7d21ce2b0885767937844.nq.gz
│   ├── 2bf72eb61aecbce4cabdedc1317353bb07af58a7.nq.gz
│   ├── 2c48305b7ebfacab31ce047af013052697fd778b.nq.gz
│   ├── 2e3ae1b5752a73004583865ef3fbef92774f69ef.nq.gz
│   ├── 33c3ad17fa5e14e1d88f4402bb31baa698e21d5c.nq.gz
│   ├── 3452c4625ca0224a78a001d4850bb5d411c23893.nq.gz
│   ├── 3761c51996477b2f2df968e62b3d3f3a0b144350.nq.gz
│   ├── 38025bc4dc3fc9acc566e0d54e40cfa539915e4c.nq.gz
│   ├── 38648f72f30398cad3743499a0ffb17b7cf599ef.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3cf7aee80358b16d35c06ad80689d6aa77575e12.nq.gz
│   ├── 40320a97d4ae2e94a2e22ec9490d3503c2969fd1.nq.gz
│   ├── 421ab34549d20198bc46d2bd870e5c7a02cdf87c.nq.gz
│   ├── 47544dc2a5aab6a8ac0ed021290c1bc982cb0cf2.nq.gz
│   ├── 48df9965f2eed578997ccc3cd335a2d2993f3a4a.nq.gz
│   ├── 4bc7dd076a2d9cb9a68dbcb687015f6339bfaed5.nq.gz
│   ├── 4bf4b99a01dd8f42532430fef7960ac19f232396.nq.gz
│   ├── 4ce7eff732553959ae774a3e363fb4d956a0e2a9.nq.gz
│   ├── 4d54be2067c48a7a90ab4f80c75fcc3145f37f02.nq.gz
│   ├── 52fb53194406d3a88e8af710fd4032884b7dd799.nq.gz
│   ├── 542a37b7d981e18b3fb509bec720e113e6732595.nq.gz
│   ├── 56261d5b66ab08dc81d97b861bc7d5353a3a9eb9.nq.gz
│   ├── 56776ea9a1eb847a7d3e14feef4bd2835c73c58b.nq.gz
│   ├── 571f06f5cb61339e8f276d494c93bf908c6eeb9a.nq.gz
│   ├── 572aee80f24ea02474e045b7c5a7c8259661f280.nq.gz
│   ├── 5927ab9dadb8331a33c8057a607d04aa1cc315da.nq.gz
│   ├── 596b1548ef9e5a68c7568247c18bd78c5dc8de57.nq.gz
│   ├── 5a475c19f60bef01f55cdc5b00b0cb969ba10790.nq.gz
│   ├── 5a47c6608629b813c809c41163de1219e9adc924.nq.gz
│   ├── 5c631d5e2d4784880dcd34583ada626c5368afb5.nq.gz
│   ├── 5f67de71cc37a04b338b7f6c9749023f3dad2bb2.nq.gz
│   ├── 60e6d939281d0cea53653bd8f7d08528fdff9f0d.nq.gz
│   ├── 6149b17ed314e94d481d83967c2e066d70cbf1a0.nq.gz
│   ├── 62867e762bbad28fdbf401e61ecfb2faebc44e67.nq.gz
│   ├── 643afa5d31516c11b1042a53bae92e8b027404df.nq.gz
│   ├── 66bd590de3d21e754381e5df9c8238fea93fef26.nq.gz
│   ├── 686e5e7a090b52f0db9acbe001915d0b9b06b06c.nq.gz
│   ├── 6da7e8617800f81b60c4c9125c38e7df533f1b06.nq.gz
│   ├── 6e21fbbafe2d15ae45f7b06e5b791d4fec01a577.nq.gz
│   ├── 70cd80e476d96f0714936f5785f2a0e10d83f838.nq.gz
│   ├── 74c76ac0081e9edf935a9d5695be22159a190073.nq.gz
│   ├── 788f6fe358ef26307db9d38f668fead168ed638e.nq.gz
│   ├── 79a6ba5925807432444c981e0d902389debe18f7.nq.gz
│   ├── 7bdc34a88494ba81502d56b2f75e8aaae69661de.nq.gz
│   ├── 81cae6c6d85b640eeaa4f12eaf3f2f677cc0acc0.nq.gz
│   ├── 8287e58c9f48c6cdab41e446e47e4b4fa3912fda.nq.gz
│   ├── 84ed4dce393a2cf862a1587e4b5a1406c4f9cd26.nq.gz
│   ├── 8617f79c014b346916f41ca9f5b5dee0227c5a11.nq.gz
│   ├── 866d9612031214c8d309b4d863c2f121465e0cce.nq.gz
│   ├── 87795354216f4ff4c68c18a3d48769e26e42eb20.nq.gz
│   ├── 8871b2179cf07e0627a81142c570f3df369ca7ce.nq.gz
│   ├── 89564228ddc5d6e761f2d3a0477115a1205b94a7.nq.gz
│   ├── 8fab92e1b2671170faafb9b6547919ff9ed347ba.nq.gz
│   ├── 8fc56bea17e3c40472cff60c5d5f80a529679154.nq.gz
│   ├── 921ff15b586fdd0d76d92df77c766c72c50f63a9.nq.gz
│   ├── 95f4748f0e1121a5f12075c3ad8c3c57cedfc6c1.nq.gz
│   ├── 9906986718fc0530b412639fafd0e9f5d10a18fe.nq.gz
│   ├── 9cf057c822ab4da556e0246142914683f6219e07.nq.gz
│   ├── 9fcad95ffee8d3e195ff79804567a23632260bcd.nq.gz
│   ├── a02ed783ac22d8beadcf3536a66f8c170f7bf684.nq.gz
│   ├── a0a4269621acc2c09d88df71ad8bdb5019630966.nq.gz
│   ├── a10ce9b3d0e1cb72ab3949f7014e3e6979b2f22d.nq.gz
│   ├── a43e8f6a5a91d1ca1a6d9c6cd703368edd1c342c.nq.gz
│   ├── a7d1d1174d96c5659a8dd2a45c9b9f6bcb7ecd5b.nq.gz
│   ├── a9145c4321c41d886cd85ffd6170dd200c4c1d43.nq.gz
│   ├── aae6c0f52768c2f305959d6414bb76391744b70e.nq.gz
│   ├── ab3faaea3bc4dd85b2d1dfb3c6383aedb938c7e7.nq.gz
│   ├── ac5c7836f4c1aa35088d7c385cef0bd63f79c318.nq.gz
│   ├── ac672d3f787bc3a9e77e5217c719747fd1c1ff94.nq.gz
│   ├── ad6b95f0c56c8e82ef1c778f8ee2f97acedc4971.nq.gz
│   ├── b85963793dcbd9f08fbd44f66e99bc9f3c3c1304.nq.gz
│   ├── bc37b540df665b773f6873ab41d061cab1c30d7c.nq.gz
│   ├── bd1448b9a95255d70eb1a693c30d6c8339207d5a.nq.gz
│   ├── bdeda4c8cb83d1ce4ba009e294c0650aff20b5e0.nq.gz
│   ├── bf0c85b727e75d1c17ca903de65e74d0c5c5b74b.nq.gz
│   ├── c1490a23086fd514dab39d98ec78a393aa2dba83.nq.gz
│   ├── c1531f57a4909c540b1066d014277fc20f473070.nq.gz
│   ├── c282b14897837b993af6fdee9b14e6f82184ce8e.nq.gz
│   ├── c531682b04295aab3dd8a83495f178894e2b9679.nq.gz
│   ├── c6654f9241c0d18c1749318015a3e5b00b8c1ef2.nq.gz
│   ├── c7308ce589537e1628d11aa613728bb886b2e98f.nq.gz
│   ├── cc72f367daaa619096d53a81906b832279195668.nq.gz
│   ├── ce737fd345dffda0767d3193e0cb4a2fdc2a3a90.nq.gz
│   ├── d0f91fa7135e7f8973dbc8c8295c4d74a07bad17.nq.gz
│   ├── d1ab3d11ca3e08539e2d630d8be781ed185cdcaf.nq.gz
│   ├── d2bb1036061e7ee93c75a69cf17f68d1ef631e8e.nq.gz
│   ├── d38e44bc62adde9ded46b66eb87266c80c9dc386.nq.gz
│   ├── d59fdd5cc5da67d27c8f315353cb822e3a22050e.nq.gz
│   ├── d67ca619bcd3362d4046982ea912c81e9719e3d0.nq.gz
│   ├── da52230e601c2c6ef9342acb125e791e38b02741.nq.gz
│   ├── da890bbba675f2fdc00bdd7a99cdb678b03afb1f.nq.gz
│   ├── db0f855cbf49c18d9d5465bde08c121f4fc2b935.nq.gz
│   ├── db1cdba7eecc9c5827d73661ff135901275fd542.nq.gz
│   ├── db61451647394843da26c63dd3547057f5e30229.nq.gz
│   ├── dc1d1b455c2e79d0cfc232b4c749c3565244e126.nq.gz
│   ├── e4e311e80ae8c4318e1e6160476ad73ab5e0efe1.nq.gz
│   ├── e619e7c06228013c919514c32226e004f65fe649.nq.gz
│   ├── e84be99a5f29789385a9c76067ec1232d026e87d.nq.gz
│   ├── ea9810fbc975d32ca2c83bdc8ef0c9644b80880b.nq.gz
│   ├── edb39c91b493d8c7308c6f53b6879c0231b09710.nq.gz
│   ├── f4df4c8e53e0014aff2c7f6f5d3d8a168200276d.nq.gz
│   ├── f7c68f0a5516e2d5097f09b9ed2fe36fc8f4dd34.nq.gz
│   ├── f941d308b1f805de5ddfab1c7daa99a98a2be490.nq.gz
│   ├── fab7586d73ec8b1804291f6bea46c36194149e38.nq.gz
│   ├── fb0d46c89888ae099953692b599d90a70b44b6a0.nq.gz
│   ├── feee51172e81fc1b4969532d70641f8f8b5e91ab.nq.gz
│   └── ffdf0241ccb0e30ad3fee4d8c6dbc97d45a8c275.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a2d143f78904f8a954f8d4b055e55ceca6939bfc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 131 files
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

[PowerShell/PSReadLine](https://github.com/PowerShell/PSReadLine)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
