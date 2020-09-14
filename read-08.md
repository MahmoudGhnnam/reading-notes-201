# CSS LAYOUT

## Building Blocks:

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

Block-level elements start on a new line Examples include: ```<h1> <p> <ul> <li>```

Inline elements flow in between surrounding text Examples include: ```<img> <b> <i>```

![element](/img/elements.png)

## Containing Elements:

If one block-level element sits inside another the block-level element then the outer box is known as the containing or parent element.

## Controlling the Position of Elements:

CSS has the following positioning schemes that allow you to control the layout of a page:

* normal flow:

Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other.

* relative positioning:

This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed

* absolute positioning:

This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements

To indicate where a box should be positioned, you may also need to use
**box offset** properties to tell the browser how far from the top or bottom
and left or right it should be placed.

* Fixed Positioning:

Elements with fixed positioning
do not affect the position of
surrounding elements and they
do not move when the user
scrolls up or down the page.

* Floating Elements:

Floating an element allows
you to take that element out
of normal flow and position
it to the far left or right of a
containing box.

You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

## Screen Sizes:

 Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

* Screen Resolution:

 Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

* Page Sizes:

 Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).

## Fixed Width Layouts

Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels.

* Advantages:

● Pixel values are accurate
at controlling size and
positioning of elements.

● The designer has far greater
control over the appearance
and position of items on the
page than with liquid layouts.

● You can control the lengths
of lines of text regardless of
the size of the user's window.

● The size of an image will
always remain the same
relative to the rest of the
pag

* Disadvantages:

● You can end up with big gaps
around the edge of a page.

● If the user's screen is a much
higher resolution than the
designer's screen, the page
can look smaller and text can
be harder to read.

● If a user increases font sizes,
text might not fit into the
allotted spaces.

● The design works best on
devices that have a site or
resolution similar to that of
desktop or laptop computers.

● The page will often take up
more vertical space than a
liquid layout with the same
content.

## Liquid Layouts
Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.

* * * 

## Fixed Positioning affect the position of surrounding element
- [ ] yes
- [x] no

## Block-level elements
- [ ] yes
- [x] no

## Liquid Layouts designs do not change size as the user increases or decreases the size of their browser window.
- [ ] yes
- [x] no