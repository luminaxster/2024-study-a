# Task: React component's click not working

## Objective

Fix the functionality of the React component `ItemModule` to allow updating its `name`.

## Task Description

You are working within a React application where multiple `ItemModule`s are created by a parent component, `RepeatModule`. The `RepeatModule` component passes down data based on the  `items` array.

## Logic Roadblock
The current implementation does not register user actions on the `ItemModule` component. The component uses clicks to updates based on user interaction.

## Experiment Focus
As you work, you should externalize your thoughts and approach while you solve the problem. As we are examining use of the programming and debugging tools, you should refrain from **AI** or **Stack Overflow** queries. **Any other search methods that you are familiar with are allowed.**

## Task Background

### Understanding Components in React
A **component** in React is a way to organize what its going to be rendered in your web app's UI. 

A functions such `function X(props){return (<div>{props.name}</div>)}` can be used to be rendered in your web app with `<X name="totoro" />`;

A functional component is a React component as a function receiving values from its parent component as arguments, the first argument is often refred as the object `props`. Within those props, functions that notify changes back to it through event handling callbacks.

### Current Implementation Details
- The `ItemModule` component uses props from the parent component.
- The component updates when a user clicks through passed props.

### Relevant React APIs

 API documentation for understanding functional components in React, including props, and event handling lifecycle.
- [React Functional Components](https://react.dev/learn/your-first-component): functions such `function X(props){return (<div>{props.name}</div>)}` can be used to be rendered in your web app with `<X name="totoro" />`;
- [Props in React](https://react.dev/learn/passing-props-to-a-component#step-1-pass-props-to-the-child-component): Read-only objects that are used to pass values from a parent to child components.
- [Event handling](https://react.dev/learn/responding-to-events#adding-event-handlers):  click handling functions as `prop`erties can be pass down to React elements such as `div`. They trigger DOM events.

## Task Completion
Your implementation should enable the `ItemModule` to make trigger changes when is clicked.

### Task Completion Checklist
- [ ] Analyze the current `ItemModule` component implementation.
- [ ] Verify the props the `RepeatModule` component passes as values to `ItemModule`.
- [ ] Ensure the `ItemModule` supports user actions when clicked.
- [ ] Test the updated functionality to confirm that `ItemModule` clickes when the app is used.

## Task Duration: 15 minutes

## Task Link (the resercher will prompt what link to follow)
- [CP](https://codepen.io/luminaxster/pen/wvZvaKm)
- [SCR](https://seecode.run](https://seecode.run/#:-NqTY07s6k7Lf7QEnSrF))

