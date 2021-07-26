# Basics of HTML, CSS & JS

## HTML (TEXT)

there are two types of texts on websites, the Headings in many sizes and paragraphs.

in HTML the headings have been styled in 6 sizes, the `<h1> </h1>` represent the largest size, which is always represented as the heading of the web page. the  `<h6> </h6>`  represent the smallest size of heading. and between them the `<h2>` , `<h3>` , `<h4>` and `<h5>` .

### Example 
theis is an Example of heading Levels

```
 <!--Doctype html-->
    <html>
    <body>
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
        <h6>Heading 6</h6>
    </body>
    </html>

```
the result will be 

![Headings](https://iq.opengenus.org/content/images/2019/08/img8.png)

-----
### Paragraphs in Html
to create a paragraph in HTML use `<p>` and close the tag by `</p>` after finish one paragraph.
inside the `<p>` you can change a little styles of texts , like bold , Italic , ect.

look at this table :

|       tag                  |   use                                     |        result                 |
|----------------------------|-------------------------------------------|-------------------------------|
| `<b>bold.</b>`             |  bold the text                            |  **bold**                     |
| `<i> Italic </i>`          | Italic the text                           |  *Italic*                     |
| `<sup>1</sup>`             | superscript the text                      |                               |
| `<sub>1</sub>`             | subscript the text                        |                               |
|`<p>hello1<br />hello2</p>` | add new line  between  hello1 and hello2  |                               | 




## CSS

CSS treats every HTML element as a one block.
> CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

 1. ***Selector*** 
 is the tag of element the style applied in it.

 1. ***Declaration***
 Declarations are contains of two parts (a property and a value).
    1. Property − A property is a type of attribute of HTML tag. 
    1. Value − Values are assigned to properties.

### Example 
`table{ border :1px}`
- **Selector** − table 
- **Property** − border
- **Value** − 1px

you can groupe more than one selector in same style.
#### Example

```h1, h2, h3 {color: yellow;}```

### TYPE OF SELECTORS
- element Selector
   Selects HTML elements based on the element name.


  `p {
     text-align: center; 
     color: red;
   }`

   
    In this example the style applied to all paragraphs in the HTML files 
   
- ID Selector
 The id selector uses the id attribute of an HTML element
 The id selector is used to select one unique element!
 To select an element with a specific id, write a hash (#) character, followed by the id of the element

  `#p1 {
  text-align: center;
  color: red;
  }
 `
 In this the style applied just to  single paragraph  how  have the attribute `id=p1`

-  class Selector
  The class selector selects HTML elements with a specific class attribute.
  To select elements with a specific class, write a period (.) character, followed by the class name.

  `.p1 {
    color: red;}
   .center {
  text-align: center;}`

  In the this example the style applied to every element have the class  name p1 
  And every elements have class name center 

- The CSS Universal Selector
  The universal selector (*) selects all HTML elements on the page of the element

  `*{
  text-align: center;  color: 000000;
  }`
In this example the style applied to all elements in the HTML files.

## Javascript
 in the previous class, we explain the javascript variables; how to declare the variable , variable datatypes, and assign them a value.


### so what is the rule of naming variables
1. The name must begin with a letter, dollar sign ($),or an underscore (_).not a number.
1. The name can contain 
   - letters
   - numbers
   - dollar sign ($)
   - an underscore (_).
   -   > Note that you must not use a dash(-) or a period (.) in a variable name. 
1. not a  keywords or reserved words.

1. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. 

















