# HTML TABLES

## Table elements:
1. tr tag ```to define table rows.```
 1. td tag ```to define table data/cell.```
 1. th tag ```to define table header and its take a deflt style bold```.

## Example 
``` 
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

--------------

## Javascript Object Constructor Notation
In constructor notation, we are creating the same dogs we created in literal notation above, by calling the constructor function with the “new” keyword.

![object](https://miro.medium.com/max/875/1*AlFcybVX3m9yXz01LcWa_A.png)

### Methods and properties with object literal and constructor notation

Objects in JavaScript have methods and properties, whether they are built with the constructor function or with the literal notation. In JavaScript, the keyword called ‘this’ is the object that “owns” the code. The value of this, when used in an object, is the object itself. Let’s see how to define them:

![method](https://miro.medium.com/max/875/1*2s2U-uXrRGFrkqYaFhBBUA.png)

## ‘this’ Keyword

The JavaScript ‘this’ keyword refers to the object it belongs to. The value of ‘this’ differs depending on how a function is invoked, so we can’t know the value of ‘this’ just by looking at the function itself, but we need to know the context in which the function is invoked.

## USING THE DOCUMENT OBJECT