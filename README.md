# Origami - A fluid mobile-first grid system
Origami is simple, barebones template for building grid-based, mobile-first websites.

Adapted from [Foldy960 by Dave Rupert](https://github.com/davatron5000/Foldy960), Origami includes:

* A 6-column, fluid grid.
* Offsets for more flexible layouts design.
* A special class to flip the order of your grids (for content choreography).
* A special class for image galleries.

## How It Works
1. Wrap your content in a `<div>` with the `.container` class. This sets the max-width for the page (1280px by default).
2. Create a row by adding the `.row` class to a `<div>`.
3. Within the `.row`, create grids by adding the `.grid-*` class to a `<div>`. You can add as many or as few grids as you'd like, but the grid number must add up to 6.
4. Offset grids by adding the class `.offset-*`.
5. Flip the order of grids by adding the class `.grid-flip` to the grid(s) you'd like to float to the right on bigger screens.
6. For image galleries, use the class `.grid-img`. You can add as many image grids per row as you would like.

See the included index.html demo for more information.

## Changelog
* 01/21/2013
  * Initial release.

## License
Origami is licensed under the [WTFPL](http://www.wtfpl.net/) + "Not going to maintain this because the rent is too damn high" License.
