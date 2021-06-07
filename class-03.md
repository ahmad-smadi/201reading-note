# HTML 
## lists
### HTML provides us with three different types of lists 
- Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.

- Unordered lists are lists that begin with a bullet point (rather than characters that indicate order) 

- Definition lists are made up of a set of terms along with the definitions for each of those terms

## orderd lists 
- The ordered list is created with the <ol> element 

Each item in the list is placed between an opening <li> tag and a closing </li> tag. (The listands for list item.)  nad we used the <li> tag with two types of list inside the tag of the list like <lo> , <lu> 

![order list](https://image.slidesharecdn.com/htmllist-100712013133-phpapp01/95/html-list-7-728.jpg?cb=1278898356)

## Unordered Lists 
- The unordered list is created with the <ul> element 
- and we used <li> inside the <ul>

![unorder list](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSu2gX1kbIJYOzqq6hTUfM8Um7_LgMUchWWzg&usqp=CAU)


## Definition Lists
- The definition list is created with the <dl> element and usually consists of a series of terms andtheir definitions.
Inside the <dl> element you will usually see pairs of <dt> and <dd> elements.
 lets talk about <dt> and <dd> 
- <dt> This is used to contain the term being defined (the definitionterm).

- <dd> This is used to contain the definition.

### definition example 
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
condiments such as shredded daikon radish or
ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
weight of ingredients</dd>
<dd>A technique by which the scales are removed
from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
cow's milk (although it was traditionally made
from buffalo milk)</dd>
</dl>

## example lists 
<html>
<head>
<title>Lists</title>
</head>
<body>
<h1>Scrambled Eggs</h1>
<p>Eggs are one of my favourite foods. Here is a
recipe for deliciously rich scrambled eggs.</p>
<h2>Ingredients</h2>
<ul>
<li>2 eggs</li>
<li>1tbs butter</li>
<li>2tbs cream</li>
</ul>
<h2>Method</h2>
<ol>
<li>Melt butter in a frying pan over a medium
heat</li>
<li>Gently mix the eggs and cream in a bowl</li>
<li>Once butter has melted add cream and eggs</li>
<li>Using a spatula fold the eggs from the edge of
the pan to the center every 20 seconds (as if
you are making an omelette)</li>
<li>When the eggs are still moist remove from the
heat (it will continue to cook on the plate
until served)</li>
</ol>
</body>
</html>


## boxes 
### box dimension ( width , hight ) 
-By default a box is sized just big enough to hold its contents. To set your own dimensions for abox you can use the height and width properties.

- The most popular ways to specify the size of a box are to use pixels, percentages, or
ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.

## Overflowing Content
### overflow
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

### hidden 
This property simply hides any extra content that does not fit in the box 

### scroll 
This property adds a scrollbar to the box so that users can scroll to see the missing content

## Border, Margin and Padding
### border 
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.
### margin 
Margins sit outside the edge of the border. You can set the width of a margin to create a
gap between the borders of two adjacent boxes
### padding 
Padding is the space between the border of a box and any content contained within it.
Adding padding can increase the readability of its contents

## example boxes 
<!DOCTYPE html>
<html>
<head>
<title>Boxes</title>
<style type="text/css">
body {
font-size: 80%;
font-family: "Courier New", Courier, monospace;
letter-spacing: 0.15em;
background-color: #efefef;}
#page {
max-width: 940px;
min-width: 720px;
margin: 10px auto 10px auto;
padding: 20px;
border: 4px double #000;
background-color: #ffffff;}
#logo {
width: 150px;
margin: 10px auto 25px auto;}
ul {
width: 570px;
padding: 15px;
margin: 0px auto 0px auto;
border-top: 2px solid #000;
border-bottom: 1px solid #000;
text-align: center;}
li {
display: inline;
margin: 0px 3px;}
p {
text-align: center;
width: 600px;
margin: 20px auto 20px auto;
font-weight: normal;}
a {
color: #000000;
text-transform: uppercase;
text-decoration: none;
padding: 6px 18px 5px 18px;}
a:hover, a.on {
color: #cc3333;
background-color: #ffffff;}
</style>
</head>
<body>
<div id="page">
<div id="logo">
<img src="images/logo.gif" alt="The Analog Specialists" />
</div>
<ul id="navigation">
<li><a href="#" class="on">Home</a></li>
<li><a href="#">For Sale</a></li>
<li><a href="#">Repairs</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Contact</a></li>
</ul>
<p>
<img src="images/keys.jpg" alt="Fender Rhodes, Hohner Clavinet,
and Wurlitzer EP200" />
</p>
<p>
We specialise in the sales and repair of classic keyboards, in particular
the Fender Rhodes, Wurlitzer EP200, and Hohner Clavinet.
</p>
</div>
</body>
</html>


# javascript 
## switch statements
- swich statements starts with a varibal called the switch value , if the value of the livel varibal is the string one , then the code for the first case is executed , if it is two the second case is executed if it is three , the third case is executed . if it is none og these , the code for the defult case is executed 

### for examole 
switch (level){
    case 'one':
    title = 'level 1 ' ;
    breack;

    case 'two':
    title = 'level 2'; 
    breack;

    case 'three' :
    title = 'level 3';
    breack;

    defult:
    title = ' test';
    break;

}

### the deferint between if and switch
#### if 
- there is no need to provide an else option (we can just use if statement)
- it performs more slowly than switch because with if statments we checked even if a match has been found

#### switch 
- we have a default option that is run if none of the cases match 
- if a match is found , that code is run then the breack statement stops the rest of the switch statement running 

## using switch statments 
[example](https://media.geeksforgeeks.org/wp-content/uploads/switch.png)

# loops 
- loops cheak a condition if it returns true a code block will run . then the condition will be checked again and if it still returns true the code block will run again , it repaet until the condition returns false 
## there are three common types of loops :
### for
if we need to run code a specifec number of times , we use a for loop ' it is the most common loop' in a for loop the condition is usually a counter which is used to tell how many times the loop shoud run
### while 
if we do'nt know how many times the code should run , we can use a while loop , in this condition can be something other than a count , and the code will continue to loop for as long as the condition is true 
### do while
the do while loop is very similer to the while loop , but has one key difference it will always run the statements inside the curly braces at least once , even if the condition evaluates to false 