---
layout: default
title: "house-of-the-dragon-207 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# house-of-the-dragon-207 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | House of the Dragon |
| Collection key | `house-of-the-dragon-207` |
| imdb_id | [tt11198330](https://www.imdb.com/title/tt11198330/) |
| wikipedia_url | [House of the Dragon](https://en.wikipedia.org/wiki/House_of_the_Dragon) |
| Sample dates | 2024-07-29-to-2025-01-26 |
| Sample days | 182 |
| BTIH count | 456 |
| Unique BTIH count | 421 |
| Downloaders total | 57,593,119 |
| Uploaders total | 5,714,209 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T18:47:30Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/house-of-the-dragon-207.xz`
- Hour directories: 4334
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (31 missing hours)
- Missing days: 1

### Sample archive discontinuities

- hourly gap: last `2024-10-19 23:03`, resumed `2024-10-21 00:03` — missing 24 hour(s)
- hourly gap: last `2024-11-29 10:03`, resumed `2024-11-29 18:03` — missing 7 hour(s)
- missing day: `2024-10-20`

## 3. File sizes histogram *median[lowest, highest]*

![House of the Dragon collection size histogram](figures/house-of-the-dragon-207-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/house-of-the-dragon-207-downloads-by-week-house-of-the-dragon-207-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![house-of-the-dragon-207 downloads by day](figures/house-of-the-dragon-207-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/house-of-the-dragon-207-cumulative-aggregate.geojson.gz" data-map-title="House of the Dragon — house-of-the-dragon-207" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open House of the Dragon (house-of-the-dragon-207) cumulative data map in new window" title="Opens interactive map for House of the Dragon (house-of-the-dragon-207) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.84 | 15.52 | 26.08 | 52.19 | 1.19 | 0.55 |

### Network infrastructure

[![House of the Dragon cumulative map](figures/house-of-the-dragon-207-carto.png)](figures/house-of-the-dragon-207-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/house-of-the-dragon-207-data-ge-1080p.webp)](figures/house-of-the-dragon-207-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/house-of-the-dragon-207-data-lt-1080p.webp)](figures/house-of-the-dragon-207-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
