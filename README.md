# Little Sioux survey maps

Static HTML viewer for Questions 11, 13, and 16. No build step required.

## Files

- `index.html`: viewer and map interactions.
- `data/maps.js`: map-only data.

## Data scope

Questions 11 and 13 contain river-stretch geometry, names, and aggregate selection counts.
Question 16 contains the 882 submitted map geometries and their category/subtopic tags.
Mapped locations are public in this viewer, but have no respondent identifiers or links to respondents.

No emails, ZIP codes, demographics, timestamps, receipt IDs, response IDs, free-text comments, custom free-text tags, or other survey answers are included. Internal category and subtopic IDs are replaced by readable display slugs.

Counts represent stretch selections (Questions 11 and 13) or mapped locations (Question 16), not unique people. One location can have multiple subtopics; subtopic totals are not additive. Counts and filters follow the visible map area.

## Hosting

Publish the main branch, root folder, with GitHub Pages. Leaflet and OpenStreetMap tiles require an internet connection. For local preview, serve this folder over HTTP rather than opening a file URL.
