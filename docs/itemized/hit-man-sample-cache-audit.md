---
layout: default
title: "hit-man Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# hit-man sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Hit Man |
| Collection key | `hit-man` |
| imdb_id | [tt20215968](https://www.imdb.com/title/tt20215968/) |
| wikipedia_url | [Hit Man (2023 film)](https://en.wikipedia.org/wiki/Hit_Man_(2023_film)) |
| Sample dates | 2024-06-06-to-2024-09-19 |
| Sample days | 106 |
| BTIH count | 204 |
| Unique BTIH count | 174 |
| Downloaders total | 19,306,820 |
| Uploaders total | 2,921,956 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T22:23:24Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/hit-man.xz`
- Hour directories: 2536
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Hit Man collection size histogram](figures/hit-man-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/hit-man-downloads-by-week-hit-man-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![hit-man downloads by day](figures/hit-man-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/hit-man-cumulative-aggregate.geojson.gz" data-map-title="Hit Man — hit-man" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Hit Man (hit-man) cumulative data map in new window" title="Opens interactive map for Hit Man (hit-man) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.89 | 16.29 | 25.86 | 47.19 | 1.13 | 0.62 |

### Network infrastructure

[![Hit Man cumulative map](figures/hit-man-carto.png)](figures/hit-man-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/hit-man-data-ge-1080p.webp)](figures/hit-man-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/hit-man-data-lt-1080p.webp)](figures/hit-man-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
