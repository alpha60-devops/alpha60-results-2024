---
layout: default
title: "rings-of-power-207 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# rings-of-power-207 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Rings of Power |
| Collection key | `rings-of-power-207` |
| imdb_id | [tt7631058](https://www.imdb.com/title/tt7631058/) |
| wikipedia_url | UNAVAILABLE |
| Sample dates | 2024-09-30-to-2025-03-30 |
| Sample days | 182 (2024–2025) |
| BTIH count | 268 |
| Unique BTIH count | 254 |
| Downloaders total | 37,032,168 |
| Uploaders total | 2,085,211 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Cache coverage report

- Generated: 2026-08-28T21:26:06Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/rings-of-power-207.xz`
- Hour directories: 4331
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 3 (32 missing hours)
- Missing days: 1

### Sample archive discontinuities

- hourly gap: last `2024-11-24 23:00`, resumed `2024-11-26 00:00` — missing 24 hour(s)
- hourly gap: last `2024-11-29 10:00`, resumed `2024-11-29 18:00` — missing 7 hour(s)
- hourly gap: last `2025-03-30 01:00`, resumed `2025-03-30 03:00` — missing 1 hour(s)
- missing day: `2024-11-25`

## 3. Collection size histogram

![Rings of Power collection size histogram](figures/rings-of-power-207-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

![rings-of-power-207 downloads by week](figures/rings-of-power-207-downloads-by-week-rings-of-power-207-week.svg)

### Downloads by day, Saturday and Sunday in gray

![rings-of-power-207 downloads by day](figures/rings-of-power-207-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Continental downloader slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.75 | 14.82 | 26.75 | 53.83 | 0.88 | 0.53 |

### Cumulative network infrastructure

[![Rings of Power cumulative map](figures/rings-of-power-207-carto.png)](figures/rings-of-power-207-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

![Cumulative >= 1080p](figures/rings-of-power-207-data-ge-1080p.webp)

**Cumulative < 1080p**

![Cumulative < 1080p](figures/rings-of-power-207-data-lt-1080p.webp)
