### HTML TABLES

The HTML tables allow web authors to arrange data like text, images, links, other tables, etc. into rows and columns of cells.

The HTML tables are created using the "<table>" tag in which the "<tr>" tag is used to create table rows and "<td>" tag is used to create data cells.
The elements under "<td>" are regular and left aligned by default

####Table Heading

Table heading can be defined using "<th>" tag.
This tag will be put to replace "<td>" tag, which is used to represent actual data cell.
Normally you will put your top row as table heading as shown below, otherwise you can use "<th>" element in any row.
Headings, which are defined in "<th>" tag are centered and bold by default.

*Cellpadding and Cellspacing Attributes
There are two attributes called cellpadding and cellspacing which you will use to adjust the white space in your table cells.
The cellspacing attribute defines space between table cells, while cellpadding represents the distance between cell borders and the content within a cell.

*Colspan and Rowspan Attributes
You will use colspan attribute if you want to merge two or more columns into a single column.
Similar way you will use rowspan if you want to merge two or more rows.

####Tables Backgrounds

You can set table background using one of the following two ways 

bgcolor attribute: You can set background color for whole table or just for one cell.

background attribute: You can set background image for whole table or just for one cell.

You can also set border color also using bordercolor attribute.

####Table Height and Width

You can set a table width and height using width and height attributes.
You can specify table width or height in terms of pixels or in terms of percentage of available screen area.


Table Header, Body, and Footer
Tables can be divided into three portions − a header, a body, and a foot. The head and foot are rather similar to headers and footers in a word-processed document that remain the same for every page, while the body is the main content holder of the table.

The three elements for separating the head, body, and foot of a table are 

"<thead>" − to create a separate table header.

"<tbody>" − to indicate the main body of the table.

"<tfoot>" − to create a separate table footer.

A table may contain several <tbody> elements to indicate different pages or groups of data.
But it is notable that "<thead>" and "<tfoot>" tags should appear before "<tbody>"
