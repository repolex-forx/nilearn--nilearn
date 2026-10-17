# Repolex Knowledge Graph of nilearn/nilearn

RDF knowledge graph data for [nilearn/nilearn](https://github.com/nilearn/nilearn), parsed by [repolex](https://repolex.ai).

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
rlex download nilearn/nilearn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 44da9ef86a8edc11c8570fb8e3e078ef9561787d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 44da9ef86a8edc11c8570fb8e3e078ef9561787d
│           └── chunk-001.nq.gz
└── blob
    ├── 0050afac18bbf6dcf16d1ef1b8fa1e0fa984c9da.nq.gz
    ├── 007a97a100f4058fb8904d1727651c5c039fcb2b.nq.gz
    ├── 016592fa19c788165644af8550b720922bc5d456.nq.gz
    ├── 01f7f47ff655a7f0b55dc7f167dd2637ebd7f093.nq.gz
    ├── 0295dfa0bcb4ddf11ef0caa1f3d86a093d450a6d.nq.gz
    ├── 035925adf32b2f5e8223ce93b524e176870e59fc.nq.gz
    ├── 037a2275de1bb9b4c94f6bfdc2c3eaa32dfd2b5e.nq.gz
    ├── 043f5afc157789fccd9cd2469077763c24726662.nq.gz
    ├── 045cee88afe96a860c9a9d282fca082f4f887d6e.nq.gz
    ├── 04921d24a82526c92f1c81fd5b8fa988dbb2e580.nq.gz
    ├── 04cc857ce154576254e997ec9a85952b8be74318.nq.gz
    ├── 05640b2d5922a39f13a0389f45988e8a428a078b.nq.gz
    ├── 065c2a2fb3d3987b0cd2291b0aab362875379184.nq.gz
    ├── 07278b4a965e87fa15085d4654593dc08f3674d8.nq.gz
    ├── 08816ff94cf8f82271c91b96387debf1f0ad90c4.nq.gz
    ├── 089bc319292ab2f0b68b6eba045eaff974c6c30c.nq.gz
    ├── 091a01b9524da8454c60e2d3c64d7bad7fba82ee.nq.gz
    ├── 095f1d7a70898c3db8ba169bfeffb0f48a923de4.nq.gz
    ├── 09d1e83807fccea54f8242da768bf22d49aa4ef8.nq.gz
    ├── 09d6ae080be4f0bf2b5daec2e70ea6c368f5965f.nq.gz
    ├── 0af768e93c77c1f864b0fc7429c05b4b32ca2a98.nq.gz
    ├── 0b9ae854c00814a862d8d7c5413944796a77045b.nq.gz
    ├── 0bae9cb950b4a19f54e7bc2f9242499ec1a9b7e3.nq.gz
    ├── 0bc0923d90329089bc02c89e4035adb02138e16d.nq.gz
    ├── 0c3b32b0cd2c771e19e1f826c32e6d2b8a9db3cc.nq.gz
    ├── 0c6fcc84fc52282802d54bb71953b216eadd10ee.nq.gz
    ├── 0d2965ebd0977b47b2b66e3015c4243919a0ce63.nq.gz
    ├── 0e741004fc2cd624f87338122e235b5c4b49434c.nq.gz
    ├── 0e9206078b4ea4abbd601da300d23da2c5292a30.nq.gz
    ├── 0f121a6405e17314185f4bdf861d234df3cd08ca.nq.gz
    ├── 0fb1b84381319b59de716e568f0ae44ae6235638.nq.gz
    ├── 10b26b98814039ab654827450917d6eebcd15b10.nq.gz
    ├── 10f92d8bf55c12ae14d1c2d81bf03492959e3f92.nq.gz
    ├── 11bd9a01e749741dbffe61b9e94ca377997f11e9.nq.gz
    ├── 121d04bc57c9c9613387317a8bc2b9e0883c086e.nq.gz
    ├── 12d34a920d4bc84788b8955879c2ed98870e8829.nq.gz
    ├── 130c9408208206c60c4fb3b1095d4ae8740d01c1.nq.gz
    ├── 131e002dfaf5e28e8593e7ac59c417457c0bd874.nq.gz
    ├── 13813e1cc95e36dbb5c42b6579ebfe865233e3cd.nq.gz
    ├── 13ebaf602ebff525a5021c583b9f97c3744a1b7e.nq.gz
    ├── 153355ac010deb6b96dca405ad8c1d5d10041a8b.nq.gz
    ├── 156976f1fb581a49cc960db76d0e9d3ce0aff2b1.nq.gz
    ├── 157b3ef7357ffbe84782d901b9fa109de153d162.nq.gz
    ├── 15fe35edeb4d7f0ed0876d1608c38cd3172a9eab.nq.gz
    ├── 1656065eddf10671f38878d6cd480fddbb3655e0.nq.gz
    ├── 1694083ead159a9e5b9dd0f247dd050a44c3c916.nq.gz
    ├── 16a8e73f1e69badc3b773d2c2d0cab8e64e5858a.nq.gz
    ├── 16ed498c5f0813b744f5f577a1739be574e1eaf6.nq.gz
    ├── 177929ab26f7bbf1d798dcbf4fb8a968a05a6fd1.nq.gz
    ├── 17ca89caad746d6f9cd6c6dd89a9663082a46d9f.nq.gz
    ├── 1827b33a92d527ee934514351a556585f44abadd.nq.gz
    ├── 187467809e3886392f26844cac6c951420e294dc.nq.gz
    ├── 1addbbc3a850982686a2a404c95f36e46b4fa7eb.nq.gz
    ├── 1b29d27804e7a88a307663457473d62749d9d658.nq.gz
    ├── 1bcb4b3618b9534d0c737510585bf8f0c9f2ac10.nq.gz
    ├── 1bdcf27b2642a3748792851d2ddf33fc9d45dcd7.nq.gz
    ├── 1c3c428ddedfd905099128b2b1b4786036aaaa19.nq.gz
    ├── 1c74dddc325bd4a473c1370e356c86dec63b22e3.nq.gz
    ├── 1f3c2a88b3c4834c63f94838de3ead4d61d5c807.nq.gz
    ├── 1ff81a387a5567ddfde12fe1e6bd68b564eaefbd.nq.gz
    ├── 20d1e5b776f2139085310b0cf87884e3f4bf4489.nq.gz
    ├── 215c34ae76fa7063a63cb6edd8720f125af7391b.nq.gz
    ├── 21db1720f2d6bfc698205b6eabee4a815cff82cd.nq.gz
    ├── 223234ac4220d065de872f3e06c21eb2e353a920.nq.gz
    ├── 2235ed18915db3d5705fb6aa14b0df216cb9d183.nq.gz
    ├── 2240d001562a753aa501a3d62cdf712231322ae6.nq.gz
    ├── 2263a48bb74f015d8e145796d2cadfc634966ee0.nq.gz
    ├── 228c44efba3a73965df0957c7432a993f47e8326.nq.gz
    ├── 231fae29dc910234205f9c7c8221698f2015bd24.nq.gz
    ├── 242ddbaa84ddde75de144abdafecb542c8c8d098.nq.gz
    ├── 246d52fad9d8e8a083f0931b2dd732297e2eefe4.nq.gz
    ├── 2539aa5309b2f268b754ec087aa896c82b5c0116.nq.gz
    ├── 25d22d13f5da92fde5006d836df19e0097be4396.nq.gz
    ├── 268dbac7ecbdd20cc05a90e43adbf505c0f30450.nq.gz
    ├── 26e66e435c71cfb14288108efb433b1e6fda6030.nq.gz
    ├── 279806e31391976b04374c851bf7df3bd39962f8.nq.gz
    ├── 284c619bc40a759cfc160193f9b0304643159f10.nq.gz
    ├── 2885fb3a729cf68750f1ad1454cc83e34687db2e.nq.gz
    ├── 28a0cd4fe6ad9c3a73b96da8942c2614ce7def7b.nq.gz
    ├── 28f339e6455fa9462f3573203370b35144b43f2c.nq.gz
    ├── 29a7f0f4e7f21365cc8e41c6ba6b5d351cc9e03b.nq.gz
    ├── 2a0239afb90d29b96d7e009b211f24c627c3f456.nq.gz
    ├── 2a77de74c58a55aa8b82f6c4359b2bf1edae7f27.nq.gz
    ├── 2b2b7e3058ba7a4bf8daec17ecd7b3d3630ebe93.nq.gz
    ├── 2b5020ce8f664a3a557b097661dcde421b984de6.nq.gz
    ├── 2bd19178a58f8c4c93e30ded7a3263e0d8b9110a.nq.gz
    ├── 2bfd5bbfd1d7f16cbf758e7ad3445dc6e90f2438.nq.gz
    ├── 2c3eef31089d42f4a62858de17b7ecb662c7689c.nq.gz
    ├── 2c9d8d5332ba8df90ae2e05ce64b9c8f783062d0.nq.gz
    ├── 2d19fc766d98a08d9d1437896bfb008a7b15f340.nq.gz
    ├── 2dacd13222d61d2c6b9dbb84055477cd7737d262.nq.gz
    ├── 2e0e73fe08bc698dd980a3b5a83fe0472f2a3eac.nq.gz
    ├── 2e9513fc2be3d63eb101be164edd5680fddc47eb.nq.gz
    ├── 2ebc2a525e1aaa9f45ab0d5ae5038636556abecf.nq.gz
    ├── 2ed995427f6f97b7ce86044e566f535bcabf2c7a.nq.gz
    ├── 2edd5ad438627e34bb67ad1d9c26454a8bb57960.nq.gz
    ├── 2f78ff0b1ecbc553ee7e8d3d789f55eb76693f8f.nq.gz
    ├── 2f7b17a22206e605756d22ee12c14d564f9d11b4.nq.gz
    ├── 2f93478c58dee42430fcd26f84bc00633f58d2b8.nq.gz
    ├── 301f388c4c4c2d702351505bb95919725b21f3bf.nq.gz
    ├── 30d7afa6dc2c640fb1d909da8a4b07038525146f.nq.gz
    ├── 3174d85bb8da6e1b09b4692d6ace0a1b86118981.nq.gz
    ├── 31c1ceea41de47ab407a8970d02f7ad8eb1f7edf.nq.gz
    ├── 31fe8a653f14d73de98d5e98a9fe3722e4423c81.nq.gz
    ├── 323acda72191b49edffa26f06bf76c2391ad1394.nq.gz
    ├── 3278d75b4113e49d3852e061c0d6fb874907628d.nq.gz
    ├── 33481d57ef492a1389bf3a2947674d882ef9ad9d.nq.gz
    ├── 337e8799243f2526e82d719f1d474a2000dbbc41.nq.gz
    ├── 33ec6c6bdc9e58bcf156520c4415c709e1c7b993.nq.gz
    ├── 340f08dccc83ad1c48a1ece9caf09165be4cca88.nq.gz
    ├── 346409750b2cafc56dc2e77aa1cd93017887c108.nq.gz
    ├── 35a3367859f7daa35cfeac5eadea3b550b106281.nq.gz
    ├── 36500876aa03b0e7bf1eda842f32db73945519a7.nq.gz
    ├── 373786289bac656b3c98abbfe522875524fbf378.nq.gz
    ├── 373d2e3fb7b0e4b48776e985bc1334f51acdf798.nq.gz
    ├── 378f75bbb6a535f97d972b59a4b4118ba501f393.nq.gz
    ├── 37ace23dff0b0297d5157bc3255db2906e1273cd.nq.gz
    ├── 37c8d1d3f82253e4f199a169c9de2fb5be7be1ec.nq.gz
    ├── 382fd4510ef49904c15dbb80f725d790380bf57b.nq.gz
    ├── 38bb89f8da6ba16479d3aa5ec8b2fc31f4a6ffb2.nq.gz
    ├── 3a80602f05306eb6394afc9b85d9ed9e919a3fa5.nq.gz
    ├── 3b5bf8c72df45d005fbba4d0c87c036195ec7b84.nq.gz
    ├── 3b6e6774cd2b6494f46c54447095314e6b924b92.nq.gz
    ├── 3bebfc485f7ac1930bc9f32e8b4d27eb7f904db9.nq.gz
    ├── 3c5e98198cb178d6840e71bd5b77991aa24ade1a.nq.gz
    ├── 3c78039df1482d5a09b20ab766be3c7ea61bab5a.nq.gz
    ├── 3dce0b39f6db92a1f141f86b05168ac792a7430b.nq.gz
    ├── 3dfe2838c984265f740b1d9169ef4880508e2a4d.nq.gz
    ├── 3e135226a94c9ac586e1cab760238c1a32465e5a.nq.gz
    ├── 3e177da006a26af5431174f120d28c6fce572b4f.nq.gz
    ├── 3e48ff42f93d6441d4628d429ff639a9687c043c.nq.gz
    ├── 3ecce160e15d71004f70dc54fa163a3d94c54a46.nq.gz
    ├── 3ed7878946c98db7aa3858c23aec77427411f3fa.nq.gz
    ├── 3f6ad915fd8dd7986383f808c50d3ed1be13d11d.nq.gz
    ├── 3fbfac36e7b5ea0e03abba998c448b41d9300808.nq.gz
    ├── 3fdf4054404d92b8cd45b5732965df7b4e7bee30.nq.gz
    ├── 405207464991a5febdd9140881edcafe6f7e6931.nq.gz
    ├── 41ce6d0eb5e024119c1f98d86020458e69f0cd73.nq.gz
    ├── 428efe9e62627c90f235240e2744352885190b2d.nq.gz
    ├── 430bb0785c09c1afaa0c4bfa962f1965b912dc75.nq.gz
    ├── 430e01919812262d3771dbc0f06577ee28740f94.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 43ceca048c68e6b258d10f366cac1eaf5c128ea0.nq.gz
    ├── 44e09b94f08536f716c29a567f6b5d52ba6f913c.nq.gz
    ├── 44eabb7b6fa18f145a2300d5275860cea40a2809.nq.gz
    ├── 453f81b1a8407d9ab1cb02fb69e1aaead81b13ed.nq.gz
    ├── 45ae950fcd2c447d52becdebe1a07c774be1fb9d.nq.gz
    ├── 45b70e60e93e8303d8443eae4327a92b0d27d68e.nq.gz
    ├── 4707abb5b3c19eed4ad4ba2bf1729a39225c6be0.nq.gz
    ├── 473e30f1b3eb80160ad15f4bbc3b544af4ebad07.nq.gz
    ├── 473fb6fb59949ab11cc98cc3d5950b09734e7498.nq.gz
    ├── 49f392543a250fa5e0cdf1a96f27b083d3689211.nq.gz
    ├── 4a2c06bde2837d902b45666a2c3200c6ed9f11be.nq.gz
    ├── 4aa3f2274157a23be8700e6caf330089eb4e4562.nq.gz
    ├── 4b4601cbeeb33c8a55a9111cc7dec580a07bbae2.nq.gz
    ├── 4ba2f8434c555a9b1886840bad9267fa9c9a9e4e.nq.gz
    ├── 4bf07b204a965d799a494577661645a034098004.nq.gz
    ├── 4c7f0cc6dccf99423a10ab74a5e57d778ccbb8e9.nq.gz
    ├── 4d4bf0981241b38afed27a7800f011593585ea1e.nq.gz
    ├── 4f41fd49b71fbb678335e895679733431f918b18.nq.gz
    ├── 4f724a60a80ae76c90b27c6a71abb0a81027ba8c.nq.gz
    ├── 4f9d3b5cf0562ed4f7151034791a77de9575f859.nq.gz
    ├── 4feb5ed57c6737e62569df1bf819f2665cd85a23.nq.gz
    ├── 500a1a394ce42b6fa192f9eaf83c43fb4077d820.nq.gz
    ├── 50663ec29bd2ad73e8ffcf7bd78fb639e1ceda5f.nq.gz
    ├── 508712bf8e143effc5148c6b43620e43ee429e8b.nq.gz
    ├── 5281d1272ef170a71681cc141dd5e2e9b5cc6ed7.nq.gz
    ├── 528edb34b96fa18525a556ca41660e75c4ebdac8.nq.gz
    ├── 53d8742c123ed3a844db960773b10a82c74b93af.nq.gz
    ├── 54848b03288a57a830b81d0237073c3d56f1d88d.nq.gz
    ├── 54e7b896df0488238f9961c9577fcc0400ffbbfd.nq.gz
    ├── 55322f0a999db5d2b0b2cda65c60706f23d53392.nq.gz
    ├── 55b1c0645476bb2b97b18e59e094d46335cdae31.nq.gz
    ├── 55c44cc310c31aadc39da005e494257339d9e5c0.nq.gz
    ├── 568fe6c7de751d8470f3284a21b65d8c9ce8895e.nq.gz
    ├── 5715b3a13975d9a1c32b8d3cc6e602bf5ccca709.nq.gz
    ├── 57e426f6c4ce0a3531fe0f831d45883ccc339493.nq.gz
    ├── 5833bdd56210f8c041df3bd58f2757a90f55c2d6.nq.gz
    ├── 58a0442443e5281d3cd534bc3ad1499688a7284e.nq.gz
    ├── 5935e681f8fa46cecfe330642e144fbf2e7fcf7d.nq.gz
    ├── 596e1e73a8ee07cfdfbfe5bd3d4ac6120cb479d9.nq.gz
    ├── 5a082a8244bf30f95921b8f315051e72ca10d11b.nq.gz
    ├── 5a32b4a5927443287efa1951d0acdd8e96c53f78.nq.gz
    ├── 5a431ed4ae81031c2d0374d8b2bb3f43e0a423e2.nq.gz
    ├── 5a62a01efe8b3af0cfd844fcd89c50617bbfbb74.nq.gz
    ├── 5b6d4a23839578ece2713f1ecbff6a521bdf8ecf.nq.gz
    ├── 5b8ce633cd8849137c0a78c81e422d92209f5a5b.nq.gz
    ├── 5c347e57f50a8c0ce330f5f9f4ee2aaadf60534d.nq.gz
    ├── 5ccc91eef414bfa338597101fee306a1356a2140.nq.gz
    ├── 5e32b33f8d7173f6a9b51c55946b67c8c38b85e1.nq.gz
    ├── 5ef60aefb93efb70af2444839250ad5d4e840c39.nq.gz
    ├── 5f00d9085e9d0707d5474ac7be546b9c69efde11.nq.gz
    ├── 5fa97f13b9a18f69d6f9d231244bd70673bc7a26.nq.gz
    ├── 5fb48f3d3bb066b11726734560ed50f3c04f3a09.nq.gz
    ├── 5fee1a4e770a0f529e15a7d5ca5ea8a79cbde27d.nq.gz
    ├── 63057a0cd4ff62543105fa6fab7664af59d75811.nq.gz
    ├── 63205f63f011353715dfc1341bbab46fbdc8ac92.nq.gz
    └── 64cf94c46731bbd7dc3859a09d07ea855fb28aa6.nq.gz

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

[nilearn/nilearn](https://github.com/nilearn/nilearn)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
