# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow

## HTML Lists
* Unordered lists use the < ul > tag and, by default, use bullet points to indicate list items
* Ordered lists use the < ol > tag, and, by default, use numbers to indicate list items
* Using a recipe as an example, unordered lists would be the ingrediants section where an ordered list would be used for the step-by-step instructions
* Definition lists are made up of a set of terms along with the definitions for each of those terms
* Definition lists use the < dl > tag for the list and < dt > to tell what is being defined, while the < dd > tag tells the definition
* Lists can aslo be nested in other lists to add levels

## CSS Boxes
* CSS treats each HTML element as if it lives in its own box
* Dimensions of a box element can be controlled using the width and height declarations
* You can also limit the width and height using the min-width, max-width, min-height, and max-height declarations
* The overflow property tells the browser what to do if the content contained within a box is larger than the box itself
* Every box has 3 available properties that can be adjusted to control it's appearance:
  * Border seperates the edge of one box from another
  * Margin sit outside the edge of the border
  * Padding is the space between the border of a box and any content contained within it
* You can control the style of a border using the border-style property to add solid, dotted, dashed, double, groove, ridge, inset, and outset lines
* Block-level boxes can be made into inline boxes and vice versa

## JS Control Flow
* If...Else statements let you set code for two eventuallities:
  * One if the condition evaluates to true
  * Another if the condition evaluates to false
* Switch Statements start with a variable called the __switch__ value; each case indicates a possible value for this variable and the code that should run if the variable matches
* Switch statements also has a _default_ option that is run if none of the casses match
* Every value in JaveScript can be treated as if it were either True or False
* Loops check a condition and if it returns true, a code block will run; the condition is then checked again and if still true the code will run again, repeating until the condition returns false
* The 3 types of loops are For, While, and Do While