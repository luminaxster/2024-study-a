# CodePen.io Tutorial

## Introduction

[CodePen.io](https://codepen.io/) is a dynamic online platform tailored for front-end developers to write, run, and display HTML, CSS, and JavaScript code instantly. It combines the concept of a `pastebin`, which allows for the sharing and editing of code snippets, with the ability to execute the code in real time. In CodePen, pastebins are referred to as `Pens`.

## Live Web Programing

![image](https://github.com/luminaxster/2024-study-a/assets/6577822/241329ee-f4d5-4c30-8d51-38a3f8dae977)

**Pen Editors**:
As you work on your code, the Pen will automatically bundle your HTML, CSS, and JS, presenting as the output. 

   - **HTML**: Add your markup in the HTML section.
   - **CSS**: Style your page using the CSS section.
   - **JavaScript**: Program interactivity in the JavaScript section.

## Web Browser Debugging

For streamlined debugging in Chrome, Edge, Firefox, and Safari, you can rely on similar practices with slight variations across browsers. Here’s a concise guide to using `console.log` for logging and setting breakpoints to follow your code's execution:

### console.log
- Insert `console.log('Message', variable);` into your JavaScript code to output values or messages for debugging.
- Access the console in:
  - **Chrome/Edge**: `Ctrl+Shift+J` (Windows/Linux) or `Cmd+Option+J` (Mac)
  - **Firefox**: `Ctrl+Shift+K` (Windows/Linux) or `Cmd+Option+K` (Mac)
  - **Safari**: Enable the Develop menu from Safari preferences, then `Cmd+Option+C`
 
For example, this pen's JS code has a `console.log` at line `14` logging some program state in the browser's console.

![image](https://github.com/luminaxster/2024-study-a/assets/6577822/3a77e7c0-af5f-4ea5-a2e2-aac957d16369)


### Breakpoints
- Open Developer Tools with `F12` or specific shortcuts (`Ctrl+Shift+I` for Chrome/Edge/Firefox, `Cmd+Option+I` for Safari).
- Navigate to the code:
  - **Chrome/Edge**: Go to the "Sources" tab.
  - **Firefox**: Look under the "Debugger" tab.
  - **Safari**: Use the "Sources" or "Debugger" tab, depending on your version.
- Click next to the desired line number to set a breakpoint and start debugging upon code execution.

####  Breakpointing CodePen' JS Script file

To locate a CodePen JavaScript's editor file for setting breakpoints, follow these steps.

1. **The Source Code Tab**:
   - In Chrome/Edge: Click on the "Sources" tab.
   - In Firefox: Select the "Debugger" tab.
   - In Safari: Choose the "Sources" or "Debugger" tab, depending on the version.

2. **Navigate to the JS File**:
   - Search for `pen.js` or `pen.js?` in the file tree.
     
   ![image](https://github.com/luminaxster/2024-study-a/assets/6577822/097c6b24-116a-4921-b2bd-dc8822f5ef61)

     
   - Select the `js` file matching your editor from the list to open the debugger's breakpointer for that file.
  
    ![image](https://github.com/luminaxster/2024-study-a/assets/6577822/baba52d3-7f06-49e9-bd95-e1ee7494d3ca)


3. **Set a Breakpoint**:
   
   - In the debbuger's `js` file tab, click on the line number where you want to set a breakpoint. A symbol (a red dot, or a blue tag like line `11` below) will appear, indicating that the breakpoint is set.

  ![image](https://github.com/luminaxster/2024-study-a/assets/6577822/a984273f-5d51-404b-baf3-0793d7aaae46)



---

## You are all set on web logging and breakpointing.
   - [Continue to the training task](https://github.com/luminaxster/2024-study-a/blob/main/1-tool-a-training.md)

