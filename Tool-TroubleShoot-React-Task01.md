# Task: React Controlled Component Value Not Updating

## Objective
Fix the functionality of a React controlled component (`ItemModule`) to allow updating its `name` programmatically from the parent component (`RepeatModule`).

## Task Description
You are working within a React application where a `ItemModule` component is used as a controlled component, meaning its value is derived from its parent component's state. The `RepeatModule` component currently prepares this for `ItemModule`s .

## Logic Roadblock
The current implementation does not support updating the `ItemModule` component's value from the parent component. The component uses clicks to updates based on user interaction.

## Task Completion
Your implementation should enable the `ItemModule` component to reflect changes initiated from the parent component, maintaining the controlled component behavior when is clicked.

## Experiment Focus
As you work, you should externalize your thoughts and approach while you solve the problem. As we are examining use of the programming and debugging tools, you should refrain from AI or Stack Overflow queries but may consult other forms of documentation.

## Task Background

### Understanding Controlled Components in React
- A controlled component in React has its data managed by another component (typically a parent). It receives its current value as a prop and notifies changes through event handling callbacks.

### Current Implementation Details
- The `ItemModule` component's selected value is stored based on a prop from the parent component.
- The component updates its state and notifies the parent when a user makes a selection through the `handleChange` method.

### Relevant React APIs
Documenation to understanding React props, including controlled components, and state management.
- [Props in React](https://react.dev/learn/passing-props-to-a-component#step-1-pass-props-to-the-child-component): Read-only objects that are used to pass values from a parent to child components.
- [State Management for Arrays](https://react.dev/learn/choosing-the-state-structure#avoid-duplication-in-state): React's mechanism for controlling component data across render cycles.

## Task Completion Checklist
- [ ] Analyze the current `ItemModule` component implementation.
- [ ] Verify the mechanism to update the `RepeatModule` component's value from the parent component.
- [ ] Ensure the `ItemModule` component remains a controlled component, and support user actions.
- [ ] Test the updated functionality to confirm that `RepeatModule` and `ItemModule` in the app.

## Task Duration: 30 minutes

## Task Link (the resercher will prompt what link to follow)
- [CP](https://codepen.io/luminaxster/pen/ZEZEGBd)
- [SCR](https://seecode.run/#:-NqTf23hkC-uf_93Q1XE)
