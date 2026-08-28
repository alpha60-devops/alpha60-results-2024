---
layout: default
title: "echo-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# echo-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Echo |
| Collection key | `echo-01` |
| imdb_id | [tt13966962](https://www.imdb.com/title/tt13966962/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-01-10-to-2024-07-09 |
| Sample days | 182 (2024–2024) |
| BTIH count | 352 |
| Unique BTIH count | 332 |
| Downloaders total | 33,399,544 |
| Uploaders total | 1,294,251 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T17:28:01Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/echo-01.xz`
- Hour directories: 4346
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 4 (16 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-02-10 22:00`, resumed `2024-02-11 00:00` — missing 1 hour(s)
- hourly gap: last `2024-02-16 19:00`, resumed `2024-02-17 09:03` — missing 13 hour(s)
- hourly gap: last `2024-02-24 01:03`, resumed `2024-02-24 03:03` — missing 1 hour(s)
- hourly gap: last `2024-03-31 01:03`, resumed `2024-03-31 03:03` — missing 1 hour(s)

## 3. Collection size histogram

![Echo collection size histogram](figures/echo-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![echo-01 downloads by week](figures/echo-01-downloads-by-week-echo-01-week.svg)

### Downloads by day, Saturday and Sunday in gray

![echo-01 downloads by day](figures/echo-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.26 | 19.17 | 23.51 | 52.96 | 0.91 | 0.64 |

### Cumulative network infrastructure

[![Echo cumulative map](figures/echo-01-carto.png)](figures/echo-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/echo-01-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/echo-01-data-lt-1080p.webp)
