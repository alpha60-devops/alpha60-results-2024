---
layout: default
title: "blink-twice Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# blink-twice sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Blink Twice |
| Collection key | `blink-twice` |
| imdb_id | [tt14858658](https://www.imdb.com/title/tt14858658/) |
| wikipedia_url | [Blink Twice](https://en.wikipedia.org/wiki/Blink_Twice) |
| Sample dates | 2024-09-18-to-2025-01-08 |
| Sample days | 113 |
| BTIH count | 184 |
| Unique BTIH count | 168 |
| Downloaders total | 17,512,731 |
| Uploaders total | 2,600,784 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T17:17:09Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/blink-twice.xz`
- Hour directories: 2712
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Blink Twice collection size histogram](figures/blink-twice-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/blink-twice-downloads-by-week-blink-twice-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![blink-twice downloads by day](figures/blink-twice-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/blink-twice-cumulative-aggregate.geojson.gz" data-map-title="Blink Twice — blink-twice" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Blink Twice (blink-twice) cumulative data map in new window" title="Opens interactive map for Blink Twice (blink-twice) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.39 | 15.76 | 23.31 | 51.82 | 1.17 | 0.53 |

### Network infrastructure

[![Blink Twice cumulative map](figures/blink-twice-carto.png)](figures/blink-twice-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/blink-twice-data-ge-1080p.webp)](figures/blink-twice-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/blink-twice-data-lt-1080p.webp)](figures/blink-twice-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
