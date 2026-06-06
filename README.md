# search-and-map-pins

An accessible "search and map pins" demo: a raster base map of a
residential subdivision with a curated, checkbox-driven pin overlay.
Pointer users move across the map and hear what is under the cursor
(Cartesian); keyboard and screen-reader users tap a pin and hear its
surroundings described as name, distance, and compass direction from a
chosen origin (polar). The pin sits at the centre of the viewport as
the datum the map orbits.

One of a family of accessible map demos; see also
[east-toronto-streetmap](https://github.com/bobdodd/east-toronto-streetmap),
[terminal-map](https://github.com/bobdodd/terminal-map), and
[accessible-maps](https://github.com/bobdodd/accessible-maps).

A runnable version is hosted at
<https://a11ybob.com/maps/search-and-map-pins>.

## Running it

Open `map.html` in a browser, or serve the folder over any static HTTP
server. There is no build step.

## A single self-contained file

`map.html` is deliberately one self-contained HTML file: the base map
and many images are inlined (base64), with the interaction logic in an
inline `<script>`. A single file is trivially portable — it can be
passed around or handed over as a stand-alone artefact with no asset
folder, server, or build to break. The external files here are the
point-of-interest photographs, a logo, and the stylesheet.

## Licence

GPL-3.0-or-later — see [LICENSE](LICENSE). The base map and all assets
are original work; there is no third-party map data. See [NOTICE](NOTICE).
