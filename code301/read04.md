# Read 04

## Forms
[link](https://reactjs.org/docs/forms.html)

You would use the technique called "controlled components" to handle the submission of a form and have access to the data that the user enters into that form. ```<input>```, ```<textarea>```, and ```<select>``` stays the same in their own state and update based on user input. The React state is the "single source of truth". "Input form elements whose value is controlled by React in this way is called a "controlled component"." (from website) The controlled component makes the input's value always driven by the React state. This allows you can pass the value to other UI elements.

```<textarea>``` uses a value attribute so that forms can be written like a form that has a single-line input.

```<input>```, ```<textarea>```, and ```<select>``` all work similarly. They accept a value attribute that is used to implemenet a controlled component. You can prevent the user from changing the input by specifying the value prop on a controlled component. If the user can still change the input, you may have set the value to undefined or null.

## Forms in bootstrap
[link](https://react-bootstrap.github.io/components/forms/)

[<== Back](https://simoneodegard.github.io/reading-notes/)