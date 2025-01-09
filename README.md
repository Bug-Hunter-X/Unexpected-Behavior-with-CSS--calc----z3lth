# Unexpected Behavior with CSS `calc()`
This repository demonstrates a common yet often overlooked issue with the CSS `calc()` function.  Specifically, it showcases problems stemming from incorrect nesting and operator precedence within `calc()` expressions. The `bug.css` file shows the problematic code, while `bugSolution.css` illustrates the corrected approach.

**Problem:** The `calc()` function's results can be unexpected if used within a context where parent elements lack explicit dimensions or if the order of operations within the `calc()` expression itself isn't carefully considered.

**Solution:** Ensure parent containers have defined dimensions (width, height) where necessary and use parentheses `()` to control the order of operations within `calc()` expressions to enforce the intended calculation.