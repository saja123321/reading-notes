#  Chart.js 

### What is a **Chart.js** ?

its a way to draw graph onto the html page using `HTML5’s` canvas element.

## Setting up 

1.  download Chart.js.

1.  Copy the Chart.min.js out of the unzipped folder 

1.  Then create a new html page and import the script like this :

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```
----------------------------------



### ***So how to draw a line ?***

as simple as we just need to create canvas element in `HTML` file
``` 
<canvas id="buyers" width="600" height="400"></canvas>
```
and inside `js` file we need to add this line :

```
   var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
```    


after that we need to create a data we need by `buyerData` object like this:

```
var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
```
-----------------------------

lets try to drow a `pie chart`

1.  ***we need the canvas element like previos***
1. ***we need to get the context like this:***

```
var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);
```

Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section:

``` 
var pieData = [
	{
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
];
```

Now, immediately after the pieData we’ll add our options:

```
var pieOptions = {
	segmentShowStroke : false,
	animateScale : true
}
```
