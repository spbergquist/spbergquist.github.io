---
# Sample entry for reviewing the guide template. Remove before launch.
title: "Sample: mapping plot locations in Google Earth"
sample: true
label: Data handling
stage: elsewhere
updated: 2026-09-10
description: >-
  For anyone with a list of plot coordinates who wants to see them on a
  map. Uses Google Earth Pro and a spreadsheet template, so it works
  whether the coordinates came from an app, a GPS unit or a site plan.
template:
  file: /assets/downloads/samples/sample-plot-template.csv
  name: Plot list template (CSV)
  note: One row per plot. Keep the column names exactly as they are.
result: >-
  Every plot shown as a pin on the satellite image, labelled with its plot
  number, ready for checking spacing and access before fieldwork.
troubleshooting:
  - problem: The pins land in the ocean off West Africa.
    fix: A blank or zero coordinate puts a pin at 0°, 0°. Look for empty cells in the latitude and longitude columns.
  - problem: The pins appear on the wrong side of the world.
    fix: Western longitudes must be negative, for example −123.07 rather than 123.07.
noindex: true
sitemap: false
---

Google Earth changes its menus from time to time, so this guide describes
the workflow rather than every click. The template does the fiddly part.

1. Fill in the template, one row per plot, with its number and its
   latitude and longitude in decimal degrees.
2. Save the file as CSV, keeping the column names unchanged.
3. Import the file into Google Earth Pro and tell it which columns hold
   the latitude, the longitude and the plot name.
4. Save the result as a KML file if you want to share the map or open it
   on a phone.
