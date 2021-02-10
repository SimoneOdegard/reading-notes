# Read 03

## HTML Ch 3 (62-73)
- **Ordered List** Numbered lists
    - ```<ol>```
    - ```<li>```
- **Unordered List** Bulleted lists
    - ```<ul>```
    - ```<li>```
- **Definition List** Definition terms lists
    - ```<dl>```
    - ```<dt>``` used to contain the definition term being defined
    - ```<dd>``` used to contain the definition
- **Nested List** When you want to have lists that are nested, you can use the ```<li>``` element.

## HTML Ch 13 (300-329)
There are lots of things you can do in CSS to change the boxes that your HTML elements live in. You can change the dimensions, create borders, change margins and padding, and even show or hide the box.

**Box Dimensions** You can change the width and height. You can even set a min and max width. This is helpful in keeping the content of the page legible. You can also set a min and max height. This can be tricky because the content could overflow. Overflow property is what it tells the browser to do with the content that is too large for the box. It can become hidden or you can create a scroll.

**Borders, Margins, and Padding** The three properties that every box has. These properties can all be adjusted.
1. **Borders** You can change the border width, border style, and border color.
1. **Padding** This is how much space appears between the content of an element and the border. You can adjust the top, right, bottom, and left padding.
1. **Margin** This is how much space appears between the gap between boxes. Again, you can adjust the top, right, bottom, and left margin.

**Hiding boxes** You can use the visibility property to hide boxes which will also allow space where the element would be. To not have a blank space, use the dispaly property instead.

**CSS3** This give you the option to have more elaborate borders. This also includes box shadows, rounded borders, and elliptical shapes.

## JS Ch 2 (70-73)
Arrays are used when you want to work with lists or other items that are related. They are great when you're not sure how many items your list will contain. A good way to use an array is using it for a shopping list since it's a list of related items.

**Array literal** is the prefered technique for creating an array.
**Array constructor** is another way to create an array.
View Javascript & Jquery, Duckett, pg 71 for coding examples.

**Values in Arrays**
- Numbering items: Each item in an array is give an index value. Index values do not start at 1, they start at 0.
- Accessing items
- Number of items: Arrays have a property called length, this holds the number of items in the array.

## JS Ch 4 (162-182)
- **if...else statement** checks a condition. One set of the condition will evaluate to true while the other is false. 
- **switch statements** starts with a variable called the switch value. Each case is a possible value for the variable and will run if the variable matches that value.
- **type coercion** When JavaScript converts data types behind the scenes to complete an operation.
- **weak typing** the data type for a value can change.
- **strong typing** when you specify what data type each variable will be. 
- **Falsy** values are treated as if they are false. Treated as the number 0.
- **Truthy** values are treated as if they are true. Treated as the number 1. When an object or array is present, it is usually considered truthy.
*Note: All values evaluate to either truthy or falsy.*
(Javascript & Jquery, Duckett, pg 166 and pg 167)

**Loops**
1. **For** When you want to run code for a specific number of times
1. **While** When you don't know how many times you want to run your code
1. **Do while** Similar to while loop but will always run the statements inside curly braces at least once

[<== Back](README.md)