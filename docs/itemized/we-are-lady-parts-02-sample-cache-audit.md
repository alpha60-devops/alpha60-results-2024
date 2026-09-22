---
layout: default
title: "we-are-lady-parts-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# we-are-lady-parts-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | We Are Lady Parts |
| Collection key | `we-are-lady-parts-02` |
| imdb_id | [tt10846104](https://www.imdb.com/title/tt10846104/) |
| wikipedia_url | [We Are Lady Parts](https://en.wikipedia.org/wiki/We_Are_Lady_Parts) |
| Sample dates | 2024-05-30-to-2024-08-07 |
| Sample days | 70 |
| BTIH count | 78 |
| Unique BTIH count | 68 |
| Downloaders total | 2,047,288 |
| Uploaders total | 77,034 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T21:57:24Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/we-are-lady-parts-02.xz`
- Hour directories: 1637
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (24 missing hours)
- Missing days: 1

### Sample archive discontinuities

- hourly gap: last `2024-07-18 23:03`, resumed `2024-07-20 00:03` — missing 24 hour(s)
- missing day: `2024-07-19`

## 3. File sizes histogram *median[lowest, highest]*

![We Are Lady Parts collection size histogram](figures/we-are-lady-parts-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/we-are-lady-parts-02-downloads-by-week-we-are-lady-parts-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![we-are-lady-parts-02 downloads by day](figures/we-are-lady-parts-02-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/we-are-lady-parts-02-cumulative-aggregate.geojson.gz" data-map-title="We Are Lady Parts — we-are-lady-parts-02" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open We Are Lady Parts (we-are-lady-parts-02) cumulative data map in new window" title="Opens interactive map for We Are Lady Parts (we-are-lady-parts-02) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.03 | 18.85 | 22.68 | 48.24 | 1.24 | 0.63 |

### Network infrastructure

[![We Are Lady Parts cumulative map](figures/we-are-lady-parts-02-carto.png)](figures/we-are-lady-parts-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/we-are-lady-parts-02-data-ge-1080p.webp)](figures/we-are-lady-parts-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/we-are-lady-parts-02-data-lt-1080p.webp)](figures/we-are-lady-parts-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
