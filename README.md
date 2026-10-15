# Repolex Knowledge Graph of jupyter/nbconvert

RDF knowledge graph data for [jupyter/nbconvert](https://github.com/jupyter/nbconvert), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter/nbconvert
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e681152f214b65387f875aad96a4726994533a0b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e681152f214b65387f875aad96a4726994533a0b
│           └── chunk-001.nq.gz
└── blob
    ├── 00b6a9f7f67fe3ea4e33871da07cd3de888ff180.nq.gz
    ├── 01da1888ad34b709932cabc842a2d5b9da28baf0.nq.gz
    ├── 023f5fdbaf950c293f8cfc7723d07d4cbf99eba2.nq.gz
    ├── 03258d76e407dd86b009840b22bbdab6f1394e44.nq.gz
    ├── 047c0dcceac848bbd7b4ddd770505b520bda640d.nq.gz
    ├── 0586923142c80c58a2fb1645d1195f6733b87f12.nq.gz
    ├── 06aee67497219d7c4966ed1c7a4e49a5a33afc53.nq.gz
    ├── 076177a497fae1482179137af028465c4f6b9c94.nq.gz
    ├── 07984d1e5ca667c4773d23008b8e3ea7f9c7dcb7.nq.gz
    ├── 07fdfa3919b06481be0b6015fe40f5fbee7b423d.nq.gz
    ├── 0839f4a418a6b1487e9c242f471c2eb4e96069f9.nq.gz
    ├── 0aa7955b0cfccc2575ffa509cb3bbc2d3fb6d80f.nq.gz
    ├── 0bbc24e5cb3c3df6458cfbada16c9425ccb28868.nq.gz
    ├── 0d2a7172fbc4c39e577ec8b808e54aa484997e03.nq.gz
    ├── 0db092a42fac7b7d047333ccd40e207bc4191afe.nq.gz
    ├── 0df08d9f895ed423f7578f6200dc77e9f26cdeb4.nq.gz
    ├── 0e07ff96f2ddff162c76121854df917b65a88b16.nq.gz
    ├── 12949a1e59424e50eb5e69c9899f8bb0c4a926c5.nq.gz
    ├── 12c4e0e73433b4f34715718b5be63dbc300033fa.nq.gz
    ├── 137a5a7d9e49a50a8f2b82666eb3f52830c5e7ec.nq.gz
    ├── 1512a2daa31159a1e9c76bbe555358d6d5d55ffd.nq.gz
    ├── 15bc4206663c2bea76ec8a77ffd4b741a75e9ee3.nq.gz
    ├── 1667513056e170e40664f8e107f9a6f9d9098838.nq.gz
    ├── 1749a9b9b36d0fd54020fedfe723de4bd0351481.nq.gz
    ├── 17df3bf6d904f425b90071fcc85c2b9c5f2a1889.nq.gz
    ├── 18a2f8e6108491e5a53944427b9d27cccb7e822d.nq.gz
    ├── 1b24ee37706a539cac74d540b6110744f90add66.nq.gz
    ├── 1bddfbcf0b644ad4452eb76b784093f89770ea70.nq.gz
    ├── 1dac45b49fb75eaabcd6048674671e3aa9c2a938.nq.gz
    ├── 1e1147c14d303defbcea1e173af1e4286377100a.nq.gz
    ├── 1e4e92054ce69fcf64b4f79d2bf052719856154e.nq.gz
    ├── 1eac748a79a59b0b03097af3eaa8320f82dcd7ba.nq.gz
    ├── 2080281d4ab1ab01690b432db55ea62d121c2414.nq.gz
    ├── 2102d33e1dda8a6cfae6578cfb1f56ce81592761.nq.gz
    ├── 211e65c9ddd9356f763220a63fd5d9a082926b9a.nq.gz
    ├── 21a039f898d2578bfb3cbd5d7443be00ef7a5a57.nq.gz
    ├── 22af74f7babb5b3da41be694070adb867f255270.nq.gz
    ├── 23d43537da540ded7cee3bcac57389c6bc5e1a22.nq.gz
    ├── 289566902a2902739a2a6361d8607c352c9022ec.nq.gz
    ├── 2b8c17f6565f11e450bec9cd1f65d8005f6867ba.nq.gz
    ├── 2c6dd0c974b53efb20b5101ac016631e0dbc7a56.nq.gz
    ├── 2e6a367b7fab5178895a437beea7358f2a24ed0c.nq.gz
    ├── 2ef60989922f860218c26acd763bd1c818d8390f.nq.gz
    ├── 2f2419532c2383f62b782dd16836ab40abe4647c.nq.gz
    ├── 30157c5b5eb7929b8fd024ad2a379e8004a0b3ef.nq.gz
    ├── 33113b55cddd1bf37cc48e37970ed3ede99e262b.nq.gz
    ├── 34fb53921874d819cf3dfef8d3c6c93db4767bd7.nq.gz
    ├── 35819a643a011153169c21365f5c3b4bc7c070cf.nq.gz
    ├── 36adcc2c9e079d6dd6d5c9165bc9a30e2b2c9e0f.nq.gz
    ├── 39b9bcaa6244fe6b2c5ef3427b36bf5fb8868293.nq.gz
    ├── 3a34e42eb35987873856b4c383056fbc4387855e.nq.gz
    ├── 3ad3d11cddf52e15a39340a76302fdd566ffbbd2.nq.gz
    ├── 3b30ea89eeded426dcc368fb8810871ceba19cd6.nq.gz
    ├── 3b5b25a2f1029cf6dfb7c2209353ddfbe81703f3.nq.gz
    ├── 3be9c9638715c699ee7dd6cba619c0f313e1adb5.nq.gz
    ├── 3ce6b0ac181f83c3b8324834e396f7e61e69f7f4.nq.gz
    ├── 3e29ae1714dacc17c173839830bd2674c1c2479a.nq.gz
    ├── 3f814615f77270b59ab81c95233d754d99ded8a0.nq.gz
    ├── 40f74721d4ca8a73bab1cc920e103e428091769e.nq.gz
    ├── 4195116a449e8f686087d25b059fcf959e351fbf.nq.gz
    ├── 428355549892f9a22efed4667f0537d6c036da70.nq.gz
    ├── 44b82fb5750404f86b92b54901fd584a349972c6.nq.gz
    ├── 48fbc03f5d0871f57f667dae3452b7d11602c470.nq.gz
    ├── 49328564af4873595977b822b544a477877db096.nq.gz
    ├── 494911f9763ba907956a68123db68705d7897f83.nq.gz
    ├── 49a40881d6fa65b571a892a3d587800a80dcc094.nq.gz
    ├── 4a6bd3275f8d557d965498674969375e35a8dfd8.nq.gz
    ├── 4ea1a9b23c4c0da67837aaebab310d755c62ec5b.nq.gz
    ├── 4f146277480df215f464e2ca068cfbbc45e8da62.nq.gz
    ├── 4ff89a4cb9cf82225ab511cb960766fe4ceb6039.nq.gz
    ├── 50de8c84811ec7697aa3c7c2d3c09af554ecd147.nq.gz
    ├── 51d4a7a56f60d160f4ce5ddd80760ca04150e996.nq.gz
    ├── 52b8a04400efc3c8cb2c8c8f949cbfa7f31f6e89.nq.gz
    ├── 52d3f26ab60bfe39a3d0f83075152fc63eb18d85.nq.gz
    ├── 54e6e0638eff22f90cd361a4fcb9ae1da1f93f2c.nq.gz
    ├── 563dd6299bfb7533c7cb229e5122769ee8127adc.nq.gz
    ├── 5754b5da842575c2f32bf49d722d3a6515b6f8b0.nq.gz
    ├── 5a3317712a91cd59db9ecb844df868e9d1909c4b.nq.gz
    ├── 5aeb837ff6765ce0412a403c92e19b56244c07c1.nq.gz
    ├── 5b84078922d9f8267d33deb221d9263c04b13ce8.nq.gz
    ├── 5b8713ddfab0a7c9815e4827e20818eef62a7761.nq.gz
    ├── 5e5821cad379cd213c6042c2ba2cac263704002f.nq.gz
    ├── 5f664c6c27afe57306082273eee1cda8c7ea4b6e.nq.gz
    ├── 5fe0c1d5163f4b0ce1ce47ee6ebfeff49f2a5171.nq.gz
    ├── 602288f31c243e8964879fa8211fbf939a78060f.nq.gz
    ├── 605e3d5e333170c25a7f38c5ad491a9a8a9e9b31.nq.gz
    ├── 609a016535db1c84ea81b44b40b02e72fe3c0dd0.nq.gz
    ├── 60cc2ad71bfb0e853155dbc67da8d9eb9587f7aa.nq.gz
    ├── 61935c69857de99c6e60e5936b939c9abea7d90a.nq.gz
    ├── 61eb654410c4f3c4d568537541d5f664e7cdea43.nq.gz
    ├── 622a2c661705d2f6fc2e686524c5c32a9907899a.nq.gz
    ├── 6276007a62a692bc52e11cf7f32a6a8f17ae483a.nq.gz
    ├── 62de859bb74be8f79ddd4c33fdb496421dd48bc4.nq.gz
    ├── 63a8fe9c08af40e1fe2b7330ac41c737ed8a0816.nq.gz
    ├── 63c5d7e288cca52ac43f145a0779c04207bdb477.nq.gz
    ├── 63f503a0d5bf0923042b028c4b36c000bea6b5d5.nq.gz
    ├── 64286288d73a3abd0fb14f3a2127ca05368c6907.nq.gz
    ├── 6464da1e7989a5cae08b15d989143544974eeb39.nq.gz
    ├── 6467bfacb330ebce2f62e488d4f741bd065a6848.nq.gz
    ├── 650701ebc91e113a3e6b4ad2f59acb7c4ee44ba7.nq.gz
    ├── 65b9ade664f7a2d2cef3380e1d7e28670a6832a5.nq.gz
    ├── 65e115b2d1bad09c90797062798516fde95f6dc0.nq.gz
    ├── 65ecd49e993d4c279095e98146a47ba873e5489d.nq.gz
    ├── 669562a2fd833a6a1e6377006dc989b55a70e2ba.nq.gz
    ├── 66b091a5394d75d40c6151c125257f97e921670c.nq.gz
    ├── 66e95837ad490beed53e247681e00400653dd8bc.nq.gz
    ├── 6a4081ad942687ba4e318f1b7345d37f07d6e71d.nq.gz
    ├── 6f46df1f626822590caaf1734fc59e40587ad5ed.nq.gz
    ├── 704840bcb5ab8ff2bc602950df2795b115eb2199.nq.gz
    ├── 709e08c670124045645fdb00f043ea793639c455.nq.gz
    ├── 70abd616b322b7dc83a8a6162e992f7afea865d6.nq.gz
    ├── 70cd67c1b6f00a048df1e238f8a79ca587534afa.nq.gz
    ├── 7216fb9f873ff8c5e80e6c333a25d338411481c8.nq.gz
    ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
    ├── 73107db2b93fc7e286450d630b35e6f8612cdd04.nq.gz
    ├── 751470a8cc4ecbe34416e875f8ce1adc2db5d0bf.nq.gz
    ├── 752c44c4b5637dc497aca822ccd54d13d4b29dd6.nq.gz
    ├── 76364245a3c333d50bd21903cdcb86212effc99b.nq.gz
    ├── 7757235adb531a3ee11bc96823f27a8777b75366.nq.gz
    ├── 777183f0cedba250ba529d7c6e3bd7711de67ad4.nq.gz
    ├── 790cdcdc82117b3c9160fdd4b290fbace6a359f3.nq.gz
    ├── 7a2b1c35b225597a3facb6c7fb810d4b23eb8a58.nq.gz
    ├── 7aa61e10e67c76154ba4e91901c8930ff6e04bbd.nq.gz
    ├── 7aae33077bf7289349167c560240ab1d09813b8b.nq.gz
    ├── 7abc8b9b32d86c385ab6e3853a88fd41511511f3.nq.gz
    ├── 7b7779beccab05271fe29bad5ae02c0b1320b08f.nq.gz
    ├── 7bb87572d0a8ad7c5ac00d6656809b6b98d6ec40.nq.gz
    ├── 7d244f11dc6f733c63d9aac11008d6e68e91499e.nq.gz
    ├── 7df8df86d3d9718d86bd0d8b69b3ecc7d38a2d04.nq.gz
    ├── 7e9372709b3dee1bfd020ff027d01856711cc4d8.nq.gz
    ├── 8349360a44750565db278c47287d1d11c1cf2a4c.nq.gz
    ├── 83836aa8629c8a983d0cece675f34a2d4cd2cc18.nq.gz
    ├── 840c9d4deaac6e685267955b3c5285058d0d25d7.nq.gz
    ├── 8456d2e4bf520a481dc6d325fdd6417dddce771e.nq.gz
    ├── 846ba94f5793e74b9f87d50c3f807b3cd48c0067.nq.gz
    ├── 858823245abb23afbbf412f65802d21c07d1655c.nq.gz
    ├── 863c94b168afb6ece344c404731e8ee82a7d4dee.nq.gz
    ├── 86a3e9275dd8748bfe709dc965f78b2d1813a913.nq.gz
    ├── 86dee7d637655c7e87494e6e6da22322e794170d.nq.gz
    ├── 89d894d2135a578b119c67bf1e60a0d80d82787d.nq.gz
    ├── 8b92e24533a8474b7cfed5c1dfbabb7391392381.nq.gz
    ├── 8f3dff3d75d9c2fb9f3509ec2b356eb5e0b4be12.nq.gz
    ├── 929b18759521838ba4de43893a3afb77d06f85b4.nq.gz
    ├── 9340e6886acc6818af0a7670cf9c6068624fda55.nq.gz
    ├── 949bba22e82c626d470125536d65973bd609e0a6.nq.gz
    ├── 955314f5af5f941fa6985fe92409d0d6c9362a7c.nq.gz
    ├── 971f8eb4d63368fd70b5048bf01fc029442a862f.nq.gz
    ├── 9858e04b137ac06ef19bafe349f314f07aeadc7b.nq.gz
    ├── 9953723ec44445f103957bd9d1b27f1088f08247.nq.gz
    ├── 9c66ecf2d679acad6e7552d5a7d82baa3ee04b1e.nq.gz
    ├── 9ccd3d58444fe0ee1a144b074454a831ae5207f1.nq.gz
    ├── 9e561c70141f1f737fc7640854017b4591ce713d.nq.gz
    ├── 9e8d7ce5a3b6abb8e67cbd93cd14b99c6690f1dc.nq.gz
    ├── 9ee8917f92a62335725a79f4a04f5501b0f61cd0.nq.gz
    ├── 9eeac151349d15ab54a62518898c7274717f7826.nq.gz
    ├── 9fcefd60a08008e40fea42a15b3e3548e0f399a9.nq.gz
    ├── 9fcf9d000ae9b415caac39c6a0a5c71668a8df72.nq.gz
    ├── a09fe9d1f5d42c241794bae9a7dae71d9148adda.nq.gz
    ├── a1f9fc51eb9557ce322983c6c376084af258d68f.nq.gz
    ├── a23013ccd893f21a910e36f656f8a64a00edda44.nq.gz
    ├── a2c82dd8d086f19b2005f72912a968a4090aea62.nq.gz
    ├── a2cbd1e21563abefa95d969d5841f6aa78a0db70.nq.gz
    ├── a2d107fe9a26a95086b1b9e5afffc953c7b2904e.nq.gz
    ├── a4636ff230f5d68b23feefe45e48cd017be043ca.nq.gz
    ├── a6137ca899f60ed6cc6def43964079aa7528e47f.nq.gz
    ├── a7ad46de221f73170b5d59d21f3f3648c4ace10e.nq.gz
    ├── a7e8a109089ae94f30ad1b160d107a31dba10f81.nq.gz
    ├── a8225248fbef0ad590226cd4f7d1fe3aaaac6df3.nq.gz
    ├── a8da9b4e8c734aaddfe59f0c7cc355ec9af407cc.nq.gz
    ├── a953ab11783f732bf86d82b9ef543d973c70355b.nq.gz
    ├── aac0a5b46c178f496679e7cfed5f23642354be19.nq.gz
    ├── ab693536ca402944b46e8f7c98ccd8ee09621081.nq.gz
    ├── ab94a09985b0346c761a7abea5b0ca443eb56cf7.nq.gz
    ├── ae01af1fdf4c25df7fd711b8310ff1c646f9fb09.nq.gz
    ├── aed02320970471974a7d41559aff3c3bb6a7aa29.nq.gz
    ├── af922b6e024d7bfc346abed1a6d93570fd44a31d.nq.gz
    ├── b090895b1b734852c727ebdceef06e7ad3967765.nq.gz
    ├── b21e34a1273c21df16bfafc5ff653ed4a38dee25.nq.gz
    ├── b4f5ae6fceaca4fd537ff1bf278c1dc5f06af1df.nq.gz
    ├── b6f801091775f2cb1b45c76cfc715e34c330a300.nq.gz
    ├── b71ce7992ab7c159315f1d52cc4c4aa284c3c2ac.nq.gz
    ├── b741de7bfcba82a80f7ee4b3649663f39707d81b.nq.gz
    ├── ba3ffa8dba3dab99936cfb961f917369ede5f84d.nq.gz
    ├── bba1a32417a18ca4b8d3c09adbfd73e3edfa564e.nq.gz
    ├── bcbcacc6c66908724cfb96cb4249ba2d338c4b7a.nq.gz
    ├── be07920d4d569f1beb9f17a9728662d0d223dca6.nq.gz
    ├── bf3a9d891d45dbe89be7b2c93414d1267e431cf6.nq.gz
    ├── bf88218419fa5365e5a6253a67bf90d1df5bd0a9.nq.gz
    ├── c0351ce2a0b227f3f67ed07cde7c720e969f33a7.nq.gz
    ├── c0541baa8ce9959487f8cf6ed66204ee19666bc1.nq.gz
    ├── c24639e9a5766ef88f771b3933a9b495eb964bc6.nq.gz
    ├── c284a270722fed638dad6dfd81767b022a630327.nq.gz
    ├── c374cd240f0274cda4e33ade4c08a0f04cb890e1.nq.gz
    ├── c628582878635ae78215737f2fa88b3e835341dd.nq.gz
    ├── c779c0cf0793107d114e15435e54cf71b6a6a6a5.nq.gz
    ├── c8672d3112e791cdd8379756b96f759cde1c99ef.nq.gz
    ├── c96416a7f82cd38ca5278a52d84768f9818fad6d.nq.gz
    └── c97736ec83d6af1446c6474a0d53e53e0cb6a268.nq.gz

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

[jupyter/nbconvert](https://github.com/jupyter/nbconvert)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
