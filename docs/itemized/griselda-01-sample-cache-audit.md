---
layout: default
title: "griselda-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# griselda-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Griselda |
| Collection key | `griselda-01` |
| imdb_id | [tt15837600](https://www.imdb.com/title/tt15837600/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-01-25-to-2024-05-08 |
| Sample days | 105 (2024–2024) |
| BTIH count | 201 |
| Unique BTIH count | 181 |
| Downloaders total | 12,460,144 |
| Uploaders total | 865,895 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T18:37:51Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/griselda-01.xz`
- Hour directories: 2490
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (13 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2024-02-16 19:06`, resumed `2024-02-17 08:45` — missing 12 hour(s)
- hourly gap: last `2024-03-31 01:00`, resumed `2024-03-31 03:00` — missing 1 hour(s)

## 3. Collection size histogram

![Griselda collection size histogram](figures/griselda-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![griselda-01 downloads by week](figures/griselda-01-downloads-by-week-griselda-01-week.svg)

### Downloads by day, Saturday and Sunday in gray

![griselda-01 downloads by day](figures/griselda-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.88 | 18.71 | 21.56 | 51.75 | 0.84 | 0.57 |

### Cumulative network infrastructure

[![Griselda cumulative map](figures/griselda-01-carto.png)](figures/griselda-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/griselda-01-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/griselda-01-data-lt-1080p.webp)
