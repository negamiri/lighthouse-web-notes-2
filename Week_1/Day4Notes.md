# Day 4 notes

## Callback notes
- Create very generic function to use with other more specific functions

## Notes

* Callbacks
  - Higher-order function:
    - Takes a function as an argument or returns function as a result
    - Allows each function to have a single responsibility

* First-class functions
  - First-class citizen: an object with no restrictions on its creation, destruction or usage

  * Closures

    ``` javascript
  function makeAdder(x) {
    return function(y) {
      return x + y;
    };
  }
  var z = makeAdder(3)(4);
  ```
  In the above example, variable x makes this a closure

  - Lexical scope:
    - A function can access its parent-function's variables
