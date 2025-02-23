# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a simple yet easily overlooked error in HTML and JavaScript: a typo in the ID used with `document.getElementById()`.  The error is subtle and can be difficult to debug if not carefully examined.

## Bug Description
The `bug.html` file contains a typo in the ID used to select an element.  The script tries to access an element with the ID `myDive`, but the actual element's ID is `myDiv`.  This leads to the element not being found and a potential JavaScript error.

## Bug Solution
The `bugSolution.html` file corrects the typo, correctly selecting the element with ID `myDiv`. This solves the issue and prevents the JavaScript error.

## How to reproduce the bug
1. Open `bug.html` in a web browser.
2. Observe the console for an error message indicating that the element was not found.

## How to fix the bug
1. Correct the typo in the JavaScript code, changing `'myDive'` to `'myDiv'`
2. Ensure that element IDs are consistent between HTML and JavaScript