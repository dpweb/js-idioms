js-idioms
=========

####Alias an object's function
````
var $ = document.querySelectorAll.bind(document);
````

####Alias the same object's function
````
Element.prototype.on = Element.prototype.addEventListener;
````

