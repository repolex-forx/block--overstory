# Repolex Knowledge Graph of block/overstory

RDF knowledge graph data for [block/overstory](https://github.com/block/overstory), parsed by [repolex](https://repolex.ai).

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
rlex download block/overstory
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d04b80114b9fe891f0f2900c36c2d53ef05644ec
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d04b80114b9fe891f0f2900c36c2d53ef05644ec.nq.gz
│   └── repolex
│       └── d04b80114b9fe891f0f2900c36c2d53ef05644ec
│           └── chunk-001.nq.gz
├── blob
│   ├── 0019916c3ce3158f580e1c24d6f8f05f37df3d82.nq.gz
│   ├── 007302f1757c075037806129f272c7efb0a7145f.nq.gz
│   ├── 0086358db1eb971c0cfa8739c27518bbc18a5ff4.nq.gz
│   ├── 13e7fc9b50bd2f9581ced450fa205e6dc705ab22.nq.gz
│   ├── 15e18319a5ce27a9b543be5d981a11a8b965a12d.nq.gz
│   ├── 1eca32e7b4b33bc173e6b75ef5871dfd705b190e.nq.gz
│   ├── 2393dc5806ec2719c57655f35e289778bcae6d9a.nq.gz
│   ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
│   ├── 313e5f1a9b253190787eda27155913985355b7e3.nq.gz
│   ├── 37c2d0c3419d5b0cdeceb98222b677f373941fb2.nq.gz
│   ├── 3edeb4737bd1de31c0107c2f35924a7e6ce28563.nq.gz
│   ├── 40e27e36c0cac01d967492fb8a1c712176571520.nq.gz
│   ├── 42f136188a9da30b1eb451c6b4bb2970d4bd648a.nq.gz
│   ├── 4eca1919d3c8e0dbc567c18217a078500de8f6d1.nq.gz
│   ├── 5097068a8d375f5bf0d15693fb5b3615c972a801.nq.gz
│   ├── 51eb8c3d6f76d856dcc76ff23875dc2ae8fc954a.nq.gz
│   ├── 556adb03c90cc88b1aa998c335e82abf5969fddb.nq.gz
│   ├── 5885086384aa54f1bc0fd812bae3cfa4ea2d0df4.nq.gz
│   ├── 5cf42195b9d34356d6d83f20aaca80d887f3fc98.nq.gz
│   ├── 65830dc33c5479bf8edc8285fb599a520ab0d53e.nq.gz
│   ├── 68ad6c97d688acaf6563aa076c4ccda4426de871.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6d23bfd5b5081eb7f9366339c0c12d35a454a6fb.nq.gz
│   ├── 70148b385dd112a2999f4afed8af218543fce7c1.nq.gz
│   ├── 7025f489324810bcee78950f9224d4f96568b6fe.nq.gz
│   ├── 75b68b37065d66ff697ef8712f3add02faae32e7.nq.gz
│   ├── 78cd1ad00be44c7b8f2a9bd5507b922216648dcc.nq.gz
│   ├── 7bd7b41721f27efdfa0e2641a0768da2f1f80a73.nq.gz
│   ├── 7c4eb5ef8a9f9ca77c8ef48f1e888887100547aa.nq.gz
│   ├── 7f53bd8ae52aed77e28910a7d397657e3a1c1e49.nq.gz
│   ├── 813732312f84189a2d3421e7d2deeaa3dc8f168a.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 87ceda51c29f7eec11205536cbae49896e478ea2.nq.gz
│   ├── 8e0bb5ba6b3992d277ee384f3b1c3bb0bf4d8944.nq.gz
│   ├── 92913084d660d9ca3e9964dcc7d9733ae901d50b.nq.gz
│   ├── 93af4003378d6a070dcd5f3576b9be21c7b9a1f1.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 9a5375cdd744d783808a462b32ff1e8151faf97b.nq.gz
│   ├── 9b33e34be0c128ca0c225098cd3a2438ec8b50f5.nq.gz
│   ├── af165f3a8917bc76eb723ad349dca2fc4ba2fcb4.nq.gz
│   ├── b03eed503421faf91ccb28dcec7e61e54df12110.nq.gz
│   ├── b27f5f78e1d472c7a5cd73ed35e9e56c3d013b17.nq.gz
│   ├── b75e06da32e5e770700d6c3595c51109e01115e9.nq.gz
│   ├── c36ba3b0f012c8925c080e6b3a5aca51ee438dd5.nq.gz
│   ├── c90b4f5bb9e357b83fced899a7f9986bb9a67ff4.nq.gz
│   ├── ce06501e76f84e471e00266480ae81e79d3b0e48.nq.gz
│   ├── dad008df7fbbf5e9050c57ff28a6d9a8f4187bfb.nq.gz
│   ├── e1af9b0a1b9e83276e91e01317b2af8c0ebdf5ea.nq.gz
│   ├── e659c1760ec93b2f69e37e5246cd4cd0a24933c9.nq.gz
│   ├── e8df5af92f1cf5fd60171c7094fbf97db491c3eb.nq.gz
│   ├── e8ee1b0315e789d43c01c1ca3044bc95b1949bef.nq.gz
│   ├── f16f50d7ee654673777b1c6cd470ff6e5327d601.nq.gz
│   ├── f45885e99352b0ac4b7234dec53ad203fb266955.nq.gz
│   ├── f82deb9756a23cf085702edc58ab7d9d8a34f671.nq.gz
│   ├── f840237a71e5caf46bae4dee3bf3ecd6d1b4040d.nq.gz
│   ├── fafa2beddc332aa8d4c8d093d1efb342f1d02742.nq.gz
│   ├── fb2573f3ff778fa77c28e87b0fe63e095ccb40e5.nq.gz
│   └── fcbb09d5d1a0101f384b7ee89a5751f7981dbe89.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d04b80114b9fe891f0f2900c36c2d53ef05644ec.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 67 files
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

[block/overstory](https://github.com/block/overstory)

---
*Parsed on 2026-10-08 by [repolex](https://repolex.ai)*
