---
layout: default
title: "diplomat-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# diplomat-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Diplomat |
| Collection key | `diplomat-02` |
| imdb_id | [tt17491088](https://www.imdb.com/title/tt17491088/) |
| wikipedia_url | [The Diplomat (American TV series)](https://en.wikipedia.org/wiki/The_Diplomat_(American_TV_series)) |
| Sample dates | 2024-10-31-to-2025-02-12 |
| Sample days | 105 |
| BTIH count | 161 |
| Unique BTIH count | 151 |
| Downloaders total | 6,432,247 |
| Uploaders total | 422,525 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T17:26:10Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/diplomat-02.xz`
- Hour directories: 2497
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (7 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-12-07 22:03`, resumed `2024-12-08 06:03` — missing 7 hour(s)

## 3. Media objects file size histogram

![The Diplomat collection size histogram](figures/diplomat-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/diplomat-02-downloads-by-week-diplomat-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![diplomat-02 downloads by day](figures/diplomat-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.71 | 15.77 | 24.81 | 51.26 | 0.98 | 0.47 |

### Cumulative network infrastructure

[![The Diplomat cumulative map](figures/diplomat-02-carto.png)](figures/diplomat-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/diplomat-02-data-ge-1080p.webp)](figures/diplomat-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/diplomat-02-data-lt-1080p.webp)](figures/diplomat-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
