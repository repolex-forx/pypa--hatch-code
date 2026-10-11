# Repolex Knowledge Graph of pypa/hatch-code

RDF knowledge graph data for [pypa/hatch-code](https://github.com/pypa/hatch-code), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/hatch-code
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cebff56f5d91e48ce709f7ba01caf26ccc2341c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cebff56f5d91e48ce709f7ba01caf26ccc2341c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01fbb9cbd7b4731998b5713235117dd60a5acb71.nq.gz
│   ├── 02536100d4906dfee0526dad53db048542d4781c.nq.gz
│   ├── 050fb177ae633a060cf68eebc443b7c8a941d770.nq.gz
│   ├── 08fb8434b2cdcdcfdf2fff672ad9f9064b4098b2.nq.gz
│   ├── 09ec3ee9d57db9e0ba970414ef4f2ef4784bfad9.nq.gz
│   ├── 0edff1b2632be2c373e7854cac809cea437af90a.nq.gz
│   ├── 1241ebdfb643418f897f9538832805e113e3b0f6.nq.gz
│   ├── 1bbb445b5e851a6aa0dac9567e5e4c8eebe074b0.nq.gz
│   ├── 1d0857836a5c6095074589b01027dad847a2a6da.nq.gz
│   ├── 1e2ba423307eaec2bce0bd94b563944cfd0ed9a0.nq.gz
│   ├── 1ee40f0bb2854700593ef32f3fdd0fd9d873b92c.nq.gz
│   ├── 28a2e7ff43cde9aeb7c6c2bc451f8c6031a92084.nq.gz
│   ├── 3aa17a50b476843d961e94cb6806b42ada871c05.nq.gz
│   ├── 3de1c72fef59944187ceacbce9b3b94786622b4d.nq.gz
│   ├── 4002653d3adf01905acf0e585764664fd56fd801.nq.gz
│   ├── 496acdb2ae812f69b9ef60a610f505fbab35aca0.nq.gz
│   ├── 4a00abf73db284a12367bda289a4ccf5fba5d087.nq.gz
│   ├── 4d63ee23aad68d9f15088529108dce4a25fcf1da.nq.gz
│   ├── 5028542310ba07f9d3180953e7bf6de081e6989a.nq.gz
│   ├── 52ce106c33c659fb5e55b8fee6cb754d431a59e3.nq.gz
│   ├── 5f1df712b3f75a7ccad146a5af1780df1626a673.nq.gz
│   ├── 6059faac8a806be35c65bab8711fa23acc6da445.nq.gz
│   ├── 62e2b69dcf4b323c3c9eb5496a5415bed9fa78c1.nq.gz
│   ├── 68fbc108a04a4d6efc5b23cff005bc3e39c0d6b9.nq.gz
│   ├── 6a5517ff797f68aec53c1df41b9c5bee6b3bd368.nq.gz
│   ├── 731a6254002980f0ed6d965671d5110b5a883bd2.nq.gz
│   ├── 77f78fee56901ccc22eb2557b179468d325e8227.nq.gz
│   ├── 795954a0b18daf92c1c9d0838527750b46e241ac.nq.gz
│   ├── 796952092a2b1bce79d02052458590f767693e26.nq.gz
│   ├── 7a52eff940418f19736f49decab32999cca5c007.nq.gz
│   ├── 8101f9bee47ad7b9f072d3fb714d3f5eb9aad212.nq.gz
│   ├── 831612680fc12f4c4d170272078f4e6198bad856.nq.gz
│   ├── 88eca2a3a9bc70b321cbf7b339b408b6d161ddc3.nq.gz
│   ├── 89a4864c7183c1c5092d23eb22c3b0280bab912d.nq.gz
│   ├── 950dcd185c05ffe14f5b2891275f57457e646bb6.nq.gz
│   ├── a5087d8103f84cabaad347846d13d3ebd47c5d30.nq.gz
│   ├── a562bf05de006f64c43516a5dee6fd78609a818f.nq.gz
│   ├── b3f1d0d57f93821dc8ffa7d7f9d5e8367a328b41.nq.gz
│   ├── b575f132d53b983100e2593893d9f047e27637ea.nq.gz
│   ├── b857056adc608d8856be4a84e9a5d2a00a8316e1.nq.gz
│   ├── bab035d9b36b20e796b2d12cc3327f1e9c082e6e.nq.gz
│   ├── bac3723662d968a0d976ff918db5423c103f691c.nq.gz
│   ├── c91206443f48947a2f9bc0957dc7795aad90df88.nq.gz
│   ├── cf427850569b738a74d53a431731df4067484fcd.nq.gz
│   ├── d2f591e0548676d4b665e9c352a9e84a1eb49dd9.nq.gz
│   ├── dfd71c4c6fef91097db666fd5a4df0891670befb.nq.gz
│   ├── e3003a4e0ff89e6c263ccca639f251dd3b5be542.nq.gz
│   ├── e3f0a0b5bc1f3943821865d556fbac0b7d833427.nq.gz
│   ├── efd69bf64c9ce402a536615de963db86c96995f1.nq.gz
│   ├── f469ef7e4ba670c4adcb8a30d05277b5f08b5bec.nq.gz
│   └── fa2fb38c9a573f02197108e5bdddbd27776fd44f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cebff56f5d91e48ce709f7ba01caf26ccc2341c2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[pypa/hatch-code](https://github.com/pypa/hatch-code)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
