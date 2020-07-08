### LINKS 

To insert a link, the tag that we're going to use is very easy to remember: <a>. However, an attribute, href, to it to indicate the page the link should lead to.
  
For example, the code below is a link that leads to Google, located at the address http://www.google.com:

<a href="http://www.google.com">Google</a>

We're going to include this link in a paragraph. So here's how you reproduce the example in the next figure:

<p>Hello. Do you want to visit the website <a href="http://www.google.com">Google</a>?<br />
It's a good website! ;-)</p>

By default, the link is highlighted in blue. If you've already opened the page, the link is displayed in purple.

We'll see how to change this appearance when we study CSS.

f you want to make a link to another site, you can just copy its address (called a URL) inhttp://.

Note that some links sometimes start withhttps://(secure websites) or other prefixes (ftp://, etc.).

*The links that we have seen are called absolute links since the full address is shown.
We are now going to see that we can write the links in a somewhat different way which will be useful for making links between the pages of our website.


![linksimg](https://sdz-upload.s3.amazonaws.com/prod/upload/relative_links.png)


### layouts 

HTML layouts provide a way to arrange web pages in well-mannered, well-structured,
and in responsive form or we can say that HTML layout specifies a way in which the web pages can be arranged.
Web-page layout works with arrangement of visual elements of an HTML document.

Web page layout is the most important part to keep in mind while creating a website so that our website can appear professional with the great look.
You can also use CSS and JAVASCRIPT based frameworks for creating layouts for responsive and dynamic website designing.

![linkimg2](https://static.javatpoint.com/htmlpages/images/html-layouts.png)

#### Absolute v. relative positioning

As far as I can tell, there are two ways to do this. Both make use of the basic “absolute” and “relative” positioning attributes.
Where a lot of people get this wrong is that the CSS Box Model defines a position:absolute block as absolute relative to its containing block,
and not relative to the page or window.



*example :

/*  #top-section {
  position:relative;
  left:0;
  top:0;
  }
  #mid-section {
  position:relative;
  left:0;
  top:0;
  }
  #bottom-section {
  position:relative;
  left:0;
  top:0;
  }*/

