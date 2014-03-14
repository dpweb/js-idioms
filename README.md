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

####AOP (extend-wrap)
````
(function(o){
  return function(p){
    // do something new
    o(p);
  }
})(oldfunc);
````
