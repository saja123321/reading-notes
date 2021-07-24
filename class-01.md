# Creating Websites

### How the Web Works

The website is hosted on a web server, this web server is located anywhere in the world. so to find the location of this web server you need to connect your browser to the DNS.

## HTML
### _Html Elements_

Every element have a starting tag and ending tag like that:

`<tag> content  </tag>`
#### Example 

`<html> </html>`

### _HTML ELEMENT WITH TAG ATTRIBUTES_

- A tag has a name (for instance, p, img, h1, br, or hr) and that name combined with attributes will describe how the browser should handle the content.
- Attributes set in a starting tag like that :

![attributes](https://www.computerhope.com/jargon/h/html-tag.gif)

> An opening tag can have any number of attributes associated with it.


### _COMMENTS IN HTML_

- Comments used  to provide information within an HTML document to be ignored and not shown to the end user.
- These are useful for notes and documentation to aid anyone who might read or amend the source of the HTML document. 
- Comments, in HTML, can be single line or multiline.

**Singleline comment**


`<-- Comment on a single line -->`

**Multiline comment**

`<!--
This comment is over multiple lines.
Comments can be used to inform 
and for detailed documentation.
-->`


### _What is the different bettwen HTML4 and HTML5_ ?

HTML5 was released with the primary objective of improving the World Wide Web experience for developers and end-users.

There are multiple new features and new elements in HTML5. Some of the most important ones are summary, time, aside, audio, command, data, datalist, and so on.

here is list of  HTML4 tags and their latest versions in HTML5


| HTML4                      |     HTML5                        | discription                                                                |
|----------------------------|----------------------------------|----------------------------------------------------------------------------|
|  `<div id=”header”>`       |           `<header>`             |  describe the header or top area of a web page.                            |
| `<div id=”menu”>`          |            `<nav>`               | contain a list of page links for the different pages of the website.       |
|  `<div id=”content”>`      |            `<section>`           |to divide some of the markup into a logical section of the page.            |
| `<div id=”post”>`          |             `<article>`          |                                                                            |
| `<div id=”footer”>`        |             `<footer>`           |  the bottom of a web page.                                                 |


# Introduction to Javascript

#### first, **WHY** we need tO learn javascript, not another language? 

1. Other Languages must be compiled to run, but JavaScript doesn’t have to compile its run as-is.
1. JavaScript is one of three fundamental languages of the web.
(we know the two other is Html and CSS)
This three language is different than each other of there purpose and function, but they are integrated together.

 
in programming, every physical thing is presented as an object. did you remember the variable, we say that each variable has one value.
objects are like variables but the objects can obtain many values.

### Accessing Object Properties

You can access object properties in two ways:

1. `objectName.propertyName`

1. `objectName["propertyName"]`

### HOW TO PUT A JAVASCRIPT INTO AN HTML PAGE?


JavaScript statements are placed within the `<script>... </script>` HTML tags in a web page. The <script> tag alerts the browser program to start interpreting all the text between these tags as a script. 

A simple syntax of your JavaScript will appear as follows.
The script tag takes two important attributes 
  * Language : its value will be `"javascript"`. 
  * Type : the value should be set to `"text/javascript"`.

Scripts can also be placed in external files:

the file extension is  .js. The why to link he external file with the html file :

`<script src="myScript.js"> </script>`






