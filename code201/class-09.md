# Read 09

## HTML Ch 7 (144-175)
The most popular form is the google search form. There are many types of forms called form controls:
- Adding text
    - text input
    - password input
    - multi-line text area
- Making choices
    - radio buttons
    - checkboxes
    - drop-down boxes
- Submitting forms
    - submit buttons
    - image buttons
- Uploading files
    - file upload

**How Forms Work** (HTML & CSS, Duckett pg 149)
1. User fills in a form and presses a button to submit information to the server
1. The name of each form control is sent to the server along with the value the user enters or selects
1. The server processes the information using a programming language (PHP, C#, VB.net, Java). It may also store the information in a database.
1. The server creates a new page to send back to the browser based on the information received.

username=Ivy
Forms may have several form controls that gathers information. The server will need to know what each piece of inputted data corresponds with each form element. "username" would be the name and "Ivy" would be the value.

```<forms>``` This is where the form controls live. Should always have the action attribute and usually will have a method and id attribute.
- **action** Its value is the URL for the page on the server that will receive the information from the form.
- **method** There are two methods, get or post.
    - get: values from the form are added to the end of the URL from the action attribute. Use for short forms and when you're retrieving data from the web server.
    - post: values are sent in as HTTP headers. Use when allowing users to upload a file, it is long, it has sensitive data, adds or deletes information from a database.

With HTML5 there are new form elements which makes filling in forms easier for users. With form validation, when a form isn't filled out correctly, you can have a form validation. There is also a way to have date input, email and url input, plus search input.

### Keywords
- Text input: used to create several different form controls. The value of the type attribute is what kind of input they will be creating.
- Password input: ```type="password"``` would be for a password input
- Text Area: ```<textarea>``` creates a multi-line text input.
- Radio Button: ```type="radio"``` used to pick one option out of a set of options
- Check box: ```type="checkbox"``` used to allow multiple options to be checked off
- Drop down list box: ```<select>``` creates a dropdown menu you can choose from
- Multiple select box: changes the drop down select box that shows more than one option.
- File input box: allows users to upload files
- Submit button: allows users to submit form to a server
- image button: ```type="image"``` let's you use an image for the submit button
- labelling form controls: ```<label>``` when you use the label tag, you can label your form controls. Each form control should have it's own label element.
- group form element: ```<fieldset>``` and ```<legend>``` Use the fieldset to group related form controls together. The legend helps identify the purpose of that group of form controls.

## HTML Ch 14 (330-357)
There are many bullet point styles as well as the option to use images for bullet points. You would use ```list-style-type``` and ```list-style-image```. You can also use ```list-style-position``` to change where the bullet point will be located. Either the inside or outside of the box that it is in.

**Styling**
- text inputs
- submit buttons
- fieldsets and legends

**Aligning form controls**: Sometimes there could be alignment problems. Having the form controls align vertically makes it easier to use. 

### Keywords
- Empty cell borders: ```empty-cells``` you can have empty cells with or without borders
- Gaps between cells: ```border-spacing``` and ```border-collapse```gives you control on what the distance is between cells.

## JS Ch 6 (243-292)
There are several different event types that can trigger functions in JavaScript code. This is a way of the browser knowing something is happening.
- UI events: when user interacts with browser's interface
- Keyboard events: when user interacts with keyboard
- Mouse events: when user interacts with mouse
- Focus events: when an element gains or loses focus
- Form events: when a user interacts with a form element
- Mutation events: when the DOM structure is changed by a script

**Triggering code**: or event handling.
1. Select element: the element that users are interacting with
1. Specify event (binding an event to a DOM node): what event on the selected nodes will trigger a response
1. Call code: state what code will run when the event is triggered

**Bind an event to an element**: Which event you are waiting to happen, and which element it will happen to.
1. HTML event handlers (considered bad practice)
1. Traditional DOM event handlers
    - ```element.onevent = functionName;``` element is the element, onevent is the event, functionName is the code. You can only attach one function to each event handler.
1. Dom level 2 event listeners
    - ```element.addEventListener('event'), functionName [, Boolean]);``` element is the element, event is the event (event to bind nodes), functionName is the cod, [, Boolean] is the event flow (Indicates something called capture, and is usually set to false). Everything after the . is the method.

**Event Flow**: HTML elements nest in other elements, ex, when you click on a link, you are also clicking on its parent element. Event bubbling starts at the most specific node and flows out to the least specific node. This is the default event flow. Event capturing is the opposite as it starts at the least specific node and flows inwards to the most specific one. Note, this is not supported in IE8 and earlier. Flow matters when your code has event handlers on an element and one of its ancestor or descendant element. (Javascript & Jquerey, Duckett, pg 261).

**Event Delegation**: This lets you monitor events that happen to all the children of an element.
- Works with new elements
- Solves limitations with *this* keyword
- Simiplifies your code

**Different types of events**:
- W3C Dom events: managed by the W3C. Most events are part of the DOM events
- HTML5 events: still being devleoped. Details events that browsers are expected to suport, specifically used with HTMl
- BOM (Brower Object Model) events: several of these events deal with touchscreen devices

**Where events occur**: Event object can tell you where hte cursor was positioned when an event was triggered (Javascript & Jquerey, Duckett, pg 278).
- Screen
- Page
- Client

### Keywords
- **Fire or Are Raised**: When an event occurs. User clicking a link would fire in the browser.
- **Trigger Scripts**: After a user fires an event, it could trigger a script.
- **Event Object**: When an event occurs, the event object tells you information about the event and the element it happened to.
- **Load**: Used to trigger scripts that access the contentss of a page.
- **Focus and blur**: When elements gain focus, the focus event fires for that DOM nodes. When an element loses focus, the blur event fires for the DOM node.



[<== Back](https://simoneodegard.github.io/reading-notes/)