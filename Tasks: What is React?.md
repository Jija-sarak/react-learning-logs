# Tasks: What is React?

## 1. What is React?
React is a JavaScript library used to build user interfaces, especially for single-page web applications.

In simple words: 
- React helps you create fast, interactive, and reusable UI components for websites.

Key points:
- Developed by Facebook (Meta)
- Uses a component-based approach (UI is broken into small reusable parts)
- Updates the UI efficiently when data changes
- Mostly used for building the frontend of web applications

### Single-page web applications
A single-page web application (SPA) is a website that loads only one HTML page, and then updates the content dynamically without reloading the entire page.

In simple terms:
- The page doesn’t refresh again and again — only the required parts change.

How it works:
- The browser loads one page at the start
- When you click links or buttons:
    - New content is fetched using JavaScript
    - The page updates without a full reload


## 2. What does "UI" mean in the context of a webpage?
UI (User Interface) refers to the visible part of a webpage that users interact with. It includes not only interactive elements like buttons and forms, but also the overall layout, visual design, colors, spacing, and how elements are arranged to create a smooth and cohesive user experience.


## 3. What is React used for? Write your answer in one line.
React is used to build user interfaces for web applications, especially single-page applications (SPAs), by creating reusable and interactive UI components.


## 4. True or False: In React, you must manually change the HTML every time data changes.
False


## 5. What does React do when your data changes?
When data changes, React automatically updates only the parts of the UI that depend on that data, instead of reloading the entire page.


## 6. What are components in React?
Components in React are reusable building blocks that represent parts of the user interface. 

There are two main types of components:
- Function components (modern and most commonly used) and class components (older style).

Components handle data in two main ways:
- **Props:** data passed from a parent component to a child component (read-only)
- **State:** data managed inside a component that can change over time

By using components with props and state, React can efficiently update only the necessary parts of the UI.


## 7. Choose the correct option:
What kind of structure does React use to build a webpage?
- `a)` Large single file
- `b)` Static HTML only
- `c)` Many small reusable components

Answer: `c)` Many small reusable components

## 8. Imagine a button that says "Click me". In React, what would you write?
- `a)` HTML only
- `b)` JavaScript code that returns the button
- `c)` CSS code only

Answer: `b)` JavaScript code that returns the button

## 9. What does React help you avoid when building large interfaces?
React helps avoid repetitive, messy, and error-prone code by using a component-based architecture. It manages state in an organized way, makes UI updates predictable using the Virtual DOM, and improves maintainability and scalability in large applications.

## In plain JavaScript, how do you change what an element shows?
In plain JavaScript, you change what an element shows by manipulating the DOM using properties like textContent, innerText, and innerHTML.
- textContent changes only the text and ignores HTML tags
- innerText changes visible text and respects styling and layout
- innerHTML changes both text and HTML structure inside the element