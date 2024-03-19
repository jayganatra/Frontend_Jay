## 1.Are the HTML tags and elements the same thing?

ANS-P,A,BR,HERF,IMG,I,U,B ETC.

------------------------------------------------------------------------

## 2 What are tags and attributes in HTML?

ANS-attribute is additional information about your tag .tag hold the
HTML element.

------------------------------------------------------------------------

## 3 What are void elements in HTML? With Example.

ans-void elements are elements that do not have a closing
tag.ex-img,br,input etc
ex-`<img src="example.jpg" alt="Example Image">`{=html}

------------------------------------------------------------------------

## 4.What are HTML Entities? With Example.

ans-html Entities used to display reserved characters.ex -
```{=html}
<p>
```
,`<i>`{=html} ex-
```{=html}
<p>
```
This is an example of using HTML entities
```{=html}
</p>
```

------------------------------------------------------------------------

## 5. What is the 'class' attribute in HTML? With Example.

ans-class attribute is used to assign one or more class names to an
element.

-Classes are used to apply styles or behaviors to multiple elements on a
page

ex-
```{=html}
<p>
```
This is a [highlighted]{.highlight} text.
```{=html}
</p>
```

------------------------------------------------------------------------

## 6.What is the difference between the 'id' attribute and the 'class' attribute of HTML elements? With Example.

ANS-The id attribute and the class attribute are both used in HTML
elements to provide additional information about the element,but they
serve different purposes.


    <div id="header">
        <h1>Welcome to our Website</h1>
    <div class="s">
        <p class="s">This is an important message.</p></div>
        

------------------------------------------------------------------------

## 7.What are the various formatting tags in HTML?

ans-they are formating tag bold,italic,underline,subscript,strike etc.

------------------------------------------------------------------------

## 8 How is Cell Padding different from Cell Spacing? With Example.

ANS-space between the content of a cell and the cell's border


    EX-<style>
        table {
            padding: 10px;
        }
    </style>
    <table>
        <tr>
            <td>This is a cell with padding</td>
        </tr>
    </table>

## 9. How can we club two or more rows or columns into a single row or column in an HTML table? With Example.

ANS-you can merge multiple rows or columns into a single row or column
using the rowspan and colspan .


    EX-<table border="1">
        <tr>
            <td rowspan="2">Row 1, Column 1</td>
            <td>Row 1, Column 2</td>
        </tr>
        <tr>
            <!-- This cell will be merged with the cell above -->
            <td>Row 2, Column 2</td>
        </tr>
        <tr>
            <td>Row 3, Column 1</td>
            <td>Row 3, Column 2</td>
        </tr>
    </table>

------------------------------------------------------------------------

## 10. What is the difference between a block-level element and an inline element?

ANS- Block level element areHTML elements that start on a new line and
typically the full width available to them. ex-

    ex-table,form,div,p etc
     Inline elements do not start on a new line and only take up as much width as necessary.

------------------------------------------------------------------------

## 11. How to create a Hyperlink in HTML? With Example.

ans- hyperlink using the `<a>`{=html} (anchor) element.

ex-`<a href="https://www.example.com">`{=html}Visit Example
Website`</a>`{=html}

------------------------------------------------------------------------

\## 12. What is the use of an iframe tag? With Example.

ans-`<iframe>`{=html} tag in HTML is used to embed another HTML
document.

ex-\
`<iframe width="560" height="315" src="https://www.youtube.com/embed/h45UL-dRZz8?si=vscHSJ7LrbgUi2rw" 
    title="YouTube video player" frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>`{=html}
`</iframe>`{=html}

------------------------------------------------------------------------

## 13.What is the use of a span tag? Explain with example?

ans-The `<span>`{=html} tag in HTML is an inline element used to group
and apply styles to inline elements.

ex-
```{=html}
<p>
```
This is a [highlighted]{.ex} text.
```{=html}
</p>
```

------------------------------------------------------------------------

\## 14.How to insert a picture into a background image of a web page?
With Example.

ans-embed the images directly into the HTML.

ex- `<img src="logo.png">`{=html}

------------------------------------------------------------------------

\## 15. How are active links different from normal links?

ans-active links and normal links refer to different states of
hyperlinks based on user interaction.

------------------------------------------------------------------------

## 14.What are the different tags to separate sections of text?

ans- you can use to structure of your
content.div,p,h1,section,artical,heder,nav etc.

------------------------------------------------------------------------

## 15.What is SVG?

ans-SVG stands for Scalable Vector Graphics.it used to describe
two-dimensional vector graphics.

------------------------------------------------------------------------

## 16. What is difference between HTML and XHTML?

ans-HTML (Hypertext Markup Language) and XHTML (Extensible Hypertext
Markup Language) are both markup languages used to create web pages.

------------------------------------------------------------------------

## 17. What are logical and physical tags in HTML?

ans-logical
```{=html}
<header>
```
,
```{=html}
<nav>
```
,
```{=html}
<main>
```
,
```{=html}
<article>
```
,
```{=html}
<section>
```
,
```{=html}
<aside>
```
,
```{=html}
<footer>
```
,
```{=html}
<h1>
```
to
```{=html}
<h6>
```
,
```{=html}
<p>
```
,
```{=html}
<ul>
```
,
```{=html}
<ol>
```
,
```{=html}
<li>
```
,
```{=html}
<table>
```
,
```{=html}
<form>
```
, etc.

physical `<font>`{=html}, `<b>`{=html}, `<i>`{=html}, `<u>`{=html},
`<strike>`{=html},
```{=html}
<center>
```
, `<big>`{=html}, `<small>`{=html}, `<br>`{=html},
```{=html}
<hr>
```
, etc.
