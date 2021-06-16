# error handling & debugging 

## execution context 
- every statement in a script lives in one of three execution context : 
1- global context : 
* there is one global context in any page ( code that is in the script but not in a function) 
2- function context : 
* code that is being run within a function 
3- eval context (not shown) : 
* text is executed like code in an intrnal function called eval() 

## variable scope 
1- global scope : 
* if a variable is declared out side a function it can be used anywhere because it has global scope 

2- function level scope 
* when a variable is declared within a function it can only be used within that function (because it has function level scope )

### error object 
* error object can help us find the where is the mistake are and there are tools in the browser to help us read them 

### when an error object created it will contain the following properties 
1- name : type of execution
2- message : description
3- file number : name of the JS file 
4- line number : line number of error 

* if there is an error we can see all of this properties in the console of the browser 

### types of bulit error object in JS 
1- error : generic error (the other error are all based opon this error )
2- syntaxError : synatx has not been followed
3- referenceError : tried to reference a variable that is not declared 
4- typeError : an unexpected data type that cannot be coerced 
5- rangeError : number not in acceptable range 
6- URIError : endcodeURI() , decodeURI() and similar methods used incorrectly 
7- evalError : eval() function used incorrectly 

## how to deal with error 
1- debug the script to fix errors 
* if someone report a bug , we need to debug the code track down the source of the error and fix it 

2- handle errors gracefully 
* we can handle errors gracefully using try , catch throw and finally statements 

