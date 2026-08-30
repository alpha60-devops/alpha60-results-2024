---
layout: default
title: "what-if-2021-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# what-if-2021-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | What if? |
| Collection key | `what-if-2021-03` |
| imdb_id | [tt10168312](https://www.imdb.com/title/tt10168312/) |
| wikipedia_url | [What If...? (TV series)](https://en.wikipedia.org/wiki/What_If...%3F_(TV_series)) |
| Sample dates | 2024-12-22-to-2025-06-21 |
| Sample days | 182 |
| BTIH count | 455 |
| Unique BTIH count | 435 |
| Downloaders total | 58,886,486 |
| Uploaders total | 2,369,461 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T21:57:35Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/what-if-2021-03.xz`
- Hour directories: 4241
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 4 (104 missing hours)
- Missing days: 4

### Sample archive discontinuities

- hourly gap: last `2025-01-10 22:06`, resumed `2025-01-12 01:06` — missing 26 hour(s)
- hourly gap: last `2025-03-14 22:06`, resumed `2025-03-15 03:06` — missing 4 hour(s)
- hourly gap: last `2025-03-30 01:06`, resumed `2025-03-30 03:06` — missing 1 hour(s)
- hourly gap: last `2025-06-11 22:06`, resumed `2025-06-15 00:06` — missing 73 hour(s)
- missing day: `2025-01-11`
- missing day: `2025-06-12`
- missing day: `2025-06-13`
- missing day: `2025-06-14`

## 3. Media objects file size histogram

![What if? collection size histogram](figures/what-if-2021-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/what-if-2021-03-downloads-by-week-what-if-2021-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![what-if-2021-03 downloads by day](figures/what-if-2021-03-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.20 | 15.34 | 28.52 | 52.75 | 0.83 | 0.55 |

### Cumulative network infrastructure

[![What if? cumulative map](figures/what-if-2021-03-carto.png)](figures/what-if-2021-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/what-if-2021-03-data-ge-1080p.webp)](figures/what-if-2021-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/what-if-2021-03-data-lt-1080p.webp)](figures/what-if-2021-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
