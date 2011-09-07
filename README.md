# Foldy960 - A responsive 960 grid from Paravel
Foldy960 isn't aiming to be Yet-Another-CSS-Framework and we hesitate to use the term "Boilerplate".  Foldy is just a little kit and some extra classes to get you going on making your [960.gs](http://960.gs) design responsive.

*New*: Foldy 6 Column is a bit different than the traditional 960. It's all fluid, but for proportions sake, think of it in the following pixel dimensions:

* 6 Columns
* 135px wide column
* 30px wide gutter
* 990px total width.

## Features
* Simplified 6 Column Responding Grid
  * `< 480px`: One column fluid.
  * `< 640px`: One column fluid.
  * `> 640px`: Fluid 3 column 960 grid. (default)
* `.grid_right` for proper content collapsing
* `.content-pad-right` & `.content-pad-left` for extra padding if you needed. Obviously, not the most desired semantics, but absolutely bulletproof when you're padding content.
* `.foldy-gallery` - a class for handling image galleries. Goes from tri-grid to bi-grid.
* Foldy defaults to `max-width: 990px;` but change that to whatever you friggin' want.

## Changelog
* 09/07/2011
  * Switched to 6 column grid.
  * Added `.foldy-gallery` class.
* 08/26/2011
  * Simplified down responsiveness down to a single media query.
* 05/23/2011
  * Initial release.

## License
Foldy is licensed under the WTFPL + "Not going to maintain this because the rent is too damn high" License.