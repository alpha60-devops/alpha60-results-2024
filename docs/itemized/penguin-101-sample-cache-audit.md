---
layout: default
title: "penguin-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# penguin-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Penguin |
| Collection key | `penguin-101` |
| imdb_id | [tt11323316](https://www.imdb.com/title/tt11323316/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-09-20-to-2025-03-20 |
| Sample days | 182 (2024–2025) |
| BTIH count | 344 |
| Unique BTIH count | 316 |
| Downloaders total | 50,019,922 |
| Uploaders total | 3,400,610 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T21:12:10Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/penguin-101.xz`
- Hour directories: 4343
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (7 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-11-29 10:00`, resumed `2024-11-29 18:00` — missing 7 hour(s)

## 3. Collection size histogram

![The Penguin collection size histogram](figures/penguin-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![penguin-101 downloads by week](figures/penguin-101-downloads-by-week-penguin-101-week.svg)

### Downloads by day, Saturday and Sunday in gray

![penguin-101 downloads by day](figures/penguin-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.09 | 15.30 | 26.58 | 52.98 | 1.01 | 0.52 |

### Cumulative network infrastructure

[![The Penguin cumulative map](figures/penguin-101-carto.png)](figures/penguin-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/penguin-101-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/penguin-101-data-lt-1080p.webp)
