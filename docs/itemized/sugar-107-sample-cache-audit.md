---
layout: default
title: "sugar-107 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# sugar-107 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Sugar |
| Collection key | `sugar-107` |
| imdb_id | [tt16418808](https://www.imdb.com/title/tt16418808/) |
| wikipedia_url | [Sugar (2024 TV series)](https://en.wikipedia.org/wiki/Sugar_(2024_TV_series)) |
| Sample dates | 2024-05-10-to-2024-08-22 |
| Sample days | 105 |
| BTIH count | 210 |
| Unique BTIH count | 192 |
| Downloaders total | 14,701,207 |
| Uploaders total | 644,232 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T21:48:34Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/sugar-107.xz`
- Hour directories: 2513
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Sugar collection size histogram](figures/sugar-107-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/sugar-107-downloads-by-week-sugar-107-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![sugar-107 downloads by day](figures/sugar-107-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.18 | 18.39 | 24.37 | 52.44 | 1.12 | 0.71 |

### Cumulative network infrastructure

[![Sugar cumulative map](figures/sugar-107-carto.png)](figures/sugar-107-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/sugar-107-data-ge-1080p.webp)](figures/sugar-107-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/sugar-107-data-lt-1080p.webp)](figures/sugar-107-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
