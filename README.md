# Repolex Knowledge Graph of geopandas/dask-geopandas

RDF knowledge graph data for [geopandas/dask-geopandas](https://github.com/geopandas/dask-geopandas), parsed by [repolex](https://repolex.ai).

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
rlex download geopandas/dask-geopandas
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3e2143495a83e4cf5073d0436b10906ddbe5fcff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3e2143495a83e4cf5073d0436b10906ddbe5fcff
│           └── chunk-001.nq.gz
├── blob
│   ├── 04b7019a924dbad739fbb617efc1bdf7879652ae.nq.gz
│   ├── 12149a641c3ef74d1687c09c34e6b5e87d856d1b.nq.gz
│   ├── 12d32e427fc8a8878ff7619525ef857d3ece0b93.nq.gz
│   ├── 13c0c82784e0fcb65503e71abcad08f6b3b62dc9.nq.gz
│   ├── 1558af0d1dfc13ca1e41cb0397af997ecb6e2b98.nq.gz
│   ├── 1c6901ad3c5bc53a218bb57d8c9f722855640ed2.nq.gz
│   ├── 1ca08b5ed7daf1ac343f31d8271d6f49c77c49cd.nq.gz
│   ├── 1e3753e63fb6d5a204a7a350b65ed69aa7ab66cd.nq.gz
│   ├── 1fb314ca9959bcc421776d9a1365c7253cb9e46e.nq.gz
│   ├── 22286769b1f235de4cb87506f2ae1e8d1f1d6a8e.nq.gz
│   ├── 25e21faf0cc99fcd739edeb3e164d4c98e46e90f.nq.gz
│   ├── 271ed8c9928f36560846de766109477fbc95a0b1.nq.gz
│   ├── 273693061355e45e719e34f42f3ad0281cda1881.nq.gz
│   ├── 275512f80d174331444d331846760d792b97b45c.nq.gz
│   ├── 2a06f5b63f7783cf1b5dec1a8cb438e925524c77.nq.gz
│   ├── 2ace9bfa3a418ab4a522c6738a70ba8a7ba8c7b3.nq.gz
│   ├── 2b8a8142ab9c87eb8cb9139121d05d085083e37b.nq.gz
│   ├── 2c3a76c3f49177648e11072e11470b5c3d247ca6.nq.gz
│   ├── 2c644fd7c7cef7a4131cf26a771c552aa5467661.nq.gz
│   ├── 2e3e58e1d04b3bbbf59bbbb132d92b3d0280a82b.nq.gz
│   ├── 304a8500d9c237d9fa79954db586541485592a72.nq.gz
│   ├── 359a5b952d49f3592571e2af081510656029298e.nq.gz
│   ├── 37b1fa6938908f990ff0985b69a82319abd54020.nq.gz
│   ├── 3bedcb66bc340a0cd6399227f46a04e0c6d234dc.nq.gz
│   ├── 3fc541e0e1cccef396551d6937eb3d2533874e5d.nq.gz
│   ├── 4b5c6f2b002cd94d5e6c01fdea498037f8a3d4be.nq.gz
│   ├── 4bcc2809717a399502bc45fc1d97256b069968b0.nq.gz
│   ├── 4e25a1a5e7d70b55a8ecd170f5ebb634aa0f6003.nq.gz
│   ├── 4f67b538ea0ea5ebb943672fa1f1562074484588.nq.gz
│   ├── 5296a606b7a69ad5ffcb850c19fca83f78863dbc.nq.gz
│   ├── 5a3440b253e0c28764a3466fa970daeeadfbcb74.nq.gz
│   ├── 5d99c490bed83d51ae0b3d7ec862dfd85c2d0305.nq.gz
│   ├── 5ec53ae72aff9c14ae9f78714e0e6d0aff49355f.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 63cd9cf733113f1e2b041d3abcc021fcb1b49ca3.nq.gz
│   ├── 646f91f91c3c0c3165e7afc0522b3c7ff599cd8f.nq.gz
│   ├── 7186ab1dd05f45d2c07abc28b8a1b4fad1734bdb.nq.gz
│   ├── 71cd22d2c56c6ea9b1b9661f8688b5b78e7530aa.nq.gz
│   ├── 73d1197de7c5b23fb304c3a23a0eadc9973d2805.nq.gz
│   ├── 756aa80002e52ac190c107b9b81f07068be439c8.nq.gz
│   ├── 759aa2c6d39e96e9d5263348691994400e4f56e7.nq.gz
│   ├── 7ad06bdad95185e396c8ea754a8753f122f0439f.nq.gz
│   ├── 7bffa422f822a145bf6c40cb1ce538a0aad1cb67.nq.gz
│   ├── 7c8989aaf5e35a49f903e71acd8c04b81f8eecb5.nq.gz
│   ├── 85ba513fdf03554db169c0ca7d4818dd9bad1502.nq.gz
│   ├── 86b3ee428bab66a54483af6797713b940c8aef24.nq.gz
│   ├── 88014eb56579d282e714c920d16f8cb34eb907d5.nq.gz
│   ├── 899eee11bdce70ffc58d11449e1ed9facd6cef72.nq.gz
│   ├── 8d671bccb61501ec312fb798d9892e602a40ef38.nq.gz
│   ├── 8ff99882c1e72dbf22c40fafd09433f929f34eef.nq.gz
│   ├── 97a3e9d2565896b0374d82816dd2a251257324b2.nq.gz
│   ├── 9949bde6a16e33c6007637dddfdf846f55cad6a5.nq.gz
│   ├── 9a84f42063e33972e6af18df82160cd321ee91bc.nq.gz
│   ├── 9de08cd9cf5bf64dd58973f429f11207caf664d7.nq.gz
│   ├── a225a44a84764f4e70b84bf8bd48dd2510594eb5.nq.gz
│   ├── a7bcefa0aee55b435bef7544f452eb72c2f136e8.nq.gz
│   ├── a8d4087ce34ceb297bcb7453b88fa3a8f54360b2.nq.gz
│   ├── ab605ce147bd6bb832c76b496e290e2a6fa2f9e4.nq.gz
│   ├── ac27a84869a2cb5b416c12fc1fcf57aa6f626958.nq.gz
│   ├── ac3403440ebdd9e0d773ec6921670aabe20ea410.nq.gz
│   ├── ac903b589ec1c1f325748dc2d8ea5e873e4b5121.nq.gz
│   ├── ad4e5d265dd1f0f4ca958bd987223fd107e8a9a6.nq.gz
│   ├── af60c1b77c4d19498280b9069adc361d8d6bc477.nq.gz
│   ├── b45d72c527b2d4363c291eaecb0ad475bf2ce3da.nq.gz
│   ├── b52f15fa68552847038a71c426e2316ff1009ff0.nq.gz
│   ├── b5489f6aa2660bdb6222625b23b1367a584b4519.nq.gz
│   ├── b69e53d81ecfa89807c4ae6baa95fb94e3441f1b.nq.gz
│   ├── bd57efbe2d12ac67d0368ffb423d1be012ed85fb.nq.gz
│   ├── be96d32911c754be9e31c1e0a0fa36f32a77ca25.nq.gz
│   ├── c2853d90f5b9a49e876a4b57f5af408c27c1f1f5.nq.gz
│   ├── c48dbded30b3801eadef68ae689187f9e0d27f43.nq.gz
│   ├── c69bed22303712934ace663e074225db0eef84a7.nq.gz
│   ├── cd89cb9758e84c59b13399a25325d366af87e4f8.nq.gz
│   ├── cde0b6a66c670e4e536c08648ea40de6aea7d1f6.nq.gz
│   ├── ce83da7357081a00644ea7b47094c93893fd39ff.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d2bbcdf824f9a828491c86f7ef201b41eab452a7.nq.gz
│   ├── d430d257e8283856e716f22c76d2d0f30cf531d2.nq.gz
│   ├── d7f7e271be4fbedf851d6483c02f702eb0f256d0.nq.gz
│   ├── da2553a5d348ece9c9b8043a70ab9522caa14971.nq.gz
│   ├── dbd1100c821f46420ae7adc8cd2462818bf9741f.nq.gz
│   ├── dbf435e12b7efa5a7b15e4d5e0830e734d267e55.nq.gz
│   ├── dcce6fd0629e442c05049a64f4e97ca6d5253f43.nq.gz
│   ├── e240ae829bb824e9ae3c56ad24c9a2161337580c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f33736b1e74725e807e66f8725a67abb6c8ace27.nq.gz
│   ├── f45cbadf0074d8b7b2669559a93bc50bb95f82d4.nq.gz
│   ├── f555bb4701a0c19d9ceb945ad416b1f8a76c7392.nq.gz
│   ├── faa1653db8a1f0bf9412abc549540f6b4ea18512.nq.gz
│   └── fcde7bbba42ca89bbc148a346536e689d05b34c5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3e2143495a83e4cf5073d0436b10906ddbe5fcff.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[geopandas/dask-geopandas](https://github.com/geopandas/dask-geopandas)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
