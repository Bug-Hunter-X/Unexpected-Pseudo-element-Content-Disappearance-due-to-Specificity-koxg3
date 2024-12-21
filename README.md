# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity and pseudo-elements.  The `bug.css` file contains CSS that unexpectedly prevents a pseudo-element's content from being displayed. The solution is presented in `bugSolution.css`.

The core issue revolves around how CSS specificity works with pseudo-elements and conflicting class selectors.  Understanding CSS specificity is crucial for resolving this type of bug.

## How to reproduce the issue:
1. Open `bug.html` in a web browser.
2. Observe that the expected "Hello!" text before the main content does not appear. 

## Solution:
The `bugSolution.css` file shows how to correctly manage specificity to ensure the pseudo-element content is displayed as intended.  Reviewing the differences between `bug.css` and `bugSolution.css` will highlight the key fix.