# charts 
A great way to get started with charts is with a JavaScript plugin that uses HTML5’s canvas element to draw the graph into the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts and pie charts

## drwing line chart 
* to draw a line chart the first thing we need to do is create a canvas element in html page <canvas> 

* next we need to write a script that will retieve the context of the canvas (we add this to the foot of html body ) 

## drwing pie chart 
* first we need the canvas element 
* after that we need to get the context and to instantiate the chart 

* next we need to create the data , this data will be different to the line chart 

* after the pie data we will add option 

## drwing bar chart 

* first we will add the canvas element 
* next we retrieve the element and create the graph 
* finally we add in the bar chart's data 

# Basic usage of canvas 

## the canvas element  
* At first sight a <canvas> looks like the <img> element, but the  difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height

## required vanvas tag 
* the canvas element requires the closing tag </canvas> 

## the rendering context 
* in 2D rendering canvas element has method called getContext() used to obtain the rendering context and its drwing function and it takes one parameter 

## Drawing rectangles 
* fillRect(x, y, width, height) : Draws a filled rectangle
* strokeRect(x, y, width, height) : Draws a rectangular outline 

* clearRect(x, y, width, height) : Clears the specified rectangular area, making it fully transparent 

## Drawing paths 
* beginPath() : Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up 

* Path methods : Methods to set different paths for objects 

* closePath() : Adds a straight line to the path, going to the start of the current sub-path 
* stroke() : Draws the shape by stroking its outline 

* fill() : Draws a solid shape by filling the path's content area 

## Moving the pen 
* moveTo(x, y) : Moves the pen to the coordinates specified by x and y 

* When the canvas is initialized or (beginPath()) is called, you typically will want to use the (moveTo()) function to place the starting point somewhere else. We could also use (moveTo()) to draw unconnected paths 

## Lines 

* lineTo(x, y) : Draws a line from the current drawing position to the position specified by x and y 



