# Unexpected Spaces in CSS calc() Function

This repository demonstrates a common error encountered when using the `calc()` function in CSS.  Incorrect spacing around operators within the `calc()` function can lead to unexpected results or parsing errors.

**Problem:**

Spaces are unintentionally added around the operators (+, -, *, /) in the `calc()` function, causing the calculation to fail. This often leads to unexpected layouts or rendering issues.

**Solution:**

Ensure there are no spaces around the operators within the `calc()` expression. The operators should be directly adjacent to the values.

**Example:**

Incorrect: `width: calc(100% - 20 px);`

Correct: `width: calc(100% - 20px);`