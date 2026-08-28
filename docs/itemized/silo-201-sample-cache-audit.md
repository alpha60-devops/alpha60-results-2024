---
layout: default
title: "silo-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# silo-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Silo |
| Collection key | `silo-201` |
| imdb_id | [tt14688458](https://www.imdb.com/title/tt14688458/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-11-15-to-2025-05-15 |
| Sample days | 182 (2024–2025) |
| BTIH count | 306 |
| Unique BTIH count | 281 |
| Downloaders total | 48,092,507 |
| Uploaders total | 3,418,016 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T21:40:57Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/silo-201.xz`
- Hour directories: 4361
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2025-03-30 01:06`, resumed `2025-03-30 03:06` — missing 1 hour(s)

## 3. Collection size histogram

![Silo collection size histogram](figures/silo-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![silo-201 downloads by week](figures/silo-201-downloads-by-week-silo-201-week.svg)

### Downloads by day, Saturday and Sunday in gray

![silo-201 downloads by day](figures/silo-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.02 | 16.16 | 25.97 | 53.21 | 1.10 | 0.52 |

### Cumulative network infrastructure

[![Silo cumulative map](figures/silo-201-carto.png)](figures/silo-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/silo-201-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/silo-201-data-lt-1080p.webp)
