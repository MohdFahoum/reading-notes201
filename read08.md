### HTML LAYOUTS


Page layout is the part of graphic design that deals with the arrangement of visual elements on a page.
Page layout is used to make the web pages look better. It establishes the overall appearance, relative importance,
and relationships between the graphic elements to achieve a smooth flow of information and eye movement for maximum effectiveness or impact.

![link](https://media.geeksforgeeks.org/wp-content/uploads/layout.png)

Page Layout Information:

Header: The part of a front end which is used at the top of the page. header tag is used to add header section in web pages.
Navigation bar: The navigation bar is same as menu list. It is used to display the content information using hyperlink.
Index / Sidebar: It holds additional information or advertisements and is not always necessary to be added into the page.
Content Section: The content section is the main part where content is displayed.
Footer: The footer section contains the contact information and other query related to web pages.
The footer section always put on the bottom of the web pages. The footer tag is used to set the footer in web pages.


### CSS LYOUTS

CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow,
the other elements around them, their parent container, or the main viewport/window.  The page layout techniques we'll be covering in more detail in this module are

Normal flow
The display property
Flexbox
Grid
Floats
Positioning
Table layout
Multiple-column layout

Each technique has its uses, advantages, and disadvantages, and no technique is designed to be used in isolation.
By understanding what each method is designed for you will be in a good place to understand which is the best layout tool for each task.

Note here how the HTML is displayed in the exact order in which it appears in the source code,
with elements stacked up on top of one another — the first paragraph, followed by the unordered list, followed by the second paragraph.

The elements that appear one below the other are described as block elements, in contrast to inline elements, which appear one beside the other


*For many of the elements on your page the normal flow will create exactly the layout you need,
however for more complex layouts you will need to alter this default behavior using some of the tools available to you in CSS.
Starting with a well-structured HTML document is very important, as you can then work with the way things are laid out by default rather than fighting against it.

####

*The methods that can change how elements are laid out in CSS are as follows:

The display property — Standard values such as block, inline or inline-block can change how elements behave in normal flow,
for example making a block-level element behave like an inline element (see Types of CSS boxes for more information).
We also have entire layout methods that are switched on via specific display values, for example CSS Grid and Flexbox,
which alter how elements inside the element they are set on are laid out.

Floats — Applying a float value such as left can cause block level elements to wrap alongside one side of an element,
like the way images sometimes have text floating around them in magazine layouts.

The position property — Allows you to precisely control the placement of boxes inside other boxes.
static positioning is the default in normal flow, but you can cause elements to be laid out differently using other values,
for example always fixed to the top of the browser viewport.

Table layout — features designed for styling the parts of an HTML table can be used on non-table elements using display: table and associated properties.

Multi-column layout — The Multi-column layout properties can cause the content of a block to layout in columns, as you might see in a newspaper.

