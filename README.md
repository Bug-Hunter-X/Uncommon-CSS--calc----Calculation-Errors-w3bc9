# Uncommon CSS `calc()` Gotchas

This repository demonstrates an uncommon error related to the use of the `calc()` function in CSS. Specifically, it showcases unexpected behavior arising from order of operations and unit conversions within `calc()` expressions and within `@media` queries.

## Bug Description

The CSS `calc()` function allows for dynamic calculation of values within CSS properties. However, there's a subtle error that can occur if you use `calc()` with multiple units without properly understanding the order of operations.  Additionally, unit conversions and rounding within `@media` queries can lead to unexpected behavior. 

## How to Reproduce

1.  Clone this repository.
2. Open `bug.css` to observe the buggy code.
3. Open `bugSolution.css` to see the corrected code.