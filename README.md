# o_voxel_vb_ap

Fully MIT-licensed fork of [o-voxel](https://github.com/microsoft/TRELLIS.2/tree/main/o-voxel) from Microsoft's TRELLIS.2.

Based on [VisualBruno's fork](https://github.com/visualbruno/TRELLIS.2) which adds tiled dual-grid decoding.

## Changes from upstream

- Removed `postprocess.py` and `rasterize.py` (nvdiffrast dependency)
- Removed all non-o-voxel code (renderers, app, pipelines)
- No nvdiffrast or nvdiffrec dependencies

## License

MIT License (Microsoft Corporation). See [LICENSE](LICENSE).
