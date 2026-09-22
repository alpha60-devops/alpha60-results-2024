---
layout: default
title: "interior-chinatown-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# interior-chinatown-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Interior Chinatown |
| Collection key | `interior-chinatown-01` |
| imdb_id | [tt13354972](https://www.imdb.com/title/tt13354972/) |
| wikipedia_url | [Interior Chinatown (TV series)](https://en.wikipedia.org/wiki/Interior_Chinatown_(TV_series)) |
| Sample dates | 2024-11-19-to-2025-05-19 |
| Sample days | 182 |
| BTIH count | 510 |
| Unique BTIH count | 502 |
| Downloaders total | 53,991,475 |
| Uploaders total | 901,803 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T20:35:34Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/interior-chinatown-01.xz`
- Hour directories: 4351
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2025-03-30 01:00`, resumed `2025-03-30 03:00` — missing 1 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![Interior Chinatown collection size histogram](figures/interior-chinatown-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/interior-chinatown-01-downloads-by-week-interior-chinatown-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![interior-chinatown-01 downloads by day](figures/interior-chinatown-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/interior-chinatown-01-cumulative-aggregate.geojson.gz" data-map-title="Interior Chinatown — interior-chinatown-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Interior Chinatown (interior-chinatown-01) cumulative data map in new window" title="Opens interactive map for Interior Chinatown (interior-chinatown-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.85 | 15.02 | 27.78 | 54.07 | 0.72 | 0.54 |

### Network infrastructure

[![Interior Chinatown cumulative map](figures/interior-chinatown-01-carto.png)](figures/interior-chinatown-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/interior-chinatown-01-data-ge-1080p.webp)](figures/interior-chinatown-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/interior-chinatown-01-data-lt-1080p.webp)](figures/interior-chinatown-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
