# Repolex Knowledge Graph of explosion/spacy-llm

RDF knowledge graph data for [explosion/spacy-llm](https://github.com/explosion/spacy-llm), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/spacy-llm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c62a9614f4b716e5c04f3c16aed7bcbecfb0189a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c62a9614f4b716e5c04f3c16aed7bcbecfb0189a
│           └── chunk-001.nq.gz
└── blob
    ├── 0348064cb608f06635ab6050f3c53160942406df.nq.gz
    ├── 049191d0bc5fb3849efb02f4c9dd325cd2811d0a.nq.gz
    ├── 06fab2f68015afd549eb489e61ad3106d3899d37.nq.gz
    ├── 083a7363f0c0af343884ac45c25b417aa6887bd4.nq.gz
    ├── 0898a500a5c2f7fe64f38c2aa038b3ef444cd0a2.nq.gz
    ├── 092241a1c0b8aa182fca07688f2a5c799047de1c.nq.gz
    ├── 0d3f85541067a3c6cd14931d9258737524e732c1.nq.gz
    ├── 0d53c7191e660d5fb7fdcabacac13202d0489960.nq.gz
    ├── 0dc0d8d07d5a20fb5c183eb4b037b717ffc82401.nq.gz
    ├── 0dfc80561104e5fb611beb0f3c7de90c9cb8a675.nq.gz
    ├── 0e147ca02aeec8d33a43782eb39cc6b487597482.nq.gz
    ├── 0ee1269924aa928a4596a4906dc635b4aad413b6.nq.gz
    ├── 1111e3de3c887f878b6affe9724dd2b914b4493f.nq.gz
    ├── 1624455f465ed2ea845e128f19417888f45c7785.nq.gz
    ├── 168e37bd03bcd4b5b3f119a7826cc4d7e5c8664b.nq.gz
    ├── 180cccc273c60075de177279f6f4da2d91397517.nq.gz
    ├── 1956308ba73b0c90daf5d218df39ef4bf1b42194.nq.gz
    ├── 1b36d7d0f519fbbd740a6eaaca3cd806cd567eaf.nq.gz
    ├── 2102362e759c81a24f16fe0e9eb0e33ed9a9914a.nq.gz
    ├── 21688a71f4bc03d32cad8d81e1c19edca56fc9e3.nq.gz
    ├── 2399b65dc7137a110519b01cbb8f9b135d62434d.nq.gz
    ├── 23eec817f69ffa65e8aca1b83d9be3e3b0230484.nq.gz
    ├── 23fe28ecd815793b5156ea26ff4e0c111f419e65.nq.gz
    ├── 258824d4e125a91b8ea40413337d862945400470.nq.gz
    ├── 25c684b6e555aa67ffd7112668d06244c11cf8bd.nq.gz
    ├── 260f6692916a5e31204e9f5dff0afbb3d839e7bf.nq.gz
    ├── 269b320968f47a48e4dcf863b4d77871ca010375.nq.gz
    ├── 270d16a811e25de3b1a471f4a5530d80009feaec.nq.gz
    ├── 27456ee7ba3ae9f347c2c80594027549a03f4e57.nq.gz
    ├── 291f5d298b3b38044915c84d2181cd69f58428cd.nq.gz
    ├── 29663aeae87e44372d9ca01f65193493e4786cae.nq.gz
    ├── 2979de7bb9d77ff06d257db43930b560c7d2c9cb.nq.gz
    ├── 2a348b4cfb1c9694ff02202c1b9577a24a426d2f.nq.gz
    ├── 2e519e3c0ddf219687a375289d4e62d7b7643609.nq.gz
    ├── 2ece55d137b410d0dc0d4b6c335d3a1f802f2a9b.nq.gz
    ├── 2ece737faf26e2f14bb957f6c0a9786487a9ca29.nq.gz
    ├── 2f141c115ddc6ac05b35e183d45ba5039d3d283f.nq.gz
    ├── 305732c61e75080d885b4bedff67865aaea679b3.nq.gz
    ├── 3058035c3adc8ea1a7f948c8a02b7ea6b8256731.nq.gz
    ├── 315c3c017538bac4393cfd505ff88eeffa2e435c.nq.gz
    ├── 31899f006bebbd19da18ff47a53756a0afcb9b17.nq.gz
    ├── 31ed6799447980584f2912295435ef03f2c49858.nq.gz
    ├── 324126a86b3ba92879b44836305610b525d690d0.nq.gz
    ├── 3246b79753fa4ad73a61132757bf56687e28244b.nq.gz
    ├── 32adc0bba675ecca2f65bb38d534994f6c65e446.nq.gz
    ├── 349fe2cfc100f8665d73b32cde946eb9800042c9.nq.gz
    ├── 352e093e3554f19d8fe13a01ff4275f2dab7e307.nq.gz
    ├── 361efa4357606e3d92c6e42f4afbe4c0533af31d.nq.gz
    ├── 381235b908ad44c66bb71201c1208b14e9aaae9e.nq.gz
    ├── 38444f712c48b3f61f8f3d4f7982d62f615c8a85.nq.gz
    ├── 38df5cb97fa3aaa7fc1ea5fda092b5684ced5aeb.nq.gz
    ├── 398523112a0b58eaf8da0c3e515ba08e15c01179.nq.gz
    ├── 39876947a291a0ff4ccea47b384d81050063a7b7.nq.gz
    ├── 3a38afc11f2a20b3e219e634905d6bd6786f1e03.nq.gz
    ├── 3a5ff1e32c962b96c000ebe9ef830f024bd9ee55.nq.gz
    ├── 3aefca844dd5d8d26a0573cdf7949cf3c4c8fbf7.nq.gz
    ├── 3c3793ff54a60deab5df3fe03dc2cd11fabaceff.nq.gz
    ├── 3cde8befab026bda1825326f271961f6d16cd748.nq.gz
    ├── 3d9d64a6c2de43c8b23d5a47a86c87612927477d.nq.gz
    ├── 4050906beed42d63864f72dfa4a3b42d51e7790c.nq.gz
    ├── 40ff3a6958534b8874efb77a22b04d8dd01e0fdc.nq.gz
    ├── 426546ca8ad4ab5602edc7c027f18a8e6dbe849c.nq.gz
    ├── 4352b62cd55185b3f7e1e83f0ee609f36879b829.nq.gz
    ├── 456161154a9e2c46dfec169766f7c5caa1b940cc.nq.gz
    ├── 45eb696f7d07d079ac33052523a8a6fa242cf3a3.nq.gz
    ├── 45f18e7e805bec6c2f5442366dc9291b41fee773.nq.gz
    ├── 460ede6c9b336bd3a5b31b5681105bba5c964f41.nq.gz
    ├── 46590e6e676acc7c1a58917cb3a24c9beb16d5a2.nq.gz
    ├── 4b8e8b4531266f632551a5f3ca50a32e1e2e3f05.nq.gz
    ├── 4b9c9a9a1f5bf55cf6b7d1bfda4107207095d38f.nq.gz
    ├── 4c5a6f803004e957e77e4167df8aae6bb789bdeb.nq.gz
    ├── 4c9a018718ad3ae6c77fee7d3f8990061e6d7b0f.nq.gz
    ├── 4d73207f320f3fb514ecb1303429ca9357b02419.nq.gz
    ├── 4dad8993371037b0d550d1cd52691cbf4e4c1252.nq.gz
    ├── 4e5aee1c2c9a35d6e1b8c519eb406d9aa54c5e0f.nq.gz
    ├── 526d168e8d8e0e4c02099453cbd2cb8a7798e1b2.nq.gz
    ├── 5364438a02a2c4d12fbc1ce2d1cc48a47014ecc4.nq.gz
    ├── 548d4d2919139a968539c070e2a86b19dd129f2e.nq.gz
    ├── 54c25443620785de72ea11df64544b0322b0e0c5.nq.gz
    ├── 54d1c19c677678b2a05cea86c24f982c689869af.nq.gz
    ├── 551e3dba2ef55118a3e486fe52e4f50517e43824.nq.gz
    ├── 558031848815ab75adf64be8db777392fde428de.nq.gz
    ├── 55c44d6f40f2ed98612d4c6d5105190b7422deed.nq.gz
    ├── 55cd78c1f362be162f23221d639a4b8b269d4073.nq.gz
    ├── 56dfa13e34baee8cbb2c2c29c2110b406b95bff1.nq.gz
    ├── 595efe69122574005260a1f9b5bda3e943faea35.nq.gz
    ├── 5cb424b1d29beefa0aca940336b99ec0589aa9e9.nq.gz
    ├── 5e4ba679730f7b316a9c7a4964f22108e16ea454.nq.gz
    ├── 5f9f34cb26426567f6ac787879b7e2ee88192475.nq.gz
    ├── 5fe4b178f20701f12f20b4ba995b1c5f71f454f2.nq.gz
    ├── 612bcf8fcff163ea2dee483d869290dcb86acdd1.nq.gz
    ├── 6315080f6a926ca24d2132423ec965f3363f30a9.nq.gz
    ├── 633d7067b1f34796ec28778a1e4e8c92c216f039.nq.gz
    ├── 67885025a4b7f4645f33bed204e412e78d5fe63f.nq.gz
    ├── 6896269b20a90a8aa4427acc967692db8ae7445f.nq.gz
    ├── 68e05726db7501d4ce279f325981c94003a6f950.nq.gz
    ├── 68ea1d4b70f0e8766eed725c826cb79a32f9bdba.nq.gz
    ├── 6a68f833f5cf1ba0710db298c84ec46866b1365c.nq.gz
    ├── 6a6dc32fe684aa12eebdf4f6dd062da239411c8a.nq.gz
    ├── 6bc818da08a6952b84c9926f6a539d1e9d9dc7a4.nq.gz
    ├── 6d024875b8a420814e46273630fe1d1d2dd26625.nq.gz
    ├── 6d02fb1ef556137d4dd17a6abc23a74d1ce08e0a.nq.gz
    ├── 6dd37704a1ebedfb069c4033c37b7ba04eb91b6d.nq.gz
    ├── 6e7468dd4a6825d816a251381952c8012f158436.nq.gz
    ├── 6e80dabc59bed444ffd4e3e79a18639810cb38d0.nq.gz
    ├── 710272201bdcc9c7e4b0206b8742a077b20145e3.nq.gz
    ├── 71c45e974f9a93f9a240518e138108cfc4165d26.nq.gz
    ├── 722627d7bd307c83ec3d997a6f151f85b3e929dd.nq.gz
    ├── 74f11944d8cd90044fe07097d556717f6d53c41d.nq.gz
    ├── 7715f12c6e77cc2ddb4f7cd45a81e8797196a3ad.nq.gz
    ├── 786a57eb592b63a2de9bc2fd19a9ec251cc8391d.nq.gz
    ├── 7958efc72ce7948cfbc212942c3f5cdad97acd3b.nq.gz
    ├── 79c711e1b90cd190422cd5c5b301433319f26ffa.nq.gz
    ├── 7a64a074e796c5cff5bf2713b966d188c12275f4.nq.gz
    ├── 7cb14dee787929b34bfa22fd39934bf9712a09fd.nq.gz
    ├── 7d285d3c24b9fbe84ba199c089b7176464308980.nq.gz
    ├── 7d54cca55848a78e7b192ca68e202955f6742c3b.nq.gz
    ├── 7e653f7d16d4443eb97649b58bf22bd3eb5bb033.nq.gz
    ├── 7eaf34a328acded3f24348e510491721045c6c34.nq.gz
    ├── 8240c6384a8a929bbfd684097d479925397dd298.nq.gz
    ├── 85950c307cf7686952c1b055dc8a7bbdb2edb1ee.nq.gz
    ├── 861171160a9fe7a5038e752decb08acf8ef11640.nq.gz
    ├── 8622db96589b404ecea7a5d9e4f0845b5373b02f.nq.gz
    ├── 8662f04b134542e9c6efb097ddeed3d40677ba01.nq.gz
    ├── 86d4080d83dda8ce9fd2afe3baea6b9133704fd3.nq.gz
    ├── 87065d0e2c3e2b6543e05e867be7a0da866c42da.nq.gz
    ├── 87b21f375100a8e3280aff18cb3d9cd56c122219.nq.gz
    ├── 8809fb94ed572f21c469ed83ceef636c01abf25d.nq.gz
    ├── 8855f6485a1d285cde188c82ca1219ad326c8b35.nq.gz
    ├── 88c8744b396ec1b91fd95962e28e064caf95c2f7.nq.gz
    ├── 88d775f4ab881867458e992bb82f2a42c65ee14f.nq.gz
    ├── 8b2fab5d3076998584a12112114bb9ec10e95e9f.nq.gz
    ├── 8ce0b194c1dc84ed00685893b96dc9b135b42ce9.nq.gz
    ├── 8e48a55ce66f9de4efb820267c7b5483e6a0acb9.nq.gz
    ├── 8e8a50878cc9c537cd57cb76747fa3a3fb4613dc.nq.gz
    ├── 902d15a50dfdfdf2fbb9b932fccb8acb6b1b184c.nq.gz
    ├── 90497c0b11c0cca7a3d7e9371b5778e9402ec861.nq.gz
    ├── 910e88fcf1c2513c91aa22c327fc43c72173f0b3.nq.gz
    ├── 91a5b02f00896bf5958ba69a7db765ccb9e18f5c.nq.gz
    ├── 92f53cd6a9bcf7e9cbb8521a8bade723ba7313bf.nq.gz
    ├── 9339bdef08883cfccaa168860c2b99f41630561f.nq.gz
    ├── 95b2bc9ae8180a6d8c4fe808ee741b5f45336455.nq.gz
    ├── 95fd9191e683382d9983ffe8f219fe55a5ef7a60.nq.gz
    ├── 96263967c7a20a34f0978013f8d4860038c1d6b6.nq.gz
    ├── 97940e0991f67406caa54f9ce18a619c81976e6b.nq.gz
    ├── 98b5af4385f63d9db207f21721559ac24e717a1d.nq.gz
    ├── 99442c2cf325d451aabb379d07e2154960e8c6ab.nq.gz
    ├── 9973135a3fdd7227d1d6b737f6abe63214a4d070.nq.gz
    ├── 9a04e2bce6baf9062876c7e48994793b42c7064e.nq.gz
    ├── 9ac259f58acb6412ce89e54e02feb5a93d50fae5.nq.gz
    ├── 9aecf23b34a87da010574e6f2e77f524475c6233.nq.gz
    ├── 9b086023eb6a6bc7803e4076fe285f2fdc463100.nq.gz
    ├── 9e2617d03674a5599b36ff94db81436ded78ea66.nq.gz
    ├── 9e793c041c7d1ec93aecf563d55621db191dae15.nq.gz
    ├── 9ee479a782efabf90ab6899d18eba6153e844b00.nq.gz
    ├── a29ebe911059671d93e7bf42ee814f51e45171d2.nq.gz
    ├── a2d958a0d977d8181f5b1cb96501bf03a474879d.nq.gz
    ├── a31c5cd3d845f59f24b0bc51e411dc7b4151bb40.nq.gz
    ├── a64b5268c7aa6c59959a5da8e5bfcc214257974e.nq.gz
    ├── a8096faacf3174e624fa9ab4f65ae379f7ed7ac2.nq.gz
    ├── a8cc0bd5e0f12fe9e92cd47b42681e360411755c.nq.gz
    ├── a8d5e26c0a23f8a840bb9ea54b92e43bd67bf512.nq.gz
    ├── a9faa3029d96f1ad585f4411bd87e2d1c47c6dac.nq.gz
    ├── aa316d4dd055ca9fb62a7c1d23aa981c93135df8.nq.gz
    ├── aa8323687c59ec947212aa5dd9c71973d45e9819.nq.gz
    ├── aac859662249b60bf35af09c64740a3256dc106d.nq.gz
    ├── abf825af2b80da1710c9298ada8a3826b637ca59.nq.gz
    ├── ac182bbcd7888fcfac6d0eb40eb5cbfa9fba2dab.nq.gz
    ├── ac5c154730dfa8998e42d027f41e04cf4e0430cb.nq.gz
    ├── ac76c11a261f879a3214c425df8eb759db4006ec.nq.gz
    ├── add263d2b68bcad1bbcbde634442a5b91459d329.nq.gz
    ├── ae3f8405f06d538f1ec06fea80f8db2fb5443da8.nq.gz
    ├── af5f7892e413ad1e4dfa33c9a050f1d9c35193bc.nq.gz
    ├── b01691bcb48684488f4b6bf704e48ded480dbf33.nq.gz
    ├── b04ef61dd0f156cceaa6c9cd679425ec4df630b8.nq.gz
    ├── b064c9efe3cce4674a656910c0fc8f16b4acf355.nq.gz
    ├── b0f4f80eebeb6e957329e382ffad2413db1f93e5.nq.gz
    ├── b1a2657da5620dcad9a5da8c251628ce3e240c31.nq.gz
    ├── b1ce44a2fdc7930c8b86199f5dcc8ea900c39992.nq.gz
    ├── b25f39e4a09ae2a37be7e558f7bfc4cbd2881309.nq.gz
    ├── b312deb9a6e475156cbc03275fff3a41c571d5b9.nq.gz
    ├── b3afbb717bfe6b3e48d23448c40ce68ceb9e4b87.nq.gz
    ├── b4835f16f86bd83b7d3e8d3cbfadbd474d7b205d.nq.gz
    ├── b6f84845148bb3f501342cd869fd87ebd74a1229.nq.gz
    ├── b8f8b7b777f7b0d5f7ac472994d5123566361e66.nq.gz
    ├── b94641ef4dfdeac3968ea9d38f8252fbba6243ab.nq.gz
    ├── b9b67137d4ca0047c6e75af46309e5d341c9c42b.nq.gz
    ├── bd1a1e718c07000f34da9c769cdcafd3d2e6193d.nq.gz
    ├── be77b7aef8a03e863a7f58b57675b8a88a3d950e.nq.gz
    ├── c18c46e8cdff0b46ce6ee5eaaf497b650d125c57.nq.gz
    ├── c23024aa38ad7a44781c97005cafb7977403c064.nq.gz
    ├── c23a1b42eb339278ebcc0391a6c3fdc7e21cfda6.nq.gz
    ├── c2980f33d129aaf7fb4605f6d16a26e64bd40074.nq.gz
    ├── c3fd3c27a93959aa98d99d22f61026a77b897ab5.nq.gz
    ├── c4159ac84e5fc63be0f9ff9f76961d083adbb408.nq.gz
    ├── c6367a54b4f6c43ac9740fb93e62d88ccd7ea1d4.nq.gz
    ├── c6900ce0517d692b3514c114018862a397a7f41c.nq.gz
    └── c80d636eedf56dcffbe3172f6689b1e2edbe2e05.nq.gz

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

[explosion/spacy-llm](https://github.com/explosion/spacy-llm)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
