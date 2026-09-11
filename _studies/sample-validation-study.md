---
# Sample entry for reviewing the study template. Remove before launch.
title: "Sample: phone-photo canopy closure against a spherical densiometer"
sample: true
kind: Validation study        # Validation study, Field study or Sector analysis
status: Published             # In progress, Published or Peer-reviewed
date: 2026-09-10              # when this page was first posted
updated: 2026-09-10
authors:
  - name: Sample Author
    affiliation: fun.limited
    cite: "Author, S."
  - name: Second Author
    affiliation: Example Institute
    cite: "Author, T."
apps:
  - id: sample-app
    version: "1.2"
reference_method: Spherical densiometer, four readings per plot
threshold: >-
  The app passes if at least 95% of paired readings fall within ±10
  percentage points of the densiometer, and the mean difference is under
  3 points.
threshold_date: 2026-09-10
document: /assets/docs/samples/sample-study.pdf
document_label: Full study (PDF placeholder)
description: >-
  We compared canopy closure measured with the sample app against a
  spherical densiometer at 40 forest plots. The two agreed closely: 38 of
  the 40 paired readings were within ten points of each other. The app
  read about two points higher than the densiometer on average, and it met
  the pass threshold.
noindex: true
sitemap: false
---

## Method

Forty plots were placed at random within a second-growth stand of
*Tsuga heterophylla* and *Thuja plicata* near 49°19′12″N. At each plot
centre, one observer took four densiometer readings, one facing each
cardinal direction, and averaged them. A second observer then took four
upward photos with the sample app at 1.3&nbsp;m, in the same four
directions, within 15 minutes of the densiometer readings.

Agreement was assessed with Bland–Altman analysis: the mean difference
between the two methods, and the range within which 95% of differences
fall.

## Results

| Measure | Value |
|---|---:|
| Paired readings | 40 |
| Mean difference, app minus densiometer | +2.1 points |
| 95% limits of agreement | −5.9 to +10.1 points |
| Readings within ±10 points | 38 of 40 (95%) |

The app read slightly higher than the densiometer across the full range
of closure, from 41% to 88%. Both parts of the pass threshold were met.

## Limitations

All plots were in one stand type under overcast skies, so the results say
nothing yet about open woodland or bright sun. The densiometer is itself
an estimate, not a true value; agreement with it shows the app reproduces
the reference method, not that either is correct.

## Sources

- Bland, J. M., & Altman, D. G. (1986). Statistical methods for assessing agreement between two methods of clinical measurement. *The Lancet*, 327(8476), 307–310.
- Lemmon, P. E. (1956). A spherical densiometer for estimating forest overstory density. *Forest Science*, 2(4), 314–320.
