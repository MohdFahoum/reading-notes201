### IMAGES 

*There are many reasons why you might want to add an image to a web page: 

you might want to include a logo, photograph, illustration, diagram, or chart.

It is tempting to use a lot of imagery on your web sites.
Images are a great way to set the mood for the visitor, and illustrations help make complex information easier to take in for visual learners.

The drawback of images on the web is that not everybody can see them.
Back in the days when images were first supported by browsers, web connections were slow, and you’d pay a lot of money for each minute you were online.
Many site visitors had images turned off to save on download costs and get a faster surfing experience.

*While this is not very common these days, there are still other problems to consider:

People surfing on mobile devices might still have images turned off due to small screen size or the cost of downloading data.

Visitors to your site might be visually impaired such that they cannot see your images properly or at all.

Other visitors might be from a different culture and not understand the icons or diagrams you use.

Search engines only index text they don’t analyze images, which means that information stored in images cannot be found and indexed.
(At least, not yet: try searching “image indexing” or “search by image” for additional information regarding the latest on image indexing.)

*Content and background images

There are two main ways to add images to a document:

content images using the <img> element, and background images applied to elements using CSS.

*Which method you use depends on your intent:

If the image is crucial to the content of the document, such as a photo of the author or a data graph,
it should be added as an <img> element with proper alternative text.

If the image is there strictly for aesthetic purposes, you should use a CSS background image.
These images should not have any alternative text
(what use is the description “round green corner with a twinkle” to a blind person?) and you have more options for image styling in CSS.


![linkimg](https://www.miltonmarketing.com/wp-content/uploads/2018/03/mmhtmlimgtag424243image-tag-example.jpg)

**Note: The <img> element is what is known as an empty tag; that is, it does not require an end tag (like </img>).
**In HTML5, it need not even be closed with an internal slash (like <img src="balconyview.jpg"/>), 
**although many web page authors do so as a matter of consistency.
