# Repolex Knowledge Graph of spacetelescope/tweakwcs

RDF knowledge graph data for [spacetelescope/tweakwcs](https://github.com/spacetelescope/tweakwcs), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/tweakwcs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d87f57c9682468bf616bd0eddf60432d70f028c9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d87f57c9682468bf616bd0eddf60432d70f028c9
│           └── chunk-001.nq.gz
├── blob
│   ├── 05f599b203a8827d9343dc6efec26af8be371e77.nq.gz
│   ├── 09929fe4369c3fb7055194ada0edabde29216d80.nq.gz
│   ├── 0a13b679af9396ce59948c5bc991cef971403e1f.nq.gz
│   ├── 11479c2c9c4f02cb758263d2f37834fa78daa2b3.nq.gz
│   ├── 12f08b0fd4babce70e7839c8830c40af2e3861c9.nq.gz
│   ├── 13c2731af82b3916b693787d8c0e015024981da3.nq.gz
│   ├── 13e0c04a22b11663bbaeee9739e00e14e1a105d1.nq.gz
│   ├── 150becf9fad87af129bb0197e777e9fd9b60410e.nq.gz
│   ├── 25facfab77fc54b8e21f0eafb72b08e8e4af076e.nq.gz
│   ├── 29c04def2ae911b679aea56c26ec4f02b7e1875a.nq.gz
│   ├── 2c5419798a52606177014c7a68dfa3e720f7f59a.nq.gz
│   ├── 2dec9cda7b9323d1dffd55fa502897acd4e1835e.nq.gz
│   ├── 305a7c22d399e5613fac8fc195d10658b196e84f.nq.gz
│   ├── 321972715c350738443a5be03ad629fb765d1c9f.nq.gz
│   ├── 3258e9f306cf2bdacf1b23de29ce67b7866d03b3.nq.gz
│   ├── 33b3390512b8fe820b9774ed7775c4f1d9514769.nq.gz
│   ├── 3d62636ed7f7fa1ec7af70a41ff297dde4522992.nq.gz
│   ├── 497365e46caee697a791c416e3b8ed0ae0791eb3.nq.gz
│   ├── 4974de34aa73e01756ca2f0e54ea5042f7942d5c.nq.gz
│   ├── 4b8739bf56058c1c71cc48afdb4fd408d8cec782.nq.gz
│   ├── 4f4273df29e4aec0e8970b7ae29898abb827b596.nq.gz
│   ├── 5c1bbc4cfb087b42124f42481d8436fad219dee0.nq.gz
│   ├── 5d62a1e42cd6704fbba9cd1d17205870ec2ee34e.nq.gz
│   ├── 5e728597309c0d8d510456e82ab84e010a67959c.nq.gz
│   ├── 62cb32312cb5e6e64392c18606c91600a64c3cf9.nq.gz
│   ├── 6de7b596e64167da4672de664183cda07ddcf483.nq.gz
│   ├── 77f756956aefe1a8cc8cfac8e6d6f34bed73d118.nq.gz
│   ├── 82d8b488c5fd15b8002925789dca17c278de8843.nq.gz
│   ├── 86cb7413f728bbfa8f3ccc8e6d3ab4e9e9dbf35b.nq.gz
│   ├── 8f1ed3887da96d054ab25eec5d9bfcdd09f52a57.nq.gz
│   ├── 8f7f50f138125688bb92d760a935b30efc35eb53.nq.gz
│   ├── 8fc1f5af25952b123b2bf8d2124bc88289556a70.nq.gz
│   ├── 92e101e38637d79014d599404783fc8352c1d4eb.nq.gz
│   ├── 9c5f8ce6c6b7550f1dd93a28857c66cce6851bcd.nq.gz
│   ├── a608fb4ee6f1fed2f0e7cce1300c5b58c8311d11.nq.gz
│   ├── a690bacdc2231068bda3c5b30b475a53a7fee094.nq.gz
│   ├── a946125e33d1989c5b165bd2508c3ff46a7107d5.nq.gz
│   ├── aa37994186f9732c80814900d387a9f737eb0e9d.nq.gz
│   ├── ab94ed2ed6ad9a16e9945793221996dd86d1d4ed.nq.gz
│   ├── b4b5f89a48206ba8348280f1ca167dce857eab85.nq.gz
│   ├── b5beb5fe19e18ba4bfa35d4b6be218fe2c928083.nq.gz
│   ├── b701ed3aebdbd1b364a4df4cb135af1f28b61913.nq.gz
│   ├── bb9100574896e3f96c5be3756548c2342cc45af3.nq.gz
│   ├── bdf2a941e9de7ab468f5ab5c50434e6d1e74b150.nq.gz
│   ├── c1da1ec2399d09639fcaa2762857a654900fcbb7.nq.gz
│   ├── cc20e9d1a4681d2b566ff0c7a0795d10ac31b53c.nq.gz
│   ├── d010fbaae3ae240c95a99aeac9014d91b5eeda96.nq.gz
│   ├── d5716f28e5149d506c6d1a93c9ab4ab171082752.nq.gz
│   ├── d5eb2816408e7b7e443286b9917e2e53efaf858a.nq.gz
│   ├── d727aadffdb8692ae4fa6e8c3f93a383436cf89b.nq.gz
│   ├── da257d8908e7fe3b68d5e5769dbdef6a5b70ef67.nq.gz
│   ├── dac81b64c9cc9dcf81a7734ccff8c0001a009a8a.nq.gz
│   ├── dbf51d036aba7061e938a1e4b5e58891bb52d4a9.nq.gz
│   ├── dcb55e7119792ebc0b971544e511f408507872ee.nq.gz
│   ├── ddb926c2be11e5e9b4b4622dadb151cfb7e2bb8e.nq.gz
│   ├── e4a422031c745fe3b5e89edcf68b98a355a0334b.nq.gz
│   ├── e542275f478f358c0edd1f0bbec5ff85476461e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6dcfa8231e11e711c455f6c1cb0e5c80ba21118.nq.gz
│   ├── e87a018a3954d3125b54279208fa54ae20cd28e5.nq.gz
│   ├── ebfc6acccab0d10ba8aed9bbd07cb38b0305c113.nq.gz
│   ├── ec6510e4a813340328f2678ac894ecd4ba160a0c.nq.gz
│   ├── ef624699f75cfa379605c2469ee30c1f3e2bcb97.nq.gz
│   ├── f12c54a4f0bf436831841aaa08b02783d5bbce34.nq.gz
│   ├── f3d9f60fb15fd095ec8334153e244ad8d5d53c4c.nq.gz
│   ├── f5e53001fb51aa5251a8cc6083bed73300ae7b61.nq.gz
│   └── fa05534e056d510e16542e79f472e39f2186483e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d87f57c9682468bf616bd0eddf60432d70f028c9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[spacetelescope/tweakwcs](https://github.com/spacetelescope/tweakwcs)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
