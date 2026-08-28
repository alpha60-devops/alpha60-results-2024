---
layout: default
title: "dune-2024 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dune-2024 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dune 2024: Part Two |
| Collection key | `dune-2024` |
| imdb_id | [tt0087182](https://www.imdb.com/title/tt0087182/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-04-06-to-2024-10-04 |
| Sample days | 182 (2024–2024) |
| BTIH count | 704 |
| Unique BTIH count | 626 |
| Downloaders total | 97,510,251 |
| Uploaders total | 11,624,985 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T17:26:58Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/dune-2024.xz`
- Hour directories: 4354
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Collection size histogram

![Dune 2024: Part Two collection size histogram](figures/dune-2024-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![dune-2024 downloads by week](figures/dune-2024-downloads-by-week-dune-2024-week.svg)

### Downloads by day, Saturday and Sunday in gray

![dune-2024 downloads by day](figures/dune-2024-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.28 | 16.47 | 25.87 | 51.30 | 1.04 | 0.67 |

### Cumulative network infrastructure

[![Dune 2024: Part Two cumulative map](figures/dune-2024-carto.png)](figures/dune-2024-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/dune-2024-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/dune-2024-data-lt-1080p.webp)
