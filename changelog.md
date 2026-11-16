# Bergen County Luxury Housing Dataset — Changelog

Publisher: Beyder&Co. Realty. Methodology:
https://www.beyderco.com/data/luxury-housing/methodology

Corrections ship as a new version of a release (v2, v3, …) with an entry
here stating what changed and why. No published figure is edited in place.

## 2026-Q3 v1 — first edition

- Data: NJMLS closed sales, July 1 – September 30, 2026, pulled
  October 28, 2026 (234 source records).
- Towns in this edition: Alpine, Tenafly, Saddle River.
- Luxury thresholds in force: Alpine $5,000,000; Tenafly $2,500,000;
  Saddle River $4,000,000 (set at this edition from each town's
  trailing-12-month top-quartile sale price; held fixed across editions).
- Alpine luxury segment: 0 closed sales at or above the threshold in the
  quarter, so every Alpine luxury metric is published as
  suppressed_small_n under the dataset's suppression rule (metrics from
  fewer than five sales are suppressed; the sales count always publishes).
- Files: alpine-2026-q3, tenafly-2026-q3, saddle-river-2026-q3, each as
  .json and .csv, published beside this changelog and the methodology
  page. The release manifest and full canonical files also live in the
  dataset repository:
  https://github.com/Beyder28/bergen-county-luxury-housing-dataset
- Hosting note, 2026-11-14: the complete edition files were added beside
  the Q3 luxury summaries above — alpine-2026-q3-complete,
  tenafly-2026-q3-complete and saddle-river-2026-q3-complete, each as
  .json and .csv, covering all segments (luxury and all-single-family)
  and all periods (2026-Q3, 2026-Q2 and 2025-Q3). No figure changed and
  no new version was created; this is a hosting addition only.
