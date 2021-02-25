# Read 14a
## What Google Learned From Its Quest to Build the Perfect Team
See [class-14b](https://simoneodegard.github.io/code201/class-14b.md)

## CSS Transforms
[Link](https://learn.shayhowe.com/advanced-html-css/css-transforms/)
The transform property is a new way of changing general layout for size, position, and changing elements. Transform property has two settings, 2D and 3D. Vendor prefixes are strongly encouraged for any code in a production environment. Warning, elements may get distorted or transformed in both dimensional planes. 2D works with x and y axes and 3D works with x, y, and z axes.

**2D**
- 2D Rotate: You can rotate an element from 0 to 360 degrees.
- 2D Scale: You can change the appeared size of an element.
- 2D Translate: Works similar to relative positioning, pushing, and pulling an element without interrupting the normal flow of the document.
- 2D Skew: Used to distort elements on the horizontal axis, vertical axis, or both.
- Combining Transforms: multiple transforms at once

**3D**
- Perspective: You need perspective for 3D elements to work. This can be seen as a vanishing point. You can set it two different ways, perspective value within the transform property or using the perspective property.
- Perspective Depth Value: Can be set as none or a length measurement. None would turn off any perspective.
- 3D Rotate: You can rotate an image with rotateX, rotateY, and rotateZ
- 3D Scale: Elements may be scaled on the z axis
- 3D Translate: Again, elements may be translated on the z axis with translateZ.
- Transform Style: 3D transforms will be applied on an element that is nested within a parent element.
- Backface Visibility: You can rotate on the Y 180 degrees.

## CSS Transitions and Animations
[Link](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
You can use CSS for transitions and animations. You don't always need to use JavaScript or Flash. Transitions can't work unless an element has a change in state. Different styles must be identified for each state.

**Transitions**
- Transitional Property: determines what properties will be altered in conjunction with the other transitional properties. Not all properties may be transitioned, only properties that have an identifiable halfway point.
- Transitional Duration: The duration in which transition takes place. You can set multiple durations for multiple transitioning properties.
- Transition Timing: Used to set the speed in which a transition will move.
- Transition Delay: You could set a delay with transition-delay.

**Animations**
- Animations Keyframes: Set multiple points at which an element should undergo a transition.
- Animation Name: used so that it is identified from the @keyframes rule.
- Animation Duration, Timing Function, and Delay: Similar behaviors to transitions.
- Animation Iteration: Animations run their cycle from beginning to end by default. Use animation-iteration-count to determine how many times the animation will repeat.
- Animation Direction: You can declare the direction that the animation completes.
- Animation Play State: Allows an animation to be played or paused using the running and paused keyword.
- Animation Fill Mode: Identifies how an element should be styled either before, after, or both when an animation is run.

## 8 simple CSS3 transitions that will wow your users
[Link](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

**8 simple but cool effects to improve UX design**
1. Fade in: color fades in or out
1. Change color: changes the color
1. Grow & Shrink: grows or shrinks the item
1. Rotate elements: elements rotate/twist
1. Square to circle: makes a square element a circle
1. 3D shadow: adds an animated shadow
1. Swing: swings side to side. note: has a larger amount of code.
1. Inset border: creates an animated border that fills the image

## Cool examples of animations
- [6 buttons animated](https://codepen.io/retyui/pen/ByoaXV)
- [CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)
- [404](https://codepen.io/kieranfivestars/pen/MYdQxX)
- [Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/gCfBv)

[<== Back](https://simoneodegard.github.io/reading-notes/)