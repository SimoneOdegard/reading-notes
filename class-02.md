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


## JS Ch 4 (145-162)

[<== Back](README.md)