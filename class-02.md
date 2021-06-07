# HTML
## text 
### heading
html has six levels of heading the content of an <h1> element is the largest and the contents of an <h6> element is the smallest , the browsers display the contents of heading at different size 
(image ) 

### paragraphs 
To create a paragraph, surround
the words that make up the
paragraph with an opening <p>
tag and closing </p> tag.
By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs

### Bold & Italic
- By enclosing words in the tags
<b> and </b> we can make
characters appear bold

- By enclosing words in the tags
<b> and </b> we can make
characters appear bold

### Superscript & Subscript
- The <sup> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.
- The <sub> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.

### White Space

- In order to make code easier to
read, web page authors often
add extra spaces or start some
elements on new lines , When the browser comes across
two or more spaces next to each
other, it only displays one space.
Similarly if it comes across a line
break, it treats that as a single
space too. This is known as

### Line Breaks & Horizontal Rules
- if we wanted to add a line break inside the
middle of a paragraph you can
use the line break tag <br /> 

- To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the <hr /> tag

## St rong & Emph asis
- The use of the <strong>
element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.

- The <em> element indicates emphasis that subtly changes the meaning of a sentence.

### Quotations
- The <blockquote> element is used for longer quotes that take up an entire paragraph. Note how the <p> element is still
used inside the <blockquote> element.

- The <q> element is used for shorter quotes that sit within a paragraph. Browsers are
supposed to put quotes around the <q> element, however Internet Explorer does not —therefore many people avoid using the <q> element

# css
- CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.


## Using External CSS 
Link element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the head element.

# JavaScript
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








