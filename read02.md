### HTML TEXT 

When creating a web page, you add tags (known as markup) to the contents of the page.
These tags provide extra meaning and allow browsers to show users the
appropriate structure for the page.

*headings: 

h1 is used for main headings

h2 is used for subheadings


h3 If there are further sections under the subheadings
and so on till the 

h6 element is the smallest.

The exact size at which each browser shows the headings can vary slightly.
Users can also adjust the size of text in their browser.

![headings](https://www.tutorialrepublic.com/lib/images/html/html-headings.png)



#### Paragraphs



paragraph tag <p> should surround every paragraph of text in your content.
Multiple line breaks in your source code (without the <br> line-break tag) will not display as line breaks on-page.
In order to get proper display spacing between paragraphs of text, you should use the <p> tag.

#### Strong & Emphasis

Many HTML elements have been designed to add semantic meaning to the content of a webpage. What this means, 
is that certain HTML elements imply a specific meaning with regard to the contents of the element.

For example, the use of emphasis tags, em, 
is rendered by a browser using an italic font and implies that the contents of the element should be read and understood with greater emphasis than surrounding content
While not all HTML elements carry semantic meaning, it is important to use HTML tags according to their semantic meaning whenever possible.

#### Definitions, Quotes, Acronyms


There are several very helpful span-level markup elements that are never used.

These provide fine-grain information about the word on your page. They can help users better understand your content,
and they can help computers (search engines, artificial intelligence) make better sense of what you have written.

dfn The definition tag. This can be for the first time you use and define a technical term.
abbr Used for abbreviations. You can put the expanded form of the abbreviation in the title tag.
q Most people just use typographical quote marks to delineate quotations, 
but using the markup makes it more explicit, and allows you to reference the source of the quote with the <cite> element.

![abbrImg](https://i.ytimg.com/vi/yN191Pkg4kg/maxresdefault.jpg)

#### What are Block elements?


Block-level elements are HTML elements which have width and height and (by default) a line break before and after.
They represents blocks of content. 
(This is in contrast to inline elements, which represent spans of text and do not create new lines by default.)



  
 
  ### CSS 
  
  Stands for "Cascading Style Sheet." Cascading style sheets are used to format the layout of Web pages.
  They can be used to define text styles, table sizes, and other aspects of Web pages that previously could only be defined in a page's HTML.
  
  CSS helps Web developers create a uniform look across several pages of a Web site. 
  Instead of defining the style of each table and each block of text within a page's HTML, 
  commonly used styles need to be defined only once in a CSS document.
  
  there are 3 ways you can link the css to your html :
  
  * href
  
  * type
  
  * rel
  
  #### css selectors
  
  ![selectorimg](https://i1.wp.com/learn-automation.com/wp-content/uploads/2015/12/Css-Selector-Table.png?resize=1024%2C395)
  
  *Why use External Style Sheets?
  
  *Advantages of External CSS:
  Since the CSS code is in a separate document, your HTML files will have a cleaner structure and are smaller in size.
  You can use the same .css file for multiple pages.

  *Disadvantages of External CSS:
  Your pages may not be rendered correctly until the external CSS is loaded.
  Uploading or linking to multiple CSS files can increase your site’s download time.



### Java script

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.

*WHAT IS A VARIABLE?
A script will have to temporarily store the bits of information it
needs to do its job. It can store this data in variables.

When you write JavaScript, you have to tell the interpreter every individual step that you want it toperform.
This sometimes involves more detail than you might expect.

![var](https://tutorial.techaltum.com/images/js-variables.jpg)

JavaScript distinguishes between numbers,strings, and true or false values known as Booleans.

* NUMERIC DATA TYPE The numeric data type handles numbers.
0.75


* STRING DATA TYPE The strings data type consists of letters and other characters.
'H.1 ' Ivy! 

* BOOLEAN DATA TYPE
Boolean data types can have one of two va lues: true or false.
**true


#### CHANGING THE VALUE OF A VARIABLE

Once you have assigned a value
to a variable, you can then
change what is stored in the
variable later in the same script.
Once the variable has been
created, you do not need to
use the var keyword to assign
it a new value. You just use the
variable name, the equals sign
(also known as the assignment
operator), and the new va lue for
that attribute.
