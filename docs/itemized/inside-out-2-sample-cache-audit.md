---
layout: default
title: "inside-out-2 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# inside-out-2 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Inside Out 2 |
| Collection key | `inside-out-2` |
| imdb_id | [tt22022452](https://www.imdb.com/title/tt22022452/) |
| wikipedia_url | [Inside Out 2](https://en.wikipedia.org/wiki/Inside_Out_2) |
| Sample dates | 2024-08-19-to-2025-02-27 |
| Sample days | 193 |
| BTIH count | 482 |
| Unique BTIH count | 428 |
| Downloaders total | 72,020,769 |
| Uploaders total | 8,040,802 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T20:35:34Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/inside-out-2.xz`
- Hour directories: 4613
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Inside Out 2 collection size histogram](figures/inside-out-2-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/inside-out-2-downloads-by-week-inside-out-2-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![inside-out-2 downloads by day](figures/inside-out-2-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/inside-out-2-cumulative-aggregate.geojson.gz" data-map-title="Inside Out 2 — inside-out-2" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Inside Out 2 (inside-out-2) cumulative data map in new window" title="Opens interactive map for Inside Out 2 (inside-out-2) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.84 | 14.86 | 26.49 | 53.97 | 0.85 | 0.59 |

### Network infrastructure

[![Inside Out 2 cumulative map](figures/inside-out-2-carto.png)](figures/inside-out-2-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/inside-out-2-data-ge-1080p.webp)](figures/inside-out-2-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/inside-out-2-data-lt-1080p.webp)](figures/inside-out-2-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
