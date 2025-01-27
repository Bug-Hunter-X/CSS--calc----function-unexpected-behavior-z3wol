# CSS `calc()` Function Unexpected Behavior
This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to missing parent element width or unit mismatches.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.

## Bug Report
The `calc()` function in CSS is powerful but can be tricky.  Incorrect usage can lead to unexpected layout issues. In this case, attempting to calculate a width based on a percentage and a pixel value without a clearly defined parent width can result in unexpected behavior.