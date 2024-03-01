# Task: jQuery Filter Malfunction

## Objective
Fix the code functionality of a JavaScript-based filter that hides items from a list based on a range of minimum and maximum values.

## Task Description
Interact with a web app with a filter that hides items from a list. The list contains 12 items, each marked with a `'data-bedrooms'` attribute indicating the number of bedrooms. The filter is currently showing values out of the selected range.

## Logic Roadblock
The previous developer was stuck at the filtering logic with the following **pseudocode** snippet:
```javascript
return $(this).attr('data-bedrooms') < minValue || > maxValue;
```
## Task Completion
Your code should fix the filter's logic so it hides items not matching the filter's range. Elements displayed should be within the selected bedroom criteria (inclusive).

## Experiment Focus
As you work, you should externalize your thoughts and approach while you solve the problem. As we are examining use of the programming and debugging tools, you should refrain from AI or Stack Overflow queries but may consult other forms of documentation.

## Task Duration

### Estimated Completion Time
30 minutes.

### Task Completion Checklist
- [ ] Observe broken interaction.
- [ ] Locate broken code.
- [ ] Fix broken code.
- [ ] Present fixed interaction.

## Task Background

### Locating the Filter in the code
- Review elements in `HTML` such as:
  ```html
  <div class="property-item" data-bedrooms="7">7 bedrooms</div>
  ```
- Review the jQuery filter in `JS` that hides items based on the 'data-bedrooms' attribute.

### Interacting with the Filter in the app
- Use dropdown menus to select the minimum (minValue) and maximum (maxValue) number of bedrooms.
- Test various minValue and maxValue combinations.

### Identifying Functional Issues
- The main issue is that selecting a second value (maxValue) disrupts the expected filter behavior.

## Task link
- [SCR](https://seecode.run/#:-Nrvu4C30oon3ynQrHH0)
- [CP](https://codepen.io/luminaxster/pen/rNRYzvq)


## Programming Background
Recommended: JavaScript programming experience, particularly in GUI and user event handling.

### Relevant jQuery Methods
- [`els.on("change", eventHandler)`](https://api.jquery.com/change/): subscribe DOM elements to “change” events such as selection changes due to user interaction. 
-	[`els.filter(filterCallback)`](https://api.jquery.com/filter/#filter-function): treats the DOM elements as a collection and return a new collection with the filterCallback function returned true;
-	[`els.fadeIn()`](https://api.jquery.com/fadeIn/#fadeIn-duration-complete), and [`els.fadeOut()`](https://api.jquery.com/fadeOut/#fadeOut-duration-complete): apply CSS styling applied to the elements to animate the element into view, and out it, respectively.

---

Thank you for your participation!
