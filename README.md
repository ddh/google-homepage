From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css)

1. Two ways to move a div around on the page
1. Stick a div onto the bottom or top of the page
1. Identify the background color of an existing webpage
1. Grab the URL for an image from an existing webpage
1. Center an element horizontally
1. Identify three ways you can include your CSS styles in a page
1. Understand how to use classes and ids to target CSS at specific elements on the page
1. Build a very basic form (even if it doesn’t “go” anywhere)

# Notes from this lesson
* Nice intro guide: https://learn.shayhowe.com/html-css
* Nav bars: https://www.w3schools.com/css/css_navbar.asp

## Basic HTML

### Block vs Inline, Divs vs Spans:
* _Block-level_ elements stack on top of each other vertical. They're intended for larger elements, like paragraphs.
* On the contrary, _inline-level_ elements line up side by side.
* `<div>` identify large groupings of elements
* Whereas `<span>` is used to identity inline grouping of elements.
* Think `block` == vertical, `inline` side-by-side

### Structure:
* `<header>`: Identifies the top of a page or section.
* `<nav>`: Identifies navigation, links/.
* `<section>`: Grouping of content; can have many per page.
* `<article>`: Content; should make sense standalone.
* `<aside>`: Related information about content.
* `<footer>`: End of the page; relevant information but not to distract from main content of page.

### Links:
* Opening links in new window:
```
<a href="http://example.com/" target="_blank">Example</a>
```
* Anchor links with `id="foo"` and `a href="#foo"`
* Display links with `display: block` makes the whole element clickable, not just the text.

### Navigation List:

