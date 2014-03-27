# SassyGrids

Just import SassyGrids and you're good to go!

SassyGrids DOESN'T rely on any other system, it just goes :)

* @import 'SassyGrids';

Sassygrids is a SCSS processed grid system that will automate the majority of your project with a few simple variables:

* $columnWidth:       40;
* $numberOfColumns:   16;
* $gutterWidth:       20;
* $breakDimensions:   auto 4;

The above variables can be edited, they are located in the _SassyGrids.scss file.

## Automating the CSS Grid System

Lets create a file called grid.scss and import Sassy into it.

* @import 'SassyGrids';
* @include generateCSS();

The above will create a style sheet with all the classnames already setup for you.

## Documentation

For extended documentation, and a full example of a site built with sassyGrids, please visit: 
* http://www.sassygrids.com/documentation

## Contributing

This is in beta, and I plan to add many features in the future. I would very much like your input, so please get in touch with any suggestions or comments. 

Of course, if you don't see what you're looking for please just drop me
a line at shannon [at] shannonhochkins.com.
