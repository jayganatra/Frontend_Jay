## 1.Are the HTML tags and elements the same thing?
ans-HTML Elements are components that are used in HTML Page.HTML Tags are building blocks of HTML Page.
Elements are the combination of opening tags, content, and closing tags that define a particular structure or component on a webpage.
```
They consist of an opening tag (<tag>) and, optionally, a closing tag (</tag>).
Examples of HTML tags include <p>, <div>, <a>, <img>, <table>, <ul>, <li>, etc.
Examples of HTML elements include paragraphs (<p>), headings (<h1>, <h2>, etc.), links (<a>), images (<img>), tables (<table>), lists (<ul>, <ol>, <li>), etc.
```

-----
## 2 What are tags and attributes in HTML?
ANS-In HTML, tags and attributes play essential roles in defining the structure, content, and behavior of web pages.tag define the beginning and end of HTML elements.Attributes provide additional information about HTML elements.While the elements tell the browser what to display, the attributes define how they will behave. The tags mark the beginning and the end of an element. They may not be necessary for some elements, especially the closing tags. Equally important, the attributes are only within the opening tags.

Tag Example: <p> is the opening tag for a paragraph element, and </p> is its closing tag.
attributes Example: `In the <img> tag <img src="image.jpg" alt="Description">`

-----
## 3 What are void elements in HTML? With Example.
ans-void elements are elements that do not have a closing.A void element is an element in HTML that cannot have any child nodes.Void elements only have a start tag; end tags must not be specified for void elements.
tag.ex-img,br,input,p,link,etc
ex-`<img src="example.jpg" alt="Example Image">`

-----
## 4.What are HTML Entities? With Example.
ans-html Entities used to display reserved characters.HTML entities are special codes used to represent reserved characters in HTML documents.We use &entity_name; to add reserved characters using Entity names.

ex - &copy;
     &sect;	
     &para;	
----------------------------------------------------------------------------------------------------------------------------------------------
## 5\. What is the 'class' attribute in HTML? With Example.
ans-The class attribute specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet. However, it can also be used by a JavaScript (via the HTML DOM) to make changes to HTML elements with a specified class.

ex-```
     <!DOCTYPE html>
<html>
<head>
    <style>
        #header {
            background-color: #f0f0f0;
            padding: 10px;
        }

        .section {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<div id="header">
    <h1>Welcome to our Website</h1>
</div>

<div class="section">
    <h2>Section 1</h2>
    <p>This is the content of section 1.</p>
</div>

<div class="section">
    <h2>Section 2</h2>
    <p>This is the content of section 2.</p>
</div>

</body>
</html>
```

-----
## 6\.What is the difference between the 'id' attribute and the 'class' attribute of HTML elements? With Example.
ANS-id Attribute:
The 'id' attribute is used to uniquely identify an HTML element within the document.
Each 'id' attribute value must be unique within the HTML document.
It is often used to target specific elements for styling or scripting purposes.
Example: <div id="header">...</div>

class' Attribute:
The 'class' attribute is used to assign one or more class names to an HTML element.
Classes allow you to apply styles or behaviors to multiple elements on a page.
Multiple elements can share the same class, and an element can have multiple classes separated by spaces.
It is often used when you want to apply the same styles or behavior to multiple elements.
Example: <div class="section">...</div>

-----
## 7\.What are the various formatting tags in HTML?
ans-they are formating tag bold,italic,underline,subscript,strike etc.

-----
## 8 How is Cell Padding different from Cell Spacing? With Example.
ANS-Cell padding is used to create a border around the content area of a web page, where as cell spacing is used for positioning elements within that content area.
~~~
<table style="padding: 10px;">
    <tr>
        <td>This is a cell with padding</td>
    </tr>
</table>
~~~
~~~
<table style="border-spacing: 10px;">
    <tr>
        <td>Cell 1</td>
        <td>Cell 2</td>
    </tr>
</table>
~~~
## 9\. How can we club two or more rows or columns into a single row or column in an HTML table? With Example.
ANS-In HTML tables, you can merge multiple rows or columns into a single row or column using the rowspan and colspan attributes.
These attributes allow you to span a cell across multiple rows or columns, effectively combining them into a single unit.
~~~
<table border="1">
    <tr>
        <td rowspan="2">Header 1</td>
        <td colspan="2">Header 2 and 3</td>
        <td>Header 4</td>
    </tr>
    <tr>
        <td>Header 5</td>
        <td>Header 6</td>
        <td>Header 7</td>
~~~

-----
## 10\. What is the difference between a block-level element and an inline element?
ANS- Block level element areHTML elements that start on a new line and
typically the full width available to them. ex-

    ex-table,form,div,p etc
     Inline elements do not start on a new line and only take up as much width as necessary.
-----
## 11\. How to create a Hyperlink in HTML? With Example.
ans- hyperlink using the `<a>`{=html} (anchor) element.

ex-`<a href="https://www.example.com">`{=html}Visit Example
Website`</a>`{=html}

-----
\## 12. What is the use of an iframe tag? With Example.

ans-`<iframe>`{=html} tag in HTML is used to embed another HTML
document.

ex-\
`<iframe width="560" height="315" src="https://www.youtube.com/embed/h45UL-dRZz8?si=vscHSJ7LrbgUi2rw"  title="YouTube video player" frameborder="0"  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>`{=html}
`</iframe>`{=html}

-----
## 13\.What is the use of a span tag? Explain with example?
ans-The `<span>`{=html} tag in HTML is an inline element used to group
and apply styles to inline elements.

ex-
~~~ {=html}
<p>
~~~

This is a [highlighted]{.ex} text.
~~~ {=html}
</p>
~~~

-----
\## 14.How to insert a picture into a background image of a web page?
With Example.

ans-embed the images directly into the HTML.

ex- `<img src="logo.png">`{=html}

-----
\## 15. How are active links different from normal links?

ans-active links and normal links refer to different states of
hyperlinks based on user interaction.

-----
## 14\.What are the different tags to separate sections of text?
ans- you can use to structure of your
content.div,p,h1,section,artical,heder,nav etc.

-----
## 15\.What is SVG?
ans-SVG stands for Scalable Vector Graphics.it used to describe
two-dimensional vector graphics.

-----
## 16\. What is difference between HTML and XHTML?
ans-HTML (Hypertext Markup Language) and XHTML (Extensible Hypertext
Markup Language) are both markup languages used to create web pages.

-----
## 17\. What are logical and physical tags in HTML?
ans-logical
~~~ {=html}
<header>
~~~

,
~~~ {=html}
<nav>
~~~

,
~~~ {=html}
<main>
~~~

,
~~~ {=html}
<article>
~~~

,
~~~ {=html}
<section>
~~~

,
~~~ {=html}
<aside>
~~~

,
~~~ {=html}
<footer>
~~~

,
~~~ {=html}
<h1>
~~~

to
~~~ {=html}
<h6>
~~~

,
~~~ {=html}
<p>
~~~

,
~~~ {=html}
<ul>
~~~

,
~~~ {=html}
<ol>
~~~

,
~~~ {=html}
<li>
~~~

,
~~~ {=html}
<table>
~~~

,
~~~ {=html}
<form>
~~~

, etc.

physical `<font>`{=html}, `<b>`{=html}, `<i>`{=html}, `<u>`{=html},
`<strike>`{=html},
~~~ {=html}
<center>
~~~

, `<big>`{=html}, `<small>`{=html}, `<br>`{=html},
~~~ {=html}
<hr>
~~~

, etc.
