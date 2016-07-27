Thanks to https://codepen.io/irinakramer/

This boilerplate includes standard folder and file structures. Styles used were made using Sass. All changes MUST only be done on theme/styles/sass folder. Use Sass compilers like Gulp or Scout(Application for Mac)

NOTE: PLEASE DO NOT MAKE ANY CHANGES ON main.css and sass/_grid.scss FILES.

- All dev styles should be placed on _custom.scss
- Place all utility/reusable classes on _utilities.scss
- Declare all variables on _varibles.scss
- Styles on _global.scss are used on ALL pages. Update with caution.

- All media queries must be placed on _mediaqueries.scss
	- max 1024px - for ipad landscape / smaller desktop view
	- max 992px - other tablets and desktop views 
	- max 768px - for mobile devices
	*Please, please add additional breakpoints only if STRONGLY needed

--------------------------------------
BASIC GRID CLASSES DIRECTORY
--------------------------------------
- .grid:			initializes flex on container
- .grid-full:		initializes full-width grid
- .grid-cols-2:		initializes two-column grid
- .grid-cols-3:		initializes three-column grid
- .grid-cols-4:		initializes four-column grid
- .grid-cols-6:		initializes six-column grid
- .grid-cols-12:	initializes twelve-column grid
- .grid-cell:		holder of contents. Similar behavior as <td>
- .grid-gutter:		for column spacing

--------------------------------------
SIDEBAR CLASSES 
--------------------------------------
* Only the first grid-cell child will be resized

- .grid-one-sixth: 		smallest sidebar. Uses six-column width
- .grid-one-fourth: 	uses four-column width
- .grid-one-third: 		uses three-column width
- .grid-one-half: 		uses two-column width

--------------------------------------
GRID ASIDE ALIGNMENT
--------------------------------------
- .grid-aside:		initializes grids with side columns
- .main:			main content. Contents in the center. Order number 2
- .aside.aside-1:	aside order 1. Left column content	
- .aside.aside-2:	aside order 3. Right column content	

--------------------------------------
OTHER GRID CLASSES
--------------------------------------
- .grid-nested:		declares nested grid
- .grid-top:		vertical align top
- .grid-center: 	vertical align center
- .grid-bottom: 	vertical align bottom
- .grid-right:		horizontal align right
- .grid-left:		horizontal align left
- .grid-center:		horizontal align center


DEMO HERE: https://rawgit.com/ticklemetintine/RWD-Boilerplate/master/index.html
