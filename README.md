# CSS Flexbox space-between Layout Bug

This repository demonstrates a subtle bug in CSS Flexbox's `space-between` justification when the total width of flex items exceeds the container width.  The bug manifests as unexpected layout behavior: items may overflow the container or not be evenly spaced.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` provides a solution.

## Reproduction

1. Clone this repository.
2. Open `bug.html` (or similar HTML structure using the CSS) in a browser.
3. Observe the unexpected layout of the items.

## Solution

The solution involves ensuring the sum of item widths (including padding, margins, and borders) does not exceed the container's width.  Adjust widths, remove extra spacing, or use a different justification method if necessary.