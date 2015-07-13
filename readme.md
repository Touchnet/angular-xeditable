# Angular-xeditable
Edit in place for AngularJS

This fork born from necessity to let work any xeditable item inside form element.
Personally i need form around 

added attribute 'editable-ignore' to form element.




## Overview
**Angular-xeditable** is a bundle of [AngularJS](http://angularjs.org) directives that allows you to create
*editable* elements in your projects.  
Such technique is also known as *click-to-edit* or *edit-in-place*.  
It is based on ideas of [x-editable](http://vitalets.github.io/x-editable) but was written from scratch
to use power of angular and support complex forms / editable grids.

## Demo and docs refear to original repository
**http://vitalets.github.io/angular-xeditable**

## Installation
#### Bower
````
bower install "https://github.com/Touchnet/angular-xeditable.git"
````
#### Manual
Download latest version from [project homepage](https://github.com/Touchnet/angular-xeditable).
#### Insert dependency 
````
var app = angular.module("app", ["xeditable"]);
````

## Dependencies
Reguire JQuery.    
Basically it does not depend on any libraries except [AngularJS](http://angularjs.org) itself.    
For themes you may need to include [Twitter Bootstrap](http://getbootstrap.com) CSS.  
For some extra controls (e.g. datepicker) you may need to include [angular-ui bootstrap](http://angular-ui.github.io/bootstrap/).


## Usage
####
````
 <form editable-form editable-ignore>
     ...
````
####


## License
MIT
