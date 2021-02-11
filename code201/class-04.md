# Read 04

## HTML Ch 4 (74-93)
Links are created using the a element. You would use the href attribute to specify which page you want to link. When you want to link to another website, you'll use an absolute URL. When linking to pages on your same site, you'll use a relative URL.

You should organize your code by putting pages for each different section of the site into a new folder aka directory.

### Keywords
- **Aboslute URL** when you want to link to a different website, you'll use a full web address for the site.
- **Relative URL** shorthand that is used when linking pages to the same site.
- **Email links** ```mailto:```
- **Opening links in a new window** ```target="_blank"```
- **Linking to a specific part of the page** You would use the id attribute to link to a specific part of the page.
```<a href="interlude">``` ```<h2 id="interlude">```

## HTML Ch 15 (358-404)
Each HTML element has it's own box. These boxes are either block-level or inline. Block-level means it starts on a new line. Inline box means it will flow inbetween the surrounding content.

If one block-level element sits inside another block-level element, the outer box containing element is the direct parent of that element. Typically, you can group elements together inside of a ```<div>```. 

You can change positions of elements with positioning schemes. CSS has positioning schemes which let you control the layout of the page.
- **Normal flow** This is the default behavior. Paragraphs appear one after the other vertically down. ```position: static```
- **Relative positioning** This shifts an elements to the top, right, bottom, or left. This does not affect the position of surrounding elements. ```position: relative```
- **Absolute positioning** The element position is in relation to the caontaining element. ```position: absolute```
- **Fixed positioning** A form of absolute positions, however the element positioning changes in relation to the browser window. ```position: fixed```
- **Floating elements** When you float an element, it takes it out of the normal flow and position of a containing box. ```float```
- ***Overlapping elements** Relative, fixed, and abolute positioning can all overlap. Use ```z-index``` to control which element sits on top. The z-index is sometimes called **stacking context**.

**Float**
You can use float to put elements side by side. You can use ```clear``` to make sure that no element in the same containing element should touch. There may be issues when a containing element only has floated elements. Some browsers will treat it as 0px tall. To fix this, you would add the CSS rules ```overflow: auto;``` and ```width: 100%;```. You can also create multi-column layouts with floats. You would use the ```<div>``` element to do so.

**Screen sizes**
Because of different screen sizes, designers often create pages to be 960-1000 pixels wide.

**Layouts**
- **Fixed width layout** These designs do not change size. Measurements are given in pixels.
- **Liquid layout** Designs stretch and contract when the user increase or decreased the size of their browser window. Measurements are usually percentages.
- **Layout grids** The page is designed according to a 960 pixel grid. This helps designers position items on a page.

## JS Ch 3 (86-99)
A function lets you group a series of statements together to perform a specific task. When you ask a function to perform a task at a later time, you should give your function a name. When you ask your function to perform a task, that is calling the function.

### Keywords:
- **Parameters** Pieces of information pass to a function
- **Declaring a function** When you give a function a name, then write the statements needed to run inside the curly braces
- **Calling a function** When you have a declared function and you ask your function to perform a task.
- **Function declaration** creates a function that you can call later.
- **Function expression** If you put a function where the interpreter would expect to see an expression, then it is treated as an expression. (Javascript & Jquery, Duckett, 96)
- **Local/function-level** When a variable is created inside a function using the var/let keywords. Note: it can only be used in that function.
- **Global/global scope** When a variable is created outside a function. It can be used anywhere within the script.

## Article - 6 Reasons for Pair Programming
What is pair programming? It is when two devs share a workstation to code together. This is a "two heads are better than one" mentality. There are two roles in pair programming, the Drive and the Navigator. The Driver is the one who types and mainly codes. The Navigator guides the Driver with words as they think about the big picture. The Navigator might use their computer screen as a way to look up questions but not to write code.

Pair programming has four fundamental skills:
1. Listening
1. Speaking
1. Reading
1. Writing

Why pair programming?
1. **Greater efficiency** When two people are working on the same code, it is easier to catch mistakes. This results in higher quality code. It is also easier to help each other when the pair get stuck.
1. **Engaged collaboration**  Both programmers become more focused when working together. It also makes it easier to know when to ask for help. Solving solutions together also boosts confidence.
1. **Learning from fellow students** You can learn a lot from each other. You might be exposed to new techniques that maybe you're not used to.
1. **Social skills** Pair programming can improve interpersonal skills and communication.
1. **Job interview readiness** Pair programming is a common step in many interview processes. This will let companies have a better feel for you as a developer.
1. **Work environment readiness** Companies utilize pair programming and are prepared to train new hires. However, since it is something we do at Code Fellows, it will be one less thing to worry about.

[<== Back](https://simoneodegard.github.io/reading-notes/)