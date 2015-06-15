# refactor-exercise

In this exercise you should be able to demonstrate your front-end refactoring skills using HTML/CSS/Scss

The goal is to improve the current HTML/CSS code without changing the visual appearence of the page.

Requirements:

* The code should be reusable for building future pages and UI components.
* The code should be easily understandable and mantainable.
* Design should be mantained.
* Identify areas of improvement and explain why.


## Refactoring by Paulo Martins:
#### index.html
	css and favicon moved to head of page (this way, page processing is faster)

#### main.scss:
	using variables to define common itens, as colours. This way, it's easier to change the whole appearance at once, if necessary.
	variables created were: 
	* $backblue => for background color and color of titles and links
	* $white and $orange => although it may look that is useless to create this variable, if in the future we want to change any color of the site, we will have all of them together in the same place. It also helps all the developers to keep consistency at the element colors and guarantees the page will not have too much poluted colors.
	* $font => font used in the page

	consistency: instead of using RGB colors sometimes and name colors other times, all colors are now in RGB format

#### fixed bower link:
	bower_components, in my environment, were installed at root folder level.
	This way, for correct import of bootstrap file, I had to fix the import, adding one level.


