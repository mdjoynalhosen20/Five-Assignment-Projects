# Hotline-project

### Answer the some important questions:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
   Ans: getElementById, getElementsByClassName, and querySelector/querySelectorAll are all JavaScript functions used to select elements from the DOM.

   getElementById is used to select a single element from the HTML page by its ID and bring it into JavaScript.

   getElementsByClassName allows us to select multiple elements that share the same class, and we can work with them together.

   querySelector lets us select an element using CSS-style selectors, but it only picks the first matching element.

   querySelectorAll works the same way as querySelector, 

2. How do you **create and insert a new element into the DOM**?
   Ans:In JavaScript, we can create a new element using the DOM. First, we usually declare a variable (for better understanding), then use document.createElement("div") to create the element. That’s all it takes to create it. After that, we use appendChild to add it to a parent element.
3. What is **Event Bubbling** and how does it work?
   Ans: Event bubbling is a concept in JavaScript where an event starts from the target element (the element where the event actually occurred) and then bubbles up through its parent elements — all the way up to the root (or grandparent) element. So, the event moves from bottom to top in the DOM hierarchy.
4. What is **Event Delegation** in JavaScript? Why is it useful?
   Ans: Event delegation works in the target phase.
5. What is the difference between **preventDefault() and stopPropagation()** methods?
   Ans: preventDefault() is used when there's a button inside a form, and clicking the button normally causes the website to reload. To control that default behavior and prevent the reload, we use preventDefault()
   And, stopPropagation() stops the event from triggering handlers on parent/ancestor elements.
