# Sound-pack licenses

## Splendid Mobile Alternate 1.0.0

- Recorded instrument: Steinway grand piano
- Source project: `sfzinstruments/SplendidGrandPiano`
- Pinned source revision: `1c595d827b7fd7f0be3134aaed0f90b3662a09cf`
- Source credit: AKAI; SFZ reconstruction by kinwie
- Source license: Public Domain
- Smart Piano changes: pitch selection, onset trim, register-aware tail length,
  stereo preservation, sample-rate selection, four-layer loudness matching,
  tail fade, and OGG Vorbis encoding for mobile playback

The same provenance is embedded in `licenses.json` inside the `.spack` file.
The catalog signature authenticates the exact pack hash; it does not alter the
source audio's public-domain status.

## FreePats Kawai Upright HQ 1.0.0

- Recorded instrument: Kawai upright piano
- Source project: `freepats/upright-piano-kw`
- Pinned source revision: `570f6c60ed2eff67accad3b85d5b452e57a3ad28`
- Creators: Gonzalo and Roberto; processing by Roberto
- Source license: CC0-1.0
- Smart Piano changes: preserve 44.1 kHz/24-bit stereo and both recorded
  velocities, apply uniform -1.7 dB headroom, encode OGG Vorbis q6, and cap
  loop-authored long sources at 5.25 seconds with a 0.25-second tail fade

The same provenance and processing disclosure are embedded in the pack's
`licenses.json`.

## Instrument expansion packs v1.2.0

The 21 expansion packs use these pinned openly licensed sources:

- TinySOL v5.0 (`zenodo-3685331-v5.0`), CC-BY-4.0: bowed strings, brass,
  woodwinds, and accordion
- Versilian Community Sample Library
  (`c1ea7bcc3c7309650ab0da9d15c9cd1fbc4a4c7e`), CC0-1.0: Yamaha upright,
  Steinway grand, FM piano, harp, marimba, and vibraphone
- FreePats Spanish Classical Guitar
  (`6f4eb1b092acc88f5448cea1a0001bd07b971af8`), CC0-1.0: nylon guitar

Each `.spack` embeds the exact recorded instrument, creator, source URL,
source revision, mobile processing disclosure, license URL, and per-sample checksums.

## Drum kit expansion pack v1.3.0

Virtuosity Acoustic Drums HQ uses this pinned openly licensed source:

- Virtuosity Drums (`9f04cf9a734527edfbb0a4eee1f674e45bbf71bc`), CC0-1.0:
  mid-position recordings of the eight core kit pieces

Mobile processing: select three recorded velocities with two alternates per
piece, normalize each piece to a common loudness target, apply the bundled
phone-speaker kick presence treatment, cap sample length at 4.8 seconds with a
0.3-second tail fade, and encode OGG Vorbis q5.

The same provenance and processing disclosure are embedded in the pack's
`licenses.json`.
