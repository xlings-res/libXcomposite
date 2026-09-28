# libXcomposite

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libXcomposite.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/xorg-libxcomposite-0.4.6-hb9d3cd8_2.conda | `753f73e990c33366a91fd42cc17a3d19bb9444b9ca5ff983605fa9e953baf57f` | conda-forge xorg-libxcomposite 0.4.6 hb9d3cd8_2 (MIT) |

## Command

```
.agents/tools/repack/repack.py \
    --name libXcomposite \
    --version 0.4.6 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/xorg-libxcomposite-0.4.6-hb9d3cd8_2.conda#753f73e990c33366a91fd42cc17a3d19bb9444b9ca5ff983605fa9e953baf57f \
    --require lib/libXcomposite.so.1
```

