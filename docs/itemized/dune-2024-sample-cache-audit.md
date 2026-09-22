---
layout: default
title: "dune-2024 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dune-2024 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dune 2024: Part Two |
| Collection key | `dune-2024` |
| imdb_id | [tt15239678](https://www.imdb.com/title/tt15239678/) |
| wikipedia_url | [Dune: Part Two](https://en.wikipedia.org/wiki/Dune:_Part_Two) |
| Sample dates | 2024-04-06-to-2024-10-04 |
| Sample days | 182 |
| BTIH count | 704 |
| Unique BTIH count | 626 |
| Downloaders total | 97,510,251 |
| Uploaders total | 11,624,985 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T17:26:58Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/dune-2024.xz`
- Hour directories: 4354
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Dune 2024: Part Two collection size histogram](figures/dune-2024-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dune-2024-downloads-by-week-dune-2024-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dune-2024 downloads by day](figures/dune-2024-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/dune-2024-cumulative-aggregate.geojson.gz" data-map-title="Dune 2024: Part Two — dune-2024" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Dune 2024: Part Two (dune-2024) cumulative data map in new window" title="Opens interactive map for Dune 2024: Part Two (dune-2024) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.28 | 16.47 | 25.87 | 51.30 | 1.04 | 0.67 |

### Network infrastructure

[![Dune 2024: Part Two cumulative map](figures/dune-2024-carto.png)](figures/dune-2024-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/dune-2024-data-ge-1080p.webp)](figures/dune-2024-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/dune-2024-data-lt-1080p.webp)](figures/dune-2024-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
