# CSS layouts

## Story

Your friend Peter has no clue about CSS layouts and wants some help in his homework.
He must use different CSS layouts in a HTML page, and asks you to help him out.
Peter is a good friend of yours, so you decide to make a template of the different utilities in CSS for making layouts.

## What are you going to learn?

- CSS positioning
- CSS flexbox
- CSS grid

## Tasks

1. Create a navigation bar template. Make a `div` element that stays at the top of the window wherever you scroll. Make sure that nothing slides behind the element on top of the page. Create an `h1` with the content `Layouts` and make it centered in the HTML element.
    - There is a `div` tag in the HTML file containing an `h1` tag
    - The `div` tag stays on top even when scrolling down the page
    - There is no element in the top of the page that is covered by the element.
    - The `h1` display the text `Layouts`.
    - The `Layouts` text is aligned to the middle.

2. Create a template for a login form using the CSS flexbox. The container of the login form container two input fields and a submit button.
    - There is a `form` tag containing two input fields and a button.
    - The `display` property of the container is `flex`
    - The input fields and the button are placed below each other in the middle of the container
    - There is equal space between the children elements of the container.

3. CSS grid is a powerful utility that you can work with. Make an example of its simple usage with colored boxes. Make a container and place four `div` elements in it, using CSS grid.
    - There is a `div` tag that functions as a grid.
    - The `div` tag has four `div` children with different colors.
    - The grid has five explicit rows, each `70px` high.
    - The grid has five explicit columns and spans the width of the window.
    - The first child span the width of the entire grid.
    - The second child spans three rows and two columns.
    - The third child starts at the last row and spans the entire width.
    - The fourth child fills up the rest of the grid cells.

## General requirements

None

## Hints

- View your changes by hard refreshing the page (Windows/Linux: `Ctrl+F5`/`Ctrl+Shift+R`, Mac: `Cmd+Shift+R`) after changing something in a CSS file.
- The default positioning of an HTML element is based on its parent.
- Use the `lorem ipsum` in the Background section if you need placeholder text.

## Background materials

- <i class="far fa-exclamation"></i> [Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)
- <i class="far fa-exclamation"></i> [Positioning documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- <i class="far fa-exclamation"></i> [Flexbox documentation](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- <i class="far fa-exclamation"></i> [Flexbox tutorial](https://flexbox.io/)
- <i class="far fa-video"></i> [How to use flexbox](https://www.youtube.com/watch?v=Vj7NZ6FiQvo&list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid) (you just need the Tutorial 2-9)
- <i class="far fa-exclamation"></i> [Grid documentation](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
- <i class="far fa-exclamation"></i> [Grid tutorial](https://cssgrid.io/)
- <i class="far fa-video"></i> [CSS grid fundamentals](https://www.youtube.com/watch?v=T-slCsOrLcc&list=PLu8EoSxDXHP5CIFvt9-ze3IngcdAc2xKG) (you just need the Tutorial 3-11)
- <i class="far fa-book-open"></i> [Multi-column layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Multiple-column_Layout)
- <i class="far fa-candy-cane"></i> [Layout tutorial from nothing to flexbox](https://learnlayout.com/)
- <i class="far fa-exclamation"></i> [CSS basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
- <i class="far fa-book-open"></i> [CSS box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
- <i class="far fa-book-open"></i> [Which unit do I need to use?](https://www.digitalocean.com/community/tutorials/css-css-units-explained)
