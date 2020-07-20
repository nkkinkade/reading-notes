# Read: 14a - CSS Transforms, Transitions, and Animations

## Transforms
* The transform property comes in two different settings: 
  * Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes
  * Three-dimensional transforms work on both the x and y axes, as well as the z axis and help define not only the length and width of an element, but also the depth
* The syntax for the transform property is transform followed by the property

# Transitions
* With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs
* Transitions provide a change from one state to another
* There are four transition related properties in total:
  * transition-property
  * transition-duration
  * transition-timing-function
  * transition-delay

# Animations
* Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes
* Animations can set multiple points of transition upon different keyframes
* To set multiple points at which an element should undergo a transition, use the @keyframes rule
* The different keyframe breakpoints are set using percentages, starting at 0% and working to 100% with an intermediate breakpoint at 50%
  * The keywords from and to could be used in place of 0% and 100% if wished