# Unexpected `calc()` behavior with percentages and viewport units

This repository demonstrates an uncommon bug related to the CSS `calc()` function when combining percentages and viewport units (like `vw` or `vh`). The expected behavior doesn't always match the actual result, leading to unexpected layout issues.

## Bug Description
The `calc()` function in CSS is powerful for dynamic calculations, but unexpected behavior can occur when mixing units. Specifically, this example highlights issues with combining percentages and viewport units within a `calc()` expression. The calculated width is not what's intuitively expected.

## How to reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected width of the element.