# Summary of Things Learned

## Day 1: JS Drum kit

- How to select HTML elements
- Event listeners - `transitionend`, `keydown`
- CSS transitions
- HTML "data" attributes, which are attributes you made up, like "data-{SOME-NAME}"
- `forEach` loop - execute a function on each element in an array

## Day 2: CSS + JS Clock

- Setting CSS styles on elements
- CSS properties:
  - `transform-origin`
  - `transition`
  - `transition-timing-function`
- `setInterval`

## Day 3: Playing with CSS Variables and JS

- CSS variables (use root element)
- cool HTML input types for range (slider) and color (picker)

## Day 4: Array Cardio Day 1

- Array functions:
  - `filter:` applies a filter function to return new array of elements that fulfill some requirement
  - `map:` does some action on each element and returns a new array
  - `sort:` uses a sort function that compares two elements and returns -1, 1, or 0
    - sorts the array in place
  - `reduce:` executes a reducer that takes in an accumulator an element, operating on element of the array, and returns a single value

## Day 5: Flex Panels Image Gallery

- Use an element's classlist to modify class attributes
- flex

## Day 6: Type Ahead

- Array.push and spread operator
- Using fetch to grab data from an endpoint
  - handling promises and blobs to retrieve raw data
- RegExp
- Using innerHTML to insert string as HTML children of an element

## Day 7: Array Cardio Day 2

- Array functions:
  - `some`: returns boolean indicating whether _at least one_ element fulfills a requirement
  - `every:` returns boolean indicating whether _all_ elements fulfills a requirement
  - `find:` returns _first_ element that fulfills a requirement
  - `findIndex:` returns _index_ of first element that fulfills a requirement
  - `slice:` return copy of array elements between specified indices
  - `splice`: remove/replace/insert elements in place
- Combine slice with spread operator to create new array with removed element

## Day 8: Fun with HTML5 Canvas

- HTML canvas element and canvas API for drawing graphics
  - technically we draw on the context
- New event listeners: `mousedown`, `mousemove`, `mouseup`, `mouseout`

## Day 9: Must Know Dev Tools Tricks

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

## Day 10: Hold Shift to Select Multiple Checkboxes

- `click` event knows if CTRL/shift/meta keys were pressed

## Day 11: Custom HTML5 Video Player

- video player built using HTML video element
- fullscreen API and cross browser requirements

## Day 12: Key Sequence Detection

- `splice` to remove elements from array

## Day 13: Slide in on Scroll 

- **debounce** function to handle tons of events being fired on scroll
- calculate element and window height

## Day 14: Javascript Reference vs. Copying

- **primitive types** (string, number, boolean, null, undefined) vs. **object types** (object, function, array, set)
- various ways of copying an array:
  - slice
  - Array.from
  - concat onto empty
  - spread operator
- various ways of copying objects
  - spread
  - Object.assign
    - this does not clone deeply - nested objects will have references copied

## Day 15: Local Storage and Event Delegation

- event delegation - "responsible parents and negligent children that don't hear instructions. We tell the parents when an event happens ST parent can tell children (current and future) what to do"

## Day 16: CSS Text Shadow Mouse Move Effect

- the following may differ:
  - current target of an event (`e.currentTarget` or `this` within an event listener) vs. originating target (`e.target`)

## Day 17: Sorting Without Articles

- using regex to parse strings
- custom sort
