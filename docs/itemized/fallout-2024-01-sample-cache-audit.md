---
layout: default
title: "fallout-2024-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# fallout-2024-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Fallout |
| Collection key | `fallout-2024-01` |
| imdb_id | [tt12637874](https://www.imdb.com/title/tt12637874/) |
| wikipedia_url | [Fallout (American TV series)](https://en.wikipedia.org/wiki/Fallout_(American_TV_series)) |
| Sample dates | 2024-04-11-to-2024-10-09 |
| Sample days | 182 |
| BTIH count | 720 |
| Unique BTIH count | 648 |
| Downloaders total | 81,673,824 |
| Uploaders total | 9,987,696 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T17:37:50Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/fallout-2024-01.xz`
- Hour directories: 4360
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Fallout collection size histogram](figures/fallout-2024-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/fallout-2024-01-downloads-by-week-fallout-2024-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![fallout-2024-01 downloads by day](figures/fallout-2024-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/fallout-2024-01-cumulative-aggregate.geojson.gz" data-map-title="Fallout — fallout-2024-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Fallout (fallout-2024-01) cumulative data map in new window" title="Opens interactive map for Fallout (fallout-2024-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.45 | 18.49 | 23.84 | 52.47 | 1.42 | 0.68 |

### Network infrastructure

[![Fallout cumulative map](figures/fallout-2024-01-carto.png)](figures/fallout-2024-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/fallout-2024-01-data-ge-1080p.webp)](figures/fallout-2024-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/fallout-2024-01-data-lt-1080p.webp)](figures/fallout-2024-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
