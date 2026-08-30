---
layout: default
title: "fantasmas-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# fantasmas-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Fantasmas |
| Collection key | `fantasmas-01` |
| imdb_id | [tt18182112](https://www.imdb.com/title/tt18182112/) |
| wikipedia_url | [Fantasmas (TV series)](https://en.wikipedia.org/wiki/Fantasmas_(TV_series)) |
| Sample dates | 2024-06-08-to-2024-07-26 |
| Sample days | 49 |
| BTIH count | 180 |
| Unique BTIH count | 152 |
| Downloaders total | 5,910,193 |
| Uploaders total | 49,724 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T17:38:21Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/fantasmas-01.xz`
- Hour directories: 1830
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (11 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-07-15 12:06`, resumed `2024-07-16 00:06` — missing 11 hour(s)

## 3. Media objects file size histogram

![Fantasmas collection size histogram](figures/fantasmas-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/fantasmas-01-downloads-by-week-fantasmas-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![fantasmas-01 downloads by day](figures/fantasmas-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.00 | 18.86 | 26.07 | 50.04 | 1.05 | 0.68 |

### Cumulative network infrastructure

[![Fantasmas cumulative map](figures/fantasmas-01-carto.png)](figures/fantasmas-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/fantasmas-01-data-ge-1080p.webp)](figures/fantasmas-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/fantasmas-01-data-lt-1080p.webp)](figures/fantasmas-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
