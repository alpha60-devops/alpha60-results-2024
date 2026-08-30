---
layout: default
title: "laid-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# laid-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Laid |
| Collection key | `laid-01` |
| imdb_id | [tt21114548](https://www.imdb.com/title/tt21114548/) |
| wikipedia_url | [Laid (American TV series)](https://en.wikipedia.org/wiki/Laid_(American_TV_series)) |
| Sample dates | 2024-12-19-to-2025-04-09 |
| Sample days | 112 |
| BTIH count | 278 |
| Unique BTIH count | 255 |
| Downloaders total | 16,843,064 |
| Uploaders total | 289,940 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-21T05:55:26Z
- Sample directory: `/home/bkoz/src/alpha60-samples/laid-01`
- Hour directories: 2666
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2025-03-30 01:06`, resumed `2025-03-30 03:06` — missing 1 hour(s)

## 3. Media objects file size histogram

![Laid collection size histogram](figures/laid-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/laid-01-downloads-by-week-laid-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![laid-01 downloads by day](figures/laid-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.95 | 14.75 | 27.49 | 53.70 | 0.71 | 0.52 |

### Cumulative network infrastructure

[![Laid cumulative map](figures/laid-01-carto.png)](figures/laid-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/laid-01-data-ge-1080p.webp)](figures/laid-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/laid-01-data-lt-1080p.webp)](figures/laid-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
