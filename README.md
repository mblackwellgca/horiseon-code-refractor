# horiseon-code-refractor
Links:
Live Application: https://mblackwellgca.github.io/horiseon-code-refractor/ 

Github URL: https://github.com/mblackwellgca/horiseon-code-refractor.git

## Description 
Accessibility ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. In this example, we are refactoring an existing site to make it more accessible.
While updating for accessibility, I cleaned up the coding a little to combine syles when appropriate, clarify elements such as class & id for future reference. Edit clarifications are below.

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png) (assignment image used here as I do not have a public repository for sharing images nor was this discussed in class regarding expectations)

## Edits
* HTML:
  * Line 7, Title changed to "Horiseon Social Solutions"
  * Line 11, removed "div" for header and line 12 added "header"
  * Line 15, changed div to nav for clarity
  * Line 30, changed div to figure for clarity
  * Line 32, changed div to section for clarity
  * Line 34, Added "id" to "search-engine-optimization" so that when clicking the link, users are taken to that location, changed div to article, and deleted class.
  * Lines 35, 43, 63, 71, 79, added alt text to image
  * Lines 42 & 50, changed div to article and deleted class
  * Line 59, changed div to section
  * Lines 61, 69, 77, changed div to aside, and deleted class.
  * Line 86, changed div to footer for clarity
* CSS:
  * Line 12, removed "." class from the main header
  * Lines 28, 36, & 39, changed to nav since this element was changed in the html.
  * Lines 90, 96, 102, 109, 119, & 124, changed class to updated semantics as this element was also changed in the html file. This change allowed the deletion of redundant coding, that cleans up the css file making it easier to read.
  * Line 130, removed "." class from footer.
