---
layout: default
title: "monsieur-spade-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# monsieur-spade-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Monsieur Spade |
| Collection key | `monsieur-spade-01` |
| imdb_id | [tt14203572](https://www.imdb.com/title/tt14203572/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-01-15-to-2024-04-28 |
| Sample days | 105 (2024–2024) |
| BTIH count | 194 |
| Unique BTIH count | 183 |
| Downloaders total | 10,585,644 |
| Uploaders total | 466,592 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T21:00:58Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/monsieur-spade-01.xz`
- Hour directories: 2509
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (11 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-02-16 19:03`, resumed `2024-02-17 06:03` — missing 10 hour(s)
- hourly gap: last `2024-03-31 01:03`, resumed `2024-03-31 03:03` — missing 1 hour(s)

## 3. Collection size histogram

![Monsieur Spade collection size histogram](figures/monsieur-spade-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![monsieur-spade-01 downloads by week](figures/monsieur-spade-01-downloads-by-week-monsieur-spade-01-week.svg)

### Downloads by day, Saturday and Sunday in gray

![monsieur-spade-01 downloads by day](figures/monsieur-spade-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.68 | 20.22 | 21.75 | 52.21 | 1.29 | 0.56 |

### Cumulative network infrastructure

[![Monsieur Spade cumulative map](figures/monsieur-spade-01-carto.png)](figures/monsieur-spade-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/monsieur-spade-01-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/monsieur-spade-01-data-lt-1080p.webp)
