# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem.
 A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.
 An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders.
 As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.


# tables 
## what is a table 
a table represents inforamtion in grid fromat 

## table structure 
<table > 
The <table> element is used to create a table. The contents
of the table are written out row by row.
 <tr>
You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.)
It is followed by one or more <td> elements (one for each cell in that row).
At the end of the row you use a closing </tr> tag.

<td> 

Each cell of a table is represented using a <td> element. (The td stands for table data.)
At the end of each cell you use a closing </td> tag.
 <th> 
The <th> element is used just like the <td> element but its purpose is to represent the
heading for either a column or a row. (The th stands for table heading.)


### example on the table 
<html>
<head>
<title>Tables</title>
</head>
<body>
<table>
<thead>
<tr>
<th></th>
<th scope="col">Home starter hosting</th>
<th scope="col">Premium business hosting</th>
</tr>
</thead>
<tbody>
<tr>
<th scope="row">Disk space</th>
<td>250mb</td>
<td>1gb</td>
</tr>
<tr>
<th scope="row">Bandwidth</th>
<td>5gb per month</td>
<td>50gb per month</td>
</tr>
<!-- more rows like the two above here -->
</tbody>
<tfoot>
<tr>
<td></td>
<td colspan="2">Sign up now and save 10%!</td>
</tr>
</tfoot>
</table>
</body>
</html>


# Js 
## creating an object : construction ntation 

the new keyword and the object constuctor creat a blank object we can then add properties and method to the object 

- first : we creat a new object using combination of the new keyword and the object 
- next having created the blank object we can add properties and methods to it using dot notation 

## updating an object 
- to update the value of properties we use dot notation or square brackets
they work on object created using litral or constructor notation 
- to delete a property we use the delete keyword 
## array is object ? 
arrays are actually a special type of object they hold a related set of key/value pairs 
but the key for each value is its index number 
