# CSS calc() Unexpected Behavior with Viewport Width

This repository demonstrates a peculiar issue with the CSS `calc()` function when attempting to subtract a fixed value from the viewport width (`vw`).  The expected behavior is that the element's width should be 20 pixels less than the viewport width, but this isn't happening.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the red box does not have a width 20px less than the viewport width, despite the `calc()` function being used.
4. For comparison, examine `bugSolution.css` for a corrected implementation.

## Bug and Solution Files

* `bug.css` contains the problematic CSS code.
* `bugSolution.css` shows a corrected version of CSS Code. 

## Possible Causes

The issue likely stems from a conflict with other CSS rules, unit inconsistencies, or a misunderstanding of how `calc()` interacts with `vw` units. The provided solution offers a potential resolution but may need adjustments depending on your specific use case.