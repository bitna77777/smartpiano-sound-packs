# Smart Piano sound packs

This repository hosts signed, immutable optional sound packs for Smart Piano.
The bundled Salamander Mobile Grand remains the application's offline default.

## Published catalogs

- `catalog-v2.json`: current downloadable pack metadata for app version 3+
- `catalog-v2.json.sig`: detached ECDSA P-256/SHA-256 signature, Base64 encoded
- `catalog-v2-public-key-base64.txt`: v2 public verification key embedded by app version 3+
- `catalog-v1.json`, `.sig`, and `catalog-public-key-base64.txt`: immutable legacy
  catalog/key retained for already-installed app versions
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

## Complete instrument expansion release

Tag: `instrument-packs-v1.2.0`

Twenty-one audited upgrade packs cover the remaining piano, string, brass, wind,
mallet, accordion, harp, and nylon-guitar expansions. Together with Kawai Upright HQ,
all 22 current upgrade expansions are listed in the signed v2 catalog.

## Drum kit expansion release

Tag: `drum-packs-v1.3.0`

- `drums-virtuosity-mid-stereo3rr2-hq-1.0.0.spack`
- `drums-virtuosity-mid-stereo3rr2-hq-1.0.0.spack.sha256`

This CC0-derived upgrade contains 48 true-stereo OGG samples: eight core
acoustic pieces with three recorded dynamics and two alternates each. It
requires app version code 5 or newer. The bundled Studio Drum Kit remains the
offline default.

## Drum kit balance update

Tag: `drum-packs-v1.3.1`

- `drums-virtuosity-mid-stereo3rr2-hq-1.0.1.spack`
- `drums-virtuosity-mid-stereo3rr2-hq-1.0.1.spack.sha256`

Version 1.0.1 remasters the previously under-level hi-hat and ride layers while retaining
the same source recordings and kit structure.
