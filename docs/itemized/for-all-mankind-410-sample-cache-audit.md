---
layout: default
title: "for-all-mankind-410 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# for-all-mankind-410 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | For All Mankind |
| Collection key | `for-all-mankind-410` |
| imdb_id | [tt7772588](https://www.imdb.com/title/tt7772588/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-01-12-to-2024-04-25 |
| Sample days | 105 (2024–2024) |
| BTIH count | 127 |
| Unique BTIH count | 117 |
| Downloaders total | 7,588,744 |
| Uploaders total | 284,052 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T17:48:33Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/for-all-mankind-410.xz`
- Hour directories: 2489
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (13 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-02-16 19:03`, resumed `2024-02-17 09:00` — missing 12 hour(s)
- hourly gap: last `2024-03-31 01:00`, resumed `2024-03-31 03:00` — missing 1 hour(s)

## 3. Collection size histogram

![For All Mankind collection size histogram](figures/for-all-mankind-410-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![for-all-mankind-410 downloads by week](figures/for-all-mankind-410-downloads-by-week-for-all-mankind-410-week.svg)

### Downloads by day, Saturday and Sunday in gray

![for-all-mankind-410 downloads by day](figures/for-all-mankind-410-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.95 | 20.24 | 21.97 | 52.36 | 1.01 | 0.54 |

### Cumulative network infrastructure

[![For All Mankind cumulative map](figures/for-all-mankind-410-carto.png)](figures/for-all-mankind-410-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/for-all-mankind-410-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/for-all-mankind-410-data-lt-1080p.webp)
