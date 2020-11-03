# Summary of Things Learned

## Day 1

- How to select HTML elements
- Event listeners - `transitionend`, `keydown`
- CSS transitions
- HTML "data" attributes, which are attributes you made up, like "data-{SOME-NAME}"
- `forEach` loop - execute a function on each element in an array

## Day 2

- Setting CSS styles on elements
- CSS properties:
  - `transform-origin`
  - `transition`
  - `transition-timing-function`
- `setInterval`

## Day 3

- CSS variables (use root element)
- cool HTML input types for range (slider) and color (picker)

## Day 4

- Array functions:
  - `filter:` applies a filter function to return new array of elements that fulfill some requirement
  - `map:` does some action on each element and returns a new array
  - `sort:` uses a sort function that compares two elements and returns -1, 1, or 0
    - sorts the array in place
  - `reduce:` executes a reducer that takes in an accumulator an element, operating on element of the array, and returns a single value

## Day 5

- Use an element's classlist to modify class attributes
- flex

## Day 6

- Array.push and spread operator
- Using fetch to grab data from an endpoint
  - handling promises and blobs to retrieve raw data
- RegExp
- Using innerHTML to insert string as HTML children of an element

## Day 7

- Array functions:
  - `some`: returns boolean indicating whether _at least one_ element fulfills a requirement
  - `every:` returns boolean indicating whether _all_ elements fulfills a requirement
  - `find:` returns _first_ element that fulfills a requirement
  - `findIndex:` returns _index_ of first element that fulfills a requirement
  - `slice:` return copy of array elements between specified indices
  - `splice`: remove/replace/insert elements in place
- Combine slice with spread operator to create new array with removed element

## Day 8

- HTML canvas element and canvas API for drawing graphics
  - technically we draw on the context
- New event listeners: `mousedown`, `mousemove`, `mouseup`, `mouseout`

## Day 9

- Dev tools - how to make use of console API for debugging
- Console functions:
  - `log` for logging variable values
    - can also log styled text by using css string
  - `warn` for outputting warning message
  - `error` for outputting error message
  - `info` (in firefox it shows the info icon)
  - `assert` for writing a test
  - `clear` to empty console
  - `dir` for accessing DOM element info
  - `group` and `groupCollapsed` for grouping logged statements (useful when looping)
  - `count` logs number of times that it has been called (use case: inside event listeners)

## Day 10

- `click` event knows if CTRL/shift/meta keys were pressed

## Day 11

- video player built using HTML video element
- fullscreen API and cross browser requirements
