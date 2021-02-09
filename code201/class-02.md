# Read 02

## HTML Ch 2 (40-61)
**Structural markup** The markup that is used to structure a page layout. Elements like the head, body, footer would be pieces of the structure that won't change.

**Semantic markup** The markup that is used to place emphasis but not change the structure of a layout. This could be like an ul or unordered list.

### Keywords
- ```<sup>``` Use when characters need to be in superscript
- ```<sub>``` Use when characters need to be in subscript
- **White Space** Used by adding multiple spaces within the code to make it easier to read. 
- ```<br />``` Adds another line break
- ```<hr />``` Adds a horizontal rule. Great for when you want to break between themes
- ```<abbr>``` Used for abbreviations and acronyms.
- ```<cite>``` Used when citing references. It will appear in italics
- ```<dfn>``` Used to explain the defining instance of a new term
- ```<address>``` Used to contain contact information for the author of the page
- ```<ins>``` and ```<del>``` Used to show when you delete text and insert new text. The deleted text appears as a strikeout while the inserted text is underlined.

## HTML Ch 10 (226-245)
CSS is the piece of code that makes everything pretty. It's best to imagine everything are in invisible boxes around each HTML element. With each invisible box, you're able to change the rules so that the stuff inside the box is presented differently.

```p { font-family: Arial;}```
p would be the selector which indicates what box or element you are applying rules to.
Everything within the {} is the declaration which tells the computer how the element will be styled.
font-family would be the property which is the aspect of the element that you want to change.
Arial is the value or the specific setting that you want as the chosen property.

```<link href="css/example.css" type="text/css" rel="stylesheet"/>```
When using external CSS, you have to remember to add code for the stylesheet into your HTML for your CSS to work.

```<style>```
When using internal CSS you would place your CSS within the style tag.

There are multiple selectors that you can choose from. You can find them on page 238 in the HTML & CSS book by Jon Duckett. Here are a few of them:
- Universal Selector = *{}
    - Applies to all elements
- Type selector = h1 would target the ```<h1>``` tag
    - Used to match element names
- Class selector = .note {}
    - Used for multiple items. Targets all element who have the class attribute of note
- ID selector = #introduction{}
    - Used when wanting to use one/make something more unique.

It is important to understand how each rule takes precedence. There is the Last Rule which means that if there are two or more selectors that are identical then the last one will take precedence. If a selector is more specific than another, then the selector that is most specific will take precedence. The way to show that something should take precedence is to add **!important** after the property value.

When applying CSS rules, if you apply to something like ```<body>```, everything within that tag will inherit the properties that were applied. The items within the tag are called child elements.

## JS Ch 2 (53-84)
A script is a series of instructions. Each step in the instructions are called a statement which end with a semicolon. Code blocks are statements that are surrounded by curly braces. It is important to note that states each start on a new line. To help others understand or read your code, you should add comments. You would do this by using //.

Variables are where you store pieces of information temporarily. Variables can change each time a script is run. Once you create a variable, you can tell it what to do using the variable name.

**var** ***quantity;***
**var** is the variable keyword that we will use as let.
***quantity;*** is the variable name. A good variable name is very important. It helps keep you organized. Names need to be lower case for the first word, and the following words would have a capital first letter.

There are 3 data types.
- Numeric Data Type: numeric data
- String Data Type: letters and other characters
- Boolean Data Type: only True or False values

Arrays are special types of variables that stores multiple values as a list. It is similar to a shopping list. The numbering starts at 0, not 1.

Expressions evaluates into (results in) a single value. Expressions rely on operators. Operators create a single value from one or more values. (Javascript & Jquery, Duckett, pg 74 and 75)
1. Expressions that just assign a value to a variable
1. Expressions that use two or more values to return a single value

Operators
- Assignment Operators: Assign a value to variable
- Arithmetic Operators: Perform math
    - Addition +
    - Subtraction -
    - Division /
    - Multiplication *
    - Increment ++: Add one to the current number
    - Decrement --: Subtract one from the current number
    - Modulus %: Divdes two values and return the remainder
- String Operators: Combine two strings
    - The + is used to join strings
- Comparison Operators: Compare two values and return true or false
- Logical Operators: Combine expressions and return true or false

## JS Ch 4 (145-162)
Using a flowchart will help you plan for when a script has to make a decision. You will need to set a condition to determine which path to take. If the condition returns true, you take one path; if it is false, you take another path. (Javascript & Jquery, Duckett, pg 148)

The two components to a decision (Javascript & Jquery, Duckett, pg 149):
1. Evaluation of a condition: Comparing two values using a comparison operator which returns a value of true or false.
2. Conditional statements: Based on if/then/else; if a condition is met, then your code executes one or more statements, else your code does something different.

**Comparison Operators**
- == is equal to
- != is not equal to
- === strict equal to
- !== strict not equal to
- < <= less than and less than or equal to
- ```> >=``` greater than and greater than or equal to
- ```(score >= pass)``` score and pass are operand. The comparison operator is in the middle of the two.
- ```((score1 + score2) > (highScore1 + highScore2)``` You can use expressions with comparison operators too. score1 + score2 is the first operand and highScore1+highScore2 is the second operand.

**Logical Operators**
Logical operators compare the results of more than one comparison operator. They are evaluated from left to right. Sometimes, the first expression has enough information that the computer can stop without checking the next expression.
- ```&&``` logical and
- ```||``` logical or
- ```!``` logical not

**If Statements**
The if statement evaluates a condition. If the condition evaluates to true, any statements in the subsequent code block are executed. (Javascript & Jquery, Duckett, pg 160)

**If...Else Statements**
The if...else statement checks a condition. If it resolves to true the first code block is executed. If the condition resolves to false the second code block is run instead. (Javascript & Jquery, Duckett, pg 162)

[<== Back](README.md)