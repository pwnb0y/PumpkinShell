# HTML Cheat Sheet
## Introduction
HTML stands for Hypertext Markup Language.HTML (Hypertext Markup Language) has come a long way since Tim Berners-Lee invented it back in 1991.HTML describes the structure of a Web page. HTML consists of a series of elements. HTML elements tell the browser how to display the content.
Today HTML5 is the standard version and it's supported by all modern web browsers. Our HTML cheat sheet gives you a full list of all the HTML elements, including descriptions, code examples.

## LIST OF HTML ELEMENTS
An HTML element (or tag) is an individual component of an HTML document.

### 1. HTML TAG
Specifies an html document. The HTML ```<html>``` element (or HTML root element) represents the root of an HTML document.

#### Code example :
```
<!DOCTYPE html>
<html>
  <head>...</head>
  <body>...</body>
</html>
```

### 2. BASE TAG
Specifies URL which non-absolute URLs are relative to. The HTML ```<base>``` element speciတဠes the base URL to use for all relative URLs contained within a document.

#### Attributes (modifiers)
```href | target (_self | _blank | _parent | _top) + global attributes```

#### Code example :
```
<base href="http://www.google.com" >
```
### 3. HEAD TAG
First element of the HTML document. Collection of metadata for the
Document. The HTML ```<head>``` element provides general information
(metadata) about the document, including its title and links to its
scripts and style sheets.

### Code example :
````
<html>
  <head>
    <title>Document title</title>
  </head>
</html>
````
####4. LINK TAG
The HTML ```<link>``` element
specifies relationships between the current document and an external resource.This Element is most used to
link to style sheets.

#### Attributes (modifiers)
```href | rel | media | hre†lang | type | sizes | crossorigin | integrity```

#### Code example :
```<link href="style.css" rel="stylesheet">```

### 5. META TAG
The HTML ```<meta>``` element represents any metadata information that cannot be represented by one of the other HTML meta-related
elements (```<base>, <link>, <script>, <style> or <title>```).

### Attributes (modiတဠers)
```charset | content | http-equiv | name```

### Code example : 
```<meta charset="utf‐8">```

### 6. STҮLE TAG
The HTML ```<style>``` element contains style information for a document, or part of a document.

### Attributes (modiတဠers)
```media | type | title```

### Code example :
````
<style type="text/css">
body {
  color:red;
}
</style>
````

### 7. TITLE TAG
The HTML ```<title>``` element defines the title
of the document, shown in a browser's title bar or on the page's tab.

### Code example:
```<title>This is the page title</title>```

### 8. ARTICLE TAG
The HTML ```<article>``` element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable.

### Code example :
````
<article class="ureview">
      <p>I love this tool.</p>
      <footer>
        <p>
          Posted on <time datetime="12-01-22
10:00">May 1ɭ</time> by Matt.
        </p>
      </footer>
    </article>
````

### 9. BODҮ TAG
The HTML ```<body>``` Element
represents the content of an HTML document. There can be only one``` <body>``` element in a document.

### Code example
````
<html>
<head>
  <title>Here goes the title of the document</title>
</head>
<body>
  Here goes the he content of the document......
</body>
</html>
````

### 10. FOOTER TAG
The HTML <footer> element
represents a footer for its nearest sectioning content or sectioning root element.
Note :-> A footer typically contains information about the author of the section, copyright data or links to related documents.

### Code example :
```<footer>Some copyright info goes here</footer>```

### 11. H1 TO H6 TAG
Heading elements implement six levels of document headings, ```<h1>``` is the most important and ```<h6>``` is the least.

### Code exapmle :
````
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>
  ````

#### 12. NAV TAG
The HTML ```<nav>```
element (HTML Navigation Element) represents a section of a page that links to other pages or to parts within the page: a section with
navigation links.

#### Code example :
````
  <nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About us</a></li>
    <li><a href="#">Contact us</a></li>
  </ul>
</nav>
 ````

#### 13. SECTION TAG
The HTML ```<section>``` element represents a generic section of a document, i.e., a thematic grouping of content, typically with a
heading. Each ```<section>``` should be identified, typically by including a heading ```<h1>-<h6>``` element as a child of the ```<section>``` element.

#### Code example :
````
<section><hɨ>Heading</hɨ><p>Bunch of awesome content</p></section>
  ````

#### 14. BR TAG
The HTML element line break ```<br>``` produces a line breakvin text. It is useful for writing a poem or an address, where the division of lines is significant.

#### Code example :
````
  <p>Pawan Kumar<br>Jha<br>Mumbai</p>
  ````

#### 15. DIV TAG
Container or section with no semantic meaning. The HTML ```<div>``` element (or HTML Document Division Element) is the generic container for flow content.

#### Code example :
```
  <div><p>Any kind of content here. Such as <p>, 
<table>. You name it!</p></div>
  ```

#### 16. LI TAG
List item. The HTML ```<li>``` element (or HTML List Item Element) is used
to represent an item in a list.

#### Code example :
````
  <ol>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ol>
  ````
#### 17. P TAG
Paragraph content. The HTML ```<p>``` element (or HTML Paragraph Element) represents a paragraph of text.

#### Code example : 
````
  <p>This is the first paragraph of text.</p>
<p>This is second paragraph of text.</p>
  ````

#### 18. UL TAG
Unordered list. The HTML ```<ul>``` element (or HTML Unordered List Element) represents an unordered list of items, namely a collection
of items that do not have a numerical ordering, and their order in the list is meaningless.

#### Code example :
````
  <ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ul>
  ````

