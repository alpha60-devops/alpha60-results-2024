---
layout: default
title: "kingdom-of-the-planet-of-the-apes Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# kingdom-of-the-planet-of-the-apes sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Kingdom of the Planet of the Apes |
| Collection key | `kingdom-of-the-planet-of-the-apes` |
| imdb_id | [tt11389872](https://www.imdb.com/title/tt11389872/) |
| wikipedia_url | [Kingdom of the Planet of the Apes](https://en.wikipedia.org/wiki/Kingdom_of_the_Planet_of_the_Apes) |
| Sample dates | 2024-07-09-to-2025-01-06 |
| Sample days | 182 |
| BTIH count | 409 |
| Unique BTIH count | 376 |
| Downloaders total | 57,526,359 |
| Uploaders total | 8,765,637 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T20:35:34Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/kingdom-of-the-planet-of-the-apes.xz`
- Hour directories: 4363
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-10-27 22:00`, resumed `2024-10-28 00:00` — missing 1 hour(s)

## 3. Media objects file size histogram

![The Kingdom of the Planet of the Apes collection size histogram](figures/kingdom-of-the-planet-of-the-apes-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/kingdom-of-the-planet-of-the-apes-downloads-by-week-kingdom-of-the-planet-of-the-apes-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![kingdom-of-the-planet-of-the-apes downloads by day](figures/kingdom-of-the-planet-of-the-apes-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.93 | 14.60 | 28.59 | 49.33 | 0.99 | 0.60 |

### Cumulative network infrastructure

[![The Kingdom of the Planet of the Apes cumulative map](figures/kingdom-of-the-planet-of-the-apes-carto.png)](figures/kingdom-of-the-planet-of-the-apes-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/kingdom-of-the-planet-of-the-apes-data-ge-1080p.webp)](figures/kingdom-of-the-planet-of-the-apes-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/kingdom-of-the-planet-of-the-apes-data-lt-1080p.webp)](figures/kingdom-of-the-planet-of-the-apes-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
