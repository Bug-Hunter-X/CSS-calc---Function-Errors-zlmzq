# CSS calc() Function Errors

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function.  The `bug.css` file shows examples of code that produce unexpected results due to order of operations, unit mismatches, or incorrect nesting.  The `bugSolution.css` file provides corrected versions of the code, along with explanations of the fixes.

**Common Issues:**

* **Order of Operations:**  `calc()` follows standard mathematical order of operations.  Parentheses are crucial for controlling the evaluation order.  Incorrect use can lead to wrong calculations.
* **Unit Mismatches:** Mixing units (e.g., `px`, `%`, `em`, `rem`) within a single `calc()` expression requires careful attention. Implicit unit conversions might not always work as expected. Always ensure units are consistent or use explicit conversions.
* **Nesting:**  Nesting `calc()` expressions can be complex and prone to errors.  Overly nested expressions should be simplified for better readability and maintainability.

This example highlights these issues to help developers avoid similar problems in their projects.