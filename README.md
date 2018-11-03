# skymap
Sky Map based on D3 and Jason Davies' "Rotate the World" example.

Displays a projection of the night sky (stars and constellation lines only - no solar system yet).
The star database derives from the astronomy nexus (http://astronexus.com/hyg) - only stars brighter than magnitude 5 are displayed.
The constellation lines come from the PP3 program (http://pp3.sourceforge.net/)

You can zoom and drag the map, and hovering over a star displays its Draper catalog number and Bayer designation if available.

The limit of magnitude 5 is necessary to remove smaller stars when displaying a large area of the sky, and to reduce the memory requirements.
The solution, of course, is to load smaller stars selectively (in tiles) when zooming.

Another version of this page (http://astro.roya.org/projects/stars/stars_v5.html) does just this. 

