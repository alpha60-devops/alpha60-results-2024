---
layout: default
title: "fargo-510 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# fargo-510 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Fargo |
| Collection key | `fargo-510` |
| imdb_id | [tt2802850](https://www.imdb.com/title/tt2802850/) |
| wikipedia_url | [Fargo (TV series)](https://en.wikipedia.org/wiki/Fargo_(TV_series)) |
| Sample dates | 2024-01-17-to-2024-03-26 |
| Sample days | 70 |
| BTIH count | 146 |
| Unique BTIH count | 132 |
| Downloaders total | 6,645,670 |
| Uploaders total | 623,653 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T17:40:47Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/fargo-510.xz`
- Hour directories: 1673
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Fargo collection size histogram](figures/fargo-510-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/fargo-510-downloads-by-week-fargo-510-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![fargo-510 downloads by day](figures/fargo-510-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.42 | 18.65 | 22.04 | 53.07 | 1.22 | 0.59 |

### Cumulative network infrastructure

[![Fargo cumulative map](figures/fargo-510-carto.png)](figures/fargo-510-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/fargo-510-data-ge-1080p.webp)](figures/fargo-510-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/fargo-510-data-lt-1080p.webp)](figures/fargo-510-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
