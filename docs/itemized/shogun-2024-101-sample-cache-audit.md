---
layout: default
title: "shogun-2024-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# shogun-2024-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Shogun 2024 |
| Collection key | `shogun-2024-101` |
| imdb_id | [tt2788316](https://www.imdb.com/title/tt2788316/) |
| wikipedia_url | [Shōgun (2024 TV series)](https://en.wikipedia.org/wiki/Sh%C5%8Dgun_(2024_TV_series)) |
| Sample dates | 2024-02-28-to-2024-06-11 |
| Sample days | 105 |
| BTIH count | 326 |
| Unique BTIH count | 297 |
| Downloaders total | 26,600,880 |
| Uploaders total | 4,342,033 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T21:36:46Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/shogun-2024-101.xz`
- Hour directories: 2518
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-03-31 01:03`, resumed `2024-03-31 03:03` — missing 1 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![Shogun 2024 collection size histogram](figures/shogun-2024-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/shogun-2024-101-downloads-by-week-shogun-2024-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![shogun-2024-101 downloads by day](figures/shogun-2024-101-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/shogun-2024-101-cumulative-aggregate.geojson.gz" data-map-title="Shogun 2024 — shogun-2024-101" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Shogun 2024 (shogun-2024-101) cumulative data map in new window" title="Opens interactive map for Shogun 2024 (shogun-2024-101) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.35 | 18.06 | 23.03 | 49.61 | 1.52 | 0.60 |

### Network infrastructure

[![Shogun 2024 cumulative map](figures/shogun-2024-101-carto.png)](figures/shogun-2024-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/shogun-2024-101-data-ge-1080p.webp)](figures/shogun-2024-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/shogun-2024-101-data-lt-1080p.webp)](figures/shogun-2024-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
