# USA TV Next Guide — Stremio addon (Native EPG)

Companion to [yowmamasita/usa-tv-next](https://github.com/yowmamasita/usa-tv-next):
same channels and streams, plus a programme guide so Stremio shows its
native TV guide — what's on now and next, in real time.

## Install

In Stremio, open this link (or paste the manifest URL into Addons):

    stremio://raw.githubusercontent.com/JPDimples/usa-tv-next-guide/main/manifest.json

Manifest: `https://raw.githubusercontent.com/JPDimples/usa-tv-next-guide/main/manifest.json`

## What's inside

- 104 watchable channels (the addon lists 169; 65 have no streams
  and are left out), across 10 genres.
- 101 channels carry real programme schedules (11122 programmes
  over the next 4 days); Fox (broadcast), HBO Family and HGTV have
  no schedule in any free source checked, so they play but show no guide rows.
- National ABC/CBS/NBC/Fox rows are network feeds; local affiliate schedules
  vary by market.
- Streams are the same community-harvested links as usa-tv-next (video first,
  audio-only last). Fox Business's only streams are audio-only.

## Data sources (free)

- Channels/streams: usa-tv-next catalog (GitHub raw).
- Programmes: epgshare01.online US2 + US Sports, i.mjh.nz Samsung TV Plus US
  + Pluto TV US (XMLTV), matched by channel name with hand-checked overrides.

## Rebuild

Regenerated daily by `scripts/build_addon.py` (see the guide repo). Generated
2026-11-11 04:34 UTC; data covers through
2026-11-15 04:34 UTC.
