# js 
## Understanding The Problem Domain Is The Hardest Part Of Programming

- the single hardest thing about programming is learning the problem domain 

### object 
 - what is an object 
objects group togther a set of variables and function to creat a model af a somthing 
you would recognize from the real world in an object variables and function take on new names 

### creating an object : 
- litral notation 
literal ntoation in the easiset and most popular way to creat objecte 

### accessing an object and dot notation 
we access the propertis or methods of an object using dot notation 
we can also access properties using square brackets 

- dot notation : access a property or method of an object you use the name of the object followed by a period
then the name of the property or method you want to access 

## DOM 
### what is the dom 
- The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content.
 The DOM represents the document as nodes and objects. That way, programming languages can connect to the page

- The following table briefly describes these data types 
1- document 
When a member returns an object of type document (e.g., the ownerDocument property of an element returns the document to which it belongs),
 this object is the root document object itself
2- Node 
Every object located within a document is a node of some kind. 
In an HTML document, an object can be an element node but also a text node or attribute node.
3- Element
The element type is based on node. It refers to an element or a node of type element returned by a member of the DOM API. 
Rather than saying, for example, that the document.createElement() method returns an object reference to a node, 
we just say that this method returns the element that has just been created in the DOM. element objects implement the DOM Element interface and also the more basic Node interface, 
both of which are included together in this reference. In an HTML document, elements are further enhanced by the HTML DOM API's
 HTMLElement interface as well as other interfaces describing capabilities of specific kinds of elements (for instance, HTMLTableElement for <table> elements).
4-nodelist
A nodeList is an array of elements, like the kind that is returned by the method document.querySelectorAll().
 Items in a nodeList are accessed by index in either of two ways:
a- list.item(1)
b- list[1] 
These two are equivalent. In the first, item() is the single method on the nodeList object.
 The latter uses the typical array syntax to fetch the second item in the list.
5-attribute 
When an attribute is returned by a member (e.g., by the createAttribute() method), 
it is an object reference that exposes a special (albeit small) interface for attributes. 
Attributes are nodes in the DOM just like elements are, though you may rarely use them as such.
6-namedNodeMap 
A namedNodeMap is like an array, but the items are accessed by name or index,
 though this latter case is merely a convenience for enumeration, as they are in no particular order in the list.
 A namedNodeMap has an item() method for this purpose, and you can also add and remove items from a namedNodeMap


