---
layout: default
title: "american-fiction Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# american-fiction sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | American Fiction |
| Collection key | `american-fiction` |
| imdb_id | [tt23561236](https://www.imdb.com/title/tt23561236/) |
| wikipedia_url | [American Fiction (film)](https://en.wikipedia.org/wiki/American_Fiction_(film)) |
| Sample dates | 2024-02-06-to-2024-05-20 |
| Sample days | 105 |
| BTIH count | 151 |
| Unique BTIH count | 129 |
| Downloaders total | 12,378,175 |
| Uploaders total | 1,562,179 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-08-28T16:48:38Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/american-fiction.xz`
- Hour directories: 2457
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (42 missing hours)
- Missing days: 1

### Sample archive discontinuities

- hourly gap: last `2024-03-31 01:00`, resumed `2024-03-31 03:00` — missing 1 hour(s)
- hourly gap: last `2024-04-20 06:00`, resumed `2024-04-22 00:00` — missing 41 hour(s)
- missing day: `2024-04-21`

## 3. Media objects file size histogram

![American Fiction collection size histogram](figures/american-fiction-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/american-fiction-downloads-by-week-american-fiction-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![american-fiction downloads by day](figures/american-fiction-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.90 | 19.46 | 21.80 | 49.48 | 0.95 | 0.58 |

### Cumulative network infrastructure

[![American Fiction cumulative map](figures/american-fiction-carto.png)](figures/american-fiction-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/american-fiction-data-ge-1080p.webp)](figures/american-fiction-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/american-fiction-data-lt-1080p.webp)](figures/american-fiction-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
