---
layout: default
title: "avatar-the-last-airbender-2024-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# avatar-the-last-airbender-2024-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Avatar: The Last Airbender |
| Collection key | `avatar-the-last-airbender-2024-01` |
| imdb_id | [tt9018736](https://www.imdb.com/title/tt9018736/) |
| wikipedia_url | [Avatar: The Last Airbender (2024 TV series)](https://en.wikipedia.org/wiki/Avatar:_The_Last_Airbender_(2024_TV_series)) |
| Sample dates | 2024-02-24-to-2024-08-23 |
| Sample days | 182 |
| BTIH count | 480 |
| Unique BTIH count | 427 |
| Downloaders total | 52,149,524 |
| Uploaders total | 3,278,199 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T17:04:04Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/avatar-the-last-airbender-2024-01.xz`
- Hour directories: 4357
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 3 (7 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-03-31 01:00`, resumed `2024-03-31 03:00` — missing 1 hour(s)
- hourly gap: last `2024-07-06 19:00`, resumed `2024-07-06 21:00` — missing 1 hour(s)
- hourly gap: last `2024-07-16 23:00`, resumed `2024-07-17 05:00` — missing 5 hour(s)

## 3. Media objects file size histogram

![Avatar: The Last Airbender collection size histogram](figures/avatar-the-last-airbender-2024-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/avatar-the-last-airbender-2024-01-downloads-by-week-avatar-the-last-airbender-2024-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![avatar-the-last-airbender-2024-01 downloads by day](figures/avatar-the-last-airbender-2024-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.83 | 18.79 | 24.74 | 51.20 | 0.89 | 0.65 |

### Cumulative network infrastructure

[![Avatar: The Last Airbender cumulative map](figures/avatar-the-last-airbender-2024-01-carto.png)](figures/avatar-the-last-airbender-2024-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/avatar-the-last-airbender-2024-01-data-ge-1080p.webp)](figures/avatar-the-last-airbender-2024-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/avatar-the-last-airbender-2024-01-data-lt-1080p.webp)](figures/avatar-the-last-airbender-2024-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
