---
layout: default
title: "rings-of-power-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# rings-of-power-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Rings of Power |
| Collection key | `rings-of-power-201` |
| imdb_id | [tt7631058](https://www.imdb.com/title/tt7631058/) |
| wikipedia_url | [The Lord of the Rings: The Rings of Power](https://en.wikipedia.org/wiki/The_Lord_of_the_Rings:_The_Rings_of_Power) |
| Sample dates | 2024-08-29-to-2025-02-26 |
| Sample days | 182 |
| BTIH count | 339 |
| Unique BTIH count | 329 |
| Downloaders total | 51,462,049 |
| Uploaders total | 4,041,923 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-08-28T21:22:31Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/rings-of-power-201.xz`
- Hour directories: 4302
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 3 (49 missing hours)
- Missing days: 1

### Sample archive discontinuities

- hourly gap: last `2024-12-12 22:00`, resumed `2024-12-13 00:00` — missing 1 hour(s)
- hourly gap: last `2024-12-28 22:00`, resumed `2024-12-30 22:00` — missing 47 hour(s)
- hourly gap: last `2025-01-19 22:00`, resumed `2025-01-20 00:00` — missing 1 hour(s)
- missing day: `2024-12-29`

## 3. File sizes histogram *median[lowest, highest]*

![Rings of Power collection size histogram](figures/rings-of-power-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/rings-of-power-201-downloads-by-week-rings-of-power-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![rings-of-power-201 downloads by day](figures/rings-of-power-201-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2024/refs/heads/main/data/geojson.cumulative/rings-of-power-201-cumulative-aggregate.geojson.gz" data-map-title="Rings of Power — rings-of-power-201" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Rings of Power (rings-of-power-201) cumulative data map in new window" title="Opens interactive map for Rings of Power (rings-of-power-201) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.59 | 15.39 | 26.45 | 52.60 | 1.08 | 0.54 |

### Network infrastructure

[![Rings of Power cumulative map](figures/rings-of-power-201-carto.png)](figures/rings-of-power-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/rings-of-power-201-data-ge-1080p.webp)](figures/rings-of-power-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/rings-of-power-201-data-lt-1080p.webp)](figures/rings-of-power-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
