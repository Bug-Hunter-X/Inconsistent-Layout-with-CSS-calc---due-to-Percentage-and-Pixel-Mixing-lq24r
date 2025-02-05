# Inconsistent Layout with CSS calc() due to Percentage and Pixel Mixing

This repository demonstrates a common yet subtle issue encountered when using the CSS `calc()` function with a mix of percentage and pixel units.  The problem arises from the order of operations and how browsers handle unit conversions within the calculation, resulting in inconsistent layout across different viewports or parent element dimensions.

The `bug.css` file shows the problematic code, while `bugSolution.css` offers a corrected approach.  This issue highlights the importance of carefully considering unit compatibility and calculation order when working with `calc()` in CSS.
