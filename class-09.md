# FORMS - HTML 
**An HTML form is used to collect user input. The user input is most often sent to a server for processing.**
Creating forms is need to open the **form element** as the root of the form.
Which include all other form elements, such as :

*inputs* , *label* ,*textarea* ,*select* ,and *buttons*.
The form element requires you to pass two attributes, which are the ***action*** and ***method*** attributes.

The ***action*** attribute allows the developer to specify the URL where the form data will go.

The ***method*** attribute allows the developer to specify whether the form data should be sent via get or post.

  ## 1. The input Element
This element use to create 
1. text input fields.
1.  radio buttons.
1. checkboxes  . 

### IT WILL BE LIKE THE IMAGE BELOW 

![form](https://www.htmlgoodies.com/wp-content/uploads/2021/04/HTML-Form.png)

----------------------------------

# Styleing Lists

### For an unordered list you can use the following values:
 none
 disc
 circle
 square

### For an ordered (numbered) list you can use the following values:
1. decimal  ( 1 2 3 ) 
1. decimal-leading-zero ( 01 02 03 ) 
1. lower-alpha ( a b c ) 
1. upper-alpha ( A B C ) 
1. lower-roman (i. ii. iii.)
1. upper-roman  ( I II III )

-------
Example 
```
ol {
list-style-type: lower-roman;}
```

***We can use an image in the list***  

```
ul {
list-style-image: url("images/star.png");}
li {
margin: 10px 0px 0px 0px;}

```

# JAVASCRIPT - EVENTS
Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.
## onclick Event Type
accurs when a user clicks the left button of his mouse.

***Example***
```
<html> 
  <head>
       <script type = "text/javascript"> 
      <!-- function sayHello() 
      { alert("Hello World") } //--> </script> 
   </head>
    <body> 
       <form>
       <input type = "button" onclick = "sayHello()" value ="Say Hello"/>
       </form> 
    </body> 
</html> 
```

> `This Example make an alert displayed after button clicked`


## onmouseover and onmouseout Event Type
The onmouseover event triggers when you bring your mouse over any element 
and the onmouseout triggers when you move your mouse out from that element.
## onsubmit Event Type
onsubmit is an event that occurs when you try to submit a form. You can put your form validation against this event type.


 