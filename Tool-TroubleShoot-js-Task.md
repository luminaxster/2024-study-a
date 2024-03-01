# Task: JavaScript DOM Element Attribute Setter

## Objective
Fix the functionality of a JavaScript snippet that iterates over DOM elements to set an attribute, ensuring no errors are encountered during the iteration process.

## Task Description
Work within a web application context where you need to apply a custom attribute to a series of DOM elements. These elements are part of a list, each with a class indicating a characteristic, such as `'data-capacity'`.

## Runtime Roadblock
The initial attempt to apply an attribute across these elements resulted in an error, with the following problematic JavaScript snippet:
```javascript
var elements = document.getElementsByClassName('data-capacity');
for (var i in elements) {
    elements[i].setAttribute('marked', '1');
}
```

## Task Completion
Your revised code should successfully apply the `'marked'` attribute to all targeted elements without throwing errors.

## Experiment Focus
As you work, you should externalize your thoughts and approach while you solve the problem. As we are examining use of the programming and debugging tools, you should refrain from AI or Stack Overflow queries but may consult other forms of documentation.

## Task Duration: 15 minutes

### Task Completion Checklist
- [ ] Identify the issue with the original iteration method.
- [ ] Implement a corrected iteration technique.
- [ ] Verify all targeted elements are correctly marked.
- [ ] Discuss the corrected approach and its benefits.

## Task Background

### Identifying Elements in the Code
- Inspect elements in `HTML` similar to:
  ```html
  <div class="item data-capacity" data-capacity="5">Capacity: 5</div>
  ```
- Locate the JavaScript snippet that iterates over elements with the 'data-capacity' class to apply a custom attribute.

### Understanding the Iteration Issue
- The initial iteration approach leads to an error, preventing the successful application of the `'marked'` attribute.

## Task Link

- [CP](https://codepen.io/luminaxster/pen/jOJjBog)
- [SCR](https://seecode.run/#:-NrrDAdCMzjel55-5rdl)

## Programming Background
Recommended: Familiarity with JavaScript, particularly DOM manipulation and understanding of different iteration methods in JavaScript.

### Key JavaScript Concepts
- [`document.getElementsByClassName(className)`](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementsByClassName): selects a live HTMLCollection of elements with the specified class name.
- [`element.setAttribute(name, value)`](https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute): sets a new value for an attribute on the specified element.
