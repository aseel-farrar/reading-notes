# Read: 14a - CSS Transforms, Transitions, and Animations
# Transforms
- The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

- syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses

```css
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
## 2D Transforms
- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 

### 2D Rotate
- he rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
```css
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```
### 2D Scale
- Scale, property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 

### 2D Translate
The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

### 2D Skew
skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. 


## 3D Transforms

### 3D Rotate
- general rotate value before, positive values will rotate the element around its dedicated axis clockwise, while negative values will rotate the element counterclockwise.
- we use three new transform values, including rotateX, rotateY, and rotateZ.
- rotateX value allows you to rotate an element around the x axis
- rotateY value allows you to rotate an element around the y axis
-  rotateZ value allows an element to be rotated around the z axis

### 3D Scale
- using the scaleZ three-dimensional transform elements may be scaled on the z axis.


### 3D Translate
-  translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.

### 3D Skew
- Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale. Elements may be skewed on the x and y axis, then transformed three-dimensionally as wished, but they cannot be skewed on the z axis.



# Transitions
- for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

  -Transitional Properties
  -background
  -colorbackground
  -positionborder
  -colorborder
  -widthborder
  -spacingbottomclipcolorcropfont
  -sizefont
  -weightheightleftletter
  -spacingline
  -heightmarginmax
  -heightmax
  -widthmin
  -heightmin
  -widthopacityoutline
  -coloroutline
  -offsetoutline
  -widthpaddingrighttext
  -indenttext
  -shadowtopvertical
  -alignvisibilitywidthword
  -spacingz
  -index

- The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.

- The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.






# Animations

Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.




***

Go back

[Back](README.md)

