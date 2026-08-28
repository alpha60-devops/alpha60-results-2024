---
layout: default
title: "acolyte-107 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# acolyte-107 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Acolyte |
| Collection key | `acolyte-107` |
| imdb_id | [tt12262202](https://www.imdb.com/title/tt12262202/) |
| wikipedia_url | [Star Wars: The Acolyte](https://en.wikipedia.org/wiki/Star_Wars%3A_The_Acolyte) |
| Sample dates | 2026-05-04-to-2026-07-26 |
| Sample days | 84 (2026–2026) |
| BTIH count | 376 |
| Unique BTIH count | 346 |
| Downloaders total | 31,714,901 |
| Uploaders total | 243,711 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T16:15:53Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/acolyte-107.xz/2024`
- Hour directories: 4315
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (47 missing hours)
- Missing days: 1

### Sample archive discontinuities

- hourly gap: last `2024-12-28 22:03`, resumed `2024-12-30 22:03` — missing 47 hour(s)
- missing day: `2024-12-29`

## 3. Collection size histogram

![The Acolyte collection size histogram](figures/acolyte-107-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![acolyte-107 downloads by week](figures/acolyte-107-downloads-by-week-acolyte-107-week.svg)

### Downloads by day, Saturday and Sunday in gray

![acolyte-107 downloads by day](figures/acolyte-107-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.08 | 15.37 | 37.31 | 43.28 | 1.05 | 0.81 |

### Cumulative network infrastructure

[![The Acolyte cumulative map](figures/acolyte-107-carto.png)](figures/acolyte-107-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/acolyte-107-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/acolyte-107-data-lt-1080p.webp)
