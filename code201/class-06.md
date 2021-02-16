# Read 06

## Understanding the problem domain is the hardest part of programming
When you have a familiar problem domain, it makes teaching and learning easier. Usually when solving puzzles, you'll want to do the following steps:
1. Figure out what the major components of the picture are
1. Sort the pieces by color or component
1. Put together all the border pieces
1. Put together each component of the picture from the piles you created.

This is similar to writing code. You're putting together small pieces of code that would later create the bigger picture of the problem domain. But not all problem domains are like a puzzle. When your problem domain is clear, it makes it easy. But some problem domains are blurry or sometimes no picture at all.

So what can you do about it? You can make the problem domain easier or you can get better at understanding the problem domain.

## JS Ch 3 (100-105)
Objects group together a set of variables and functions to create a model of something you would recognize in the real world. In an object, variables and functions take on new names. (Javascript & Jquery, Duckett, pg 100.)

In an object, variables become properties and functions become methods. A literal notation is the most popular way to create objects.

```var hotelName = hotel.name;```
```var roomsFree = hotel.checkAvailability();```
"hotel" is the object
"name; and checkAvailability();" are the property/method names
"." is the member operator.

### Keywords
- **Property** Tells us about the object
- **Method** Represents tasks that are associated with the object.
- **Key** the name and value of properties and methods.

## JS Ch 5 (183-242)
A DOM tree is the model of a page that the browser loaded. It is stored in the browser's memory.

**Steps to access and update the DOM tree:**
1. Access the elements
    - Select an individual element node
    - Select multiple elements
    - Traverse between element nodes
1. Work with those elements
    - Access/update text nodes
    - Work with HTML content
    - Access or update attribute values

Dom queries can return one element or may return a collects of nodes called a NodeList. When a method returns a single element, you can use id as a css selector. If a method returns a NodeList, you can use class as a css selector.

id: ```document.getElementById('one')```
class: ```document.getElementsByClassName('hot')```
"document" is the object
"." is the member operator
"getElementById('one')" is the method
"one" is the parameter
This allows you to select a single element node. You need to specify the value with the id attribute.

```for (var i = 0; i < hotItems.length; i++){```
```    hotItems[i].className = 'cool';```
```}```
For a looping example see page 206 & 207.

**Traversing the DOM**
- parentNode: finds the element node for the containing elemenet in the HTML
- previousSibling/nextSibling: find the previous or next sibling of a node
- firstChild/lastChild: find the first or last child of the current element

**Adding or removing HTML content**
- The innerHTML Property: there are security risks
    - Approach: Used on any element node. Can retrieve and replace content. New content is provided as a string.
    - Adding content
        1. Store new content
        1. Select the element whose content you want to replace
        1. Set the element's innerHTML property to be the new string
    - Removing content: set your innerHTML to an empty string
- DOM manipulation methods
    - Approach: DOM methods that allow you to create element and text nodes, then attatch or remove them to the DOM tree
    - Adding content: Use a DOM method to create new content one node at a time, store it in a variable.
    - Removing content: Remove an element using a single method.

**Cross-site scripting Attacks (XSS)**
An attacker could gain access to your users' accounts. To defend against XSS, you need to validate input going to the server and you'll need to escape data comikng from the server and database.

### Keywords
- **Document node** Located at the top of a DOM tree. It represents the entire page (and also corresponds to the document object)
- **Element nodes** In order to access a DOM tree, you need to start looking for elements. Once you locate your element, you can access it.
- **Attribute nodes**  The opening tags of HTML carry attributes, in a DOM tree, they are represented by attribute nodes.
- **Text nodes** After accessing the element node, you can reach the text within that element which is called a text node.
- **DOM queries** Methods that find elements in the DOM tree

[<== Back](https://simoneodegard.github.io/reading-notes/)