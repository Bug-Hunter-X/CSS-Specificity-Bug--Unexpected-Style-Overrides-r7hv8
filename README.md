# CSS Specificity Bug: Unexpected Style Overrides

This repository demonstrates a common CSS bug related to specificity.  Incorrect specificity calculations can lead to unexpected style overrides, making debugging challenging. The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a corrected version.

## Bug Description

In `bug.css`, inline styles or styles with higher specificity are unexpectedly overridden by styles with lower specificity.  This behavior is inconsistent and deviates from expected CSS behavior.

## Solution

The solution in `bugSolution.css` addresses the specificity issue by carefully structuring selectors and ensuring they have the appropriate specificity to avoid unintended overrides.  The key is to carefully review your selectors and to adjust their specificity to enforce the correct cascading style sheet behavior.