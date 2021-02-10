# Read 01

## HTML: Ch 1 (12-39)
HTML is similar to newpapers. Newpapers have structure and it is often seen as a header, a main, and a footer. This is the same as webpages. HTML is used to create or describe that structure. To describe the structure, elements are used. These are the pieces that are inside the carrots or angled brackets. Elements are made up of tags, an opening and closing tag. Attributes give us even more information. They are on the opening tag of an element and have two parts. The attribute name which tells us what kind of information and the attribute value which sets the value of the attribute. The value is usually in double quotes.

## HTML: Ch 8 (176-199)
There have been several versions of HTML. Right now there is HTML5 which is a work in progress. You'll need to be careful with HTML5 because it might not be capable of all browsers. Due to there being several versions, you will need to declare what version of HTML the webpage will be using with a DOCTYPE. This will help the browser render the page correctly.

To group text and elements in a block, you will use a div. div elements will start on a new line. To group text and elements inline, you will use a span. span is similar to a div but works for keeping things inline.

### Keywords
- **ID** The golden attribute. It is used to identify elements as unique. This means that it can only be used once.
- **Class** This is used to identify multiple elements and you are able to change multiple things. 
- **Block elements** When elements appear to start on a new line. That is a block elemnent. h1, p, and ul are examples of block elements.
- **Inline elements** When elements appear to stay on the same line. a, em, and img are examples of inline elements.
- **iframe** This is used when something is embedded into the page. The most common would be a map on a webpage.
- **meta** meta lives inside the head element. This would be used for suppling different information of the webpage. Some values for this attribute would be description, keywords, and robots.
- **Escape Characters** This allows you to use characters on your page that would have been normally used in code.

## HTML: Ch 17 (428-451)
In order to help older browsers to understand HTML5, you need to use CSS. CSS will describe which elements are block elements. You may also need additional JavaScript to help browsers like Internet Explorer understand what HTML5 is trying to say.

### Keywords
- **headers and footers** On webpages there are headers and footers. They can be used at the top and bottom of every page or for an individual article or section of a page.
- **nav** is used for site navigation.
- **article** are containers for sections that can stand alone. 
- **aside** When inside an article, it has information relating to that article. When outside of an article, it is a container for the information on the whole page.
- **section** used to group related content together. Do not use as a wrapper for the entire page.
- **hgroup** is used to group multiple headings together.
- **figure and figcaption** Figure is used to contain content reference outside of the main flow of an article. Usually used when something references the element. A figcaption is something that describes the content of the figure.

## HTML: Ch 18 (452-475)
When designing you website, you need to know who your audience is. It will influence the design and even color pallet of your website. You'll want to understand why customers are coming to your website and what are they doing when they get there. Once you have an idea of that, you'll need to determine what kind of information your visitors will need. 

It will be helpful to create a site map. Site maps are used to help create a structure of your website. You will create a diagram and the card sorting technique. Card sorting is where you decide what information should go on each page. Once you have your site map, it's time to create wireframes. A wireframe is your blueprint for the website. It is a sketch that you do to determine the look and feel before you start coding.

To be able to get your message across, you will need to think of the design of the website. You will need to understand your content (What is it, hat things do you need on your site, etc.), prioritize your content by creating a visual hierarchy, and also organize or group related content into blocks.

### Keywords
- **Visual hierarchy** The flow that your eye views the page. Items that are higher in contrast will be recognized first.

## JS: Introduction
Javascripts makes web pages more interactive.
1. Access content
1. Modify content
1. Program rules the browser can follow
1. React to events

## JS: Ch 1 (11-52)
A script is like a recipe, handbook, or manual. It is a set of instructions that the computer follows to reach an outcome or goal.

**Steps for writing a script**
1. Define the goal - what is your goal? What is the big picture?
1. Design the script - split the goal out into a series of steps.
    1. Create a flowchart
    1. List the steps
1. Code each step - this is the recipe you create for the computer to understand. You will need to think like a computer!

A web browser are programs built using objects. HTML markup creates a model of the webpage. Each element creates its own node. The three languages (HTML, CSS, and JavaScript) work together to have websites behave the way we want them to. HTML is the content layer, CSS is the presentation layer, JavaScript is the behavior layer.

**document**.*write(**'Good Afternoon'**);*
- document is the object. It represents the entire webpage
- the *italic* section is the method of the **document**. It allows new content to be written into the page where the script element sits
- 'Good Afternoon' is the parameters. That is where you put the information so that the script works.
- the . is the member operator. **document** will have several different methods so you'll use the member operator to differenciate between them.

**Note:** The JavaScript does not change the HTML. The script works with the model of the web page.

### Keywords
- **Vocabulary** Words that computers understand
- **Syntax** How you put those words together to create instructions computers can follow. (page 20 - JS)
- **Objects** = things
- **Properties** = characteristics
- **Events** an outcome or response from an interaction
- **Method**  represents how people interact with an object

[<== Back](https://simoneodegard.github.io/reading-notes/)