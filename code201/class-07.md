# Read 07

## HTMl Ch 6 (126-145)
Table structures: 
- ```<table>``` Used to create a table
- ```<tr>``` Indicates the start of each row
- ```<td>``` How each cell of a table is represented
- ```<th>``` Used like td but represents the heading for a column or a row

When you want a cell to expand to more than one column, you would create a spanning column using ```colspan```. Spanning rows are similar only it's for when you want your cell to span more than one row. You would use the ```rowspan``` attribute.

```<thead> <tbody> <tfoot>```
When working with long tables, there are three elements that will let you differentiate tables from content. These are also used to help people with screen readers.

## JS Ch 3 (106-144)
You can create a new object using a combination of the new keyword and the Object() constructor function. Once you have your new object, you can add properties and methods using dot notation. Statements should end with a ; When you want to delete a property, you would use the delete keyword. When you want several objects to represent similar things, object constructors can use a function as a template for creating objects. Using the constructor function, you can create instances of the object. A new keyword followed by a call to the function creates a new object. The properties of each object are given as arguments to the function. (Javascript & Jquery, Duckett pg 109.)

This. A keyword used inside functions and objects. It always refers to one objects, usually the object in which the function operates. The global scope or global context is when a function is created at the top level of script that is not inside another object or function. The default object is the window object, when this is used inside a function in the global context, it refers to the window object. This can be used to return properties of the window object.

**Storing Data**
- Variables
- Arrays
- Individual objects: Store sets of name/value pairs. They can be properties (variables) or methods (functionS).
- Multiple objects: When you need to create multiple objects within the same page.

**Arrays**
Arrays are objects. They hold a related set of key/value pairs but the key for each value is its index number. Arrays and objects can be combined to create more complex data structures. Arrays can store a series of objects while objects can also hold arrays.

**Object Models**
**Object Model** a group of objects, that each represent related things from the real world. Together they form a model of something larger. (Javascript & Jquery, Duckett pg 121.)
1. **Browser Object Model** creates a model of the browser tab or window. The topmost object is the window object. 
1. **Document Object Model** DOM creates a model of the current web page. Document is the topmost object.
1. **Global Javascript Objects** Does not form a single model. A group of individual objects that relate to different parts of the Javascript language. When you have a value that is a string, you can use the properties and methods of the string object on that value.

**Date object**
Used to work with dates. You can specify the time and date you want it to represent. Page 136-139 give more information and examples about the date object.

[<== Back](https://simoneodegard.github.io/reading-notes/)