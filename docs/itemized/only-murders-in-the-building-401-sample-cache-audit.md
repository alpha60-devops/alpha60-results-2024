---
layout: default
title: "only-murders-in-the-building-401 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# only-murders-in-the-building-401 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Only Murders In the Building |
| Collection key | `only-murders-in-the-building-401` |
| imdb_id | [tt11691774](https://www.imdb.com/title/tt11691774/) |
| wikipedia_url | [Only Murders in the Building](https://en.wikipedia.org/wiki/Only_Murders_in_the_Building) |
| Sample dates | 2024-08-27-to-2025-02-24 |
| Sample days | 182 |
| BTIH count | 208 |
| Unique BTIH count | 179 |
| Downloaders total | 24,399,610 |
| Uploaders total | 1,003,783 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T21:05:49Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/only-murders-in-the-building-401.xz`
- Hour directories: 4290
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 5 (61 missing hours)
- Missing days: 2

### Sample archive discontinuities

- hourly gap: last `2024-12-30 20:06`, resumed `2024-12-30 22:06` — missing 1 hour(s)
- hourly gap: last `2025-01-11 22:06`, resumed `2025-01-12 01:06` — missing 2 hour(s)
- hourly gap: last `2025-02-08 22:06`, resumed `2025-02-10 00:06` — missing 25 hour(s)
- hourly gap: last `2025-02-18 17:06`, resumed `2025-02-19 00:06` — missing 6 hour(s)
- hourly gap: last `2025-02-20 22:06`, resumed `2025-02-22 02:06` — missing 27 hour(s)
- missing day: `2025-02-09`
- missing day: `2025-02-21`

## 3. Media objects file size histogram

![Only Murders In the Building collection size histogram](figures/only-murders-in-the-building-401-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/only-murders-in-the-building-401-downloads-by-week-only-murders-in-the-building-401-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![only-murders-in-the-building-401 downloads by day](figures/only-murders-in-the-building-401-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.93 | 15.70 | 26.51 | 53.16 | 0.89 | 0.57 |

### Cumulative network infrastructure

[![Only Murders In the Building cumulative map](figures/only-murders-in-the-building-401-carto.png)](figures/only-murders-in-the-building-401-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/only-murders-in-the-building-401-data-ge-1080p.webp)](figures/only-murders-in-the-building-401-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/only-murders-in-the-building-401-data-lt-1080p.webp)](figures/only-murders-in-the-building-401-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
