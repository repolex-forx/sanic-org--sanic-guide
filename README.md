# Repolex Knowledge Graph of sanic-org/sanic-guide

RDF knowledge graph data for [sanic-org/sanic-guide](https://github.com/sanic-org/sanic-guide), parsed by [repolex](https://repolex.ai).

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
rlex download sanic-org/sanic-guide
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2719a58b8c97caa17e4fdaae20c06edbb6143c84
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2719a58b8c97caa17e4fdaae20c06edbb6143c84
│           └── chunk-001.nq.gz
└── blob
    ├── 00372841161c566ea2d650fb8567aaf3741ed37d.nq.gz
    ├── 008a168b8edba5121c5e9fcbd10bea4af1a1b59c.nq.gz
    ├── 01d045f23ee82aa4fd16b43f52a88fb84ab4ce2c.nq.gz
    ├── 01f797d9c740240552be60afa02885940e85aec2.nq.gz
    ├── 03757d385dad9e8e531077b9cbca47078b34ec8b.nq.gz
    ├── 0416c60b481d77c71c09206cced9e5a32c267ee3.nq.gz
    ├── 050b5bf4922799f1aa84050bfd33cf2e4b727076.nq.gz
    ├── 0620baf7c6b0f595bcd029f20a41eef13f544e0a.nq.gz
    ├── 07d5d10e93d9f764bf5634448ea8511fc8a14f6b.nq.gz
    ├── 08346f1fc88bfd784fe7d3067c1bb45b17ffb802.nq.gz
    ├── 0962a1e4b781a5d3c395fd9bddd928cef1df672e.nq.gz
    ├── 0a5d5732c0fb5d907f29f610320f5ac1b7658bb8.nq.gz
    ├── 0a5d9dec9e97a4bfc82ac1ac4964031672949ea8.nq.gz
    ├── 0a6a74b335402b185cf8918d7fc1fab2b0825db8.nq.gz
    ├── 0b39dd6a5158de1317393061ea1dede6d141ade9.nq.gz
    ├── 0dfc62d35bf98728b7b510dfa1dcd0b95e0f0985.nq.gz
    ├── 0e06deb66b839c981186adbd639a583aabb29719.nq.gz
    ├── 0e498a78191c59ba1188a4eb0b105a1c1ce67a3f.nq.gz
    ├── 0e8eb44554cb8ce927f3026077a1eef9eac1db0a.nq.gz
    ├── 0e92a5663a902cf21c642cf88cec37a7592f4558.nq.gz
    ├── 0f3dd716ef3409c234271b61ac6dbef27dd00f65.nq.gz
    ├── 0f6f129714ccea79e54f93b1a6a47d41d31a818b.nq.gz
    ├── 0f7c6dba60b96b8fa83dd2323a48b688304d6e1d.nq.gz
    ├── 0f92497cc2b922ac3196c2f44ea1af4ce8ad21c7.nq.gz
    ├── 0fe3d63fe10d51945b95b213169528d4fd9ab2f2.nq.gz
    ├── 0ff02944c520a984824d88bd526be4d5d1f54892.nq.gz
    ├── 0ff738cb2fd94b94da289ffd7be0c903f53a3c0d.nq.gz
    ├── 10fa1a630737a7079facf8fafef98a1d4d8927f4.nq.gz
    ├── 1106cbe07a07fb390ad9b172239b2aa85ec6456f.nq.gz
    ├── 1203dd7f7cebdfa9d2686af15a5e0be5626bc09b.nq.gz
    ├── 13536d80d54487fa01a3eba0941c8829a269b9c2.nq.gz
    ├── 149d87086b25dd4a79c98d3cadd82533ddbb7df4.nq.gz
    ├── 158b2b4383c1f6bc831ebf6b9c4aa57d583f7fb2.nq.gz
    ├── 176c973f3ee120353f7a68a16e8174c063e8c259.nq.gz
    ├── 1875a93ba1f1fd3ab9eda059cd9bf13b345e7d39.nq.gz
    ├── 18fa2c5ec7a7d001eb190de76e8cb87fb24877b6.nq.gz
    ├── 1ae3b3ac4e8eb653495331862ed9d0d7e13cebdd.nq.gz
    ├── 1af529361a940c34a7340b1053e88dd2e433f84d.nq.gz
    ├── 1b308c39306a5e2f2ed1e2df7c5b0f434ff09b5c.nq.gz
    ├── 1b4561095dc853704dddfd0b5ab07ee1dd41afa4.nq.gz
    ├── 1c13349c9c102a3b59202f74b54f5c6679a720a7.nq.gz
    ├── 1e770f6457e30e496a77b372e742625dbb208609.nq.gz
    ├── 1f3b0cef685b1a0ce77053e8ae581cb1d66f04d4.nq.gz
    ├── 21b9a3accaa5f93f90cfb67f7ea06f8d16e80ff7.nq.gz
    ├── 228472c155f5dcb32698dd2d886cef554d5f55bf.nq.gz
    ├── 23969ec2e30a06b83f9f8733c547da089d7f1d19.nq.gz
    ├── 2454531405e46bf1ce2d9386b2065aafbd950cd9.nq.gz
    ├── 245c197b9f77bfff7cef9df64cbe54fb48fbeb3f.nq.gz
    ├── 2488dcf90908acee01c0bc0f228db1f41b62e401.nq.gz
    ├── 24c8cdacdc4ddf02f59051d89c0300acb5e88706.nq.gz
    ├── 25938257eb5c9f319a4308bd96b3d9093ee45b18.nq.gz
    ├── 25dcc520441b6e6fd0d77ff101c39981908d08cb.nq.gz
    ├── 2973288bf9ef9fe3195e7e0225f20cd2e6f10185.nq.gz
    ├── 29961b960426ad8be5423f78922c0db72f17196a.nq.gz
    ├── 2b79cd089ed1dde6bcd87de30e3f8dc23b57b5c5.nq.gz
    ├── 2cf2469319915bc0c89f8a9dcf9628f7bb1c5578.nq.gz
    ├── 2d7fc81cc931750eb6c4a7b286c9a15d08c765fd.nq.gz
    ├── 2de93dd596c7cb57582925e73984e015663f1fe5.nq.gz
    ├── 2dede140a08ed4a4729a3b5de01e5af3242a77dc.nq.gz
    ├── 2e04d16ab4f9ec63abbceaf867c704410015a654.nq.gz
    ├── 2f5016fe281443de69f3d224d5536e35838cf73d.nq.gz
    ├── 2fddd3544142a659cdb161444a1f8ce740d502dd.nq.gz
    ├── 31fd1a28e73f5d96a5613963c275a5166d6f23f9.nq.gz
    ├── 33495604247a3a50e2032a1a8450f9e10f56620c.nq.gz
    ├── 334cb2727a25f2c2248d1aa8b82318a10b2c8d0f.nq.gz
    ├── 33d6427378b3051219cd6801c4d244285c014a34.nq.gz
    ├── 33dc2846fe83dc3a85f43aba2e6dfb5f9b039f81.nq.gz
    ├── 359f64a5a41884305222f62d435d336acdb970d4.nq.gz
    ├── 367fbe828b853bc4e10bab088d50a18dec64c925.nq.gz
    ├── 3788c61bf9710c5e27d2e6bfa247e67dc4982ef3.nq.gz
    ├── 394a24e9a3084b7f058d1bffda00721872f001a0.nq.gz
    ├── 3a0760f1145760f57842369973ceb58b89b163ce.nq.gz
    ├── 3a673be7228fcdf9859b49b401a5656e739183fb.nq.gz
    ├── 3a6aa57deb95161439fc68bb8462b2ad665cb41c.nq.gz
    ├── 3b143737d06d01a935494db12523f7cad811ff1d.nq.gz
    ├── 3b39e5d7f68d70bca8d607aeee0496df4b17cb5b.nq.gz
    ├── 3c009b32db4140d67f5baf91ec0ec6866cce332f.nq.gz
    ├── 3c4f2cf078ee3100c4dc08c4ed7293ff33576f90.nq.gz
    ├── 3c67beaa0c460cace335ecf48ee9fab1ae3c476d.nq.gz
    ├── 3c6cabd4edff80b61a79d49e62075c54e7219f70.nq.gz
    ├── 3e2fcf1ede6231e76f9386a92347a63559fdb72c.nq.gz
    ├── 3e774831a85fa6501e27033a1989cfe671a2e4cb.nq.gz
    ├── 3f6b79194330cb5ee856c23cdbfc46ba8ddfc828.nq.gz
    ├── 3f6cdf553e4b0bce6227e2c292736435b26a2267.nq.gz
    ├── 400776338483edb1813594b1ce614e8c1143c71b.nq.gz
    ├── 4025b5ed9c868acf3f4f7daf970aed6f0ac1d37d.nq.gz
    ├── 40912aa10dec904a768bd99f18c00da9cb7145c4.nq.gz
    ├── 40d56cbae77436257826ff8929d31a4ed816e230.nq.gz
    ├── 413752a978e3872812def2988c9b266b73dce481.nq.gz
    ├── 41723de61170b095b6f8e345cba42a8dea1603e1.nq.gz
    ├── 41c2547f70d222f642f0d83b6690ece5c407a819.nq.gz
    ├── 420f4882e16d719e966b42ed6330cb30acec5548.nq.gz
    ├── 42d7cf6cfc710eed7e7ed7c67c422f063d91cd8e.nq.gz
    ├── 43c64b9b6577a86ff60e34b59d2c7b9fe38b29e0.nq.gz
    ├── 46c3c45ec628edc8d98f278bb856cbdb3b9659c5.nq.gz
    ├── 47e2fd9b1807e1fb95235947a0d83042f234c038.nq.gz
    ├── 47f4966b27d4e42d02c9c639e1f9bf506647d426.nq.gz
    ├── 493b5223699d22daaf391a9157d3a90b90748db1.nq.gz
    ├── 493dc33b297906f77ad27e2f3e7cca9d0dd749f4.nq.gz
    ├── 4a0df9be07a89d8eb2773d4f10d6eb5f8bce4974.nq.gz
    ├── 4bc98ad66caafda2fc044552c5704f567b96e3d2.nq.gz
    ├── 4bde3db20e78ff8550a4becf9110a97513e63230.nq.gz
    ├── 4c15b683a404bb696c9f8de6d69afc8e2f9bb940.nq.gz
    ├── 4ccaf8e3bb71d3399e372b8b4a8950562397eb9e.nq.gz
    ├── 51b07aeca7d97c7717b23be081fdc9ecc26854ec.nq.gz
    ├── 53edaba57bf2f25ef3ef06bdbc6dbca875d63813.nq.gz
    ├── 53ef3e6215afe2bbfbdc44b1a549bd05bef0fed5.nq.gz
    ├── 54743da43bd705d6e0bb67a8dd672b95ca366165.nq.gz
    ├── 54b0b864930f4e11f1d06a5acd247a959ca37161.nq.gz
    ├── 54fc47b61a0efd3a88dbb99a11c7a78c1ea87224.nq.gz
    ├── 585d4449f73bdd9f760216c39ca1b3cd6c9f5047.nq.gz
    ├── 5a4df190020345083939dcbc3161c04e7e81c152.nq.gz
    ├── 5a512390b3d1dff379ad4aba0ff88b61999921d5.nq.gz
    ├── 5afed58d1eb34ea0157025b328c514f12ff22dc3.nq.gz
    ├── 5bcc1321969467c5825f8d72f55f6f5f19b9a6c2.nq.gz
    ├── 5c57ea1f0270c646da6efa3afcad0212fef2de17.nq.gz
    ├── 5c9f26e6734c4b8495f21cdfbc59eed04f44af73.nq.gz
    ├── 5d31e03de8b37e5e683544b252cd7a64df5bf402.nq.gz
    ├── 5edc501dae48ef4357903a1ec91f6e5519d95e25.nq.gz
    ├── 5fc4ad53ea6fe561c946afe01af83da85b23cefe.nq.gz
    ├── 5ffc401c5639ee287afff37242fb380d4012ca8b.nq.gz
    ├── 607a7265b741f48589b69ef3542b94de0cba16b8.nq.gz
    ├── 60ca822eacc2af1f7783b97d593cd3cefa928eed.nq.gz
    ├── 639ec63c8cc916cbc1b5536f71b4459e8efecf73.nq.gz
    ├── 63e91ef0ec376b62bd5a516e4e47b10ff463f4ef.nq.gz
    ├── 64bd25ec7d87e26d64e4e62be28c3c18ff38d3bc.nq.gz
    ├── 6672702ff31d38eb96830490b5e3f8b56fc58629.nq.gz
    ├── 6724f5c80b22cb76d3bb5b94def14f0c7e7db2a3.nq.gz
    ├── 67fd9cacce68dae5dbc4e7d01ce73473d9655931.nq.gz
    ├── 69d977e6eb7042b89fa7656476b36ee9c48d2768.nq.gz
    ├── 6a54668505a6ced5843087b7db380efe3985d198.nq.gz
    ├── 6afdd8bf3d568000ae335ec9d564257981a5d026.nq.gz
    ├── 6d7ad6bf4114eaebb308e1251848680bb0375522.nq.gz
    ├── 6eadc499ebf6a32e9805ee6c04f3e041ca69069a.nq.gz
    ├── 6efd5711b0d390b222c22a9dcd5c38b55958dd42.nq.gz
    ├── 6f2931d54a780dfcf4c3b86b5b199fee21426cb9.nq.gz
    ├── 6f7654f89e23454abbbc4241f818793a41c4057b.nq.gz
    ├── 6fa13f5973f820ad715f4dba15837cbbe70299c0.nq.gz
    ├── 704f8c71984c8caf52b6d1ce9fa8554fbaf902f9.nq.gz
    ├── 71ce9fe9f1682bb0ea15278514524eee4254883e.nq.gz
    ├── 72419c6caa30706b909fda58409b96605832a870.nq.gz
    ├── 731343f4fec84b14b510dd0df3ab5d84ccb2fd86.nq.gz
    ├── 73310441407327cbb5f205721430767d3e85188a.nq.gz
    ├── 7350a88b4a00e465eb773fd3abcfc8960d180f8f.nq.gz
    ├── 74663a422899035662b99d5219e9445900d21058.nq.gz
    ├── 758b9acc8fce64baba9f1a16e2db7b0ae5039dcd.nq.gz
    ├── 76c651a0f21dad4880cd43e168272a477fe18fee.nq.gz
    ├── 773a6652cf3289713a753023042b7a2eb63b0ca1.nq.gz
    ├── 77477df51ed6033cc2dc5492ab566721979dd374.nq.gz
    ├── 77a84c2e5ff531e4e210232c04270e0f4c4cfe94.nq.gz
    ├── 791ba108f200ea559d0acd4afd23c436a00acd9a.nq.gz
    ├── 7ac86e30a76f3a1949b43cf672170635526bf175.nq.gz
    ├── 7b3643dcb838d8683237e6ff4d9241c23f2eb417.nq.gz
    ├── 7b9bca6d0e02de206e7c38a299eec46804af418b.nq.gz
    ├── 7cc85e52a8bcd9819555362180a70129d98962f9.nq.gz
    ├── 7d0cb355117909f47163cb01a595ae3e92302523.nq.gz
    ├── 7daf86745e0a37fcb8404ccd4a0078cdfa6c4e0f.nq.gz
    ├── 7e3314aa8cf5ae4d2817f89898d80e68737c5d16.nq.gz
    ├── 7e52446c9711af69902a7b2117cff5ff18830e74.nq.gz
    ├── 7f982ff12ff9a4eb9c0f7a4cebd181556df50b9d.nq.gz
    ├── 7fbdba85c44da0d314fbbeeef25e004e919f6d80.nq.gz
    ├── 7feefc02b464ad8c958d9b0e6a129476a07c1180.nq.gz
    ├── 8029b076ba8915d0812c131800468c1e49f834e8.nq.gz
    ├── 81e2a025215b259648ee6ac2b60402f549193799.nq.gz
    ├── 8249f88c05e44108f1a7d51ede4c962c28ab4898.nq.gz
    ├── 83928e031c38a68c89c88c60793b535d634c8c4b.nq.gz
    ├── 84c8734cc7168bd6207d7ac455298d5ebfab46f3.nq.gz
    ├── 84fddd4d9a54a5310c44b7418880bd81fcee82a5.nq.gz
    ├── 8640124d74824f37d3925fcbde3a746d777db1c1.nq.gz
    ├── 8651d525381806bcc18f7530940c4189ecf6f9b2.nq.gz
    ├── 874ca7f3c6be57b3a208808aa7b340325c4430f0.nq.gz
    ├── 88a5dfcfb4a11e5a058e4b5665661ef18d217154.nq.gz
    ├── 8a8f88083820aa72e8c21174fa022d2cf6392847.nq.gz
    ├── 8b041009a98257cf165f9141cea4e01854d9f693.nq.gz
    ├── 8b11ab4d782e95b24b905228be03e7d771ebe8e9.nq.gz
    ├── 8b56a7ee1e335672ffca09739fced742b69f416e.nq.gz
    ├── 8b795ad25adce8d4f513640153947e68ef5c91df.nq.gz
    ├── 8cae9faa31e9dc912332a1f298c4db4aa854f7ef.nq.gz
    ├── 8d6340de1c213a17ae12da81700a930ad7fb04b5.nq.gz
    ├── 8e66fc0483eea462a67fe877096a5392abc6704a.nq.gz
    ├── 8f35d9eb4de1fdee80c477c0cf06249d49a50a0f.nq.gz
    ├── 8ff9abc06955246a5067ac3ad208b37b052c9214.nq.gz
    ├── 918c422cdb2025fc5e66b6e40504993ed6992bfc.nq.gz
    ├── 919041f000c747052dcfecad47d1525cd484f7d8.nq.gz
    ├── 91915b5fd3d6c2dad1fe2c78084c6d0a9a86164d.nq.gz
    ├── 931fae06c0b0b834b8fc7be350b314e01d32f167.nq.gz
    ├── 9404fa908722dfac7a165f2b87901fc3cf3de2a8.nq.gz
    ├── 94bf34b283a8001930fbc51c38e08f572d4f6081.nq.gz
    ├── 95a77ec6d1b160c8c5c4f9d8f61e43934cac0123.nq.gz
    ├── 960727e5f440fb9965b2e04a6e2372b19056f42a.nq.gz
    ├── 96cc648296cf3ca186864906b8cbcf1afc387afe.nq.gz
    ├── 9848992f01f4805706f0dd8f22f393bfae72de39.nq.gz
    ├── 9ab1ce8fba77a637d24d57224ae214737065c1c0.nq.gz
    ├── 9af63452352991e598bb897ee2cfb6dec24c1951.nq.gz
    ├── 9b3140f273cd19092d7f4043af53924ab8d2fdc0.nq.gz
    ├── 9cef631df7b33017f50bd70408ffb5b5a8d29455.nq.gz
    ├── 9d06af649024eaab873035e4e30e6f8487ff6cbb.nq.gz
    └── 9ef318134e828ee160a8222b1ac8437b6b8a08ca.nq.gz

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

[sanic-org/sanic-guide](https://github.com/sanic-org/sanic-guide)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
