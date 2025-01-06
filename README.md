# CSS Selector Issue: Unexpected Behavior with Direct Child Selector

This repository demonstrates an uncommon issue related to CSS selectors, specifically the direct child selector (`>`).  The issue arises when developers assume that the direct child selector selects all descendants, when it only selects immediate children.

The `bug.css` file contains the problematic CSS, showcasing how the direct child selector limits selection to immediate children only. The `solution.css` provides a corrected approach using either more general selectors or a different strategy to achieve the desired styling.

This example highlights the importance of understanding CSS selector specificity and the implications of different selector types.