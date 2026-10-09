# Repolex Knowledge Graph of modelcontextprotocol/experimental-ext-variants

RDF knowledge graph data for [modelcontextprotocol/experimental-ext-variants](https://github.com/modelcontextprotocol/experimental-ext-variants), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/experimental-ext-variants
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cfc05d6f5eb8829f9896d44a6d47360bd15c3b5c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cfc05d6f5eb8829f9896d44a6d47360bd15c3b5c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ab8a2aa0408d023a800c684fb4bea6d49d4ba2e.nq.gz
│   ├── 0e5b6d160801a383cb40b43f3f63600364b14a32.nq.gz
│   ├── 0f41f0e81d8c9df7f0c0aba8a50db202ca494229.nq.gz
│   ├── 12d5667a51ec9f4478d6bd45debef9cc75dc6fa7.nq.gz
│   ├── 17c097ce4f36f7419ae450c23af8550d1dd78f08.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2865dab92fd7cb1f130e0610aff9f543e3f68a03.nq.gz
│   ├── 29360887d82de9775d4a23ea53b7d68f40a1477d.nq.gz
│   ├── 2a38b2ba08c0b3b3f9940126c45118f7c8074748.nq.gz
│   ├── 2edeafb09db0093bae6ff060e2dcd2166f5c9387.nq.gz
│   ├── 37f75858c34f04e6be843cafa6e38e91fea2c6b0.nq.gz
│   ├── 3a7b758269b86c6764376b6aa21471d8eacf801c.nq.gz
│   ├── 4fdd95c7349f50e4138d1e7cc651130f6e4f4411.nq.gz
│   ├── 540f963810346767ba1368104cf11560352dab8e.nq.gz
│   ├── 5840587910c5d7e1ca5431e510da0071545a9c67.nq.gz
│   ├── 5f23a08483ded6c878c96ea72137177341b9444d.nq.gz
│   ├── 615788d063552f97c3d0cd22eff0bcb55c5041ff.nq.gz
│   ├── 63d22f4d181310bfc0365f8dc32618a473126d18.nq.gz
│   ├── 667596f27e7a25ebdd00849a08936d271beb0339.nq.gz
│   ├── 66a1f464a19ce835e6a614ab69ee3939841a1141.nq.gz
│   ├── 677768c96249c8f28015cf4c8a6c0cad881bf784.nq.gz
│   ├── 67b0c42b103aa4c2fa6b9f1ea1996882485c8288.nq.gz
│   ├── 6a7718fe70b1044a3d3bb273d73783b9d247088e.nq.gz
│   ├── 6deab61a15d05afbe05afc6cff993dc38340d175.nq.gz
│   ├── 7be5eee2ea87b0810e557fcd264524689b707786.nq.gz
│   ├── 8277baaf672ec0aefb12b6b9bc6c196b2a808c08.nq.gz
│   ├── 86aa1887d90189b3e1d50a65953079d7c14c797f.nq.gz
│   ├── 87c3dc483b83a22f75b005efef8eab5f7b43b12e.nq.gz
│   ├── 95b019869856fa3de96c4d14e3c42d4e2c33f3f9.nq.gz
│   ├── 96e7d6f288d32d4399dbe8b6873ebf6ba1e5bbfa.nq.gz
│   ├── 9cbaaeaf099cd94610fc3a82cec2b2f7c5c709a6.nq.gz
│   ├── a1fb6bd1366714e389c762fb91867d3baf5f36c6.nq.gz
│   ├── b51fb72dbbd8fbeecf8d09e2819739797671d020.nq.gz
│   ├── b548351ff9e3366d9cc32a0c28c192bd2fe8392e.nq.gz
│   ├── b8e0a57155ae973c27412d1e7be6efe60a35a2a3.nq.gz
│   ├── bc22099b65088b7520083fcd26256311dc7e2983.nq.gz
│   ├── bfa5448fdd9d50837581e5b9203fb1a35fb63ece.nq.gz
│   ├── c0df32e6a2e0043fdfb8986fef194e12d9294a4d.nq.gz
│   ├── c7d5111ee411812992b2dd152ce967c692b86fdc.nq.gz
│   ├── c9445651f7d7059108b17a6653883256b3fb4dbd.nq.gz
│   ├── cd392ed54d1b4123eba34f6e48c294caedd67f7f.nq.gz
│   ├── d2f0449e29f601c0c88076cb0c7aa11b47373c13.nq.gz
│   ├── d4de6ecc66f20b20440d0b7ca1fe000a16b828fe.nq.gz
│   ├── db42afcc84ad23bafd5c4bce2e4a80153b437ca6.nq.gz
│   ├── df4f03dcd616eb801a4e2ec5230cc2a39c8ca951.nq.gz
│   ├── e5c82d461e522dac0d5c05880835495588e203ee.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea62aa8eb2fe2acb0cf8a485df7b619f4441e8f5.nq.gz
│   ├── eab7d8aced028ee0f3c183333cca26a62a378928.nq.gz
│   ├── fba0aa63d11e13de8c638a2fd0593e20c0735b73.nq.gz
│   └── fedaf6613a647013eb4abd1378c8cfe05c3b02bc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cfc05d6f5eb8829f9896d44a6d47360bd15c3b5c.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 58 files
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

[modelcontextprotocol/experimental-ext-variants](https://github.com/modelcontextprotocol/experimental-ext-variants)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
