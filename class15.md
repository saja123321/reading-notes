# CSS Transforms
## 2D Rotate 

-------------------------
![Transform](https://res.cloudinary.com/dno0vkynk/image/upload/v1475392871/CSS3Transforms2D.png)
------------------------

#### To add a rotate to any element 

```
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```

# Scale Size 
```.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}
```

# Spacific Scale in X or Y

```
.box-1 {
  transform: scaleX(.5);
}
.box-2 {
  transform: scaleY(1.15);
}
.box-3 {
  transform: scale(.5, 1.15);
}
```

# 2D Translate

### Example :

![translate](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/translate-example.png)


***Translate can adedd to X , Y ***

```
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}
```