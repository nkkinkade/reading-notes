# Read: 09 - Refactoring

## Functional Programming
* Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
* Pure functions return the same result if given the same arguments (it is also referred as deterministic)
* If a function reads external files, it’s not a pure function
* Any function that relies on a random number generator cannot be pure
* Pure functions do not cause any observable side effects
  * Examples of observable side effects include modifying a global object or a parameter passed by reference
* Mutability is discouraged in functional programming