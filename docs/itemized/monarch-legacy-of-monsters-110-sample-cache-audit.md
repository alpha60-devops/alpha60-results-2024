---
layout: default
title: "monarch-legacy-of-monsters-110 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# monarch-legacy-of-monsters-110 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Monarch: Legacy of Monsters |
| Collection key | `monarch-legacy-of-monsters-110` |
| imdb_id | [tt17220216](https://www.imdb.com/title/tt17220216/) |
| wikipedia_url | [Monarch: Legacy of Monsters](https://en.wikipedia.org/wiki/Monarch:_Legacy_of_Monsters) |
| Sample dates | 2024-01-12-to-2024-06-06 |
| Sample days | 147 |
| BTIH count | 204 |
| Unique BTIH count | 186 |
| Downloaders total | 17,401,369 |
| Uploaders total | 767,563 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T20:58:42Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/monarch-legacy-of-monsters-110.xz`
- Hour directories: 3480
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 3 (41 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-03-31 01:06`, resumed `2024-03-31 03:06` — missing 1 hour(s)
- hourly gap: last `2024-04-20 06:06`, resumed `2024-04-21 00:06` — missing 17 hour(s)
- hourly gap: last `2024-04-21 00:06`, resumed `2024-04-22 00:06` — missing 23 hour(s)

## 3. Media objects file size histogram

![Monarch: Legacy of Monsters collection size histogram](figures/monarch-legacy-of-monsters-110-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/monarch-legacy-of-monsters-110-downloads-by-week-monarch-legacy-of-monsters-110-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![monarch-legacy-of-monsters-110 downloads by day](figures/monarch-legacy-of-monsters-110-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.50 | 19.07 | 23.73 | 51.94 | 0.96 | 0.65 |

### Cumulative network infrastructure

[![Monarch: Legacy of Monsters cumulative map](figures/monarch-legacy-of-monsters-110-carto.png)](figures/monarch-legacy-of-monsters-110-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/monarch-legacy-of-monsters-110-data-ge-1080p.webp)](figures/monarch-legacy-of-monsters-110-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/monarch-legacy-of-monsters-110-data-lt-1080p.webp)](figures/monarch-legacy-of-monsters-110-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
