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


[<== Back](https://simoneodegard.github.io/reading-notes/)