# Repolex Knowledge Graph of litestar-org/litestar-skills

RDF knowledge graph data for [litestar-org/litestar-skills](https://github.com/litestar-org/litestar-skills), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-skills
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d2d7b8276c3fcabe89658edbd74c16654910bf5e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d2d7b8276c3fcabe89658edbd74c16654910bf5e
│           └── chunk-001.nq.gz
└── blob
    ├── 00f9e26ba1c74d208e08f1f442fcbe45220da86a.nq.gz
    ├── 0166ada66fe9a8876778f9ce6d41414632eb5913.nq.gz
    ├── 02084625ada7fa8918d50900cf62895aa33472ee.nq.gz
    ├── 02a78199898ea02d52dd7f1da36018751d7d3cef.nq.gz
    ├── 0354de5487a27a8940b0abbe63c021a013c8f5f9.nq.gz
    ├── 03df2a2ef6793d8ac1cc65561ffcedc7a21c575b.nq.gz
    ├── 0699c4d23271073aefe5624d6cfe6e63a9bd1dde.nq.gz
    ├── 07f6c8b6fb7cd293a4ddbed696a9a1fab6cb2297.nq.gz
    ├── 0839a08bbff289831866244d783091d01ef79552.nq.gz
    ├── 0b3a6ad968a0247037c22f09e9e4ae5ddd09ed10.nq.gz
    ├── 120f2dd4481c4aee105353b6d91b5069a1909e54.nq.gz
    ├── 1250fc62c910dbed51856b83784a7f161b501a88.nq.gz
    ├── 129d99a65956af925cd28ca0f3aea4d60b117eaa.nq.gz
    ├── 12e5c0a8ba64db3f7c8ee90f3d58559f3b73658e.nq.gz
    ├── 13597488a5efa9fd3b1c4879eaffe76e8c2700b7.nq.gz
    ├── 13703990af0cc028eef7b0df43b5028ab0cd289b.nq.gz
    ├── 142520a35745020ff0e66f4e61e1d5ab6839c485.nq.gz
    ├── 14abab3c1e2cf0187fe008e35152c7164d709056.nq.gz
    ├── 1764812b5f857cfe5657573aaf5e8728d01befad.nq.gz
    ├── 184a143a4115decd5e82cc15bfdd163e03311c52.nq.gz
    ├── 187cefc54b85f15f97dc7aa0496e3535c5261e02.nq.gz
    ├── 1a7a0e20ca6e27a8c61272f899050afc76d480e2.nq.gz
    ├── 1b08691052ca975dd74a5ddcfa1d14276c583c5c.nq.gz
    ├── 1b5f3579bcd968d638a3557c2e1c450aadf17ec9.nq.gz
    ├── 1c125d73ab2d6c1ce3fd078e18cce39442ae996c.nq.gz
    ├── 1c7ff9a7d49c5b23d902b6fb34dd9af3d8699364.nq.gz
    ├── 1e402cf25611821c43ff9a0da973d41da8521f51.nq.gz
    ├── 1e49a40e9cfed96183a2955856f25338d04a8729.nq.gz
    ├── 1f0f6a121161bb6249ae68ec6bf1094611c32207.nq.gz
    ├── 216703f34b2d573c4bed858176e5c5785b36af62.nq.gz
    ├── 25d5f9831135d05ddaa02c4fc4a3a6b775ca2fbb.nq.gz
    ├── 25dc3413feda3d0035d4974abef094feeb5e4c13.nq.gz
    ├── 270a963a41f98663d89a88f8f57101f05b002877.nq.gz
    ├── 2780cf7e649fae791c20c5e5ae3c3b83afc4636e.nq.gz
    ├── 27a4f29ab83f80a40da06ae3b1cc7b03db06e228.nq.gz
    ├── 27af679fd0421a60cd0eee6bfb52cef494ccbb33.nq.gz
    ├── 2893113eb9df159897708d3cc95b1f2455a69a4f.nq.gz
    ├── 29daba04f32189b24a0781f397ec3f82b88f02b1.nq.gz
    ├── 2ac3ed7c6cdf0d3c9e498719cb70c0b893c3c5c1.nq.gz
    ├── 2b84399d1656dbade23a86dc6beaa964a2c2201e.nq.gz
    ├── 2cece379e6d1b312ca649dbc7ec785502bf8baea.nq.gz
    ├── 2d2f47cadbb2bcfdbf1b340155cca090e27be770.nq.gz
    ├── 2d59abc9ffd7900fe9e2902bbb219f887c5fd908.nq.gz
    ├── 31061bcc89f8a8d0696dcb4a832bb2013608f61c.nq.gz
    ├── 3149e6f0cac99b62901d869e68f3e9bdfd802de6.nq.gz
    ├── 31a54f4a614d62d2fcab6c874c936551d0852fc1.nq.gz
    ├── 31d41997ab15f79cfcbfe6ef8ef2472d21dfb8b8.nq.gz
    ├── 33c5b891a7c0436c9ea9844c5a89cfb7a00a24f5.nq.gz
    ├── 34158392f45498d2cac84d1c52e87da31b4b1b18.nq.gz
    ├── 341ae0c09c0fbfd14d9d1c70de36bcbdf5dae47c.nq.gz
    ├── 346184f27a825518e70714d6d42fa78d14fc32a9.nq.gz
    ├── 3490feb707f2716d9b3968fc977bc809b0e267db.nq.gz
    ├── 352ae6f5d6ff06ab410023b39d07fb6eb8d47ab3.nq.gz
    ├── 36279328c55800e9218fb7c6b8a6f9229656455d.nq.gz
    ├── 385f5e50df007964d24a49b8e7f7fe131edc680a.nq.gz
    ├── 38bb16b665c828f0640ca8ad137459dcb7a95e23.nq.gz
    ├── 38c58d93e03f4b5f489e4a4a0fdf1ea995103117.nq.gz
    ├── 38df929fbc247461344c4d90a7edc3dbe8a6b841.nq.gz
    ├── 38ef0fb69b553c60dad7a08dddd18ad9e98be408.nq.gz
    ├── 394b3cd33740e0adf977e44d61d132b8f2a46e49.nq.gz
    ├── 3a1f37e2dc3ae4fc661cfbb34b181fbf67b5cb1d.nq.gz
    ├── 3ac4d542b9f087c873340a41611158a36db5d043.nq.gz
    ├── 3b5ee48ab4e5cfa39dcf0d9945f4ca7f7a4ee46c.nq.gz
    ├── 3da2c0b194c0e52099b517b1c1b0c2a18f764c1f.nq.gz
    ├── 3ef0f352387d24a5ec46a4028d813b1a56dad4c1.nq.gz
    ├── 3f0329ad57cc31ec24f6267e8582a18d67dfb299.nq.gz
    ├── 403874bf99d65469df53db8eabf08409b09313ea.nq.gz
    ├── 4096556f14f38988037e77f2b3280564d56c5853.nq.gz
    ├── 41c7096ae0f8160ca5c3c91985e1eb173ffd0fe0.nq.gz
    ├── 4204fc6edb7a4cc970859d781c4df5c03d1a2538.nq.gz
    ├── 420db204ff1ac5c3dc2ebf0ee2d4db43078e6e8e.nq.gz
    ├── 4615d6674150dc745100510474e771900f334443.nq.gz
    ├── 4a8257e62612fb276cca3b15a8ca06430f361086.nq.gz
    ├── 4a8edea6b626e5b45812d89baed83a3b1b571d99.nq.gz
    ├── 4b711787236862650a7b9c55eeda40b91f95c11c.nq.gz
    ├── 4bf98c28750c9ade81558d8ff34566bf6fb2572c.nq.gz
    ├── 4c37d16bc7badf857d91255bd67721a29fc149c7.nq.gz
    ├── 4c5f78df5580b08d925c5fea4db398421787a12a.nq.gz
    ├── 4d2558718acc70a295e622aaa1e432436239665e.nq.gz
    ├── 4de8e99fbbc7014a915207d384be1a236f6e6a0f.nq.gz
    ├── 4eaaec9465ccab1e3f617da7dca137dc3e1314a8.nq.gz
    ├── 4f01dd7e1f0116c4fc045d96758a99b402945bc8.nq.gz
    ├── 51208517ffd4d8ce18baeabeac311cacf7d1a230.nq.gz
    ├── 517aa180cd3566752327599dcd137a808a8e4b66.nq.gz
    ├── 51e45f0f1b8571c5b370a5707a0a837173320e3a.nq.gz
    ├── 5240089b1cc29c6af6d7307a4790bb75ff3da5d8.nq.gz
    ├── 5271ac49edd28cb217a72ece945ed3a9233610fc.nq.gz
    ├── 52fc433fd6e85b09961343899afd53f8a4405955.nq.gz
    ├── 535f4804aae6b59179bcbeaf54bc1c45fcfb55df.nq.gz
    ├── 5448e53363dab60dd579b49b7a72b200c4da4ba3.nq.gz
    ├── 5837fc5f6f4055d916f7ff5b831ba977510cc3c3.nq.gz
    ├── 5946f2d8a8dc599247b7013f6fc138ddf00da89b.nq.gz
    ├── 59e4b90334409fb7cf6281b54ed85a3a4978937b.nq.gz
    ├── 5b2cd132a2e0d3e4edfedd0a20754754163f48d8.nq.gz
    ├── 636f6e2e39ccdea2b33dd3b1cb418c4dfbce8acf.nq.gz
    ├── 6480de62e63f3e027374c23f1ca7ee64cf6908bf.nq.gz
    ├── 65fbb65e2a706d297005de802e2610fe402d3d94.nq.gz
    ├── 6829aacb3c7ecbcf3510f9cd3b8da845cfb45abf.nq.gz
    ├── 686135c323064ea625499a10d42e3e1f8bc469bf.nq.gz
    ├── 694331ee6e28161f9885abd382a3aecccdcd476a.nq.gz
    ├── 698f99909dd816b9a96abead55d46efc5ff4f746.nq.gz
    ├── 69b0dd912f557b23376bb88ce74d24276df1b104.nq.gz
    ├── 6a38444585078b1edda20caf767b6d5d63048aab.nq.gz
    ├── 6a6c8646e6b29f4367e3c671071e69a04573349c.nq.gz
    ├── 6a9a2600b4821baac07080094d86c26691734368.nq.gz
    ├── 6b38c8043579fcf2fe45fb01cf8fd46056d21040.nq.gz
    ├── 6c3a3ed81817f7a9e47ac8d5cea1c31e6c5044f2.nq.gz
    ├── 6cee765eb032d963cf92cb445132c61a7d0ec2e0.nq.gz
    ├── 6e3021fe2b280e5ea28b9feedb32f459397b9f55.nq.gz
    ├── 6f718d0a244b00bc019a5b165d439e77764a7285.nq.gz
    ├── 6f8f229ba7dabbc516c6378889492f1e0002b4ee.nq.gz
    ├── 6fb2710b1d57a0601da72abf707582f9a350a1fa.nq.gz
    ├── 6fc4cad9506277dd27ddcf007071b3bd1e24d397.nq.gz
    ├── 7228d530c883ef06e22dc009c0545dbd381c1eae.nq.gz
    ├── 7693df05986904bc63d39112fe5bbfd2a46a9a18.nq.gz
    ├── 7708b99d2ff8a3b6244c205b361b4fb3055df7b4.nq.gz
    ├── 77c6238e63ff1ed90fbd148d5204c58148a1bde0.nq.gz
    ├── 7821a00581622231e483522ea30120fd6fa8b36b.nq.gz
    ├── 7864f7b4a010151603fb6d5d62965f1c5518e8f9.nq.gz
    ├── 7a586049ef92aa8fe24709c2e012efd050deaca2.nq.gz
    ├── 7b306c0eda05304e28ee9b0f35ba26fdad940c09.nq.gz
    ├── 7c2a10cb4f83d950284243db80c2b4015a8aa70d.nq.gz
    ├── 7c37780071dc12fc4d8ca50ad76d7c2188110cb7.nq.gz
    ├── 7c68761b6ab89dd0a249ab38cd69f77bc919f827.nq.gz
    ├── 7c98423cde3561b0c31d6fc2c48f9faf19c39005.nq.gz
    ├── 7d75023bdc12142975d5b1819bf82c1b9795323d.nq.gz
    ├── 7defe5f1271b2d2ebb20b941c513a91f6fa4ad2e.nq.gz
    ├── 7df160f26a55f39a546ea42ae8cef39a9fbdbcab.nq.gz
    ├── 7e1cbbde0a346d1bcc38740aae459f54e15acd25.nq.gz
    ├── 7f0d706f550466e281338ac223f0c00280d9da2a.nq.gz
    ├── 804c852d19da02bcd533dfe86d5e3050d8037dbd.nq.gz
    ├── 809dd7709d0bc9547beed0ff4c50a47886c0cc82.nq.gz
    ├── 80b85e4cf28e6e7e20bf1d528fe8410c508bbf0d.nq.gz
    ├── 848f4c098897153d21b5c9c6d1d85bd1254292a8.nq.gz
    ├── 868365a9bf5564e496bb6267cd15f3aad2cffd1e.nq.gz
    ├── 87ddb2521a0ea266159bf619dd1c6f544e4205fe.nq.gz
    ├── 898cd7c311836ca1826bd87f7e57f51bd607d099.nq.gz
    ├── 8e141185aef623a9e3a86c16cf738b476c71e0ba.nq.gz
    ├── 8f713d16ea9e94fd9e40db1a6b3620c1420594e1.nq.gz
    ├── 8f85981f59bbcb906e159ea9f119fbed48f9b4f7.nq.gz
    ├── 8faebe01432aecded8b81e5ba34f8fe6c785ef6a.nq.gz
    ├── 92295f5e1ef3970137105543e4bf1956f241afb4.nq.gz
    ├── 92717c131119a9253cfa4cb7b43ffd54a54768d5.nq.gz
    ├── 93bd2827b0457481b5249cf48ac45bd1f4109334.nq.gz
    ├── 94102d55ce3424c70e2a250f98de9f0e9fe0d3c7.nq.gz
    ├── 943af3efe38a3ea2de936ac03aa9d2a15ebf11a8.nq.gz
    ├── 9616b4f106bbf6a523999955996951afe966a0a3.nq.gz
    ├── 96f05bb5d30c51641625fca9732a708653fb88e9.nq.gz
    ├── 994c7bdc322f21af65a1418fc913d42ce07a5e85.nq.gz
    ├── 9959a5b65df2d499f4cf73acd72f475b94ef23a3.nq.gz
    ├── 996ba59b2f6546b053245113f321528d8c984c76.nq.gz
    ├── 9a64cc387e192e2a707745c4748e0cb4381f8e94.nq.gz
    ├── 9add68b7211f6255a3e0d3aa999281e3528ea793.nq.gz
    ├── 9ae31082afaa8168312cc525ebc44cf45ca6b6e8.nq.gz
    ├── 9af8f5ee66d308a9189d832239e8c49e94d8b96f.nq.gz
    ├── 9bfef8560e6f9b7675e2d29e3769c07be9c83eac.nq.gz
    ├── 9f33197c07bbf98d8841cb5b6912decfbb967174.nq.gz
    ├── 9fe54bea521f9a1c70df4e211783baa50b107306.nq.gz
    ├── a01ad56aba80403a6421fb838d82e1d27d23924d.nq.gz
    ├── a0ed36f5f54446ecd03da45b5c8d0a5d8cf771d8.nq.gz
    ├── a34e4a44988bc095794f481c7374bf20050c40fd.nq.gz
    ├── a3825aca405ec054afa294ce836dafb729f44646.nq.gz
    ├── a44418b5464c730bf18f42a57bcc35fdc285af14.nq.gz
    ├── a94e36ce2c6c77e2ccb0f27e7db8c4fdefcec612.nq.gz
    ├── aa410cbae40b1fc09c568016ad399b1d05d2734c.nq.gz
    ├── ab3f42e1cfea18c55a92eca1cffe1c7a68916801.nq.gz
    ├── ab67020698c07e94b59e3ff972909be1e1d9ded7.nq.gz
    ├── abc741c0621bcc485f859555e8805decd74ad01f.nq.gz
    ├── aed2c6d02c2426e21be52d9aae9deaa5b59f3358.nq.gz
    ├── af24416eafcba4652e668fb3fb0e6d7a711dc762.nq.gz
    ├── b02529c948c1a5aaa9447f1199c13ccc2217d0b2.nq.gz
    ├── b0655c14dfed30c72c7478b11cb864498f010fe4.nq.gz
    ├── b20af77136665e4e2c497881e621a778bdc14ad0.nq.gz
    ├── b343fed0f2af794bbce42b957e4500ab6fb1ee66.nq.gz
    ├── b4011a15643cfb0a0015c421e877b1bda0964ec1.nq.gz
    ├── b53eb0f43f675b2709ffedb65a1455b895541460.nq.gz
    ├── b6a19eade11f75bff69c952cb86df13e7a4f360e.nq.gz
    ├── b87eae14ada2565db3155b8ef2a69bef08001628.nq.gz
    ├── bcb7d66d4a446a064d31d836260bcb706a555a44.nq.gz
    ├── bd3fddd76832f12c35ae801daf4d7f0a5d836ced.nq.gz
    ├── bd6c0cfb6e1474554558b39ed7fae1989dc49a24.nq.gz
    ├── be9b0db5bca685b3aef7fc717e689d5b180a60c2.nq.gz
    ├── bec38b9d1a93a10581963e9380bb51b4a733ae9b.nq.gz
    ├── c0b93fa9f153aa8da94186cec3cfe6f61b5c6f77.nq.gz
    ├── c1d8eb0c304a40725d545c347e0c433349f750bd.nq.gz
    ├── c20520dded48047a2279f3770b724f81d1d9d8e3.nq.gz
    ├── c2fb60e0b7a539f7bae17daeb44f486840471912.nq.gz
    ├── c36de84ff90b9fa75d0a7c074584fcb1a3fc212e.nq.gz
    ├── c421ebe4ff6fe9f4b375c7d99de7ef7528ed9c5b.nq.gz
    ├── c43a630b6854ccbc0ee0478fb5e4bc80e40bb151.nq.gz
    ├── c4709cb1c2bf4942a2a1dcc7a6ff6911b8a43e4e.nq.gz
    ├── c5885b5b7c4f837aa6addb831350f9bde5720538.nq.gz
    ├── c705cc6f16bf5c897b65bdc03e76877a5317e0a0.nq.gz
    ├── c70bf2000f581da7c812a8eca9146c1364e46c37.nq.gz
    ├── c7a4381d454362089ed50358aa4388465a61d08d.nq.gz
    ├── c7b0be8d541c39eb093419ad2a4ca688c9e918ab.nq.gz
    ├── c805f410cbe3444a88a089aee91bccc89952170b.nq.gz
    └── c87c6b1c3ad117960a6cfbefd10132bd5db40957.nq.gz

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

[litestar-org/litestar-skills](https://github.com/litestar-org/litestar-skills)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
