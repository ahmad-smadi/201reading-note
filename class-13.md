# the pas , present and future of local storage for web applications 

## what is HTML5 ? 
* it’s a way for web pages to store named key/value pairs locally 

### HTML5 STORAGE SUPPORT 
1- IE : 8.0+ 
2-FIREFOX :  3.5+ 
3- SAFARI : 4.0+
4- chrome : 4.0+ 
5- opera : 10.5+ 
6- iphone : 2.0+
7- android : 2.0+ 

* STORAGEEVENT OBJECT 
1- key ===	string ===	the named key that was added, removed, or modified

2- oldValue ===	any	 ===the previous value (now overwritten), or null if a new item was added

3-  newValue ===	any	=== the new value, or null if an item was removed

4-  url* ===	string ===	the page which called a method that triggered this change

#### the history of local storage hacks 

1- 5 megabytes (is how much storage space each origin gets by default)
2- QUOTA_EXCEEDED_ERR(is the exception that will get thrown if you exceed your storage quota of 5 megabytes)
3- no 


## FURTHER READING 
### HTML5 storage:
1- HTML5 Storage specification
2- Introduction to DOM Storage on MSDN 
3- Web Storage: easier, more powerful client-side data storage on Opera Developer Community 
4- DOM Storage 
5- Unlock local storage for mobile Web applications with HTML5 

### Early work by Brad Neuberg et. al. (pre-HTML5): 
1- Internet Explorer Has Native Support for Persistence?!?! (about the userData object in IE) 
2- Dojo Storage, part of a larger tutorial about the (now-defunct) Dojo Offline library 
3- dojox.storage.manager API reference 
4- dojox.storage Subversion repository 

### Web SQL Database: 
1- Web SQL Database specification 
2- Introducing Web SQL Databases 
3- Web Database demonstration
4- persistence.js,  

### IndexedDB: 
1- Indexed Database API specification
2- Beyond HTML5: Database APIs and the Road to IndexedDB 
3- Firefox 4: An early walk-through of IndexedDB 



