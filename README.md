# Repolex Knowledge Graph of allenai/safety-eval

RDF knowledge graph data for [allenai/safety-eval](https://github.com/allenai/safety-eval), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/safety-eval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 060cc903d64703214c549b5c3a30ea8ceef2e588
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 060cc903d64703214c549b5c3a30ea8ceef2e588
│           └── chunk-001.nq.gz
└── blob
    ├── 009a601d547067fba875ed972d349555942ecfb5.nq.gz
    ├── 01343158c1d075cb233019fd1f9921b48fdaae42.nq.gz
    ├── 019f2ead65831591a171d6b7d1348f5a27ebf8ef.nq.gz
    ├── 0475b3fb5a6d9834afe3a6ec9a5869895f29e081.nq.gz
    ├── 04c1bbcafb444c5915258ae1b137f476207dfce3.nq.gz
    ├── 05d215abb96d82832a30824572162601385048ca.nq.gz
    ├── 062e011eb05eff0c45879fb8cb808a72ffc086b9.nq.gz
    ├── 077c68f42bd42bbca66fc51d975caf56279321c4.nq.gz
    ├── 08823375445d7ed42043a4b250af7f18f8412c01.nq.gz
    ├── 09f460b3d7408dd186c36557a397136417e3ecc1.nq.gz
    ├── 0a18847a3a47e68ac411ad15e5d3661995d34545.nq.gz
    ├── 0b69fdd06b31435f55ebb5d43baac8f393600918.nq.gz
    ├── 0b865a225390c5eeeac0548cefcbb61cf6cc6359.nq.gz
    ├── 0d4d49a39ca0f6f85dc54ff0775e1b0d96b275aa.nq.gz
    ├── 114c8345d7dc18c2ebcc9def9d7e2227eacc023e.nq.gz
    ├── 12e4c1deedf487ab771d197bdec8988695bccf73.nq.gz
    ├── 130792e39a8625c5c0c4fefba9e2a50bc42ec686.nq.gz
    ├── 132023a085f51b1fb8fbe1519c793198a6662633.nq.gz
    ├── 13213d879d334f34ee27e6da1d584c416ed9ee89.nq.gz
    ├── 14ea20877cea489708f80a4bce0313995ff5c0c3.nq.gz
    ├── 182f560eb32832b4d85e2e518f9c5d6fd8032d52.nq.gz
    ├── 184a358770c56a1192a072562e997e748d5186d6.nq.gz
    ├── 1ad6f0b29483774613579be4aab1e23472afba02.nq.gz
    ├── 1aeef95be6839f6c1e70b861cdfe3ca9754071bb.nq.gz
    ├── 1b0d01fd5f49138034913187d7dca5dc9ee18b21.nq.gz
    ├── 1d0e679b117114aa20770ee9225188475089ee8c.nq.gz
    ├── 1d433991ad970ee779cd4d841cb8095bc42c2e4b.nq.gz
    ├── 1f309e9149498607914cb2c7f031743bf9e2604f.nq.gz
    ├── 1fe286ed43c7f41214421523b3ce56738d6ed465.nq.gz
    ├── 20a53516a647710f7c1ac273a0b6981622b93218.nq.gz
    ├── 23504ff4608e567b150d1d0b436b7b0ef38c0190.nq.gz
    ├── 258346bee9b40e041c57c27318b2b913299c889a.nq.gz
    ├── 2607c0ee04f152631c96dd3a65ccbae8475f266c.nq.gz
    ├── 28ff393ae0eb3cec03334afdd9f735b7e7926abc.nq.gz
    ├── 29d773be74033ed3dcf461c4aa23ae278c4b6891.nq.gz
    ├── 2bc4304adbf8572a7cd93070ad44f084a939f9ab.nq.gz
    ├── 2cd086952f95dd578caa91c3d7499183d46e34a4.nq.gz
    ├── 2d57f5871da56dc030387dd7a371e30bf410ff98.nq.gz
    ├── 2d5ec667e942bf3c4cbc1aa852f707c569685c1b.nq.gz
    ├── 2edfca6cf8c6bca066af4bbc5e562cc6d206eb53.nq.gz
    ├── 320e516c66da01da350df877e2cd0e6632facb6a.nq.gz
    ├── 33dd1d9e926551d17229ccef429e613abdffcc88.nq.gz
    ├── 355a1252a6728382dcd981a53f9e5b933be35c62.nq.gz
    ├── 36a7577483a2511833fa4cc5bf5b839d66f7c35b.nq.gz
    ├── 36ab3fae25dcae3b8eab4d7f1d1e1ea07a84c5de.nq.gz
    ├── 3b4886a8bf1313fd6855ea77133ad66734c84224.nq.gz
    ├── 3bc5f085060b823bb8c02fb7739236b2fb410a7e.nq.gz
    ├── 3c4e0df2eb15993376a4afdca0efbebaf467a127.nq.gz
    ├── 3c5ce67de04d9b5f6d2a892ebd9f0c44005faf65.nq.gz
    ├── 3fa4cc7885981143f28347954da572767d2d5821.nq.gz
    ├── 4141402d405840044b012ed2d930b25dd3ecab28.nq.gz
    ├── 41dcdbbb122735120b01334a7a3ef57d02f9e1ca.nq.gz
    ├── 425bf1cd1886af936f306aad987ac062a9e52f62.nq.gz
    ├── 4420d7ca3acf8270937a2c815c1a21490cdd4146.nq.gz
    ├── 4566d6d903df2d77237434c7ea797ecec87a6550.nq.gz
    ├── 45a57737e665a903ace89c9c3a2b77005a0bf430.nq.gz
    ├── 464e2c22f7a021a0f9a584d232338a9a17c40066.nq.gz
    ├── 46f5de487655252926d72d7f5a01f9451d844822.nq.gz
    ├── 47b097008de3fc1431faa1fc165c1f72bdd68ac3.nq.gz
    ├── 482baac5f69a6904b1de00f6abda726f4022e080.nq.gz
    ├── 48a1bb33ec54f16f64826fe7f2575229873ad4fb.nq.gz
    ├── 498bb2ff585622ce00a0e533e9148a8677344ba4.nq.gz
    ├── 49da1195a40b7c14b72a9d34c1de2f5113159dc2.nq.gz
    ├── 49f4c5306687e359bc7bf9fafe0b1904cfd60756.nq.gz
    ├── 4caaf84ac014e26f64a2c6c07b1ef46eb16ed6e6.nq.gz
    ├── 4d1b8a2243053ba559c2bf94ae93e164e14927a2.nq.gz
    ├── 4d835b685f12bac2bf6c54ff4d27c5be32ab74fd.nq.gz
    ├── 4e202f6e562798705dc257fcb9c1508330025551.nq.gz
    ├── 4e4600ee85c11debdff998616f86e832d929438a.nq.gz
    ├── 4ec7524cbcdf308766fddc52df31e203316ad75f.nq.gz
    ├── 4f3bbc85d4faa6762e3ec35c141b849646f8df98.nq.gz
    ├── 513ef0d1f63e651f763db5f36db0fd6ea30d8e49.nq.gz
    ├── 5210cc0d7a4fccce9f7100082037cbbb0ff8e17a.nq.gz
    ├── 5459e2ecef3c31a37ddfbc05b497e1567161e17f.nq.gz
    ├── 555c84f71ab06d963d81cec124f63c13e7485fd8.nq.gz
    ├── 56cec225a1c595bc957ab570420d1009a664ab17.nq.gz
    ├── 571b6588d13673c92ecb4727b4e7739a3554248f.nq.gz
    ├── 585a0abefdcf4906da4ae1ce3cb01285b26c6540.nq.gz
    ├── 5972d94e34026b9209a9a9928bdc5bcf36a8c786.nq.gz
    ├── 59834d1e8ef5555e6b5ceafbb94434768b4ac675.nq.gz
    ├── 59f0776136ebd1b212fb00ec3aaa247103aec360.nq.gz
    ├── 5a2a8311c47a9ece199596c607ef51190c4fcf57.nq.gz
    ├── 5bce12626a1c2f64cac63ada0a4ffc1371504cb9.nq.gz
    ├── 5c710084498ade66c24a6124331d8d9ee06a686d.nq.gz
    ├── 5c9ebf9f254bf1e1b92bbc8abda5707465f3d690.nq.gz
    ├── 5ce3d4d936fd7e0b8f050da76fba6b6d0615ac9b.nq.gz
    ├── 5d2d8bd0fc412e63fa8830fdda1d62cb13847ca8.nq.gz
    ├── 5dc79683e85cb8c0e791cf9650a720080742b58a.nq.gz
    ├── 5f3f98bde02294de84ec25b5daa4aca13acc19a5.nq.gz
    ├── 5ffab163cb9a797692e7c2d054a11b090f66b0d7.nq.gz
    ├── 60ce4423522d5beb8981120369cd2e027fc7de1c.nq.gz
    ├── 612604ead1c1d917c932badc0b4f2fdbc343efcf.nq.gz
    ├── 62844ec38039bf2982486812e1d76e3f28e9da41.nq.gz
    ├── 629820c539b28b6f551f4368892187d080a98cb6.nq.gz
    ├── 63858932fe704d76bbb836b26eb298339f9aa275.nq.gz
    ├── 646f5be50f549e5f1e700972d912c0efe5063522.nq.gz
    ├── 65bc759f56da854e291c3b27adebce76c8195bae.nq.gz
    ├── 665f14f0b2baf62462e2211fa0df8a0b1d89ab9f.nq.gz
    ├── 6669e60b3c2241b73a0a2ffbe784012a17fd1d8b.nq.gz
    ├── 670b76f14ded4975f64bcb78700ebfa3ed6e6218.nq.gz
    ├── 68258990a60a19e8c8d231c21035378babe5e655.nq.gz
    ├── 6851d594000403306d9751094cab1e01dfa66f3d.nq.gz
    ├── 6ba5df87949ae6c65fb556a44d6c9ce17b58da34.nq.gz
    ├── 6ba878d5526ec90687fa9a8e6b6cf63bb599bf80.nq.gz
    ├── 6e3250404294eeb1a417eebf29959ed4735a4939.nq.gz
    ├── 6f47b55c471b6781f928596f8ab0adb83981aa84.nq.gz
    ├── 6feea545fbb60a17ce06a2686693593abb187528.nq.gz
    ├── 725549d25464faebe67ef75d99078dde1679aa8b.nq.gz
    ├── 7295c01b132b22d8b991ccb340d1ea7e3a5000ce.nq.gz
    ├── 747db4f8578c95b9b9cf628b94ae3964cefd9a85.nq.gz
    ├── 76447251bc440c7b746f36ec20fb136b48a6efb6.nq.gz
    ├── 7795b9d7447b849d031bc1151d535da5d8f75ed7.nq.gz
    ├── 783e9bbe7a6ebf2051c3e276a2cacc7fffe1721c.nq.gz
    ├── 78412f8ffa62fee940fa5685462c551c160cae09.nq.gz
    ├── 784492e335107bc96b6fddeabbc3d0d1cc550245.nq.gz
    ├── 788f02d360b2ff765a6047a656850c4080f21ba1.nq.gz
    ├── 78b0718061efc81309d37dc0a3e8492457d1f22e.nq.gz
    ├── 7b0d20afa74c9f9f46bd1301f7077f43a913c856.nq.gz
    ├── 7b220c56af5ed60498fb93fd93fdd50a2160904c.nq.gz
    ├── 7b31ec683e007ee51fbbd56960436b4e993c0ec7.nq.gz
    ├── 7c78d27a15275943940c9d9ce0d8d2a788618561.nq.gz
    ├── 7e3dac2f70848f1dda1611b0ca86dcc43dbd0b5d.nq.gz
    ├── 7ec8857848a0e3e3a8bfde4714bf67f2237632d9.nq.gz
    ├── 7ed9cf2df69259ddb0dda8a5b3942506ed219c71.nq.gz
    ├── 7f30e9628ebdfeb17e374d6c7336a9621f7360d5.nq.gz
    ├── 80531e64e13f6f37672f7eae14c0587ca1b3b4ea.nq.gz
    ├── 808275e4c248e694cc92bc92375c36c6f152fa1a.nq.gz
    ├── 81a845a72945c8ac763cc82d2766b051e3a20b51.nq.gz
    ├── 8293b9db56b21133ff4dd6f042d237a766baabe8.nq.gz
    ├── 8456ff82bdc21fe4b290d1b1033233b16adb53f8.nq.gz
    ├── 84b7bfe5228f81d968e8e739ef1be1db070500b8.nq.gz
    ├── 84e45d8c4da9ca8326b3aa88cc42c2bbe8238f3d.nq.gz
    ├── 854b6954d42a52cf1580b10242bf5e92693ec2ec.nq.gz
    ├── 8699c60e78fe31bdc8bf6c2490a7f958b02fe36c.nq.gz
    ├── 871a2c4bb119f6a94e2ab8f018db4643b1fe7ce4.nq.gz
    ├── 872066276d6798fc631a5c6b9b6f0ae5273d27f9.nq.gz
    ├── 875bfdae3631f65dfa0cffa0a10f06f7d891cdbc.nq.gz
    ├── 8b66387a3129cbb117178fe515491df553dd52df.nq.gz
    ├── 8c189cbb9b689d24cc0d84ee6131ac3d4c444096.nq.gz
    ├── 8dbe0bbf5d35d38ff4ea3d2b89cf31b30aa7470b.nq.gz
    ├── 904bb6d94c88db8b045ac00dd585b43b98e4cf56.nq.gz
    ├── 9070d68b24978917332d42793043713a4123f0a1.nq.gz
    ├── 9135604839ea2859dc03d1bbdee5a6c642f26a20.nq.gz
    ├── 917fb865884f777c69d56a6bac838389cea05db8.nq.gz
    ├── 91e05d830e82d672a0561e675f0936020bc060ca.nq.gz
    ├── 934a866ff93f392a70d7eba4c720022a08b2e114.nq.gz
    ├── 937f008853434232aad14ed57502a02b0eadf326.nq.gz
    ├── 9558058302acf9083cd34fb7cfcd0b66449b65fd.nq.gz
    ├── 9809c67b5af0aaeaf932b5b77a5d92fc2209d36b.nq.gz
    ├── 9859b4da10206da1034f6844e76df41a7e79ddab.nq.gz
    ├── 9925a5a11bf3824079595c8493cbbf57555c695f.nq.gz
    ├── 99956aa47dd1d75cdf43037fe5fd5122e48aeaec.nq.gz
    ├── 9bec2ba16958b29c6dfd4b80c37d1b5a25736a68.nq.gz
    ├── 9cdd74baba46f4b1c6b1c16fd90af1ce0efd011a.nq.gz
    ├── 9e791d413a20dd6cd88d17ace1b261ce63954441.nq.gz
    ├── 9f4fcdacb4c132625a8b3373c0b33b63726755c2.nq.gz
    ├── a21eb121490d3e83012e87639a0008cd84f52842.nq.gz
    ├── a2d2e4e0a6c74bb8532d03dd38ffeba4602ecc87.nq.gz
    ├── a3b9350efb1aab4a6bfa1ca41f8b14acdd09c031.nq.gz
    ├── a77a70941db426d914bf54142e881c88a2a58790.nq.gz
    ├── aa39173089af85b51d1a4863a2083f12c89ac3f1.nq.gz
    ├── aa681007e8b7b60e76f98a0e83a881308b719b25.nq.gz
    ├── adf0e3b7ff5712500f1c7b1f05ea1c89513491d9.nq.gz
    ├── b00f3b8cca0afabccfb2cd79d5c170b441836000.nq.gz
    ├── b08bc5558689b8ceff745008c7fbfba7f3940521.nq.gz
    ├── b10b350720e6ff0994ee0f235da63d3da9602cf4.nq.gz
    ├── b1ab3887641fef1c40c91f290fe3c082269da087.nq.gz
    ├── b1b129d137f7c6aa84c6d7ce2a950cfa3b2453e2.nq.gz
    ├── b32a3d1c2d816b1a5150dfae9e1aa8b93458aa51.nq.gz
    ├── b3d7c6b0fac18731807f971194e78213222d9b6b.nq.gz
    ├── b521a78a9ad16c3a5ee0bbfbc8482cca231dac8f.nq.gz
    ├── b57a22fb5e841b0458fa2259999183f1a10565e0.nq.gz
    ├── b736e059fd42afec5d622670e96e972b03f531d6.nq.gz
    ├── b9909b062577696b97cee95fc3dccf2de3b47994.nq.gz
    ├── ba57aa7fb2a3aa98a82b152e9c4370af981f1fad.nq.gz
    ├── bad1584a81655946593595f5c64f6990ed617455.nq.gz
    ├── bbf1580a12f343c5ba1b0f562f1c1709871319ff.nq.gz
    ├── bc0625786db959a339c66c5060b1e9a580aaa0ef.nq.gz
    ├── bf137bdce3fa0eee0c21f5dcb98b7abcf1bb9377.nq.gz
    ├── bf402588d949e5a84ad25b3a9cbf64dcce31c5ee.nq.gz
    ├── c00fa3bfbea34f616804f9226ea2e7b1f6ca0bc1.nq.gz
    ├── c2a8bf73fab136fd7f9bfa02329186a8752f2eda.nq.gz
    ├── c2c42defca831441d7b39ded291fbc440e5158ea.nq.gz
    ├── c36235f32373c4bc789457274061d483bc9fa967.nq.gz
    ├── c550fe605f7a36d93c718a631ad46b1e91e06d72.nq.gz
    ├── c606c4612e066c1042fa7bb3d83477db68d8f34f.nq.gz
    ├── c6fe1c3289ca98eb7a6773bf70c15e9ee9346ad3.nq.gz
    ├── cb6a507606112e692e5c9d9b62574bfaa68995ad.nq.gz
    ├── cdb3790498cc1fda136c1626487e5ee947a6c95d.nq.gz
    ├── ceca40a72dadee65ff2cad58d99331856893da6b.nq.gz
    ├── cf626e9017aa8b1fffbc3ce23252720719cf8634.nq.gz
    ├── d111cdf9c0f846183ed85a8b8d46b63b6da4d7c9.nq.gz
    ├── d13719c09db75771c4e6fb31232fafb1fd60474b.nq.gz
    ├── d29bdd5194cd34dca4e659d3f022f41ae089a451.nq.gz
    ├── d37c3b07d157b1d3450e96b25911632e3cc52b08.nq.gz
    ├── d5040db3d1cf1037ecc5a8526b6edbf2a37cc1ab.nq.gz
    ├── d67d5e4cd110d506c5fa3c6711b02584493dd3d9.nq.gz
    └── d83cbb9a4c5bfff99c495df347324238a4b28dd4.nq.gz

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

[allenai/safety-eval](https://github.com/allenai/safety-eval)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
