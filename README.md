# CSS Specificity Trap: Unexpected Style Overrides

This repository demonstrates a common yet subtle issue in CSS related to selector specificity.  The bug.css file shows the unexpected behavior of higher specificity overriding less specific selectors, even when the less specific selector seems to more closely match the target element.

The solution is provided in bugSolution.css, demonstrating a proper approach to handling specificity in the CSS.

## How to reproduce the bug:
1. Open `bug.css` and inspect the CSS code.
2. Observe that the intended style is not applied due to specificity.