# Read: 06 - JS Object Literals; The DOM

## Object Literals
* Properties take the place of variables in Objects but act the same
* There are two parts to a property:
  * A key is what the name is called
  * A value is what the key refers to
* Methods are functions inside objects that use properties to run code
* To access an object use dot notation:
  1. Type the name of the object
  2. Then a period
  3. Followed by the name ( key ) of the property or method

## Document Object Model
* The DOM tree is a model of a webpage
  * The document node represents the entire page and is used to access the other parts
  * Element nodes describe the structure of a page
  * Attribute nodes are carried in opening tags and are part of the element
  * Text nodes represent the text in an element
* DOM queries are methods that find elements in the DOM tree
* Methods that return a single element node:
  * getElementById('id')
  * querySelector('css selector')
* Methods that return one or more elements:
  * getElementsByClassName('class')
  * getElementsByTagName('tagName')
  * querySelectorAll('css selector')