# This repository contains all answers to BANKI questions

# Behavioral Questions

# Technical Questions

## HTML
1. What does a doctype do?
   > Doctype HTML is a declaration that tells the browser what version of HTML the document is written in. This declaration appears as the very first line in an HTML file. This ensures that the web page is parsed the same way by different web browsers. source: geeksforgeeks.org
2. How do you serve a page with content in multiple languages?
   > You can use <html lang="en">. To change the language, just simply set the lang attribute. We can define it anywhere in the document, such as in the body, in the paragraph, in the heading, or in the span tag. But the best practice is to set the lang in the span tag. source: mdn
3. 

## CSS
1. What is CSS selector specificity and how does it work?
   > Specificity is the means by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied. If two CSS selectors apply to the same element, the one with higher specificity is used. source: freecodecamp.org
   * Element and pseudo-element selectors have the lowest specificity. In the specificity weight system, they have a value of 1.
    * Classes, attributes and pseudo classes have higher specificity than elements and have a value of 10.
    * ID selectors which are used to target an element using element's ID have a value of 100.
    * Inline styles which can be applied directly on the element in the HTML document has the highest .specificity with a value of 1000.
    * Finally applying !important to the property value of any selector makes it the value that will be applied to the element. This happens regardless of the rank of the selector on the Specificity hierarchy.
2. What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?

## Javascript

## Javascript General

## Node

# CS Theory

# Questions to ask interviewer