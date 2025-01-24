# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug related to the incorrect usage of the `innerHTML` property in HTML.  The bug arises from attempting to concatenate a string with a partially constructed HTML element directly within the `innerHTML` assignment, which causes a syntax error.

The `bug.html` file showcases the incorrect code that leads to the bug. The `bugSolution.html` demonstrates the corrected version.

This bug highlights the importance of constructing complete HTML elements before assigning them as innerHTML. Simply concatenating string and DOM elements within innerHTML is not valid.