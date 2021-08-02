# CSS Layout

***CSS has the following positioning schemes that allow you to control the layout of a page:***

## Normal Flow 
This is the default behavior of the css element.

Every element locates on a new line, each item locates lower down than the previous one.

## Relative Positioning
Relative is positioned relative to its normal position of the element.

```
div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}
```

this image will explain the defferance bettwen the `Relative` ,`Absoute` ,`Relatively Absolutw` and `Fixed`

![relative](https://www.internetingishard.com/html-and-css/advanced-positioning/css-positioning-schemes-summary-d7f831.png)

## Absolute positioning
The element is positioned relative to its first positioned (not static) ancestor element.

You use the positioning attributes **`top`** , **`left`**, **`bottom`**, and **`right`** to set the location. Remember that these values will be relative to the next parent element with relative (or absolute) positioning

## Fixed Positioning

A fixed position element is positioned relative to the  browser window itself.

The viewport doesn’t change when the window is scrolled, so a fixed positioned element will stay right where it is when the page is scrolled.


## Floating Elements

The floated element becomes a block-level element around which other content can flow.

-------------------
***your design needs to be able to work on a range of different sized screens. because Different visitors to your site will have different-sized screens that show different amounts of information.***
You have keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).

-------------

### A Liquid Layout

![liquid](https://3wga6448744j404mpt11pbx4-wpengine.netdna-ssl.com/wp-content/uploads/2014/07/liquid.png)

--------
```
This is the way I always used to design my web pages 
in my opinion, it's an easier one. 
```

The **`Liquid Layout`** is used to make the web page shown in different screen sizes without change the layout of the page.
## so how its work ?
you need to make the width of each element by a percentage 
that's mean that the width of the element depending on the screen width. 
