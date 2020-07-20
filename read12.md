### CHART JS

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
They’re easier to look at and convey data quickly, but they’re not always easy to create.

Chart.js is a community maintained open-source library (it’s available on GitHub) that helps you easily visualize data using JavaScript.
It’s similar to Chartist and Google Charts. It supports 8 different chart types (including bars, lines, & pies), and they’re all responsive.
In other words, you set up your chart once, and Chart.js will do the heavy-lifting for you and make sure that it’s always legible
(for example by removing some uncritical details if the chart gets smaller).

In a gist, this is what you need to do to draw a chart with Chart.js:

*Define where on your page to draw the graph.
*Define what type of graph you want to draw.
*Supply Chart.js with data, labels, and other options.


#### Prepare a place in your HTML to render the chart

The last thing we need to prepare before we can start visualizing our data is to define an area in our HTML where we want to draw the graph.
For Chart.js you do this by adding a canvas element, and setting width and height to define the proportions of your graph.

Notice that we’ve added an id (myChart) to the canvas element that we can later use to reference our designated graph element in JavaScript or CSS.
What this ID is set to has no significance for Chart.js; you can name it whatever you want.
What matters is that you use the exact same ID when you reference it in JavaScript or CSS.
If you’re adding several graphs to a page, just make sure that every ID is unique (you could for example give your graphs more specific names, like populationChart or regionChart).


#### Prepare the data
The data we’re using is from Wikipedia’s article on World population, and includes a world population prediction from UN’s World Population Prospects report.
Here’s the raw data that we’ll be using:


Region	1500	1600	1700	1750	1800	1850	1900	1950	1999	2050
Africa	86	114	106	106	107	111	133	221	783	2478
Asia	282	350	411	502	635	809	947	1402	3700	5267
Europe	168	170	178	190	203	276	408	547	675	734
Latin America	40	20	10	16	24	38	74	167	508	784 
North America	6	3	2	2	7	26	82	172	312	433


To draw lines and add labels along axes, Chart.js expects the data to be passed in the form of a set of arrays,
like so: [10, 4, 7]. We’re going to use 6 arrays in total: one for all the year labels to be shown along the X axis (1500-2050) and one array for each region containing the population data.
So all we need to do is copy each row in our table above, seperate each value with a comma, and then end and start the list with []-brackets.


### CAnvas Elemnt 

![link](https://www.webfx.com/blog/images/assets/images.sixrevisions.com/2010/10/03-01_html5_canvas_element_ld_img.png)

The HTML5 canvas element has a unique history. Starting out as an Apple creation and dating back to 2004,
canvas was eventually added to the official W3C HTML5 spec, becoming one of the most interesting and exciting parts of HTML5.

It is used by web designers all over the world.

Unfortunately, this element takes a bit of work to understand and, unlike your usual run-of-the-mill HTML elements,
requires more than just static markup and styling.  This element is great for sites looking for a more responsive web design, like maybe a realtor.

In this guide, I hope to get you started on understanding the canvas element and what kinds of things are required and expected in its associated code. 
This should help you get a firm fundamental understanding of canvas in preparation for creating something interesting and powerful with this unique HTML5 element.


#### Definition and Markup

I can’t possibly define the canvas element better than the official W3C spec, so I’ll just quote part of that document here:

The canvas element provides scripts with a resolution-dependent bitmap canvas, which can be used for rendering graphs, game graphics, or other visual images on the fly.

I also like the way Wikipedia describes its usage:

Canvas consists of a drawable region defined in HTML code with height and width attributes. 
JavaScript code may access the area through a full set of drawing functions similar to other common 2D APIs,
thus allowing for dynamically generated graphics. Some anticipated uses of canvas include building graphs, animations, games, and image composition.

As you can see already, this element has a bit of complexity to it. Let’s take it one step at a time, beginning with the markup.
