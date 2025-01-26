# CSS `calc()` Gotchas

This repository demonstrates some less common errors that can occur when using the `calc()` function in CSS.  Specifically, it highlights issues with:

1. **Operator Precedence:** Incorrect order of operations within the `calc()` expression can lead to wrong calculations.
2. **Unit Mismatches:** Mixing percentages and pixels without proper consideration can yield unexpected results.

The `bug.css` file shows examples of problematic `calc()` usage, and `bugSolution.css` provides corrected versions.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser (you might need to create a simple HTML file to use it).
3. Observe the unexpected behavior of the elements with incorrect `calc()` calculations.
4. Compare these to the corrected versions in `bugSolution.css`.

## Learning Points

* Always use parentheses to clarify operator precedence in complex `calc()` expressions.
* Be careful when mixing units within a `calc()` expression; ensure you understand how the units interact.
* Thoroughly test your CSS to identify unexpected behavior from `calc()`.