# **CSS**

![CSS](https://cdn.iconscout.com/icon/free/png-256/css-131-722685.png)

** CSS referred to cascading Style Sheets **

### HOW TO INSERT CSS? 

* ### three ways of inserting a style sheet:
    1. **External CSS**
       - Creating text file and save at as css sheet ,and in HTML file we call the css file in link tag in head section       
    1. **Internal CSS**
       - CThe internal style is defined inside the
        ><style> </style> element, inside the head section.
    1. **Inline CSS**
      - Add the style attribute to the relevant element.


        
### CSS SYNTAX

A style rule is made of three parts :

1. Selector − A selector is an HTML tag at which a style will be applied. 
1. Property − A property is a type of attribute of HTML tag. 
1. Value − Values are assigned to properties.
#### Ex :

```

table{ border :1px}

```

- _**Selector**_ − table 
- _**Property**_ − border
-  _**Value**_ − 1px



### CSS COLOR

***A color can be specified by many format***


Format             |       Syntax         |
-------------------|----------------------|
Hex Code           |       #RRGGBB        |
Short Hex Code     |       #RGB           |
RGB %              |  rgb(rrr%,ggg%,bbb%) |
RGB Absolute       |   rgb(rrr,ggg,bbb)   |
keyword            |  aqua, black, etc.   |


**Example to apply a bg color to paragraph in deafferent way:**
```
p{background-color :#000000;}
```

```
p{background-color :#000;}

```

```
p{background-color :rgb(0%,0%,0%);}
```
```
p{background-color :rgb(0,0,0);}
```

```
p{background-color :black;}
```


### CSS FONTS

- **font-family** property is used to change the face of a font.
- **font-style** property is used to make a font italic or oblique.
- **font-variant** property is used to create a small-caps effect.
- **font-weight** property is used to increase or decrease how bold or light a font appears.
- **font-size** property is used to increase or decrease the size of a font.



[**Back to Html**](https://saja123321.github.io/reading-notes/read03)