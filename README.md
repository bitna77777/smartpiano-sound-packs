# Smart Piano sound packs

This repository hosts signed, immutable optional sound packs for Smart Piano.
The bundled Salamander Mobile Grand remains the application's offline default.

## Published catalog

- `catalog-v1.json`: current downloadable pack metadata
- `catalog-v1.json.sig`: detached ECDSA P-256/SHA-256 signature, Base64 encoded
- `catalog-public-key-base64.txt`: public verification key embedded by the app
- `SOUND_PACK_LICENSES.md`: source provenance and processing disclosure

Release assets are immutable. A changed pack receives a new semantic version,
file name, SHA-256, and release tag. Large assets are uploaded to GitHub
Releases, not committed to Git or Git LFS.

## First release

Tag: `piano-packs-v1.0.0`

- `piano-grand-splendid-mobile-alt-1.0.0.spack`
- `piano-grand-splendid-mobile-alt-1.0.0.spack.sha256`

The audio is derived from the public-domain Splendid Grand Piano source pinned
in Smart Piano's source manifest. The pack contains 88 true-stereo OGG samples
(22 pitches x 4 recorded dynamics).

## Kawai Upright HQ release

Tag: `piano-packs-v1.1.0`

- `piano-kawai-freepats-stereo2-hq-1.0.0.spack`
- `piano-kawai-freepats-stereo2-hq-1.0.0.spack.sha256`

This CC0-derived upgrade contains 66 true-stereo OGG samples with two recorded
velocity layers. The bundled Kawai bank remains the offline fallback.
