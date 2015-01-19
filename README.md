INT-1
=====

INT-1 symbols SVG, JOSM preset, mapcss for JOSM

Most of this have been moved to [OpenSeaMap/josm](https://github.com/OpenSeaMap/josm), and therefore removed from this repo. The remaining bits might with time end up there, or in other more appropriate repos.

Purpose
=====

The purpose of this project is to make a symbol database with all IHO INT-1
symbols in SVG format under Public Domain license. This is due to the fact that
many of the online sources of these INT-1 symbols are either under restricted
licenses, or in non-scalable formats such as PNG, GIF and JPG. The motive for 
creating SVG symbols is that it can easily be converted into other formats, and
are completely scalable, so it doesn't make difference if it is a small icon of
16x16 pixels, or a large illustration of 2000x2000 pixels.

INT-1 subcategories
=====

A: Chart Number, Title, Marginal Notes

B: Positions, Distances, Directions, Compass

C: Natural Features

D: Cultural Features

E: Landmarks

F: Ports

H: Tides, Currents

I: Depths

J: Nature of the Seabed

K: Rocks, Wrecks, Obstructions

L: Offshore Installations

M: Tracks, Routes

N: Areas, Limits

P: Lights

Q: Buoys, Beacons

R: Fog Signals

S: Radar, Radio, Satellite Navigation Systems

T: Services

U: Small Craft (Leisure) Facilities

JOSM
=====

As OpenStreetMap have been used as platform for http://www.openseamap.org/
an editor solution have been desirable. As the OpenSeaMapEditor plugin for JOSM
did not include all INT-1 symbols I found it desirable to create a complete
INT-1 tagging preset for JOSM, utilizing the SVG symbols from this list. I have
also increased this with a paint style using the same symbols. There are severl
issues to resolve with this before this can be considered a "stable" release.

Currently several of the symbols are missing icons (missing SVG files), and
paths are absolute to a computer path. In the future this will be substituted
to a repository path.

Improvements
=====

If you do any improvements to the files, feel free to request a push on the GIT
repository, or email the changes directly to me on lists@gimnechiske.org
If changes refer to the tagging prefix or the paint style please inform in the
email what or where you did the changes. It is also possible to open an issue on
GIT.
