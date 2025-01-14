# Uncommon CSS Errors

This repository demonstrates two relatively uncommon issues that can arise in CSS:

1. **Unexpected `calc()` Behavior with Percentages:**  `calc()` can produce unexpected results when used with percentages that rely on parent element dimensions that are not yet determined.
2. **Specificity Conflicts:**  When multiple CSS rules have equal specificity, the order matters, with the last one taking precedence. This can be a source of subtle bugs.

The `bug.css` file showcases the problem, and `bugSolution.css` demonstrates solutions.