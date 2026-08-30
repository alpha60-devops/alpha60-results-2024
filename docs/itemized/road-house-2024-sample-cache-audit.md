---
layout: default
title: "road-house-2024 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# road-house-2024 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Road House 2024 |
| Collection key | `road-house-2024` |
| imdb_id | [tt3359350](https://www.imdb.com/title/tt3359350/) |
| wikipedia_url | [Road House (2024 film)](https://en.wikipedia.org/wiki/Road_House_(2024_film)) |
| Sample dates | 2024-03-21-to-2024-09-18 |
| Sample days | 182 |
| BTIH count | 322 |
| Unique BTIH count | 264 |
| Downloaders total | 51,053,418 |
| Uploaders total | 6,047,114 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T21:27:57Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/road-house-2024.xz`
- Hour directories: 4298
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 5 (51 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-03-31 01:03`, resumed `2024-03-31 03:03` — missing 1 hour(s)
- hourly gap: last `2024-04-20 06:03`, resumed `2024-04-21 00:03` — missing 17 hour(s)
- hourly gap: last `2024-04-21 00:03`, resumed `2024-04-21 23:37` — missing 22 hour(s)
- hourly gap: last `2024-05-22 22:03`, resumed `2024-05-23 00:03` — missing 1 hour(s)
- hourly gap: last `2024-07-15 12:03`, resumed `2024-07-15 23:20` — missing 10 hour(s)

## 3. Media objects file size histogram

![Road House 2024 collection size histogram](figures/road-house-2024-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/road-house-2024-downloads-by-week-road-house-2024-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![road-house-2024 downloads by day](figures/road-house-2024-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.66 | 16.34 | 24.46 | 51.83 | 1.02 | 0.65 |

### Cumulative network infrastructure

[![Road House 2024 cumulative map](figures/road-house-2024-carto.png)](figures/road-house-2024-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/road-house-2024-data-ge-1080p.webp)](figures/road-house-2024-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/road-house-2024-data-lt-1080p.webp)](figures/road-house-2024-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
