# HTML_Assignment_7

               Assignment 7

Ques -1 What are inline and bock elements in HTML and the difference between them ? name a few inline elements and block elements

Ans 

Block Elements:-

1-Block elements always start from a new line.

2-Block elements cover space from left to right as far as it can go.

3-Block elements have top and bottom margins

Examples of block elements - <p>,<div>,<hr> .

Inline Elements:-

1-Inline elements never start from a new line.

2-Inline elements only cover the space as bounded by the tags in the HTML element.

3-Inline elements don't have a top and bottom margin.

Examples of inline elements - <span>,<br>

Quese- 2 

How to work with images in HTML and explain in details <img/>tag important attributes 

Ans

How to insert an image:

<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">

ADVERTISEMENT
Good Morning Friends
Attributes of HTML img tag
The src and alt are important attributes of HTML img tag. All attributes of HTML image tag are given below.

1) src

It is a necessary attribute that describes the source or path of the image. It instructs the browser where to look for the image on the server.

The location of image may be on the same directory or another server.

2) alt

The alt attribute defines an alternate text for the image, if it can't be displayed. The value of the alt attribute describe the image in words. The alt attribute is considered good for SEO prospective.

3) width
It is an optional attribute which is used to specify the width to display the image. It is not recommended now. You should apply CSS in place of width attribute.

4) height
It h3 the height of the image. The HTML height attribute also supports iframe, image and object elements. It is not recommended now. You should apply CSS in place of height attribute.

Ques -3 how to create list in html

Ans 

HTML offers web authors three ways for specifying lists of information. All lists must contain one or more list elements. Lists may contain −

<ul> − An unordered list. This will list items using plain bullets.

<ol> − An ordered list. This will use different schemes of numbers to list your items.

<dl> − A definition list. This arranges your items in the same way as they are arranged in a dictionary.

!DOCTYPE html>
<html>

   <head>
      <title>HTML Unordered List</title>
   </head>
	
   <body>
      <ul>
←ul type = "square">
<ul type = "disc">
<ul type = "circle">--->

         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
      </ul>
   </body>
   
</html>



<!DOCTYPE html>
<html>

   <head>
      <title>HTML Ordered List</title>
   </head>

   <body>
      <ol>
         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
      </ol>
   </body>

</html>



<!DOCTYPE html>
<html>

   <head>
      <title>HTML Definition List</title>
   </head>
	
   <body>
      <dl>
         <dt><b>HTML</b></dt>
         <dd>This stands for Hyper Text Markup Language</dd>
         <dt><b>HTTP</b></dt>
         <dd>This stands for Hyper Text Transfer Protocol</dd>
      </dl>
   </body>
	
</html>


Ques- 4 How to interlink webpages and navigate people to other websites


Ans 

Linking in HTML code is done with the anchor tag, the <A> tag. The letter "A" in the tag is then followed by an attribute. For a link to another web page, the "A" is followed by "HREF". To set a bookmark in the same page, the "A" is followed by "NAME", which you'll see how to do later.

Take a look at this example, which is a link to the popular search engine Google:

<A HREF = "http://www.google.com/">Google Search Engine</A>





