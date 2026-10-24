# Corstorphine Nature Connections

An interactive community map of Corstorphine and Clermiston, Edinburgh. It shows open mapping records and eight clearly labelled candidate pollinator and garden wildlife connections.

The map is a working discussion tool, not an approved scheme or a surveyed ecological network. It includes independent layers, search, evidence links, candidate details, private browser notes and shortlist exports. Notes stay in local browser storage and are never uploaded.

## Hosting

This is a static website. Publish the root of the main branch with GitHub Pages. No build step, mapping key or external tile server is required. Assets and fonts are bundled.

## Sources

OpenStreetMap contributors (ODbL), extracted 23 October 2026. The study boundary is City of Edinburgh Council’s Corstorphine and Clermiston community council area, effective 28 March 2025 (OGL v3.0). The eight candidate axes are unverified interpretations. See DATA-LICENCES.md, the in-map Sources & method panel and data/metadata.json.

## Software

Leaflet 1.9.4 uses the BSD 2-Clause licence. DM Sans and Libre Caslon Display use the SIL Open Font Licence. Their licence files are retained under vendor/.

## Local inspection

Open the site through a local static web server so the browser can fetch the GeoJSON files. Keep all relative paths intact when publishing at a repository subpath.