#### 19. A TAG
Hyperlink (a hypertext anchor). The HTML Anchor Element (```<a>``` tag)
defines a hyperlink to a location on the same page or any other page on the Web.

#### Code example :
````
 <a	href="www.google.com">Review it</a>
 ````

#### 20. EM TAG
Text that should be emphasized.The ```<em>``` element can be nested, with each level of nesting indicating a greater degree of emphasis.

#### Code example :
````
 <p>In HTML ɬ, what was previously called 
<em>block‐level</em> content is now called 
<em>flow</em> content.</p>
````

### 21. MARK TAG
Text highlighted for referencing elsewhere. The HTML Mark Element ```<mark>``` represents highlighted text, i.e., a run of text marked for reference purpose, due to its relevance in a particular context.

### Code example : 
````
<p>The <mark> element is used to <mark>highlight</mark> text</p>
````

### 22. SPAN TAG
Container with no semantic meaning. The HTML ```<span>``` element is a generic inline container for phrasing content, which does not inherently represent anything.

### Code example :
```
<p><span>Some text</span></p>
 ````

### 23. STRONG TAG
Text that is important. The HTML Strong Element ```<strong>``` gives text strong importance, and is typically displayed in bold.

### Code example : 
````
<p>When doing x it is 
<strong>imperative</strong> to do y before 
proceeding.</p>
  ````

### 24. TABLE TAG
Table of multi-dimensional data. The HTML Table Element ```<table>``` represents tabular data.

### Code example :
````
  <table>
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$10</td>
  </tr>
</table>
  ````

### 25. TD TAG
Table cell. The Table cell HTML element ```<td>``` deတဠnes a cell of a table
that contains data. It participates in the table model.

### Code example :
 ````
  <tr>
    <td>January</td>
    <td>$ɨ00</td>
 </tr>
  ````

### 26. BUTTON TAG
A button. The HTML ```<button>``` Element represents a clickable button.

### Code example :
````
 <button name="button">I am a button. Click me!</button>
  ````

### 27. FORM TAG
The HTML ```<form>```element represents a document section that contains interactive
controls to submit information to a web server.

### Code example :
````
  <form action="" method="post">
  <fieldset>
    <legend>Title</legend>
    <input type="radio" id="radio"> <label 
for="radio">Click me</label>
  </fieldset>
</form>
  ````

### 28. INPUT TAG
Generic form input. The HTML element ```<input>``` is used to create interactive controls for web-based forms in order to accept data from the user.

### Code example :
````
 <input type="text" value="Type here">
  ````

### 29. LABEL TAG
Caption for a form control. The HTML Label Element ```<label>```represents a caption for an item in a user interface.

### Code example :
````
 <label>Click me <input type="text"></label>
 ````

### 30. OPTION TAG
Single option within a select control. In a Web form, the HTML ```<option>``` element is used to create a control representing an item
within a ```<select>```, an ```<optgroup> ```or a <datalist> HTML5 element.

### Code example :
````
 <select name="select">
  <option value="value1">Value ɨ</option> 
  <option value="value2" selected>Value 
ɩ</option>
  <option value="value3">Value ɪ</option>
</select>
  ````

### 31. SELECT TAG
Control for selecting from multiple options. The HTML select ```<select>``` element represents a control that presents a menu of options.

### Code example :
````
  <select name="select">
  <option value="value1">Value ɨ</option> 
  <option value="value2" selected>Value 
ɩ</option>
  <option value="value3">Value ɪ</option>
</select>
  ````

### 32. TEXTAREA TAG
Multiline free-form text input. The HTML ```<textarea>``` element represents a multi-line plain-text editing control.

### Code example :
````
 <textarea name="textarea" rows="10" cols="10">Write something here</textarea>
  ````

### 33. IFRAME TAG
Nested browser frame. The HTML Inline Frame Element ```<iframe>```represents a nested browsing context, effectively embedding another HTML page into the current page.

### Code example : 
````
  <iframe src="http:www.example.com/iframe‐example" width="ɫ00" height="ɪ00">
  <p>Your browser does not support iframes.</p>
</iframe>
  ````

### 34. IMG TAG
An image. The HTML ```<img>``` element represents an image in the document.

### Code example :
```
 <img src="logo‐sm.png" alt="Img Tag">
````

### 35. AUDIO TAG
Sound or audio stream. The HTML ```<audio>``` element is used to embed sound content in documents.

### Code example :
````
  <audio 
src="http://developer.mozilla.org/@api/deki/fi
les/ɩɰɩɭ/=AudioTest_ſɨƀ.ogg" autoplay>
  Your browser does not support the 
<code>audio</code> element.
</audio>
 ````

### 36. VIDEO TAG
Used for playing videos or movies. Use the HTML ```<video>``` element to embed video content in a document.

### Code example :
````
  <video src="videofile.webm" autoplay poster="posterimage.jpg">
  Sorry, your browser doesn't support embedded 
videos, 
  but don't worry, you can <a 
href="videofile.webm">download it</a>
  and watch it with your favorite video 
player!
</video>
 ````

### 37. CANVAS TAG
The HTML ```<canvas>```
Element can be used to draw graphics via scripting (usually JavaScript).

### Code example :
````
  <canvas id="canvas" width="100" height="100">An alternative text describing 
what your canvas displays.</canvas>
````

### 38. SCRIPT TAG
Inline or linked client side scripts. The HTML Script Element ```<script>```is used to embed or reference an executable script within an HTML or XHTML document.

### Code example :
````
<script src="javascript.js"></script>
````

### Thank You





