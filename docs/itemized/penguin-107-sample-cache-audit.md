---
layout: default
title: "penguin-107 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# penguin-107 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Penguin |
| Collection key | `penguin-107` |
| imdb_id | [tt15435876](https://www.imdb.com/title/tt15435876/) |
| wikipedia_url | [The Penguin (TV series)](https://en.wikipedia.org/wiki/The_Penguin_(TV_series)) |
| Sample dates | 2024-11-04-to-2025-05-03 |
| Sample days | 181 |
| BTIH count | 393 |
| Unique BTIH count | 359 |
| Downloaders total | 56,197,557 |
| Uploaders total | 3,695,540 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T21:12:29Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/penguin-107.xz`
- Hour directories: 4316
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (8 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-12-07 22:00`, resumed `2024-12-08 06:00` — missing 7 hour(s)
- hourly gap: last `2025-03-30 01:00`, resumed `2025-03-30 03:00` — missing 1 hour(s)

## 3. Media objects file size histogram

![The Penguin collection size histogram](figures/penguin-107-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/penguin-107-downloads-by-week-penguin-107-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![penguin-107 downloads by day](figures/penguin-107-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.86 | 15.29 | 26.94 | 53.18 | 0.92 | 0.53 |

### Cumulative network infrastructure

[![The Penguin cumulative map](figures/penguin-107-carto.png)](figures/penguin-107-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/penguin-107-data-ge-1080p.webp)](figures/penguin-107-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/penguin-107-data-lt-1080p.webp)](figures/penguin-107-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
