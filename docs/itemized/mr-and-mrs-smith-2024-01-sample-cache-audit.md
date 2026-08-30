---
layout: default
title: "mr-and-mrs-smith-2024-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mr-and-mrs-smith-2024-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Mr. & Mrs. Smith |
| Collection key | `mr-and-mrs-smith-2024-01` |
| imdb_id | [tt14044212](https://www.imdb.com/title/tt14044212/) |
| wikipedia_url | [Mr. & Mrs. Smith (2024 TV series)](https://en.wikipedia.org/wiki/Mr._%26_Mrs._Smith_(2024_TV_series)) |
| Sample dates | 2024-02-02-to-2024-05-30 |
| Sample days | 119 |
| BTIH count | 298 |
| Unique BTIH count | 274 |
| Downloaders total | 19,314,432 |
| Uploaders total | 1,297,099 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T21:04:50Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/mr-and-mrs-smith-2024-01.xz`
- Hour directories: 2838
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (10 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-02-16 19:03`, resumed `2024-02-17 05:51` — missing 9 hour(s)
- hourly gap: last `2024-03-31 01:03`, resumed `2024-03-31 03:03` — missing 1 hour(s)

## 3. Media objects file size histogram

![Mr. & Mrs. Smith collection size histogram](figures/mr-and-mrs-smith-2024-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mr-and-mrs-smith-2024-01-downloads-by-week-mr-and-mrs-smith-2024-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mr-and-mrs-smith-2024-01 downloads by day](figures/mr-and-mrs-smith-2024-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.94 | 19.19 | 22.86 | 51.01 | 1.05 | 0.61 |

### Cumulative network infrastructure

[![Mr. & Mrs. Smith cumulative map](figures/mr-and-mrs-smith-2024-01-carto.png)](figures/mr-and-mrs-smith-2024-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/mr-and-mrs-smith-2024-01-data-ge-1080p.webp)](figures/mr-and-mrs-smith-2024-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/mr-and-mrs-smith-2024-01-data-lt-1080p.webp)](figures/mr-and-mrs-smith-2024-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
