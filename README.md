# Unexpected Behavior of calc() with Percentages and Other Units

This repository demonstrates a bug where the CSS `calc()` function produces unexpected results when combining percentages and pixels. The issue is observed in certain browsers and can lead to inconsistent layout.

## Bug Description

The `calc()` function, intended for dynamic calculations within CSS, unexpectedly misinterprets the combination of percentage and fixed units, leading to incorrect rendering.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.css` and examine the problematic CSS code.
3. Open the associated HTML file (not included, but easily created) containing the element styled with `bug.css`.
4. Observe the unexpected rendering of the element's width.

## Solution

The solution involves using a more consistent unit system within `calc()`, primarily sticking to percentages or a combination of pixel values for accurate layout.

Check `bugSolution.css` for a corrected implementation.
