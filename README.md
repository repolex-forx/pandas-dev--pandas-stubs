# Repolex Knowledge Graph of pandas-dev/pandas-stubs

RDF knowledge graph data for [pandas-dev/pandas-stubs](https://github.com/pandas-dev/pandas-stubs), parsed by [repolex](https://repolex.ai).

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
rlex download pandas-dev/pandas-stubs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96c49cbe8918f14da9bd7e0dfde6fc7767f72f58
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 96c49cbe8918f14da9bd7e0dfde6fc7767f72f58
│           └── chunk-001.nq.gz
└── blob
    ├── 01d8ec985bb968c5739d33cf5c3cbabc9b850903.nq.gz
    ├── 025b87a18374916cf6e15081d30e56ea27272c15.nq.gz
    ├── 026e358e5789180dbb371d2a60f54d5c72456e3f.nq.gz
    ├── 036dc91fbbd385e68ec4c3bac5f5da66c7036396.nq.gz
    ├── 03b0be285980b0d9da1071544036329c664f64df.nq.gz
    ├── 070ebdc1142051204871cfac7edb785a9d1112cf.nq.gz
    ├── 074f3398ce39cb6541952c6c811bc3e2beb40435.nq.gz
    ├── 085d4908a0be7f34ba1fbf954c16df1cfdf4c276.nq.gz
    ├── 085d75d99b8a75c99a828aa55c12968112c95599.nq.gz
    ├── 08a6d561d5050da6d74e5c68f2fe869a923babe5.nq.gz
    ├── 0944836963f3318ad558f273761155d61a37376e.nq.gz
    ├── 0b18706f1fd9cb4dfc86bf03be9c420d346c7f8d.nq.gz
    ├── 0bb9e5c207cf366460c7ce31b2b01c4b7c29b349.nq.gz
    ├── 0c4bdc67a4906bc1370e33c396058fd124eedaed.nq.gz
    ├── 0d375e17fcb2b88073ac5bac9c5373de68595e31.nq.gz
    ├── 0dffb6bb64923d658790ade8d7af1f72847eb55b.nq.gz
    ├── 0eac3711d416651619a1112264bf2d9ba8761543.nq.gz
    ├── 0f46e07d2504a65a238c4b41cdacd46316975337.nq.gz
    ├── 103695a65d803e5019087280d2abc35bd1043e5c.nq.gz
    ├── 1175807e1dce7bcd28ea0068bcb0c877a2f37319.nq.gz
    ├── 118c6afb19b76854862d4cfbba1c96cc0d8bcf54.nq.gz
    ├── 1265a5406cfb58f4f4e9be3cdd8db4580b1f35d9.nq.gz
    ├── 13516d65b1442eac8e04320f33cc0a59452646a3.nq.gz
    ├── 137356130e443ccbdf1a09317a66a8ed4c0d7f49.nq.gz
    ├── 13851e4744a9c9cdc55338f4f2f6371f906303f8.nq.gz
    ├── 13fcf337da942f7c165170215cbd4e4e21071ea2.nq.gz
    ├── 15709a2de337b08a81a846c63e5080bc4c3220e6.nq.gz
    ├── 163156ec17e74d6142d93731a754cc7b8863f819.nq.gz
    ├── 16eee7f1b630d1d73f12445d5761dfaf2b88a1c8.nq.gz
    ├── 189d4497cbe0b7ac6c325e137f754ebda6ecd2af.nq.gz
    ├── 18fc7d5922d0729df6de4e632d5ae68f39752d19.nq.gz
    ├── 19592c366b15bdca310e6c3fdc4887d64af791ea.nq.gz
    ├── 195bff892aba91d8e3b52869652567f9699c6a05.nq.gz
    ├── 1974564b0acdd429cdf462bcf34dbacf61c9f041.nq.gz
    ├── 1a40593f7de939a38a7c4d8f6d99e895041c31e2.nq.gz
    ├── 1a5cdd9b8b3993b283c394e27175f3863b5b2e78.nq.gz
    ├── 1a7e83ed950bec57fbcaf949814390852ead0eb2.nq.gz
    ├── 1b257344d63d9cd269fd7abc116d5ee91b3204c4.nq.gz
    ├── 1cc31c0dba44bf57b8e4ca3b2eb4e67b7d8f88f4.nq.gz
    ├── 1d6c050e0975af3c1b17b2382867522acd3b70bc.nq.gz
    ├── 1e2e85e5d6b020571c03ca799fde9e6d3b9f762b.nq.gz
    ├── 1e340f7a436d7d76bb51d18921dfa996999ca7c3.nq.gz
    ├── 1e95992423e2643e0f5bfb82c55fe0d2b8b435da.nq.gz
    ├── 1efea573216649c6c7a730386d043991c4874fd4.nq.gz
    ├── 1f6e44b38dc044cecaea4e634087c5807136ac09.nq.gz
    ├── 1fe6111cebf26713757e0715298d660c910f2029.nq.gz
    ├── 2217a782ceee7bd31a2f941f4dff999a1af96d83.nq.gz
    ├── 221d4dad9b95a539945e5425803d3051f3b72e90.nq.gz
    ├── 22248a54860bddbd875169abd893b62d21afb25e.nq.gz
    ├── 23040f1f4551082617ba037070ed354ea18006cb.nq.gz
    ├── 2464b5077d496f59e3ad9821a9b650827e8b8223.nq.gz
    ├── 24ef6845c722aadcfa78e924ebfc350bf91c99dd.nq.gz
    ├── 253f12ae0f1539c83c84f4688881f5140bf57dbf.nq.gz
    ├── 2572ba8d0fdfa9f6676ea4bd739fefecfa6154d2.nq.gz
    ├── 25b83215f9604151c2c990475a0cdb662ba89d47.nq.gz
    ├── 2903acf805f3cc6876d1c03b31ddf54016bafca4.nq.gz
    ├── 299521caf4b9d3ff6b6589a9e84f51a7e4bb618d.nq.gz
    ├── 2a050673e5aaf7e38a46903fb0d40f977f05c081.nq.gz
    ├── 2a1d4e9af6b20ae9c684ba7b52175aebafe7266a.nq.gz
    ├── 2b874ae1f7e8cd4abb4a9b0b23ea5e10eaa3b683.nq.gz
    ├── 2bc0236dc9ae48ab8577aaf9846d3b2ff2019731.nq.gz
    ├── 2c95969512a65520805060bb5c258006adca6b10.nq.gz
    ├── 2d16990ff45e773118442b99aa336710a2695b5f.nq.gz
    ├── 2dc6c203ed4e9df362045379f96818d1cc53222b.nq.gz
    ├── 2ea1c8ee2dd263792382644e53382ce45abff4bb.nq.gz
    ├── 2f1af474ea8734a8bea1c6796eecef0263bdcfa8.nq.gz
    ├── 30f0d6566ffcf74ae4d91fece4c900346e84c3af.nq.gz
    ├── 3156999fe4ad02edf6544f5b5eef4d4f06392718.nq.gz
    ├── 31f42eb1a7db6fb63ffe10a283ac1e9162a27f30.nq.gz
    ├── 32180c0ae0fc8fa5c50ce098ce89e07c6b87d44f.nq.gz
    ├── 327c5d49901a888ce85cf0e184622c6a458b1fca.nq.gz
    ├── 3320bd41197946379a15f5ac3783f63980977b50.nq.gz
    ├── 33dfe6e88ebf070ed5a017a0aeb920a290de68c9.nq.gz
    ├── 3403a46f0648e142c7f8914546c482f5d880a0b8.nq.gz
    ├── 3520153a29421a52793b07ec80f52516891adc63.nq.gz
    ├── 355bfd9874a063d88e58a732f960491a6da99e65.nq.gz
    ├── 35f76c259c0cf034eeb2efbbe004e4d3eac416c1.nq.gz
    ├── 382cac20f7025f14c9862c92bf8784baa2a44109.nq.gz
    ├── 396732a78edc4e8abd3ab132a8fa2c264a839f14.nq.gz
    ├── 39f6f8a9e782e4a4a213c7ff78d3db117eb0d028.nq.gz
    ├── 3beda37d084373d47ca9d9fecfa2e60f06f0c67a.nq.gz
    ├── 3ccac241928e5eb9dab8c66e498c7c8f87fa09d9.nq.gz
    ├── 3dad35f192ca5060c165531b1a5a948b6c86941c.nq.gz
    ├── 3e6836253d23ea438951f4b4d5d54427f32f3ce0.nq.gz
    ├── 3ee1d42b9beaf6f9913d1b50b9800653b741444e.nq.gz
    ├── 3f0948bf3d7067eec82d54c8af8ca2f585281339.nq.gz
    ├── 40a12223b973ba0a7ce193bf18fb46eb19cc0d9f.nq.gz
    ├── 40f619d7d5fd7a0e856114ebd2d3aa82b78c2245.nq.gz
    ├── 4149bff86a82077dbced735328275a27a5e3e0d9.nq.gz
    ├── 41c2ba632775514f9605647d5efe6b8ec8ec349e.nq.gz
    ├── 438a9f87e9216616d31af19dd79b783f20997342.nq.gz
    ├── 43e9074703e5ba88eb0b61ccb9cfe814d5198f45.nq.gz
    ├── 444c0ea5116c2d9e21c3eff6bbd82e65eb623ab1.nq.gz
    ├── 4451d06158202d06a0a29462b5677aad484bd3d1.nq.gz
    ├── 462299bc6a952a38e360592c3f10799dad8481a0.nq.gz
    ├── 46f48435e8a34f246556123e46abc1d18b39ece1.nq.gz
    ├── 48352157b78c9d05d33c1defdf927a9ece4d5088.nq.gz
    ├── 49268b4f1cc1d6c5e78e13faad8af8ef454af585.nq.gz
    ├── 492d6f3c44caffe1ba20e8b81e2299bdfdd4489b.nq.gz
    ├── 494656963187f2423bb16f972d4fd91639281d30.nq.gz
    ├── 4a26be45a1b74a62026ca6c82bfcbfde5e0c06be.nq.gz
    ├── 4b639a991a06cee7a819c39289165d1a589b3afd.nq.gz
    ├── 4cece08b91b5621386bd84b449403f462e77cf56.nq.gz
    ├── 4d4bd490a3bc122a55c545ba2f5bc2cac546f3a5.nq.gz
    ├── 4dd5feb0f70d1407a22717b7b2c5ffa8cba93774.nq.gz
    ├── 4ed5966b8fe30292d2b8287888146c904c2ed241.nq.gz
    ├── 4fb5ab89ccccda9a6d9bd9c027b5c7471f77ac09.nq.gz
    ├── 4fc7062abdddb92249522c811c5bd3d4e1d1643a.nq.gz
    ├── 4fd62ebe3814642ecaead8b02d0d73c3bff0e016.nq.gz
    ├── 50066214e15270008a11472ab4269a393bb5cec4.nq.gz
    ├── 5078ab65e12eedc7f7a2c753bc74a354f3f91ec3.nq.gz
    ├── 50c278e2571798b77b8e68d60595f1c835d88d13.nq.gz
    ├── 52007903f760f0f16cc21e367f39a70d7958e894.nq.gz
    ├── 5357513ed3d6076b0ad28fd81b8e442168daea30.nq.gz
    ├── 539cd8e7e8ee05c815a5964c7f9f080e1a97114b.nq.gz
    ├── 54dcf2a1e25fac43f11228de5076e367416577d4.nq.gz
    ├── 5664617f427788a51515c87f8fe7970b05d2c4e2.nq.gz
    ├── 58951e625bd3445f7d7d1bc3c3667f7fc02015f0.nq.gz
    ├── 58b268cbdd22173f8701c4ccd27c5117a072d966.nq.gz
    ├── 5a2214b0b97fbf70ea51bfe6aad5d8bd8f63e335.nq.gz
    ├── 5a570f9c9e90c778052efd284e87f6ea89518864.nq.gz
    ├── 5c5b18a0b154bdc0236aff9af7930c8d11036da0.nq.gz
    ├── 5c8c56d839502e7c55b6fa4a52dc9f94fecd033b.nq.gz
    ├── 5cf869eaeca62d457fe10bf7d65011eb6f25d52b.nq.gz
    ├── 5d4cced82316199e5da9628dec364f6220d9a477.nq.gz
    ├── 5e8837c52fd928bcb42ab26f3926ad74d735aad9.nq.gz
    ├── 5e9ef673b2c259e4bbcf29e6f21e0f8fcc686f8f.nq.gz
    ├── 5ec9deded39aeac31e915518f01454b2e9026f7b.nq.gz
    ├── 5f071260843b3c72d8df70b5901d6496d7b179be.nq.gz
    ├── 605c6b8287339d14322b3d2b4c0b718b79862a83.nq.gz
    ├── 60aa0fd377ab877434fb347483ad61e2afb1d26e.nq.gz
    ├── 60fbdd711a6dfc5dba5ccef9119f3efb27df4e30.nq.gz
    ├── 61d7aad435ebf70436d3db6a65409203f8b76c51.nq.gz
    ├── 61e0b352910fb8d06ec04b7d686a970e52d9ab27.nq.gz
    ├── 62afb78d25971b0c68ec1220f70e3226cb39d62d.nq.gz
    ├── 630979db0522924d594d90ebb549734ff2b2f214.nq.gz
    ├── 63e760ceab65022f6718f394ee9c199f2e35307b.nq.gz
    ├── 64556243709a007f32b9fe353ff6ad5e3a175057.nq.gz
    ├── 6522b7add80eb175d29ae5386fab5306f1e64189.nq.gz
    ├── 6545719d741fda5a6672db257fb25f36b102e5e0.nq.gz
    ├── 656905fb711c9618261a4bbd23a61527f6b0c697.nq.gz
    ├── 6580d99512c05087ab7cda051b0b9d4b60d05d85.nq.gz
    ├── 65ed2ff41a79ed073a9b99223c0b32f53a93389e.nq.gz
    ├── 65fae01fca959b03ef3a429a0220a33ebdfa29a8.nq.gz
    ├── 663a178833dea4fac5ed9d76bdd18fbfab5184dc.nq.gz
    ├── 66abbb7a398728c47085a6cf0bae33d21aae3a22.nq.gz
    ├── 67244e9152dc0b79f96cec01063b0e0299af5f9d.nq.gz
    ├── 67585d0d15a0ae01e4470f7db444e26ad767b8a3.nq.gz
    ├── 679a033fd973e626eabb3d32eef284bc3d5fc1f9.nq.gz
    ├── 67dad9732bc48c4dd8b9a19216b8c65239e23c4c.nq.gz
    ├── 68b960105bb031d72f9dbfdcec65d298b276bdf2.nq.gz
    ├── 6952c2c9dbc28b87b7da0cc42c00c08f2b952678.nq.gz
    ├── 6a67688029d26f0aca802cc054a400add2259de1.nq.gz
    ├── 6b2b6abd85d67d2bdc2148ef0cb2700ffa1d8555.nq.gz
    ├── 6bc0b5cca51cbfc0ebfb43e4d642f76cecf76a1d.nq.gz
    ├── 6d5d61b6955121dec0f24591a2df4308f7909b0a.nq.gz
    ├── 6d709733132a7ba948fd25e2b2bf1a10f2b030b1.nq.gz
    ├── 6dae63c9a55ec06f4189f8efaf17d48567ba0d6d.nq.gz
    ├── 6e15b87e40ab7c387504eb30e01ad7c5aaa857e8.nq.gz
    ├── 6e555cc2480432b4b01f7188c71508e8823425f6.nq.gz
    ├── 6fd96626ee96c9b8c2dc3d067c1f90e63b16e2bf.nq.gz
    ├── 70b664f2c867532c74667368966ded6d3f4a3086.nq.gz
    ├── 7158da6ca8567dcefa81e455519dce2ca60f939f.nq.gz
    ├── 716a7d4686b41330cebf241e1a8e3a18cc7d500c.nq.gz
    ├── 71fab0377dffadf791b2238159c7efd913ce82b2.nq.gz
    ├── 73131e3373ce739cf8b712d79680e7dc40475b30.nq.gz
    ├── 733015f71f8f4becebd0ac2ede3dc71bc3870cc0.nq.gz
    ├── 7335a0429e3f8168376d34c1d719d351b317b064.nq.gz
    ├── 7377aa6b2f316346e4d02df6ccc0af0efcc237c2.nq.gz
    ├── 7386611cb131dbc614b89de3c40e8fd4f70234eb.nq.gz
    ├── 73c5f2d7848cf8c6ca6c8944ddbf5f458d92c5a1.nq.gz
    ├── 741c28cd1670448c0476f8e84312925a37b33afa.nq.gz
    ├── 745076f5d90f5bca0a5be38d8a8a0dad094c140d.nq.gz
    ├── 7455982b3e1a369d4408b577bfb13774b0e05642.nq.gz
    ├── 74ab2f506027f851940cfd661a4321bcb57ed956.nq.gz
    ├── 74c88ca56cf9572b053c6897a75c3f23143b9f59.nq.gz
    ├── 75c2fbe79fe18930271d9b88eae457ed9f27d49d.nq.gz
    ├── 7657f2b8c393642f3cffd07efd50674a4e025cc8.nq.gz
    ├── 76ca67f6c008eafa538ecb9fce746f30d343a1cc.nq.gz
    ├── 773f5152220c6a102df3bd688c61facdc1c61858.nq.gz
    ├── 775c05503d92461d6e1ad71d2ca6dfdd7c6c4843.nq.gz
    ├── 77760315930fb4ccb5b0e3cd28c023db116bdad5.nq.gz
    ├── 7811714d26e49b19a857803d24c857f16a4a0000.nq.gz
    ├── 7822501d2115555e33d8794b63e15e2ba4edb217.nq.gz
    ├── 78465b1cf95b7814e87bc7b17f565c2bde817363.nq.gz
    ├── 78e5ecec2d1abd3e29ebc0116953f3a4fadee152.nq.gz
    ├── 79f69683d2b62e44965e4175ac5f4565196e1047.nq.gz
    ├── 7a8f649105527ee0979edfe6289fb179370d021d.nq.gz
    ├── 7af18a43ac14d1a7efa53123bf3cdeb94ef02e87.nq.gz
    ├── 7b6d2132d24aafb1b9e7cdbd7c26f94f9505827e.nq.gz
    ├── 7bef24cf31ee0dc1cc07b2999e21b4f0c0d6a196.nq.gz
    ├── 7c06e8dc86c734aeff0be1c587bd5b8b72ce0649.nq.gz
    ├── 7cbdc34f1c17c037396a07a0bfa3232f8532e000.nq.gz
    ├── 7d20a2de72a990a18e2bdfcc3f36b326c716695d.nq.gz
    ├── 7e15da1cadd48e67810fb2703298881129a66631.nq.gz
    ├── 7f0a3ca5c38b1dfadccb2a0413202f58088c676d.nq.gz
    ├── 7f0c6a816497a5a35bd0a8a6f663e9ef2066a86d.nq.gz
    └── 80431d3a898ee7c7f943903181ace2be052d8165.nq.gz

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

[pandas-dev/pandas-stubs](https://github.com/pandas-dev/pandas-stubs)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
